---
title: Beheerdersbevoegdheden voor Azure CSP
ms.topic: how-to
ms.date: 05/27/2021
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Meer informatie over hoe u klanten kunt helpen de beheerdersbevoegdheden van een partner te herstellen, zodat de partner kan helpen bij het beheren van de Azure Cloud Solution Provider(CSP)-abonnementen van een klant.
author: dhirajgandhi
ms.author: dhgandhi
ms.localizationpriority: High
ms.custom: SEOMAY.20
ms.openlocfilehash: 5d784aef33cce2a722583a77e73c35d5fc8136b1
ms.sourcegitcommit: 8dc9f28f15d9760a8363826513b4470b76b40ff3
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 06/23/2021
ms.locfileid: "112551585"
---
# <a name="reinstate-admin-privileges-for-a-customers-azure-csp-subscriptions"></a><span data-ttu-id="ab550-103">Beheerdersbevoegdheden voor de Azure CSP van een klant herstellen</span><span class="sxs-lookup"><span data-stu-id="ab550-103">Reinstate admin privileges for a customer's Azure CSP subscriptions</span></span>  

<span data-ttu-id="ab550-104">**Juiste rollen:** globale | Beheeragent</span><span class="sxs-lookup"><span data-stu-id="ab550-104">**Appropriate roles**: Global admin | Admin agent</span></span>

<span data-ttu-id="ab550-105">Als Cloud Solution Provider (CSP)-partner verwachten uw klanten vaak dat u hun Azure-gebruik en hun systemen voor hen beheert.</span><span class="sxs-lookup"><span data-stu-id="ab550-105">As a Cloud Solution Provider (CSP) partner, your customers often expect that you'll manage their Azure usage and their systems for them.</span></span> <span data-ttu-id="ab550-106">U moet beheerdersbevoegdheden hebben om dit te doen.</span><span class="sxs-lookup"><span data-stu-id="ab550-106">You must have admin privileges to do so.</span></span> <span data-ttu-id="ab550-107">Sommige bevoegdheden worden verleend wanneer uw resellerrelatie met de klant tot stand is gebracht.</span><span class="sxs-lookup"><span data-stu-id="ab550-107">Some privileges are granted when your reseller relationship with the customer is established.</span></span> <span data-ttu-id="ab550-108">Andere worden aan u verleend door uw klant.</span><span class="sxs-lookup"><span data-stu-id="ab550-108">Others are granted to you by your customer.</span></span>

## <a name="admin-privileges-for-azure-in-csp"></a><span data-ttu-id="ab550-109">Beheerdersbevoegdheden voor Azure in CSP</span><span class="sxs-lookup"><span data-stu-id="ab550-109">Admin privileges for Azure in CSP</span></span>

<span data-ttu-id="ab550-110">Er zijn twee niveaus van beheerdersbevoegdheden voor Azure in CSP.</span><span class="sxs-lookup"><span data-stu-id="ab550-110">There are two levels of admin privileges for Azure in CSP.</span></span>

- <span data-ttu-id="ab550-111">**Beheerdersbevoegdheden op tenantniveau (gedelegeerde beheerdersbevoegdheden)**: CSP-partners krijgen deze bevoegdheden tijdens het tot stand brengen van een CSP-resellerrelatie met klanten.</span><span class="sxs-lookup"><span data-stu-id="ab550-111">**Tenant level admin privileges (Delegated admin privileges)**:  CSP partners get these privileges while establishing CSP reseller relationship with customers.</span></span> <span data-ttu-id="ab550-112">Gedelegeerde beheerdersbevoegdheden geven CSP-partners toegang tot de tenants van hun klanten.</span><span class="sxs-lookup"><span data-stu-id="ab550-112">Delegated admin privileges give CSP partners access to their customers' tenants.</span></span> <span data-ttu-id="ab550-113">Met deze toegang kunnen ze beheerfuncties uitvoeren, zoals gebruikers toevoegen/beheren, wachtwoorden opnieuw instellen en gebruikerslicenties beheren.</span><span class="sxs-lookup"><span data-stu-id="ab550-113">This access allows them to do administrative functions such as add/manage users, reset passwords and manage user licenses.</span></span>
- <span data-ttu-id="ab550-114">**Beheerdersbevoegdheden op abonnementsniveau:** CSP-partners krijgen deze bevoegdheden tijdens het maken Azure CSP abonnementen voor hun klanten.</span><span class="sxs-lookup"><span data-stu-id="ab550-114">**Subscription level admin privileges**: CSP partners get these privileges while creating Azure CSP subscriptions for their customers.</span></span> <span data-ttu-id="ab550-115">Deze bevoegdheden geven CSP-partners volledige toegang tot deze abonnementen, zodat ze Azure-resources kunnen inrichten en beheren.</span><span class="sxs-lookup"><span data-stu-id="ab550-115">Having these privileges gives CSP partners complete access to these subscriptions, which allows them to provision and manage Azure resources.</span></span>

