---
title: Hoe BTW-beleid invloed heeft op de uitbetaling voor Azure Marketplace
description: Meer informatie over hoe BTW-beleid invloed heeft op de uitbetaling voor Azure Marketplace.
ms.topic: conceptual
ms.service: partner-dashboard
author: mingshen-ms
ms.author: mingshen
ms.date: 02/09/2021
ms.openlocfilehash: 3630824c839ccd9f54f3e8e5199a573b5824bb91
ms.sourcegitcommit: bff907bdbddc769716c7418a2b4a94ca37c2d590
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/03/2021
ms.locfileid: "101758888"
---
# <a name="how-tax-policies-affect-payout-for-azure-marketplace"></a><span data-ttu-id="016a1-103">Hoe BTW-beleid invloed heeft op de uitbetaling voor Azure Marketplace</span><span class="sxs-lookup"><span data-stu-id="016a1-103">How tax policies affect payout for Azure Marketplace</span></span>

<span data-ttu-id="016a1-104">**Juiste rollen**</span><span class="sxs-lookup"><span data-stu-id="016a1-104">**Appropriate roles**</span></span>
-    <span data-ttu-id="016a1-105">Globale beheerder</span><span class="sxs-lookup"><span data-stu-id="016a1-105">Global admin</span></span>
-    <span data-ttu-id="016a1-106">Gebruikersbeheerder</span><span class="sxs-lookup"><span data-stu-id="016a1-106">User admin</span></span>
-    <span data-ttu-id="016a1-107">Beheer agent</span><span class="sxs-lookup"><span data-stu-id="016a1-107">Admin agent</span></span>

## <a name="introduction"></a><span data-ttu-id="016a1-108">Introductie</span><span class="sxs-lookup"><span data-stu-id="016a1-108">Introduction</span></span>

<span data-ttu-id="016a1-109">Micro soft Commercial Marketplace heeft wereld wijde bereik.</span><span class="sxs-lookup"><span data-stu-id="016a1-109">The Microsoft commercial marketplace has global reach.</span></span> <span data-ttu-id="016a1-110">Trans acties vinden plaats in de grenzen en afhankelijk van waar de ISV en de klant zich bevinden, kunnen de gevolgen voor de belasting verschillen.</span><span class="sxs-lookup"><span data-stu-id="016a1-110">Transactions occur across borders and depending on where the ISV and the customer are located, tax implications can vary.</span></span> <span data-ttu-id="016a1-111">Microsoft AppSource en Azure Marketplace gebruiken de gegevens van het Partner Center-BTW-profiel om het land van de ISV te bepalen.</span><span class="sxs-lookup"><span data-stu-id="016a1-111">Microsoft AppSource and Azure Marketplace use the Partner Center Tax Profile Information to determine the ISV's country.</span></span> <span data-ttu-id="016a1-112">Om het land van de klant te bepalen, kunt u de facturerings gegevens van de klant gebruiken of, als de klant zich in de EU bevindt, twee verschillende gegevens gebruiken.</span><span class="sxs-lookup"><span data-stu-id="016a1-112">To determine the customer's country, either use the customer's billing information or, if the customer is in the EU, we use two different pieces of information.</span></span>

<span data-ttu-id="016a1-113">Raadpleeg de tabel [Tax Details voor meer](tax-details-marketplace.md) informatie over de volgende scenario's, waarin wordt weer gegeven of micro soft belasting namens de uitgever verzamelt en betaalt, of dat de verantwoordelijkheid bij de uitgever hoort.</span><span class="sxs-lookup"><span data-stu-id="016a1-113">To better understand the following scenarios, refer to the [Tax details](tax-details-marketplace.md) table, which shows whether Microsoft collects and pays taxes on behalf of the publisher or if that responsibility belongs to the publisher.</span></span>

> [!NOTE]
> <span data-ttu-id="016a1-114">Alle voor beelden van verkoop waarden en BTW-percentages in dit onderwerp zijn alleen ter illustratie, niet van de exacte cijfers.</span><span class="sxs-lookup"><span data-stu-id="016a1-114">All examples sale values and tax percentages in this topic are for illustrative purposes only, not exact figures.</span></span>

