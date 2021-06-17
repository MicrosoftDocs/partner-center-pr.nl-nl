---
title: Facturering van Azure-plan - &-bestanden
ms.topic: article
ms.date: 05/19/2021
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Meer informatie over het openen en begrijpen van de factuur- en afstemmingsbestandsstructuur met betrekking tot facturering voor het Azure-plan.
author: khpavan
ms.author: sakhanda
ms.localizationpriority: High
ms.custom: SEOMAY.20
ms.openlocfilehash: 725050d370d1266205f979aa6317768d05ae5c4c
ms.sourcegitcommit: 376a49bcd245d3358a78871128761175a96ec200
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 06/17/2021
ms.locfileid: "112277178"
---
# <a name="new-commerce-experience-in-csp---azure-billing"></a><span data-ttu-id="82e8a-103">Nieuwe Commerce-ervaring in CSP - Azure-facturering</span><span class="sxs-lookup"><span data-stu-id="82e8a-103">New commerce experience in CSP - Azure billing</span></span> 

<span data-ttu-id="82e8a-104">**Juiste rollen:** beheeragent | Factureringsbeheerder | Globale beheerder</span><span class="sxs-lookup"><span data-stu-id="82e8a-104">**Appropriate roles**: Admin agent | Billing admin | Global admin</span></span>

<span data-ttu-id="82e8a-105">In dit artikel wordt uitgelegd hoe u de factuur- en afstemmingsbestandsstructuur met betrekking tot facturering voor het Azure-plan kunt openen en begrijpen.</span><span class="sxs-lookup"><span data-stu-id="82e8a-105">This article explains how to access and understand the invoice and reconciliation file structure related to billing for the Azure plan.</span></span> <span data-ttu-id="82e8a-106">Facturering onder het Azure-plan is een vereenvoudigde factureringservaring met behulp van een uitgelijnde factureringsdatum en factureringsperiode op basis van een kalendermaand.</span><span class="sxs-lookup"><span data-stu-id="82e8a-106">Billing under the Azure plan is a simplified billing experience using an aligned single billing date and calendar month-based billing period.</span></span>

## <a name="summary-of-billing-essentials"></a><span data-ttu-id="82e8a-107">Samenvatting van de belangrijkste factureringsgegevens</span><span class="sxs-lookup"><span data-stu-id="82e8a-107">Summary of billing essentials</span></span>

- <span data-ttu-id="82e8a-108">**Factuurdatum:** Het factuur- en afstemmingsbestand is op de 8e (middernacht UTC) beschikbaar in Partner Center dashboard/API.</span><span class="sxs-lookup"><span data-stu-id="82e8a-108">**Invoice date**: Invoice and reconciliation file will be available in the Partner Center dashboard/API by the 8th (midnight UTC).</span></span>

- <span data-ttu-id="82e8a-109">Factuurfactureringsperiode: de factuurfactureringsperiode is afgestemd op de kalendermaand, bijvoorbeeld 10/1-10/31, 11/1-11/30.</span><span class="sxs-lookup"><span data-stu-id="82e8a-109">**Invoice billing period**: The invoice billing period is aligned to the calendar month, for example,  10/1-10/31, 11/1-11/30.</span></span>

- <span data-ttu-id="82e8a-110">**Serviceperioden voor** kosten: de kosten worden afgestemd op de kalendermaand.</span><span class="sxs-lookup"><span data-stu-id="82e8a-110">**Charge service periods**: Charges will align to the calendar month.</span></span> <span data-ttu-id="82e8a-111">Als de gefactureerde partner bijvoorbeeld Azure-services toevoegt via een Azure-plan op 15-10 en de klant het verbruik van Azure-services op 10/15 begint, ontvangt de gefactureerde partner factuur/recon op 11/8 voor klantverbruik voor de serviceperiode 10/15 - 10/31.</span><span class="sxs-lookup"><span data-stu-id="82e8a-111">For example, if billed partner adds Azure services through an Azure plan on 10/15 and the customer begins consumption of Azure services on 10/15, then billed partner will receive invoice/recon on 11/8 for customer consumption for the service period 10/15 - 10/31.</span></span> <span data-ttu-id="82e8a-112">De factuur van de volgende maand die wordt gegenereerd op 12/8 bevat alle kosten voor de serviceperiode 11/1- 11/31.</span><span class="sxs-lookup"><span data-stu-id="82e8a-112">The next month's invoice that is going to be generated on 12/8 contains all the charges for the service period 11/1- 11/31.</span></span>

