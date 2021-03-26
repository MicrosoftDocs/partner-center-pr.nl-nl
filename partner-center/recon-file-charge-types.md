---
title: Kostentypen voor afstemmingsbestanden
ms.topic: article
ms.date: 06/05/2020
description: Ontdek de typen kosten (zoals, op gebruik gebaseerde en eenmalige), tegoeden en kortingen in Partner Center-afstemmings bestanden.
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
author: sodeb
ms.author: sodeb
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: ba42ac5beb28a3cf819c54a86385fb79853cdcd0
ms.sourcegitcommit: 700150044ea4f1a0b96cb4caeb97d7197da29ef6
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/25/2021
ms.locfileid: "105549223"
---
# <a name="understand-the-different-charge-types-in-partner-center-reconciliation-files"></a><span data-ttu-id="1e131-103">Meer informatie over de verschillende kosten typen in Partner Center reconciliatie bestanden</span><span class="sxs-lookup"><span data-stu-id="1e131-103">Understand the different charge types in Partner Center reconciliation files</span></span>

<span data-ttu-id="1e131-104">**Van toepassing op**</span><span class="sxs-lookup"><span data-stu-id="1e131-104">**Applies to**</span></span>

- <span data-ttu-id="1e131-105">Partner centrum voor micro soft Government Cloud</span><span class="sxs-lookup"><span data-stu-id="1e131-105">Partner Center for Microsoft Government cloud</span></span>

<span data-ttu-id="1e131-106">**Juiste rollen**</span><span class="sxs-lookup"><span data-stu-id="1e131-106">**Appropriate roles**</span></span>

- <span data-ttu-id="1e131-107">Beheer agent</span><span class="sxs-lookup"><span data-stu-id="1e131-107">Admin agent</span></span>
- <span data-ttu-id="1e131-108">Factureringsbeheerder</span><span class="sxs-lookup"><span data-stu-id="1e131-108">Billing admin</span></span>
- <span data-ttu-id="1e131-109">Globale beheerder</span><span class="sxs-lookup"><span data-stu-id="1e131-109">Global admin</span></span>

<span data-ttu-id="1e131-110">In dit artikel worden de toewijzingen beschreven tussen een factuur gedeelte en gekoppelde kosten typen die mogelijk in uw afstemmings bestand staan.</span><span class="sxs-lookup"><span data-stu-id="1e131-110">This article describes the mappings between an invoice section and associated charge types that might be on your reconciliation file.</span></span> <span data-ttu-id="1e131-111">Uw factuur bevat een samen vatting van de kosten.</span><span class="sxs-lookup"><span data-stu-id="1e131-111">Your invoice provides a summary of charges.</span></span> <span data-ttu-id="1e131-112">Uw afstemmings bestand bevat een gedetailleerde verdeling van trans acties met regel items, inclusief kosten typen.</span><span class="sxs-lookup"><span data-stu-id="1e131-112">Your reconciliation file provides a detailed breakdown of line-item transactions, including charge types.</span></span> <span data-ttu-id="1e131-113">Zie [reconciliatie bestanden gebruiken](use-the-reconciliation-files.md)voor meer informatie over het afstemmen van bestanden.</span><span class="sxs-lookup"><span data-stu-id="1e131-113">For more information on reconciliation files, see [how to use reconciliation files](use-the-reconciliation-files.md).</span></span>

<span data-ttu-id="1e131-114">Zowel [afstemmings bestanden op basis van gebruik](usage-based-recon-files.md) en [afstemmings bestanden op basis van een licentie](license-based-recon-files.md) geven alleen gebruiks gerelateerde trans acties en kosten (verbruikte eenheden en gerelateerde kosten) weer.</span><span class="sxs-lookup"><span data-stu-id="1e131-114">Both [usage-based reconciliation files](usage-based-recon-files.md) and [license-based reconciliation files](license-based-recon-files.md) only show usage-related transactions and charges (units consumed and related charges).</span></span>

> [!NOTE]
> <span data-ttu-id="1e131-115">Eenmalige kredieten, kortingen of terugstortingen die worden weer gegeven op de factuur als **aanpassingen** , worden niet weer gegeven in het afstemmings bestand.</span><span class="sxs-lookup"><span data-stu-id="1e131-115">One-off credits, discounts or refunds that appear on the invoice as **Adjustments** are not shown in the reconciliation file.</span></span>

