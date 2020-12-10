---
title: Beheerders bevoegdheden voor Azure CSP opnieuw invoeren
ms.topic: how-to
ms.date: 07/28/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Meer informatie over hoe u klanten helpt om de beheerders bevoegdheden van een partner te herstellen, zodat de partner de Azure CSP-abonnementen van een klant kan beheren.
author: dhirajgandhi
ms.author: dhgandhi
ms.localizationpriority: High
ms.custom: SEOMAY.20
ms.openlocfilehash: 13fdeb01ecd73dc1a63d174a4ad5cb8e1bdc813a
ms.sourcegitcommit: 455894365fa488368f7572ac72312e84a267ef5e
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 12/10/2020
ms.locfileid: "97011499"
---
# <a name="reinstate-admin-privileges-for-a-customers-azure-csp-subscriptions"></a>Beheerders bevoegdheden voor de Azure CSP-abonnementen van een klant opnieuw invoeren  

**Toepasselijke rollen**

- Globale beheerder
- Beheer agent

Als CSP-partner verwachten uw klanten vaak dat u hun Azure-gebruik en hun systemen hiervoor gaat beheren. Hiervoor moet u beheerders bevoegdheden hebben. Sommige bevoegdheden worden verleend wanneer uw reseller-relatie met de klant tot stand is gebracht. Anderen worden aan u verleend door uw klant.

## <a name="admin-privileges-for-azure-in-csp"></a>Beheerders bevoegdheden voor Azure in CSP

Er zijn twee niveaus van beheerders bevoegdheden voor Azure in CSP.

**Beheerders bevoegdheden op Tenant niveau** (**gedelegeerde beheerders bevoegdheden**): CSP-partners krijgen deze bevoegdheden bij het tot stand brengen van de leverancier van de CSP-dealer met klanten. Dit geeft CSP-partners toegang tot de tenants van hun klanten, waardoor ze beheer functies kunnen uitvoeren zoals gebruikers toevoegen/beheren, wacht woorden opnieuw instellen en gebruikers licenties beheren.

**Beheerders bevoegdheden op abonnements niveau** : CSP-partners krijgen deze bevoegdheden tijdens het maken van Azure CSP-abonnementen voor hun klanten. Met deze bevoegdheden hebben CSP-partners volledige toegang tot deze abonnementen, waardoor ze Azure-bronnen kunnen inrichten en beheren.

## <a name="reinstate-csp-partners-admin-privileges"></a>Beheerders bevoegdheden voor de CSP-partners herstellen

Als u gedelegeerde beheerders bevoegdheden wilt herstellen, moet u samen werken met uw klant.

1. Meld u aan bij het Partner Center-dash board en selecteer **klanten** in het menu van het partner centrum.

2. Selecteer de klant waarmee u werkt en **vraag een reseller-relatie aan.** Hiermee genereert u een koppeling naar de klant die Tenant beheerders rechten heeft.

3. Deze gebruiker moet de koppeling selecteren en de wederverkoper-relatie aanvraag goed keuren.

   :::image type="content" source="images/azure/revoke4.png" alt-text="Reseller-relatie":::

## <a name="adding-the-admin-agents-group-as-an-owner-for-the-azure-csp-subscription"></a>De groep Administrator-agents toevoegen als eigenaar van het Azure CSP-abonnement

Uw klant moet uw groep Administrators agent toevoegen als eigenaar van een Azure CSP-abonnement, een resource groep of een resource. 

1. Gebruik de Power shell-console of Power shell Integrated Scripting Environment (ISE). Zorg ervoor dat AzureAD-modules zijn geïnstalleerd.

2. Maak verbinding met uw Azure AD-Tenant.

   ```powershell
   Connect-AzureAD
   ```

3. ObjectId ophalen van de groepen beheerders agents.

   ```powershell
   Get-AzureADGroup
   ```
   De volgende stappen worden uitgevoerd door de gebruiker in het bedrijf van uw klant die eigenaar toegang heeft tot het abonnement van de Azure CSP.

4. De gebruiker met de eigenaar heeft toegang tot het abonnement van Azure CSP, meldt zich aan bij Azure met haar referenties.

   ```powershell
   Connect-AzureRmAccount
   ```

5. Ze kan de groep van uw beheerders agent als eigenaar toevoegen aan het CSP Azure-abonnement, de resource groep of de resource door een juiste resource-URI in de bereik parameter toe te passen. 

    ```powershell
    # Grant owner role at subscription level
    New-AzureRmRoleAssignment -ObjectId <Object Id that you got from step 3> -RoleDefinitionName Owner -Scope "/subscriptions/<SubscriptionId of CSP subscription>"

    # Grant owner role at resource group level
    New-AzureRmRoleAssignment -ObjectId <Object Id that you got from step 3> -RoleDefinitionName Owner -Scope "/subscriptions/<SubscriptionId of CSP subscription>/resourceGroups/<Resource group name>"

    # Grant owner role at resource level
    New-AzureRmRoleAssignment -ObjectId <Object Id that you got from step 3> -RoleDefinitionName Owner -Scope "<Resource Uri>"
    ```

## <a name="next-steps"></a>Volgende stappen

[Abonnementen en resources beheren onder het Azure-abonnement](azure-plan-manage.md)