- <span data-ttu-id="82e8a-113">**Betalingstermijn factuur:** netto 60 dagen.</span><span class="sxs-lookup"><span data-stu-id="82e8a-113">**Invoice payment term**: Net 60 days.</span></span>

- <span data-ttu-id="82e8a-114">Factuurvaluta: vanaf 28 januari 2021 worden partners in de regio EU/EFTA en het VK die nieuwe klanten hebben en bestaande CSP-klanten die voor het eerst nieuwe commerceaanbiedingen aanschaffen waarvan de tenants zijn gemaakt vóór 11 mei 2020, gefactureerd voor deze aankopen in partnerlocatievaluta.</span><span class="sxs-lookup"><span data-stu-id="82e8a-114">**Invoice currency**: Starting January 28th 2021, partners in the EU/EFTA and UK region who have new customers and existing CSP customers purchasing new commerce offers for the first time whose tenants were created prior to 11 May 2020, will be billed for those purchases in partner location currency.</span></span> <span data-ttu-id="82e8a-115">Partners die zich buiten de regio EU/EFTA en het VK bevinden, worden nog steeds gefactureerd in partnerlocatievaluta.</span><span class="sxs-lookup"><span data-stu-id="82e8a-115">Partners located outside of the EU/EFTA and UK region will continue to be billed in partner location currency.</span></span>

- <span data-ttu-id="82e8a-116">**Incentives voor partners:** betaalde 45 dagen vanaf het einde van de factuurmaand.</span><span class="sxs-lookup"><span data-stu-id="82e8a-116">**Partner incentives**: Paid 45 days from the end of the invoice month.</span></span>

## <a name="access-your-invoices-and-reconciliation-files"></a><span data-ttu-id="82e8a-117">Toegang tot uw facturen en afstemmingsbestanden</span><span class="sxs-lookup"><span data-stu-id="82e8a-117">Access your invoices and reconciliation files</span></span>

<span data-ttu-id="82e8a-118">De globale beheerder of factureringsbeheerder voor uw bedrijf ontvangt een e-mail wanneer een factuur gereed is om te worden bekeken.</span><span class="sxs-lookup"><span data-stu-id="82e8a-118">The global admin or billing admin for your company will receive an email when an invoice is ready to view.</span></span>

<span data-ttu-id="82e8a-119">Voor toegang tot het factuur- en afstemmingsbestand:</span><span class="sxs-lookup"><span data-stu-id="82e8a-119">To access the invoice and reconciliation file:</span></span>