## <a name="reinstate-csp-a-partners-admin-privileges"></a><span data-ttu-id="ab550-116">De beheerdersbevoegdheden van een partner opnieuw in CSP herstellen</span><span class="sxs-lookup"><span data-stu-id="ab550-116">Reinstate CSP a partner's admin privileges</span></span>

<span data-ttu-id="ab550-117">Uw klant kan de CSP-roltoewijzing opnieuw maken als u de van de `object ID` groep AdminAgents aan uw klant verstrekt.</span><span class="sxs-lookup"><span data-stu-id="ab550-117">Your customer can re-create the CSP role assignment if you provide the `object ID` of the AdminAgents group to your customer.</span></span> <span data-ttu-id="ab550-118">Als u weer gedelegeerde beheerdersbevoegdheden wilt krijgen, moet u met uw klant samenwerken door de volgende stappen uit te voeren.</span><span class="sxs-lookup"><span data-stu-id="ab550-118">To regain delegated admin privileges, you need to work with your customer through the following steps.</span></span>

1. <span data-ttu-id="ab550-119">Meld u aan bij Partner Center dashboard.</span><span class="sxs-lookup"><span data-stu-id="ab550-119">Sign into the Partner Center dashboard.</span></span>

2. <span data-ttu-id="ab550-120">Selecteer in Partner Center menu **Klanten.**</span><span class="sxs-lookup"><span data-stu-id="ab550-120">On the Partner Center menu, select **Customers**.</span></span>

3. <span data-ttu-id="ab550-121">Selecteer de klant met wie u werkt en vraag **een resellerrelatie aan.**</span><span class="sxs-lookup"><span data-stu-id="ab550-121">Select the customer you are working with and **request a reseller relationship**.</span></span> <span data-ttu-id="ab550-122">Met deze actie wordt een koppeling gegenereerd naar de klant die tenantbeheerdersrechten heeft.</span><span class="sxs-lookup"><span data-stu-id="ab550-122">This action generates a link to the customer who has tenant admin rights.</span></span>

4. <span data-ttu-id="ab550-123">Uw klant moet de koppeling selecteren en de aanvraag voor de resellerrelatie goedkeuren.</span><span class="sxs-lookup"><span data-stu-id="ab550-123">Your customer needs to select the link and approve the reseller relationship request.</span></span>

   :::image type="content" source="images/azure/revoke4.png" alt-text="E-mailvoorbeeld van een resellerrelatie maken.":::

5. <span data-ttu-id="ab550-125">U, de partner, moet verbinding maken met de partnerten tenant om de object-id van de groep AdminAgents op te halen.</span><span class="sxs-lookup"><span data-stu-id="ab550-125">You, the partner, need to connect to partner tenant to get the Object ID of the AdminAgents group.</span></span>
  
   ```powershell
   Connect-AzAccount -Tenant "Partner tenant"
   # Get Object ID of AdminAgents group
   Get-AzADGroup -DisplayName AdminAgents
   ```

6. <span data-ttu-id="ab550-126">Uw klant moet vervolgens de volgende stappen uitvoeren met behulp van PowerShell of Azure CLI.</span><span class="sxs-lookup"><span data-stu-id="ab550-126">Your customer must then do the following steps using either PowerShell or Azure CLI.</span></span> <span data-ttu-id="ab550-127">Uw klant moet het volgende hebben:</span><span class="sxs-lookup"><span data-stu-id="ab550-127">Your customer must have:</span></span>