## <a name="map-charge-types-to-invoice-charges"></a><span data-ttu-id="1e131-116">Kosten typen toewijzen aan facturerings kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-116">Map charge types to invoice charges</span></span>

<span data-ttu-id="1e131-117">Gebruik de filter opties in micro soft Excel om de bedragen te verdelen tussen uw factuur-en afstemmings bestand.</span><span class="sxs-lookup"><span data-stu-id="1e131-117">To cross-reference charge amounts between your invoice and reconciliation file, use the filter options in Microsoft Excel.</span></span> <span data-ttu-id="1e131-118">Filter op kosten typen in het afstemmings bestand om de kosten van de factuur toe te wijzen aan een set toeslag uitsplitsingen in het afstemmings bestand.</span><span class="sxs-lookup"><span data-stu-id="1e131-118">Filter by charge types on your reconciliation file to map the invoice charges to a set of charge breakdowns on the reconciliation file.</span></span>

## <a name="license-based-charges"></a><span data-ttu-id="1e131-119">Kosten op basis van licenties</span><span class="sxs-lookup"><span data-stu-id="1e131-119">License-based charges</span></span>

<span data-ttu-id="1e131-120">Als u deze kosten op basis van licenties aan uw factuur wilt toewijzen, moet u de kolom **bedrag** in het bestand op basis van licentie optellen.</span><span class="sxs-lookup"><span data-stu-id="1e131-120">To map these license-based charges to your invoice, sum the **Amount** column from the license-based file.</span></span>