1. <span data-ttu-id="82e8a-120">Meld u aan bij het [dashboard](https://partner.microsoft.com/dashboard/) van het Partnercentrum.</span><span class="sxs-lookup"><span data-stu-id="82e8a-120">Sign in to the Partner Center [dashboard](https://partner.microsoft.com/dashboard/).</span></span>

2. <span data-ttu-id="82e8a-121">Selecteer in Partner Center menu **Facturering.**</span><span class="sxs-lookup"><span data-stu-id="82e8a-121">From the Partner Center menu, select **Billing**.</span></span>

3. <span data-ttu-id="82e8a-122">Selecteer het tabblad **Terugkerend en** **Eenmalige** en de valuta waarin u geïnteresseerd bent.</span><span class="sxs-lookup"><span data-stu-id="82e8a-122">Select the tab for the **Recurring** and **One-time** and the currency you are interested in.</span></span>

   :::image type="content" source="images/azure/billing3.png" alt-text="Facturering.":::

4. <span data-ttu-id="82e8a-124">Selecteer **Factuur-** **of afstemmingsbestand.**</span><span class="sxs-lookup"><span data-stu-id="82e8a-124">Select **Invoice** or **Reconciliation file**.</span></span>  

   <span data-ttu-id="82e8a-125">Als u historische facturen en recon-bestanden wilt weergeven, vouwt u de onderstaande rij Factureringsgeschiedenis uit.</span><span class="sxs-lookup"><span data-stu-id="82e8a-125">To view historical invoices and recon files expand the Billing history row below.</span></span>

## <a name="understanding-usage-data"></a><span data-ttu-id="82e8a-126">Inzicht in gebruiksgegevens</span><span class="sxs-lookup"><span data-stu-id="82e8a-126">Understanding usage data</span></span> 

1. <span data-ttu-id="82e8a-127">Azure-plan is de hoofdcontainer of container op het hoogste niveau voor gebruik.</span><span class="sxs-lookup"><span data-stu-id="82e8a-127">Azure plan is the root or top-level container for usage.</span></span> <span data-ttu-id="82e8a-128">Al het gebruik is gekoppeld aan één Azure-plan.</span><span class="sxs-lookup"><span data-stu-id="82e8a-128">All usage is tied back to a single Azure plan.</span></span>

2. <span data-ttu-id="82e8a-129">Binnen een abonnement zijn er een of meer Azure-abonnementen.</span><span class="sxs-lookup"><span data-stu-id="82e8a-129">Within a plan, there will be one or more Azure subscriptions.</span></span> <span data-ttu-id="82e8a-130">Dit zijn containers die worden gebruikt voor resourcebeheer en implementatie.</span><span class="sxs-lookup"><span data-stu-id="82e8a-130">These are containers used for resource management and deployment.</span></span> 

3. <span data-ttu-id="82e8a-131">Binnen een abonnement voegen resourcegroepen toe aan groepsresources.</span><span class="sxs-lookup"><span data-stu-id="82e8a-131">Within a subscription, resource groups add to group resources.</span></span> <span data-ttu-id="82e8a-132">Elke resource wordt geïmplementeerd in één resourcegroep.</span><span class="sxs-lookup"><span data-stu-id="82e8a-132">Every resource is deployed to one resource group.</span></span> 

4. <span data-ttu-id="82e8a-133">Voorbeelden van resources zijn virtuele machines en opslagaccounts.</span><span class="sxs-lookup"><span data-stu-id="82e8a-133">Examples of resources include virtual machines and storage accounts.</span></span> 

5. <span data-ttu-id="82e8a-134">Bronmeters: Meters zijn metingen van het verbruik van een resource en één resource kan het gebruik voor meerdere meters gebruiken.</span><span class="sxs-lookup"><span data-stu-id="82e8a-134">Resource emit meters: Meters are measurements of consumption of a resource, and one resource may emit usage for multiple meters.</span></span> <span data-ttu-id="82e8a-135">Meters worden geïdentificeerd door een ProductId, SKUId en AvailabilityId.</span><span class="sxs-lookup"><span data-stu-id="82e8a-135">Meters are identified by a ProductId, SKUId, and AvailabilityId.</span></span> 

### <a name="hierarchy-of-subscription-resource-groups-and-metering"></a><span data-ttu-id="82e8a-136">Hiërarchie van abonnementsresourcegroepen en meting</span><span class="sxs-lookup"><span data-stu-id="82e8a-136">Hierarchy of subscription resource groups and metering</span></span>

<span data-ttu-id="82e8a-137">**Azure-account (tenant)**</span><span class="sxs-lookup"><span data-stu-id="82e8a-137">**Azure account (tenant)**</span></span>

- <span data-ttu-id="82e8a-138">Abonnement A</span><span class="sxs-lookup"><span data-stu-id="82e8a-138">Subscription A</span></span>
    - <span data-ttu-id="82e8a-139">ResourceGroup 1</span><span class="sxs-lookup"><span data-stu-id="82e8a-139">ResourceGroup 1</span></span>
        - <span data-ttu-id="82e8a-140">Virtuele machine (resource)</span><span class="sxs-lookup"><span data-stu-id="82e8a-140">Virtual machine (resource)</span></span>
            - <span data-ttu-id="82e8a-141">Rekenmeter</span><span class="sxs-lookup"><span data-stu-id="82e8a-141">Compute meter</span></span>
        - <span data-ttu-id="82e8a-142">Virtueel netwerk (resource)</span><span class="sxs-lookup"><span data-stu-id="82e8a-142">Virtual network (resource)</span></span>
            - <span data-ttu-id="82e8a-143">Geen factureringsmeter</span><span class="sxs-lookup"><span data-stu-id="82e8a-143">No billing meter</span></span>

    - <span data-ttu-id="82e8a-144">ResourceGroup 2</span><span class="sxs-lookup"><span data-stu-id="82e8a-144">ResourceGroup 2</span></span>
        - <span data-ttu-id="82e8a-145">Virtuele machine (resource)</span><span class="sxs-lookup"><span data-stu-id="82e8a-145">Virtual machine (resource)</span></span>
            - <span data-ttu-id="82e8a-146">Computermeter</span><span class="sxs-lookup"><span data-stu-id="82e8a-146">Computer meter</span></span>
        - <span data-ttu-id="82e8a-147">Premium - SSD beheerde schijf (resource)</span><span class="sxs-lookup"><span data-stu-id="82e8a-147">Premium SSD-managed disk (resource)</span></span>
            - <span data-ttu-id="82e8a-148">Meter voor opslagcapaciteit</span><span class="sxs-lookup"><span data-stu-id="82e8a-148">Storage capacity meter</span></span>
            - <span data-ttu-id="82e8a-149">Meter voor opslagbewerkingen</span><span class="sxs-lookup"><span data-stu-id="82e8a-149">Storage operations meter</span></span>

- <span data-ttu-id="82e8a-150">Abonnement B -ResourceGroup 1 - Azure SQL (resource) - DTU-meter - VPN Gateway (resource) - VPN-gatewaymeter</span><span class="sxs-lookup"><span data-stu-id="82e8a-150">Subscription B   -ResourceGroup 1       - Azure SQL (resource)           - DTU meter       - VPN Gateway (resource)           - VPN gateway meter</span></span>

    - <span data-ttu-id="82e8a-151">ResourceGroup 2</span><span class="sxs-lookup"><span data-stu-id="82e8a-151">ResourceGroup 2</span></span>
        - <span data-ttu-id="82e8a-152">Virtual Network Interface (resource)</span><span class="sxs-lookup"><span data-stu-id="82e8a-152">Virtual Network Interface (resource)</span></span>
            - <span data-ttu-id="82e8a-153">Geen factureringsmeter</span><span class="sxs-lookup"><span data-stu-id="82e8a-153">No billing meter</span></span>

## <a name="read-the-invoice"></a><span data-ttu-id="82e8a-154">De factuur lezen</span><span class="sxs-lookup"><span data-stu-id="82e8a-154">Read the invoice</span></span>

1. <span data-ttu-id="82e8a-155">Factuur is niet later dan de acht dagen van elke maand beschikbaar.</span><span class="sxs-lookup"><span data-stu-id="82e8a-155">Invoice will be available no later than the eighth of each month.</span></span>

2. <span data-ttu-id="82e8a-156">Partners hebben 60 dagen de tijd om de betaling door te geven.</span><span class="sxs-lookup"><span data-stu-id="82e8a-156">Partners have 60 days to remit payment.</span></span>

3. <span data-ttu-id="82e8a-157">De factureringsperiode heeft betrekking op een bepaalde kalendermaand, bijvoorbeeld 10/1-10/31.</span><span class="sxs-lookup"><span data-stu-id="82e8a-157">The billing period will cover a given calendar month, for example, 10/1-10/31.</span></span>

4. <span data-ttu-id="82e8a-158">Kosten zijn netto correcties (bedrag is netto van 'Partnertegoed voor beheerde services').</span><span class="sxs-lookup"><span data-stu-id="82e8a-158">Charges are net of adjustments (amount is net of “Partner earned credit for services managed").</span></span>

5. <span data-ttu-id="82e8a-159">Controleer het factuur recon-bestand en het bestand met dagelijks beoordeeld gebruik voor aanvullende factureringsgegevens.</span><span class="sxs-lookup"><span data-stu-id="82e8a-159">Review the invoice recon file and daily rated usage file for additional billing details.</span></span>

   :::image type="content" source="images/azure/invoice1.png" alt-text="Factuur.":::

## <a name="read-the-invoice-reconciliation-file"></a><span data-ttu-id="82e8a-161">Het factuurafstemmingsbestand lezen</span><span class="sxs-lookup"><span data-stu-id="82e8a-161">Read the invoice reconciliation file</span></span>

1. <span data-ttu-id="82e8a-162">Elke combinatie van Azure-plan en -meter kan maximaal twee factureringslijnen in het reconbestand hebben.</span><span class="sxs-lookup"><span data-stu-id="82e8a-162">Each Azure plan and meter combination may have up to two billing lines on the recon file.</span></span>

2. <span data-ttu-id="82e8a-163">Als de meter is gekwalificeerd voor elk type korting of tegoed (zoals gelaagde kortingen of het partnertegoed voor beheerde services) gedurende de hele kalendermaand, bevat het reconbestand slechts één factureringsregel.</span><span class="sxs-lookup"><span data-stu-id="82e8a-163">If the meter qualified for any type of discount or credit (such as tiered discounts or the Partner earned credit for services managed) throughout the entire calendar month, then the recon file will only contain one billing line.</span></span> <span data-ttu-id="82e8a-164">De kolom **PriceAdjusmentDescription verwijst** naar de korting of het verdiend tegoed.</span><span class="sxs-lookup"><span data-stu-id="82e8a-164">The column **PriceAdjusmentDescription** will reference the discount or earned credit.</span></span>

3. <span data-ttu-id="82e8a-165">Als er geen resources zijn voor een bepaalde meter die geschikt zijn voor korting of partnertegoed, bevat het reconbestand slechts één factureringsregel en is de effectieve eenheidsprijs de detailhandelprijs (de eenheidsprijs).</span><span class="sxs-lookup"><span data-stu-id="82e8a-165">If there are no resources for a particular meter that qualified for discount or partner earned credit, then the recon file will only contain one billing line and the effective unit price will be the retail price (which is the unit price).</span></span>

4. <span data-ttu-id="82e8a-166">Als de meter of resources die die meter uitzenden, gekwalificeerd zijn voor partnertegoed voor **services** die een deel van de maand worden beheerd, bevat het reconbestand twee factureringslijnen.</span><span class="sxs-lookup"><span data-stu-id="82e8a-166">If the meter, or any resources emitting that meter, qualified for **Partner earned credit for services managed** for a part of the month, the recon file will contain two billing lines.</span></span> <span data-ttu-id="82e8a-167">Eén regel vertegenwoordigt de dagen dat de meter gekwalificeerd is en de tweede regel de dagen dat de meter niet in aanmerking komt.</span><span class="sxs-lookup"><span data-stu-id="82e8a-167">One line will represent the days the meter qualified and the second line will represent the days the meter did not qualify.</span></span>

>[!NOTE]
><span data-ttu-id="82e8a-168">U kunt uw Azure-verbruik afstemmen in uw een-keer-aankoop recon-bestand.</span><span class="sxs-lookup"><span data-stu-id="82e8a-168">You can reconcile your Azure consumption in your one-time purchase recon file.</span></span> <span data-ttu-id="82e8a-169">Als u dit wilt doen, gaat u naar uw dagelijks beoordeelde reconbestand voor gebruik en zoekt u naar uw SubscriptionID.</span><span class="sxs-lookup"><span data-stu-id="82e8a-169">To do this, go to your daily-rated usage recon file and search for your SubscriptionID.</span></span> <span data-ttu-id="82e8a-170">Hiermee worden alle kosten weergegeven die zijn gekoppeld aan uw Azure-plan-id.</span><span class="sxs-lookup"><span data-stu-id="82e8a-170">This will display all costs associated with your Azure Plan ID.</span></span> <span data-ttu-id="82e8a-171">Uw Azure SubscriptionID wordt weergegeven als de EntitlementID.</span><span class="sxs-lookup"><span data-stu-id="82e8a-171">Your Azure SubscriptionID is shown as the EntitlementID.</span></span>

## <a name="read-the-daily-usage-file"></a><span data-ttu-id="82e8a-172">Het dagelijkse gebruiksbestand lezen</span><span class="sxs-lookup"><span data-stu-id="82e8a-172">Read the daily usage file</span></span>

- <span data-ttu-id="82e8a-173">Abonnementsmeters onder een Azure-plan worden dagelijks beoordeeld en gecumuleerd.</span><span class="sxs-lookup"><span data-stu-id="82e8a-173">Subscription meters under an Azure plan are rated, and are cumulated, on a daily basis.</span></span>

- <span data-ttu-id="82e8a-174">**Partnertegoed voor beheerde services** wordt dagelijks bepaald en toegepast.</span><span class="sxs-lookup"><span data-stu-id="82e8a-174">**Partner earned credit for services managed** is determined and applied on a daily basis.</span></span>

- <span data-ttu-id="82e8a-175">Elke abonnementsmeter heeft een rij voor elke dag van de maand waarin het verbruik is geweest.</span><span class="sxs-lookup"><span data-stu-id="82e8a-175">Every subscription meter will have a row for every day of the month where there was consumption.</span></span>

- <span data-ttu-id="82e8a-176">In het voorbeeld hieronder:</span><span class="sxs-lookup"><span data-stu-id="82e8a-176">In the example below:</span></span>

  - <span data-ttu-id="82e8a-177">Meter die is gekwalificeerd **voor partnertegoed** voor services die worden beheerd van 7/1 - 7/3 (let op: de effectieve eenheidsprijs is de detailhandelsprijs die minder partnertegoed is.</span><span class="sxs-lookup"><span data-stu-id="82e8a-177">Meter qualified for **Partner earned credit for services managed** from 7/1 - 7/3 (note the effective unit price is retail price less partner earned credit.</span></span>

  - <span data-ttu-id="82e8a-178">Meter komt niet in aanmerking voor **partnertegoed** voor services die worden beheerd op 7-7-7-7-2017 (de effectieve eenheidsprijs is de detailhandelsprijs).</span><span class="sxs-lookup"><span data-stu-id="82e8a-178">Meter didn't qualify for **Partner earned credit for services managed** from 7/4 - 7/7 (note the effective unit price is retail price).</span></span>

  - <span data-ttu-id="82e8a-179">Meter die is gekwalificeerd **voor partnertegoed** voor services die worden beheerd van 7/8 - 7/31 (let op: de effectieve eenheidsprijs is de detailhandelsprijs die minder partnertegoed is).</span><span class="sxs-lookup"><span data-stu-id="82e8a-179">Meter qualified for **Partner earned credit for services managed** from 7/8 - 7/31 (note the effective unit price is retail price less partner earned credit).</span></span>

   :::image type="content" source="images/azure/pecfinal.png" alt-text="recon2.":::

## <a name="invoice-in-customer-currency"></a><span data-ttu-id="82e8a-181">Factuur in klantvaluta</span><span class="sxs-lookup"><span data-stu-id="82e8a-181">Invoice in customer currency</span></span>

<span data-ttu-id="82e8a-182">Azure-services via een Azure-plan worden in USD geprijsd en gefactureerd in de door de klant toegewezen valuta in het land van de klant.</span><span class="sxs-lookup"><span data-stu-id="82e8a-182">Azure services through an Azure plan will be priced in USD and billed in the customer country assigned currency.</span></span> <span data-ttu-id="82e8a-183">Als de factureringsvaluta niet usd is, wordt het gebruikte valutatarief (Foreign Exchange) weergegeven op de laatste pagina van de factuur.</span><span class="sxs-lookup"><span data-stu-id="82e8a-183">If the billing currency is non-USD, then the Foreign exchange (FX) rate used will be shown on the last page of the invoice.</span></span> <span data-ttu-id="82e8a-184">FX-tarieven worden maandelijks bepaald en toegepast op de volgende factuur.</span><span class="sxs-lookup"><span data-stu-id="82e8a-184">FX rates are determined monthly and applied to the following invoice.</span></span> <span data-ttu-id="82e8a-185">Voor een volledige lijst met landvaluta bekijkt u de nieuwe commerceaanbiedingen voor de beschikbaarheid van landen en [de valutamatrix van klanten.](https://go.microsoft.com/fwlink/?linkid=2112354)</span><span class="sxs-lookup"><span data-stu-id="82e8a-185">For a full list of country currencies, please view the [new commerce offers country availability and customer currency matrix](https://go.microsoft.com/fwlink/?linkid=2112354).</span></span>

<span data-ttu-id="82e8a-186">Microsoft volgt de London Stock Exchange voor conversie.</span><span class="sxs-lookup"><span data-stu-id="82e8a-186">Microsoft follows the London Stock Exchange for conversion.</span></span> <span data-ttu-id="82e8a-187">We gebruiken de wisselkoers, die gelijk is aan de wisselkoers die is vastgelegd op de laatste seconde van de laatste werkdag van de maand op de London Stock Exchange.</span><span class="sxs-lookup"><span data-stu-id="82e8a-187">We use the exchange rate, which is equal to the exchange rate captured on the last second of the last business day of the month on the London Stock Exchange.</span></span> <span data-ttu-id="82e8a-188">De FX-tarieven worden vernieuwd en beschikbaar op de dag vóór de eerste van de maand waarvoor ze van toepassing zijn.</span><span class="sxs-lookup"><span data-stu-id="82e8a-188">The FX rates will be refreshed and available on the day before the first of the month for which they apply.</span></span>

## <a name="azure-reservations"></a><span data-ttu-id="82e8a-189">Azure-reserveringen</span><span class="sxs-lookup"><span data-stu-id="82e8a-189">Azure reservations</span></span>


<span data-ttu-id="82e8a-190">Als u [Azure-reserveringen aanschaft](azure-reservations.md) via een Azure-abonnement, kunt u kiezen voor een een-keer- of maandelijkse facturering.</span><span class="sxs-lookup"><span data-stu-id="82e8a-190">If purchasing [Azure reservations](azure-reservations.md) through an Azure plan, you can choose either one-time or monthly billing.</span></span>


## <a name="azure-spending"></a><span data-ttu-id="82e8a-191">Uitgaven voor Azure</span><span class="sxs-lookup"><span data-stu-id="82e8a-191">Azure spending</span></span>

<span data-ttu-id="82e8a-192">De bestaande Azure-bestedingservaring wordt bijgewerkt ter ondersteuning van de nieuwe facturering van Azure-plannen in Partner Center.</span><span class="sxs-lookup"><span data-stu-id="82e8a-192">The existing Azure spending experience is updated to support the new Azure plan billing in Partner Center.</span></span> <span data-ttu-id="82e8a-193">Hierdoor kunnen partners:</span><span class="sxs-lookup"><span data-stu-id="82e8a-193">This enables partners to:</span></span>

- <span data-ttu-id="82e8a-194">Waarschuwingen weergeven, beheren en ontvangen voor budgetten die zijn ingesteld op klantniveau</span><span class="sxs-lookup"><span data-stu-id="82e8a-194">View, manage, and receive alerts for budget set at a customer level</span></span> 

- <span data-ttu-id="82e8a-195">Totale geschatte uitgaven voor een Azure-plan weergeven (onderverdeeld op resource- en meterniveau)</span><span class="sxs-lookup"><span data-stu-id="82e8a-195">View total estimated spending on an Azure plan (broken down by resource and meter level)</span></span>

<span data-ttu-id="82e8a-196">Omdat het factureringsmodel voor Azure-services via een Azure-plan gebruik na betaling is, kunnen partners een maandelijks budget toepassen en het gebruikspercentage bijhouden om een hogere factuur te voorkomen dan verwacht.</span><span class="sxs-lookup"><span data-stu-id="82e8a-196">Because the billing model for Azure services through an Azure plan is post-pay consumption, to avoid a bigger bill than anticipated, partners can apply a monthly budget and track the percentage of usage.</span></span> <span data-ttu-id="82e8a-197">Een budget kan worden toegepast op één klant of meerdere klanten tegelijk.</span><span class="sxs-lookup"><span data-stu-id="82e8a-197">A budget can be applied to one customer or multiple customers at one time.</span></span> 

:::image type="content" source="images/azure/azurespend.png" alt-text="Azure-uitgaven.":::

## <a name="next-steps"></a><span data-ttu-id="82e8a-199">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="82e8a-199">Next steps</span></span>

- <span data-ttu-id="82e8a-200">Zie hoe het partnertegoed (PEC) wordt berekend.</span><span class="sxs-lookup"><span data-stu-id="82e8a-200">See how the partner earned credit (PEC) is calculated.</span></span> <span data-ttu-id="82e8a-201">Meld u aan Partner Center [dashboard en](https://partner.microsoft.com/dashboard/) zoek de prijslijst die beschikbaar is.</span><span class="sxs-lookup"><span data-stu-id="82e8a-201">Sign into the Partner Center [dashboard](https://partner.microsoft.com/dashboard/) and locate the price list available.</span></span>

- <span data-ttu-id="82e8a-202">Meer informatie over [het kopen van het Azure-abonnement](purchase-azure-plan.md)</span><span class="sxs-lookup"><span data-stu-id="82e8a-202">Learn about [purchasing the Azure plan](purchase-azure-plan.md)</span></span>

- <span data-ttu-id="82e8a-203">Zie de [prijslijst voor de nieuwe commerce-ervaring in CSP](azure-plan-price-list.md)</span><span class="sxs-lookup"><span data-stu-id="82e8a-203">See the [price list for the new commerce experience in CSP](azure-plan-price-list.md)</span></span>