- <span data-ttu-id="ab550-128">De rol **van** eigenaar of **beheerder van gebruikerstoegang**</span><span class="sxs-lookup"><span data-stu-id="ab550-128">The role of **owner** or **user access administrator**</span></span> 
- <span data-ttu-id="ab550-129">Machtigingen voor het maken van roltoewijzingen op abonnementsniveau</span><span class="sxs-lookup"><span data-stu-id="ab550-129">Permissions to create role assignments at the subscription level</span></span>

   <span data-ttu-id="ab550-130">a.</span><span class="sxs-lookup"><span data-stu-id="ab550-130">a.</span></span> <span data-ttu-id="ab550-131">Alleen voor PowerShell moet de klant de `Az.Resources` module bijwerken.</span><span class="sxs-lookup"><span data-stu-id="ab550-131">For PowerShell only, the customer must update the `Az.Resources` module.</span></span>
   ```powershell
   Update-Module Az.Resources
   ```

   <span data-ttu-id="ab550-132">b.</span><span class="sxs-lookup"><span data-stu-id="ab550-132">b.</span></span> <span data-ttu-id="ab550-133">De klant maakt verbinding met de tenant waar het CSP-abonnement zich bevindt.</span><span class="sxs-lookup"><span data-stu-id="ab550-133">The customer connects to the tenant where the CSP subscription exists.</span></span>
   ```powershell
   Connect-AzAccount -TenantID "<Customer tenant>"
   ```
   ```azurecli
   az login --tenant <Customer tenant>
   ```

   <span data-ttu-id="ab550-134">c.</span><span class="sxs-lookup"><span data-stu-id="ab550-134">c.</span></span> <span data-ttu-id="ab550-135">De klant maakt verbinding met het abonnement.</span><span class="sxs-lookup"><span data-stu-id="ab550-135">The customer connects to the subscription.</span></span> <span data-ttu-id="ab550-136">Dit is *alleen* van toepassing als de gebruiker machtigingen voor roltoewijzing heeft voor meerdere abonnementen in de tenant.</span><span class="sxs-lookup"><span data-stu-id="ab550-136">This is *only* applicable if the user has role assignment permissions over multiple subscriptions in the tenant.</span></span>

   ```powershell
   Set-AzContext -SubscriptionID <"CSP Subscription ID">
   ```
   ```azurecli
   az account set --subscription <CSP Subscription ID>
   ```

   <span data-ttu-id="ab550-137">d.</span><span class="sxs-lookup"><span data-stu-id="ab550-137">d.</span></span> <span data-ttu-id="ab550-138">De klant maakt vervolgens de roltoewijzing.</span><span class="sxs-lookup"><span data-stu-id="ab550-138">The customer then creates the role assignment.</span></span>
    
   ```powershell
   New-AzRoleAssignment -ObjectID "<Object ID of the Admin Agents group provided by partner>" -RoleDefinitionName "Owner" -Scope "/subscriptions/'<CSP subscription ID>'"
   ```
   ```azurecli
   az role assignment create --role "Owner" --assignee-object-id <Object Id of the Admin Agents group provided by partner> --scope "/subscriptions/<CSP Subscription Id>"
   ```

<span data-ttu-id="ab550-139">In plaats van eigenaarsmachtigingen te verlenen voor het abonnementsbereik, kunt u machtigingen verlenen op het niveau van de resourcegroep of resource.</span><span class="sxs-lookup"><span data-stu-id="ab550-139">Instead of granting owner permissions at the subscription scope, you can grant at the resource group or resource level.</span></span> 

- <span data-ttu-id="ab550-140">Op het niveau van de resourcegroep</span><span class="sxs-lookup"><span data-stu-id="ab550-140">At the resource group level</span></span>

   ```powershell
   New-AzRoleAssignment -ObjectID "<Object ID from step 3>" -RoleDefinitionName Owner -Scope "/subscriptions/'SubscriptionID of CSP subscription'/resourceGroups/'Resource group name'"
   ```
   ```azurecli
   az role assignment create --role "Owner" --assignee-object-id <Object Id of the Admin Agents group provided by partner> --scope "/subscriptions/<CSP Subscription Id>//resourceGroups/<Resource group name>"
   ```

- <span data-ttu-id="ab550-141">Op resourceniveau</span><span class="sxs-lookup"><span data-stu-id="ab550-141">At the resource level</span></span>

   ```powershell
   New-AzRoleAssignment -ObjectID "<Object ID from step 3>" -RoleDefinitionName Owner -Scope "<Resource URI>"
   ```
   ```azurecli
   az role assignment create --role "Owner" --assignee-object-id <Object Id of the Admin Agents group provided by partner> --scope "<Resource URI>"
   ```