| <span data-ttu-id="1e131-121">Beschrijving van kosten (kolom ChargeType in afstemmings bestand)</span><span class="sxs-lookup"><span data-stu-id="1e131-121">Charge description (ChargeType column in reconciliation file)</span></span> | <span data-ttu-id="1e131-122">Uitleg bij kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-122">Charge explanation</span></span> |
| ------------------------------------------------------------- | ------------------ |
| <span data-ttu-id="1e131-123">Activerings kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-123">Activation fee</span></span> | <span data-ttu-id="1e131-124">De hoeveelheid die bij de klant in rekening wordt gebracht wanneer deze na de aankoop gebruikmaakt van het abonnement.</span><span class="sxs-lookup"><span data-stu-id="1e131-124">The amount charged to the customer when they use the subscription after purchase.</span></span> |
| <span data-ttu-id="1e131-125">Annulerings kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-125">Cancel fee</span></span> | <span data-ttu-id="1e131-126">Gefactureerde kosten worden aan de klant gerestitueerd wanneer de gekoppelde licenties worden gewijzigd.</span><span class="sxs-lookup"><span data-stu-id="1e131-126">Prorated charges refunded to the customer when associated licenses are changed.</span></span> |
| <span data-ttu-id="1e131-127">Exemplaar van prorente annuleren</span><span class="sxs-lookup"><span data-stu-id="1e131-127">Cancel instance prorate</span></span> | <span data-ttu-id="1e131-128">Gefactureerde kosten worden geannuleerd wanneer de klant met een maandelijks abonnement abonnementen heeft opgeschort en de bijbehorende licenties zijn gewijzigd binnen dezelfde maand.</span><span class="sxs-lookup"><span data-stu-id="1e131-128">Prorated charges canceled when customer with monthly subscription has subscription suspended and associated licenses changed within the same month.</span></span> |
| <span data-ttu-id="1e131-129">Cyclus kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-129">Cycle fee</span></span> | <span data-ttu-id="1e131-130">Periodieke kosten voor een abonnement.</span><span class="sxs-lookup"><span data-stu-id="1e131-130">Periodic charges for a subscription.</span></span> |
| <span data-ttu-id="1e131-131">Cyclus exemplaar prorente</span><span class="sxs-lookup"><span data-stu-id="1e131-131">Cycle instance prorate</span></span> | <span data-ttu-id="1e131-132">De geraamde kosten die van de klant worden berekend wanneer de gekoppelde licenties worden gewijzigd.</span><span class="sxs-lookup"><span data-stu-id="1e131-132">Prorated charges assessed from the customer when associated licenses are changed.</span></span> |
| <span data-ttu-id="1e131-133">Tarief vergoedingen wanneer annuleren</span><span class="sxs-lookup"><span data-stu-id="1e131-133">Prorate fees when cancel</span></span> | <span data-ttu-id="1e131-134">Gefactureerde restitutie voor ongebruikt servicef onderdeel na annulering.</span><span class="sxs-lookup"><span data-stu-id="1e131-134">Prorated refund for unused portion of service upon cancellation.</span></span> |
| <span data-ttu-id="1e131-135">Kosten evenredigheid bij het converteren van de huidige aanbieding</span><span class="sxs-lookup"><span data-stu-id="1e131-135">Prorate fees when convert away from current offering</span></span> | <span data-ttu-id="1e131-136">Gefactureerde kosten na de conversie van het huidige maandelijkse abonnement op een jaar abonnement.</span><span class="sxs-lookup"><span data-stu-id="1e131-136">Prorated charges after converting away from the current monthly subscription to an annual subscription.</span></span> |
| <span data-ttu-id="1e131-137">Kosten per tarief bij conversie naar een nieuwe aanbieding</span><span class="sxs-lookup"><span data-stu-id="1e131-137">Prorate fees when convert to a new offering</span></span> | <span data-ttu-id="1e131-138">Gefactureerde kosten nadat een maandelijks abonnement is geconverteerd naar een nieuw jaarlijks abonnement.</span><span class="sxs-lookup"><span data-stu-id="1e131-138">Prorated charges after converting a monthly subscription to a new annual subscription.</span></span> |
| <span data-ttu-id="1e131-139">Tarief vergoedingen bij aankoop</span><span class="sxs-lookup"><span data-stu-id="1e131-139">Prorate fees when purchase</span></span> | <span data-ttu-id="1e131-140">Het type kosten voor een abonnement bij het gebruik van zowel maandelijkse als jaarlijkse facturering.</span><span class="sxs-lookup"><span data-stu-id="1e131-140">The charge type for a subscription when using both monthly or annual billing.</span></span> |
| <span data-ttu-id="1e131-141">Tarief vergoeding bij verlenging</span><span class="sxs-lookup"><span data-stu-id="1e131-141">Prorate fee when renew</span></span> | <span data-ttu-id="1e131-142">Gefactureerde kosten bij het verlengen van het abonnement.</span><span class="sxs-lookup"><span data-stu-id="1e131-142">Prorated fees upon subscription renewal.</span></span> |
| <span data-ttu-id="1e131-143">Kosten verlengen</span><span class="sxs-lookup"><span data-stu-id="1e131-143">Renew fee</span></span> | <span data-ttu-id="1e131-144">Kosten voor het vernieuwen van een abonnement</span><span class="sxs-lookup"><span data-stu-id="1e131-144">Charge for renewing a subscription</span></span> |
| <span data-ttu-id="1e131-145">Tarief vergoedingen bij activeren</span><span class="sxs-lookup"><span data-stu-id="1e131-145">Prorate fees when activate</span></span> | <span data-ttu-id="1e131-146">Gefactureerde kosten van de Activering tot het einde van de facturerings periode.</span><span class="sxs-lookup"><span data-stu-id="1e131-146">Prorated fees from activation until end of billing period.</span></span> |

## <a name="one-time-charges"></a><span data-ttu-id="1e131-147">Eenmalige kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-147">One-time charges</span></span>

<span data-ttu-id="1e131-148">Als u deze eenmalige kosten aan uw factuur wilt toewijzen, moet u de kolom **bedrag** in het bestand op basis van licentie optellen.</span><span class="sxs-lookup"><span data-stu-id="1e131-148">To map these one-time charges to your invoice, sum the **Amount** column from the license-based file.</span></span>

