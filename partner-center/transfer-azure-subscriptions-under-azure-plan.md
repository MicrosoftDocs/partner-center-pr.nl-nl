---
title: Een Azure-abonnement onder een Azure-plan overdragen aan een andere CSP-partner
ms.topic: article
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Meer informatie over het wijzigen van Cloud Solution Provider programmapartner die is gekoppeld aan de Azure-abonnementen van een klant onder een Azure-plan.
ms.custom: SEOMAY.20
ms.localizationpriority: medium
author: mckennaville
ms.author: mcville
ms.date: 07/29/2020
ms.openlocfilehash: 12afa751d2e7cb6b6ef0cd7308f09746a8a43b52
ms.sourcegitcommit: 1899307642f057070b1bdd647594fc46ba61fb08
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/30/2021
ms.locfileid: "108284499"
---
# <a name="transfer-a-customers-azure-plan-subscriptions-to-a-different-partner"></a>De Azure-abonnementsabonnementen van een klant overdragen aan een andere partner

**Juiste rollen**

- Accountbeheerder
- Verkoopagent
- Factureringsagent

In dit artikel wordt beschreven hoe een klant zijn Azure-abonnementen onder een Azure-plan van de ene Cloud Solution Provider (CSP) naar een andere kan overstappen.

Volg deze stappen om de Azure-abonnementen van een klant van een andere partner over te schakelen. Zowel de partner als de klant moeten de stappen voltooien.

>[!Note]  
>Alleen partners met een directe factureringsrelatie met Microsoft hebben toegang tot de overgangshulpprogramma's. Indirecte resellers moeten samenwerken met hun indirecte providers om gebruik te kunnen maken van dit overgangshulpprogramma.

De klant moet in gesprek zijn met beide partners (huidige en toekomstige) voordat dit hulpprogramma wordt gebruikt. Er moet een offline gesprek worden gehad om verwarring en verloop te voorkomen. Daarnaast moeten partners en klanten deze overwegingen en vereisten begrijpen voordat ze een overgang starten:

**Belangrijke overwegingen:**

- Azure-reserveringen worden niet verplaatst met het abonnement naar een toekomstige partner
- CSP-prijzen voor Azure-services onder de huidige partner zullen niet overstappen  
- Ondersteuningsverantwoordelijkheden voor klant worden verplaatst naar toekomstige partner
- Facturering en facturering worden op het moment van overdracht verplaatst naar een toekomstige partner
- Azure Role-Based Access Control (RBAC) wordt niet beïnvloed door de overdracht
- Beheerder namens (AOBO) wordt niet standaard verleend aan de toekomstige partner
- Marketplace-producten van derden worden overdragen zolang de producten voldoen aan de geschiktheidscontrole van Marketplace.
    - Er zijn geen speciale kortingen of regionale beperkingen
    - De producten zijn niet gebaseerd op een abonnement
    - De toekomstige partner moet samenwerken met de uitgever om ervoor te zorgen dat deze op de toegestane lijst voor implementatie van het product staat
    - Als niet aan al deze voorwaarden wordt voldaan om de Marketplace-producten over te dragen, moeten de Azure-abonnementen worden geannuleerd en vervolgens opnieuw worden gekocht van Marketplace-producten met de nieuwe partner

**Vereisten:**

- Klant betrek huidige CSP-partner bij de intentie om over te zetten
- Toekomstige CSP-partner werkt samen met de klant om ervoor te zorgen dat aan de behoeften van de klant kan worden voldaan
- Toekomstige CSP-partner brengt een relatie tot leven met de klant en koopt een Azure-plan voordat de overgang begint  
- De klant moet een Microsoft-klantovereenkomst met een toekomstige CSP-partner
- Toekomstige CSP-partner moet de Microsoft Partner-overeenkomst hebben ondertekend om dit hulpprogramma te kunnen gebruiken

## <a name="customer-tasks-to-be-completed"></a>Te voltooien klanttaken