## <a name="publisher-transacts-in-microsoft-managed-tax-country"></a><span data-ttu-id="016a1-115">Publisher transacties in het land van door micro soft beheerde belasting</span><span class="sxs-lookup"><span data-stu-id="016a1-115">Publisher Transacts in Microsoft-managed Tax Country</span></span>

<span data-ttu-id="016a1-116">**Scenario A** : trans acties die plaatsvinden tussen een uitgever en een klant in een door [micro soft beheerd fiscaal land](tax-details-marketplace.md#microsoft-managed-countries).</span><span class="sxs-lookup"><span data-stu-id="016a1-116">**Scenario A** – Transactions that take place between a publisher and a customer in a [Microsoft-managed tax country](tax-details-marketplace.md#microsoft-managed-countries).</span></span> <span data-ttu-id="016a1-117">Deze trans acties zijn van toepassing op de belasting die op het moment van de verkoop geldt, en micro soft stuurt deze belasting naar het betreffende land.</span><span class="sxs-lookup"><span data-stu-id="016a1-117">These transactions will have applicable tax added at the time of sale and Microsoft sends that tax to the applicable country.</span></span> <span data-ttu-id="016a1-118">Er worden geen BTW-afbetalingen afgehouden van de toekenning en de uitbetalings berekeningen zijn exclusief BTW.</span><span class="sxs-lookup"><span data-stu-id="016a1-118">No taxes are withheld from payout and payout calculations are tax exclusive.</span></span>

<span data-ttu-id="016a1-119">Zie [Scenario D](#foreign-publisher-transacts-with-us-customer) voor trans acties tussen een niet-Amerikaanse uitgever en een klant van de VS.</span><span class="sxs-lookup"><span data-stu-id="016a1-119">See [Scenario D](#foreign-publisher-transacts-with-us-customer) for transactions between a non-US publisher and a US customer.</span></span>

:::image type="content" source="images/tax-policies/payout-scenario-a.png" alt-text="Geeft werk stroom weer voor het uitbetalings proces scenario A.":::

## <a name="publisher-transacts-in-microsoft-managed-tax-country-where-marketplace-fee-is-taxable-service"></a><span data-ttu-id="016a1-121">Publisher transvindt zich in het land van micro soft Managed Tax waarbij de kosten voor Marketplace de belastde service zijn</span><span class="sxs-lookup"><span data-stu-id="016a1-121">Publisher Transacts in Microsoft-managed Tax Country where Marketplace Fee is Taxable Service</span></span>

<span data-ttu-id="016a1-122">**Scenario B** : trans acties die plaatsvinden tussen een US-gebaseerde Uitgever (zoals gedefinieerd door de informatie over het BTW-Profiel van de Partner Center) naar een klant in een door micro soft beheerd fiscaal land waar het land een belasting oplegt van de kosten voor Marketplace (een belaste dienst).</span><span class="sxs-lookup"><span data-stu-id="016a1-122">**Scenario B** – Transactions that take place between a US-based publisher (as defined by their Partner Center Tax Profile Information) to a customer in a Microsoft-managed tax country where the country imposes a tax on the Marketplace Fee (a taxable service).</span></span> <span data-ttu-id="016a1-123">In dit scenario wordt de belasting van de winkel service-kosten afgetrokken van de uitbetaling van de uitgever.</span><span class="sxs-lookup"><span data-stu-id="016a1-123">In this scenario, the tax on the store service fee is subtracted from the publisher's payout.</span></span>

:::image type="content" source="images/tax-policies/payout-scenario-b.png" alt-text="Geeft werk stroom voor het uitbetalings proces scenario B weer.":::

## <a name="publisher-transacts-in-publisher-managed-tax-country"></a><span data-ttu-id="016a1-125">Publisher communiceert in een door Publisher beheerd land van belasting</span><span class="sxs-lookup"><span data-stu-id="016a1-125">Publisher Transacts in Publisher-managed Tax Country</span></span>

<span data-ttu-id="016a1-126">**Scenario C** : trans acties die worden uitgevoerd tussen een uitgever en een klant in een door de uitgever beheerd fiscaal land dat geen bron belasting voor klanten oplegt.</span><span class="sxs-lookup"><span data-stu-id="016a1-126">**Scenario C** – Transactions that take place between a publisher and a customer in a publisher-managed tax country that does not impose a withholding tax on customers.</span></span> <span data-ttu-id="016a1-127">Klanten betalen geen BTW op het verkoop punt en het is de verplichting van de uitgever om alle toepasselijke belastingen te betalen.</span><span class="sxs-lookup"><span data-stu-id="016a1-127">Customers pay no tax at the point of sale and it is the publisher's obligation to pay all applicable taxes.</span></span>

<span data-ttu-id="016a1-128">Zie [Abonnementen en prijzen voor commerciële Marketplace-aanbiedingen](https://docs.microsoft.com/azure/marketplace/plans-pricing#custom-prices)voor meer informatie over landspecifieke prijzen (bijvoorbeeld om toekomstige belasting te verrekenen).</span><span class="sxs-lookup"><span data-stu-id="016a1-128">For more information on country-specific pricing (for example, to offset upcoming taxation) see [Plans and pricing for commercial marketplace offers](https://docs.microsoft.com/azure/marketplace/plans-pricing#custom-prices).</span></span>

:::image type="content" source="images/tax-policies/payout-scenario-c.png" alt-text="Geeft werk stroom weer voor het uitbetalings proces scenario C.":::

## <a name="foreign-publisher-transacts-with-us-customer"></a><span data-ttu-id="016a1-130">Afwijkende Uitgever communiceert met de klanten van de VS</span><span class="sxs-lookup"><span data-stu-id="016a1-130">Foreign Publisher Transacts with US Customer</span></span>

<span data-ttu-id="016a1-131">**Scenario D** : alle externe uitgevers (zoals gedefinieerd door de informatie over het BTW-Profiel van het partner centrum) in landen zonder een Amerikaanse Verdrag (Zie [scenario E](#foreign-publisher-with-a-treaty-transacts-with-us-customer)) een verkoop aan een klant in de VS (zoals gedefinieerd door het adres van de klant account).</span><span class="sxs-lookup"><span data-stu-id="016a1-131">**Scenario D** – All foreign publishers (as defined by their Partner Center Tax Profile Information) in countries without a US treaty (see [Scenario E](#foreign-publisher-with-a-treaty-transacts-with-us-customer)) making a sale to a US-based customer (as defined by their customer account address).</span></span> <span data-ttu-id="016a1-132">Voor de Amerikaanse overheid moet de belasting van micro soft worden geheven namens de uitgever.</span><span class="sxs-lookup"><span data-stu-id="016a1-132">US government requires that Microsoft withhold tax on behalf of the publisher.</span></span> <span data-ttu-id="016a1-133">De BTW van de betaling aan de uitgever wordt berekend op basis van de prijs van de aanbieding.</span><span class="sxs-lookup"><span data-stu-id="016a1-133">Tax withheld from payout to publisher is calculated based on offer price.</span></span>

:::image type="content" source="images/tax-policies/payout-scenario-d.png" alt-text="Geeft werk stroom weer voor het uitbetalings proces scenario D.":::

## <a name="foreign-publisher-with-a-treaty-transacts-with-us-customer"></a><span data-ttu-id="016a1-135">Afwijkende uitgever met een Verdrag draagt bij aan de klant</span><span class="sxs-lookup"><span data-stu-id="016a1-135">Foreign publisher with a Treaty Transacts with US customer</span></span>

<span data-ttu-id="016a1-136">**Scenario E** : alle externe uitgevers (zoals gedefinieerd door de informatie over het BTW-Profiel van de Partner Center) in landen met een Amerikaanse Verdrag, waarbij een verkoop wordt gedaan aan een klant die is gebaseerd op de klant (zoals gedefinieerd in het adres van hun klanten account).</span><span class="sxs-lookup"><span data-stu-id="016a1-136">**Scenario E** – All foreign publishers (as defined by their Partner Center Tax Profile Information) in countries with a US treaty making a sale to a US-based customer (as defined by their customer account address).</span></span> <span data-ttu-id="016a1-137">Voor Amerikaanse overheid is micro soft niet verplicht om de belasting namens de uitgever te inhouden.</span><span class="sxs-lookup"><span data-stu-id="016a1-137">US government does not require Microsoft to withhold tax on behalf of the publisher.</span></span>

:::image type="content" source="images/tax-policies/payout-scenario-e.png" alt-text="Geeft werk stroom weer voor het uitbetalings proces scenario E.":::

## <a name="foreign-publisher-sells-to-an-eu-vat-registered-customer-in-a-microsoft-managed-country-outside-ireland"></a><span data-ttu-id="016a1-139">Afwijkende Uitgever verkoopt aan een BTW-geregistreerde klant in een door micro soft beheerd land (buiten Ierland)</span><span class="sxs-lookup"><span data-stu-id="016a1-139">Foreign publisher sells to an EU VAT-registered customer in a Microsoft-managed country (outside Ireland)</span></span>

<span data-ttu-id="016a1-140">**Scenario F** : alle trans acties tussen externe uitgevers en de BTW-geregistreerde klanten van de EU (buiten Ierland) in een Microsoft-Managed land.</span><span class="sxs-lookup"><span data-stu-id="016a1-140">**Scenario F** – All transactions between foreign publishers and EU VAT-registered customers (outside Ireland) in a Microsoft-Managed country.</span></span> <span data-ttu-id="016a1-141">De klant betaalt geen belasting op de verkoop.</span><span class="sxs-lookup"><span data-stu-id="016a1-141">The customer does not pay tax on the sale.</span></span>

:::image type="content" source="images/tax-policies/payout-scenario-f.png" alt-text="Geeft werk stroom weer voor het uitbetalings proces scenario F.":::

## <a name="foreign-publisher-sells-to-an-eu-vat-registered-customer-in-a-microsoft-managed-country-in-ireland"></a><span data-ttu-id="016a1-143">Afwijkende Uitgever verkoopt aan een BTW-geregistreerde klant in een door micro soft beheerd land (in Ierland)</span><span class="sxs-lookup"><span data-stu-id="016a1-143">Foreign publisher sells to an EU VAT-registered customer in a Microsoft-managed country (in Ireland)</span></span>

<span data-ttu-id="016a1-144">**Scenario G** : alle trans acties tussen externe uitgevers en de BTW-geregistreerde klanten van de EU (in Ierland) in een Microsoft-Managed land.</span><span class="sxs-lookup"><span data-stu-id="016a1-144">**Scenario G** – All transactions between foreign publishers and EU VAT-registered customers (inside Ireland) in a Microsoft-Managed country.</span></span> <span data-ttu-id="016a1-145">De klant betaalt Ierse BTW en micro soft betaalt deze belasting aan de Ierse overheid.</span><span class="sxs-lookup"><span data-stu-id="016a1-145">The customer pays Irish VAT and Microsoft pays this tax to the Irish government.</span></span>

:::image type="content" source="images/tax-policies/payout-scenario-g.png" alt-text="Geeft werk stroom weer voor het uitbetalings proces scenario G.":::

## <a name="next-steps"></a><span data-ttu-id="016a1-147">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="016a1-147">Next steps</span></span>

- [<span data-ttu-id="016a1-148">Veelgestelde vragen over Uitgever</span><span class="sxs-lookup"><span data-stu-id="016a1-148">Publisher FAQ</span></span>](https://docs.microsoft.com/azure/marketplace/marketplace-faq-publisher-guide)
- [<span data-ttu-id="016a1-149">Instructies voor het maken van betalings-en belasting profielen</span><span class="sxs-lookup"><span data-stu-id="016a1-149">Instructions to create payment and tax profiles</span></span>](https://docs.microsoft.com/partner-center/set-up-your-payout-account?context=/azure/marketplace/context/context#create-a-payment-profile)