| <span data-ttu-id="1e131-149">Beschrijving van kosten (kolom ChargeType in afstemmings bestand)</span><span class="sxs-lookup"><span data-stu-id="1e131-149">Charge description (ChargeType column in reconciliation file)</span></span> | <span data-ttu-id="1e131-150">Uitleg bij kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-150">Charge explanation</span></span> |
| ------------------------------------------------------------- | ------------------ |
| <span data-ttu-id="1e131-151">Nieuw</span><span class="sxs-lookup"><span data-stu-id="1e131-151">New</span></span> | <span data-ttu-id="1e131-152">Wordt gebruikt wanneer een nieuwe aankoop wordt gemaakt.</span><span class="sxs-lookup"><span data-stu-id="1e131-152">Used when a new purchase is created.</span></span> |
| <span data-ttu-id="1e131-153">addQuantity</span><span class="sxs-lookup"><span data-stu-id="1e131-153">addQuantity</span></span> | <span data-ttu-id="1e131-154">Wordt gebruikt in de restitutie van de oorspronkelijke aankoop en de nieuwe hoeveelheid na een verhoging.</span><span class="sxs-lookup"><span data-stu-id="1e131-154">Used in both the refund of the original purchase and the new quantity after an increase.</span></span> |
| <span data-ttu-id="1e131-155">removeQuantity</span><span class="sxs-lookup"><span data-stu-id="1e131-155">removeQuantity</span></span> | <span data-ttu-id="1e131-156">Wordt gebruikt in de restitutie van de oorspronkelijke aankoop en de nieuwe hoeveelheid na een afname.</span><span class="sxs-lookup"><span data-stu-id="1e131-156">Used in both the refund of the original purchase and the new quantity after a decrease.</span></span> |
| <span data-ttu-id="1e131-157">Annuleren</span><span class="sxs-lookup"><span data-stu-id="1e131-157">Cancel</span></span> | <span data-ttu-id="1e131-158">Wordt gebruikt wanneer een abonnement wordt geannuleerd.</span><span class="sxs-lookup"><span data-stu-id="1e131-158">Used when a subscription is canceled.</span></span> |
| <span data-ttu-id="1e131-159">Converteren</span><span class="sxs-lookup"><span data-stu-id="1e131-159">Convert</span></span> | <span data-ttu-id="1e131-160">Wordt gebruikt wanneer een licentie wordt bijgewerkt, maar het aantal licenties blijft ongewijzigd.</span><span class="sxs-lookup"><span data-stu-id="1e131-160">Used when a license is upgraded but the number of licenses remains unchanged.</span></span> |

## <a name="usage-charges"></a><span data-ttu-id="1e131-161">Gebruikskosten</span><span class="sxs-lookup"><span data-stu-id="1e131-161">Usage charges</span></span>

<span data-ttu-id="1e131-162">Als u deze gebruiks kosten aan uw factuur wilt toewijzen, moet u de kolom **PretaxCharges** in het op gebruik gebaseerde bestand opsommen.</span><span class="sxs-lookup"><span data-stu-id="1e131-162">To map these usage charges to your invoice, sum the **PretaxCharges** column from the usage-based file.</span></span>

| <span data-ttu-id="1e131-163">Beschrijving van kosten (kolom ChargeType in afstemmings bestand)</span><span class="sxs-lookup"><span data-stu-id="1e131-163">Charge description (ChargeType column in reconciliation file)</span></span> | <span data-ttu-id="1e131-164">Uitleg bij kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-164">Charge explanation</span></span> |
| ------------------------------------------------------------- | ------------------ |
| <span data-ttu-id="1e131-165">Gebruiks kosten evalueren bij annuleren</span><span class="sxs-lookup"><span data-stu-id="1e131-165">Assess usage fee when cancel</span></span> | <span data-ttu-id="1e131-166">Toegang tot gebruiks kosten na annulering voor onbetaald gebruik tijdens de huidige facturerings periode.</span><span class="sxs-lookup"><span data-stu-id="1e131-166">Access usage fee upon cancellation for unpaid usage during the current billing period.</span></span> |
| <span data-ttu-id="1e131-167">Gebruiks kosten evalueren voor de huidige cyclus</span><span class="sxs-lookup"><span data-stu-id="1e131-167">Assess usage fee for current cycle</span></span> | <span data-ttu-id="1e131-168">Gebruiks kosten voor de huidige facturerings periode.</span><span class="sxs-lookup"><span data-stu-id="1e131-168">Access usage fee for the current billing period.</span></span> |

### <a name="credits"></a><span data-ttu-id="1e131-169">Tegoeden</span><span class="sxs-lookup"><span data-stu-id="1e131-169">Credits</span></span>

<span data-ttu-id="1e131-170">Deze tegoeden toewijzen aan uw factuur:</span><span class="sxs-lookup"><span data-stu-id="1e131-170">To map these credits to your invoice:</span></span>

- <span data-ttu-id="1e131-171">Som van de **TotalForCustomer** van het bestand op basis van licentie.</span><span class="sxs-lookup"><span data-stu-id="1e131-171">Sum the **TotalForCustomer** from the license-based file.</span></span>
- <span data-ttu-id="1e131-172">Som van de kolom **PostTaxTotal** van het bestand op basis van gebruik.</span><span class="sxs-lookup"><span data-stu-id="1e131-172">Sum the **PostTaxTotal** column from the usage-based file.</span></span>