Als u een Azure-abonnement wilt overdragen onder een Azure-plan, moet de klant het proces starten door contact op te nemen met de huidige partner. Ze moeten de bedrijfsnaam en het domein van hun huidige partner verzamelen, zodat hun toekomstige partner het formulier voor overdrachtsaanvraag namens hen kan invullen.

De klant moet ook de abonnementen identificeren die hij wil overdragen van zijn huidige partner. U kunt geen partners wijzigen voor abonnementen op Office 365, Enterprise Mobility Suite of Microsoft Dynamics CRM.

>[!Note]  
>Het is de verantwoordelijkheid van de toekomstige partner om het overdrachtsaanvraagformulier in te vullen dat het overdrachtsproces initieert. Microsoft kan niet ingrijpen namens de klant of de huidige partner. De klant moet van plan zijn nauw samen te werken met zijn toekomstige en huidige partner om de overgang soepel te laten verlopen.

## <a name="future-partner-tasks-to-be-completed"></a>Toekomstige partnertaken die moeten worden voltooid

De toekomstige partner van het abonnement moet een overdrachtsaanvraagformulier invullen van Partner Center om een abonnementsoverdracht aan te vragen:

1.  Selecteer in Partner Center menu Klanten **en** selecteer vervolgens de klant die u namens een overdrachtsaanvraagformulier wilt invullen.
2.  Selecteer abonnementen in het menu **Klant.**
3.  Selecteer de **sectie Overdrachtsaanvraag.**
4.  Selecteer in **de sectie Overdrachtsaanvraag** **de optie Nieuwe aanvraag toevoegen.**

    :::image type="content" source="images/modernazuretransfers/Transferrequestheader.png" alt-text="Sectie Overdrachten":::

5.  Vul het **formulier Nieuwe overdrachtsaanvraag** in.

6.  Selecteer **Overdrachtsaanvraag verzenden**  >  **Verzenden.**

    :::image type="content" source="images/modernazuretransfers/CompleteTrnasferRequestForm.png" alt-text="Formulier voor overdrachtsaanvraag voltooien":::

7.  Bevestiging van overdrachtsaanvraag controleren

    :::image type="content" source="images/modernazuretransfers/TransferPending.png" alt-text="Overdracht in behandeling controleren":::

    >[!Note]
    >De toekomstige partner kan de overdrachtsaanvraag annuleren door **aanvraag** annuleren alleen in de rechterbovenhoek te selecteren wanneer de status van de overdrachtsaanvraag 'in behandeling' is. Zodra de status van de overdrachtsaanvraag 'wordt uitgevoerd' of 'voltooid' is, zijn annuleringen niet meer mogelijk.

## <a name="current-partner-tasks-to-be-completed"></a>Huidige partnertaken die moeten worden voltooid

De beheerderagent van de huidige partner van de klant ontvangt een e-mailbericht dat de klant een overdracht van zijn of haar abonnementen aanvraagt:

:::image type="content" source="images/modernazuretransfers/SourceReviewEmail.png" alt-text="Beoordelen":::

Controleer en accepteer het overdrachtsaanvraagformulier van Partner Center om de abonnementsoverdracht te voltooien.

>[!Note]  
>Als de huidige partner binnen 30 dagen geen actie onderneemt, verloopt de aanvraag en heeft de toekomstige partner een om een nieuwe overdrachtsaanvraag te maken.

1.  Selecteer **Overdrachtsaanvraag controleren in** de e-mail OF
1.  Selecteer in Partner Center menu Klanten **en** selecteer vervolgens de klant namens welke een overdrachtsaanvraag is ingediend.
2.  Selecteer abonnementen in het menu **Klant.**
3.  Selecteer de **sectie Overdrachtsaanvraag.**
4.  Vouw overdrachtsgegevens uit door de gekozen **aanvraag-id voor overdracht te selecteren** onder Ontvangen **aanvragen**

:::image type="content" source="images/modernazuretransfers/ReviewRequest.png" alt-text="Overdrachtsaanvraag voor bronbeoordelingen":::