<span data-ttu-id="ab550-142">Als de bovenstaande stappen niet werken of als er fouten optreden bij het proberen, kunt u de volgende catch-all-procedure volgen om de beheerdersrechten voor uw klant te herstellen.</span><span class="sxs-lookup"><span data-stu-id="ab550-142">If the above steps don't work or you get errors when attempting them, try the following "catch-all" procedure to reinstate admin rights for your customer.</span></span>

```powershell
Install-Module -Name Az.Resources -Force -Verbose
Import-Module -Name Az.Resources -Verbose -MinimumVersion 4.1.1
Connect-AzAccount -Tenant <customer tenant>
Set-AzContext -SubscriptionId <customer subscriptions>
New-AzRoleAssignment -ObjectId <principal ID> -RoleDefinitionName "Owner" -Scope "/subscriptions/<customer subscription>" -ObjectType "ForeignGroup"
```

### <a name="troubleshooting"></a><span data-ttu-id="ab550-143">Problemen oplossen</span><span class="sxs-lookup"><span data-stu-id="ab550-143">Troubleshooting</span></span>

<span data-ttu-id="ab550-144">Als de klant stap 6 hierboven niet kan voltooien, moet u de klant de volgende opdracht laten uitvoeren:</span><span class="sxs-lookup"><span data-stu-id="ab550-144">If the customer is unable to complete step 6 above, have the customer try the following command:</span></span>

```powershell
New-AzRoleAssignment -ObjectId <principal ID> -RoleDefinitionName "Owner" -Scope "/subscriptions/<costumer subscription>" -ObjectType "ForeignGroup" -Debug > newRoleAssignment.log
```

<span data-ttu-id="ab550-145">Geef het `newRoleAssignment.log` resulterende bestand aan Microsoft op voor verdere analyse.</span><span class="sxs-lookup"><span data-stu-id="ab550-145">Provide the resulting `newRoleAssignment.log` file to Microsoft for further analysis.</span></span>

<span data-ttu-id="ab550-146">Als de procedure 'catch-all' mislukt tijdens `Import-Module` de , probeert u de volgende stappen:</span><span class="sxs-lookup"><span data-stu-id="ab550-146">If the "catch-all" procedure fails during the `Import-Module`, try the following steps:</span></span>
- <span data-ttu-id="ab550-147">Als het importeren mislukt omdat de module in gebruik is, start u de PowerShell-sessie opnieuw door alle vensters te sluiten en opnieuw te openen.</span><span class="sxs-lookup"><span data-stu-id="ab550-147">If the import fails because the module is in use, restart the PowerShell session by closing and reopening all windows.</span></span>
- <span data-ttu-id="ab550-148">Controleer de versie `Az.Resources` van met `Get-Module Az.Resources -ListAvailable` .</span><span class="sxs-lookup"><span data-stu-id="ab550-148">Check version of `Az.Resources` with `Get-Module Az.Resources -ListAvailable`.</span></span>
- <span data-ttu-id="ab550-149">Als versie 4.1.1 niet in de beschikbare lijst staat, moet u `Update-Module Az.Resources -Force` gebruiken.</span><span class="sxs-lookup"><span data-stu-id="ab550-149">If version 4.1.1 is not within the available list, you must use `Update-Module Az.Resources -Force`.</span></span>
- <span data-ttu-id="ab550-150">Als de foutmelding geeft dat een specifieke versie moet zijn, moet u die module ook `Az.Accounts` bijwerken en vervangen door `Az.Resources` `Az.Accounts` .</span><span class="sxs-lookup"><span data-stu-id="ab550-150">If the error states that `Az.Accounts` needs to be a specific version, update that module as well, replacing `Az.Resources` with `Az.Accounts`.</span></span> <span data-ttu-id="ab550-151">Vervolgens moet u de PowerShell-sessie opnieuw starten.</span><span class="sxs-lookup"><span data-stu-id="ab550-151">You must then restart the PowerShell session.</span></span>


## <a name="next-steps"></a><span data-ttu-id="ab550-152">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="ab550-152">Next steps</span></span>

- [<span data-ttu-id="ab550-153">Abonnementen en resources beheren onder het Azure-abonnement</span><span class="sxs-lookup"><span data-stu-id="ab550-153">Manage subscriptions and resources under the Azure plan</span></span>](azure-plan-manage.md)