| <span data-ttu-id="1e131-173">Beschrijving van kosten (kolom ChargeType in afstemmings bestand)</span><span class="sxs-lookup"><span data-stu-id="1e131-173">Charge description (ChargeType column in reconciliation file)</span></span> | <span data-ttu-id="1e131-174">Uitleg bij kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-174">Charge explanation</span></span> |
| ------------------------------------------------------------- | ------------------ |
| <span data-ttu-id="1e131-175">Verschuiving van een regel item</span><span class="sxs-lookup"><span data-stu-id="1e131-175">Offset a line item</span></span> | <span data-ttu-id="1e131-176">Gedeeltelijke of volledige restitutie voor een regel item, inclusief BTW.</span><span class="sxs-lookup"><span data-stu-id="1e131-176">Partial or whole refund to a line item, including taxes.</span></span> |

### <a name="usage-based-discounts"></a><span data-ttu-id="1e131-177">Kortingen op basis van gebruik</span><span class="sxs-lookup"><span data-stu-id="1e131-177">Usage-based discounts</span></span>

<span data-ttu-id="1e131-178">Als u deze op gebruik gebaseerde kortingen wilt toewijzen aan uw factuur, kunt u de kolom **PretaxCharges** van het bestand op basis van gebruik opsommen.</span><span class="sxs-lookup"><span data-stu-id="1e131-178">To map these usage-based discounts to your invoice, sum the **PretaxCharges** column from the usage-based file.</span></span>

| <span data-ttu-id="1e131-179">Beschrijving van kosten (kolom ChargeType in afstemmings bestand)</span><span class="sxs-lookup"><span data-stu-id="1e131-179">Charge description (ChargeType column in reconciliation file)</span></span> | <span data-ttu-id="1e131-180">Uitleg bij kosten</span><span class="sxs-lookup"><span data-stu-id="1e131-180">Charge explanation</span></span> |
| ------------------------------------------------------------- | ------------------ |
| <span data-ttu-id="1e131-181">Activerings korting</span><span class="sxs-lookup"><span data-stu-id="1e131-181">Activation discount</span></span> | <span data-ttu-id="1e131-182">Korting toegepast wanneer het abonnement wordt geactiveerd.</span><span class="sxs-lookup"><span data-stu-id="1e131-182">Discount applied when subscription activated.</span></span> |
| <span data-ttu-id="1e131-183">Cyclus korting</span><span class="sxs-lookup"><span data-stu-id="1e131-183">Cycle discount</span></span> | <span data-ttu-id="1e131-184">Korting toegepast op periodieke kosten.</span><span class="sxs-lookup"><span data-stu-id="1e131-184">Discount applied on periodic charges.</span></span> |
| <span data-ttu-id="1e131-185">Korting vernieuwen</span><span class="sxs-lookup"><span data-stu-id="1e131-185">Renew discount</span></span> | <span data-ttu-id="1e131-186">Korting toegepast wanneer het abonnement wordt verlengd.</span><span class="sxs-lookup"><span data-stu-id="1e131-186">Discount applied when subscription renewed.</span></span> |
| <span data-ttu-id="1e131-187">Korting annuleren</span><span class="sxs-lookup"><span data-stu-id="1e131-187">Cancel discount</span></span> | <span data-ttu-id="1e131-188">Kosten worden toegepast wanneer kortingen worden geannuleerd.</span><span class="sxs-lookup"><span data-stu-id="1e131-188">Charges applied when discounts are canceled.</span></span> |

### <a name="license-based-discounts"></a><span data-ttu-id="1e131-189">Kortingen op basis van licenties</span><span class="sxs-lookup"><span data-stu-id="1e131-189">License-based discounts</span></span>

<span data-ttu-id="1e131-190">Als u kortingen op basis van licenties aan uw factuur wilt toewijzen, moet u de kolom **TotalOtherDiscount** in het bestand op basis van licentie opsommen.</span><span class="sxs-lookup"><span data-stu-id="1e131-190">To map license-based discounts to your invoice, sum the **TotalOtherDiscount** column from the license-based file.</span></span>

<span data-ttu-id="1e131-191">*Kortingen op basis van licenties kunnen worden toegepast op meerdere kosten typen.*</span><span class="sxs-lookup"><span data-stu-id="1e131-191">*License-based discounts may be applied to multiple charge types.*</span></span>