5.  Controleer de overdrachtsaanvraag. Selecteer de aangevraagde Azure-abonnementen die u wilt overdragen.

>[!Note]  
> Voordat u doorgaat, hebt u geen toegang meer tot de geselecteerde abonnementen.
> U wordt niet gefactureerd voor verder gebruik.
> Azure-reserveringen worden niet overdraagt met de abonnementen.

6.  Selecteer vervolgens **Accepteren en overdragen om** het overdrachtsproces te voltooien.

:::image type="content" source="images/modernazuretransfers/SelectSubs.png" alt-text="Abonnementen selecteren die moeten worden overgedragen onder uw Azure-abonnementen":::

7.  Bevestiging van acceptatie van overdracht weergeven.

   Op dit moment worden de toekomstige partner, de klant en de huidige partner via e-mail op de hoogte gesteld van de geaccepteerde overdrachtsaanvraag.

   Nadat de overgang is geaccepteerd, kan de overdrachtsstatus maximaal 15 minuten in behandeling blijven terwijl het systeem wordt bijgewerkt. Als het langer duurt, blijft het systeem het drie dagen proberen. Als de overdrachtsstatus nog steeds In behandeling is, moet de partner een serviceaanvraag indienen.

   Zodra de overdracht is voltooid, worden de abonnementen die in de aanvraag zijn opgenomen, weergegeven in het Azure-plan van de toekomstige partner en worden ze niet meer bij u vermeld.

>[!Note]  
>Voor indirecte providers: informeer uw indirecte reseller dat de overdrachtsaanvraag is geaccepteerd.

### <a name="managing-your-transferred-customer-subscriptions"></a>Uw overgedragen klantabonnementen beheren
- Toegang voor bestaande gebruikers, groepen of service-principals die is toegewezen met behulp van Azure RBAC (op rollen gebaseerd toegangsbeheer) wordt niet beïnvloed tijdens de overgang. Op rollen gebaseerd toegangsbeheer [van Azure (Azure RBAC)](/azure/role-based-access-control/overview) helpt uw klant bij het beheren van wie toegang heeft tot Azure-resources, wat ze kunnen doen met deze resources en tot welke gebieden ze toegang hebben. Als nieuwe partner krijgt u na de abonnementsoverdracht geen RBAC-toegang tot de resources van uw klant. De vorige partner van uw klant behoudt zijn RBAC-toegang. Werk samen met uw klant om te begrijpen wie inzicht heeft in hun abonnementen en hoe u gezochte wijzigingen kunt aanbrengen.

- Daarom is het belangrijk dat uw klant Azure RBAC-toegang voor de vorige partner verwijdert en toegang toevoegt voor de nieuwe partner. Zie Wat is op rollen gebaseerd toegangsbeheer van [Azure (Azure RBAC)?](/azure/role-based-access-control/overview) voor meer informatie over het verlenen van nieuwe toegang door uw klant. Zie Een roltoewijzing [verwijderen](/azure/role-based-access-control/role-assignments-portal#remove-a-role-assignment)voor meer informatie over het verwijderen van de RBAC-toegang van uw vorige partner.

- Bovendien krijgt u niet automatisch beheerderstoegang [namens (AOBO)](https://channel9.msdn.com/Series/cspdev/Module-11-Admin-On-Behalf-Of-AOBO) tot uw abonnementen. AOBO is nodig voor partners om de Azure-abonnementen van hun klant namens hen te beheren. Zie Machtigingen verkrijgen voor het beheren van de service of het abonnement van een klant voor meer informatie over [Azure-bevoegdheden.](./customers-revoke-admin-privileges.md)

## <a name="next-steps"></a>Volgende stappen:

- [(Azure RBAC)](/azure/role-based-access-control/overview)
- [Machtigingen verkrijgen voor het beheren van de service of het abonnement van een klant.](./customers-revoke-admin-privileges.md)
