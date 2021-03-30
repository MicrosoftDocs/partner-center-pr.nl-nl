---
title: Uw afstemmings bestanden gebruiken
ms.topic: article
ms.date: 03/26/2021
description: Meer informatie over reconciliatie bestanden in het partner centrum en het interpreteren van gedetailleerde weer gaven van het regel item van kosten voor een bepaalde facturerings cyclus.
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
author: sodeb
ms.author: sodeb
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: aefd5258c778fd8a7b92bfe49f245bf818497fb8
ms.sourcegitcommit: dd51744a4af3797493a5ebbfc766dab86ff00477
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/29/2021
ms.locfileid: "105730076"
---
# <a name="learn-how-to-read-the-line-items-in-your-partner-center-reconciliation-files"></a><span data-ttu-id="c0eb4-103">Meer informatie over het lezen van regel items in uw partner centrum-afstemmings bestanden</span><span class="sxs-lookup"><span data-stu-id="c0eb4-103">Learn how to read the line items in your Partner Center reconciliation files</span></span>

<span data-ttu-id="c0eb4-104">**Juiste rollen**</span><span class="sxs-lookup"><span data-stu-id="c0eb4-104">**Appropriate roles**</span></span>

- <span data-ttu-id="c0eb4-105">Factureringsbeheerder</span><span class="sxs-lookup"><span data-stu-id="c0eb4-105">Billing admin</span></span>
- <span data-ttu-id="c0eb4-106">Globale beheerder</span><span class="sxs-lookup"><span data-stu-id="c0eb4-106">Global admin</span></span>

<span data-ttu-id="c0eb4-107">U kunt uw afstemmings bestanden downloaden van het partner centrum voor een gedetailleerde weer gave van regel items van elke kosten in een facturerings cyclus.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-107">You can download your reconciliation files from Partner Center for a detailed, line-item view of each charge in a billing cycle.</span></span> <span data-ttu-id="c0eb4-108">Details van regel items zijn kosten voor abonnementen van elke klant en gedetailleerde gebeurtenissen (zoals een middel grote aanvulling van licenties voor een abonnement).</span><span class="sxs-lookup"><span data-stu-id="c0eb4-108">Line-item details include charges for each customer's subscriptions, and detailed events (such as a mid-term addition of licenses to a subscription).</span></span>

<span data-ttu-id="c0eb4-109">Zie [uw factuur lezen](read-your-bill.md)voor meer informatie over het lezen van uw **facturen**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-109">For information on how to read your **invoice**, see [Read your bill](read-your-bill.md).</span></span>

## <a name="understand-reconciliation-file-fields"></a><span data-ttu-id="c0eb4-110">Informatie over afstemmings bestand velden</span><span class="sxs-lookup"><span data-stu-id="c0eb4-110">Understand reconciliation file fields</span></span>

- [<span data-ttu-id="c0eb4-111">Velden voor afstemmingsbestand op basis van licentie</span><span class="sxs-lookup"><span data-stu-id="c0eb4-111">License-based reconciliation file fields</span></span>](license-based-recon-files.md)
- [<span data-ttu-id="c0eb4-112">Velden voor afstemmingsbestand op basis van gebruik</span><span class="sxs-lookup"><span data-stu-id="c0eb4-112">Usage-based reconciliation file fields</span></span>](usage-based-recon-files.md)
- [<span data-ttu-id="c0eb4-113">Velden voor afstemmingsbestand over dagelijks gebruik</span><span class="sxs-lookup"><span data-stu-id="c0eb4-113">Daily-rated usage reconciliation file fields</span></span>](daily-rated-usage-recon-files.md)
- [<span data-ttu-id="c0eb4-114">Eenmalige inkopen CSP-afstemmings bestand velden</span><span class="sxs-lookup"><span data-stu-id="c0eb4-114">One-time purchase CSP reconciliation file fields</span></span>](modern-invoice-reconciliation-file.md)

## <a name="understand-charge-types-in-reconciliation-files"></a><span data-ttu-id="c0eb4-115">Meer informatie over kosten typen in afstemmings bestanden</span><span class="sxs-lookup"><span data-stu-id="c0eb4-115">Understand charge types in reconciliation files</span></span>

<span data-ttu-id="c0eb4-116">Zie [reconciliatie bestands toeslag typen](recon-file-charge-types.md)voor meer informatie over de typen kosten in reconciliatie bestanden (de kolom **ChargeType** ).</span><span class="sxs-lookup"><span data-stu-id="c0eb4-116">To understand the types of charges in reconciliation files (the **ChargeType** column), see [Reconciliation file charge types](recon-file-charge-types.md).</span></span>

## <a name="fix-formatting-issues"></a><span data-ttu-id="c0eb4-117">Opmaak problemen oplossen</span><span class="sxs-lookup"><span data-stu-id="c0eb4-117">Fix formatting issues</span></span>

<span data-ttu-id="c0eb4-118">Af en toe kan een afstemmings bestand opmaak problemen bevatten.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-118">Occasionally, a reconciliation file might contain formatting issues.</span></span> <span data-ttu-id="c0eb4-119">Dit probleem kan bijvoorbeeld optreden als de land instelling en niet wordt gebruikt.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-119">For example, this issue might occur if the en-US locale is not used.</span></span>

<span data-ttu-id="c0eb4-120">Volg deze stappen voor het oplossen van problemen met de opmaak in uw afstemmings bestanden:</span><span class="sxs-lookup"><span data-stu-id="c0eb4-120">Follow these steps for fix any formatting issues in your reconciliation files:</span></span>

1. <span data-ttu-id="c0eb4-121">Open het afstemmings bestand (in CSV-indeling) in micro soft Excel.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-121">Open the reconciliation file (in .csv format) in Microsoft Excel.</span></span>
2. <span data-ttu-id="c0eb4-122">Selecteer de eerste kolom in het bestand.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-122">Select the first column in the file.</span></span>
3. <span data-ttu-id="c0eb4-123">Open de **wizard tekst naar kolommen converteren**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-123">Open the **Convert Text to Columns Wizard**.</span></span> <span data-ttu-id="c0eb4-124">Selecteer op het lint de optie **gegevens** en selecteer vervolgens **tekst naar kolommen**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-124">On the ribbon, select **Data**, then select **Text to Columns**.</span></span>
4. <span data-ttu-id="c0eb4-125">Selecteer in de wizard **gescheiden bestands type**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-125">In the wizard, select **Delimited file type**.</span></span> <span data-ttu-id="c0eb4-126">Selecteer vervolgens **Volgende**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-126">Then, select **Next**.</span></span>
5. <span data-ttu-id="c0eb4-127">Selecteer **komma** in het veld scheidings **tekens** .</span><span class="sxs-lookup"><span data-stu-id="c0eb4-127">In the **Delimiters** field, select **Comma**.</span></span> <span data-ttu-id="c0eb4-128">(Als **tabblad** al is geselecteerd, kunt u deze optie ingeschakeld laten.) Selecteer vervolgens **volgende**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-128">(If **Tab** is already selected, you can leave this option selected.) Then, select **Next**.</span></span>
6. <span data-ttu-id="c0eb4-129">Selecteer in het veld **kolom gegevens indeling** de optie **datum: MDJ**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-129">In the **Column data format** field, select **Date:MDY**.</span></span> <span data-ttu-id="c0eb4-130">Selecteer vervolgens **Volgende**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-130">Then, select **Next**.</span></span>
7. <span data-ttu-id="c0eb4-131">Selecteer in het veld **kolom gegevens indeling** de **tekst** voor alle bedragkolommen.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-131">In the **Column data format** field, select **Text** for all amount columns.</span></span> <span data-ttu-id="c0eb4-132">Selecteer vervolgens **Voltooien**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-132">Then, select **Finish**.</span></span>

## <a name="download-reconciliation-files-programmatically"></a><span data-ttu-id="c0eb4-133">Afstemmings bestanden programmatisch downloaden</span><span class="sxs-lookup"><span data-stu-id="c0eb4-133">Download reconciliation files programmatically</span></span>

<span data-ttu-id="c0eb4-134">Afstemmings bestanden kunnen erg groot zijn en soms moeilijk te downloaden.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-134">Reconciliation files can be very large and are sometimes difficult to download.</span></span> <span data-ttu-id="c0eb4-135">Zie [factuur regel items ophalen](/partner-center/develop/get-invoiceline-items)om de afstemmings bestanden via een programma te downloaden.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-135">To download reconciliation files programmatically, see [Get invoice line items](/partner-center/develop/get-invoiceline-items).</span></span>

## <a name="if-your-file-exceeds-the-row-limit-in-excel"></a><span data-ttu-id="c0eb4-136">Als uw bestand de rijlimiet in Excel overschrijdt</span><span class="sxs-lookup"><span data-stu-id="c0eb4-136">If your file exceeds the row limit in Excel</span></span>

<span data-ttu-id="c0eb4-137">Als u een afstemmings bestand kunt downloaden, maar niet in micro soft Excel wilt openen, betekent dit waarschijnlijk dat het bestand meer rijen bevat dan Excel toestaat.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-137">If you’re able to download a reconciliation file but not open it in Microsoft Excel, it probably means the file contains more rows than Excel will allow.</span></span> <span data-ttu-id="c0eb4-138">Als dit het geval is, kunt u een van de onderstaande procedures gebruiken om het bestand te openen.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-138">If this happens, you can use either of the procedures below to open the file.</span></span>

### <a name="open-a-recon-file-in-power-bi"></a><span data-ttu-id="c0eb4-139">Een afstemmings bestand openen in Power BI</span><span class="sxs-lookup"><span data-stu-id="c0eb4-139">Open a recon file in Power BI</span></span>

1. <span data-ttu-id="c0eb4-140">Down load het afstemmings bestand zoals u dat gewend bent.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-140">Download the reconciliation file as you normally would.</span></span>
2. <span data-ttu-id="c0eb4-141">Down load, installeer en open een exemplaar van Power BI.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-141">Download, install, and open an instance of Power BI.</span></span>
3. <span data-ttu-id="c0eb4-142">Selecteer op het tabblad Power BI **Start** de optie **gegevens ophalen**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-142">On the Power BI **Home** tab, select **Get data**.</span></span>
4. <span data-ttu-id="c0eb4-143">Selecteer in de lijst met **algemene gegevens bronnen** de optie **tekst/CSV**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-143">In the list of **Common data sources**, select **Text/CSV**.</span></span>
5. <span data-ttu-id="c0eb4-144">Open uw afstemmings bestand wanneer u hierom wordt gevraagd.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-144">When prompted, open your recon file.</span></span>

### <a name="open-a-recon-file-in-an-excel-pivot-table"></a><span data-ttu-id="c0eb4-145">Een afstemmings bestand openen in een Excel-draai tabel</span><span class="sxs-lookup"><span data-stu-id="c0eb4-145">Open a recon file in an Excel pivot table</span></span>

1. <span data-ttu-id="c0eb4-146">Down load het afstemmings bestand zoals u dat gewend bent.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-146">Download the reconciliation file as you normally would.</span></span>
2. <span data-ttu-id="c0eb4-147">Open een nieuw bestand in micro soft Excel.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-147">Open a new file in Microsoft Excel.</span></span>
3. <span data-ttu-id="c0eb4-148">Op het tabblad **gegevens** selecteert u **gegevens ophalen**, selecteert u **uit bestand** en selecteert u vervolgens **tekst/CSV**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-148">On the **Data** tab, select **Get data**, select **From file**, and then select **Text/CSV**.</span></span>
4. <span data-ttu-id="c0eb4-149">Open uw afstemmings bestand wanneer u hierom wordt gevraagd.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-149">When prompted, open your recon file.</span></span> <span data-ttu-id="c0eb4-150">Uw gegevens worden weer gegeven.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-150">Your data will appear.</span></span>
5. <span data-ttu-id="c0eb4-151">Selecteer in de vervolg keuzelijst **laden** de optie **laden naar** en klik vervolgens op **OK**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-151">In the **Load** dropdown menu, select **Load to**, and then **OK**.</span></span>
6. <span data-ttu-id="c0eb4-152">Selecteer in het dialoog venster **gegevens importeren** het **draai tabel rapport** om het bestand te openen.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-152">In the **Import Data** dialog box, select **PivotTable Report** to open your file.</span></span>

## <a name="negative-amount-displayed"></a><span data-ttu-id="c0eb4-153">Weer gegeven negatief bedrag</span><span class="sxs-lookup"><span data-stu-id="c0eb4-153">Negative amount displayed</span></span>

<span data-ttu-id="c0eb4-154">Mogelijk wordt er een negatief bedrag in het afstemmings bestand weer geven.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-154">You may see a negative amount in your reconciliation file.</span></span> <span data-ttu-id="c0eb4-155">Dit wordt waarschijnlijk veroorzaakt door een van de volgende dingen:</span><span class="sxs-lookup"><span data-stu-id="c0eb4-155">This is probably caused by one of the following things:</span></span>

- <span data-ttu-id="c0eb4-156">U hebt uw aantal licenties onlangs geannuleerd of gereduceerd</span><span class="sxs-lookup"><span data-stu-id="c0eb4-156">You recently canceled or reduced your number of licenses</span></span>
- <span data-ttu-id="c0eb4-157">U hebt een tegoed ontvangen voor een service licentieovereenkomst (SLA) of voor Azure-verbruik</span><span class="sxs-lookup"><span data-stu-id="c0eb4-157">You received credit for either a service license agreement (SLA) or for Azure consumption</span></span>

<span data-ttu-id="c0eb4-158">Als u meer informatie wilt over deze trans actie, controleert u het kenmerk van het type kosten in het afstemmings bestand.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-158">To get more information about this transaction, review its charge type attribute in your reconciliation file.</span></span>

## <a name="map-taxes-or-vat"></a><span data-ttu-id="c0eb4-159">Belastingen of BTW toewijzen</span><span class="sxs-lookup"><span data-stu-id="c0eb4-159">Map taxes or VAT</span></span>

<span data-ttu-id="c0eb4-160">BTW of belasting toegevoegde waarde (BTW) toewijzen aan uw factuur:</span><span class="sxs-lookup"><span data-stu-id="c0eb4-160">To map Taxes or value-added tax (VAT) to your invoice:</span></span>

- <span data-ttu-id="c0eb4-161">Som van de **belasting** kolom van het bestand op basis van licentie.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-161">Sum the **Tax** column from the license-based file.</span></span>
- <span data-ttu-id="c0eb4-162">Som van de kolom **TaxAmount** van het bestand op basis van gebruik.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-162">Sum the **TaxAmount** column from the usage-based file.</span></span>

## <a name="itemize-reconciliation-files-by-partner"></a><span data-ttu-id="c0eb4-163">Afstemmings bestanden specificeren op partner</span><span class="sxs-lookup"><span data-stu-id="c0eb4-163">Itemize reconciliation files by partner</span></span>

<span data-ttu-id="c0eb4-164">Partners in het **indirecte model** kunnen deze extra velden gebruiken in zowel op licenties gebaseerde afstemmings bestanden als voor het specificeren van de bestanden op reseller.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-164">Partners in the **indirect model** can use these additional fields in both license-based and usage-based reconciliation files to itemize the files by reseller.</span></span>

| <span data-ttu-id="c0eb4-165">MPN-id</span><span class="sxs-lookup"><span data-stu-id="c0eb4-165">MPN ID</span></span> | <span data-ttu-id="c0eb4-166">Beschrijving</span><span class="sxs-lookup"><span data-stu-id="c0eb4-166">Description</span></span> |
| ------ | ----------- |
| <span data-ttu-id="c0eb4-167">MPN-id</span><span class="sxs-lookup"><span data-stu-id="c0eb4-167">MPN ID</span></span> | <span data-ttu-id="c0eb4-168">De Microsoft Partner Network-ID (MPN) van de Cloud Solution Provider (CSP)-partner (direct of indirect).</span><span class="sxs-lookup"><span data-stu-id="c0eb4-168">The Microsoft Partner Network (MPN) identifier of the Cloud Solution Provider (CSP) partner (direct or indirect).</span></span> |
| [<span data-ttu-id="c0eb4-169">Reseller MPN-ID</span><span class="sxs-lookup"><span data-stu-id="c0eb4-169">Reseller MPN ID</span></span>](#reseller-mpn-id) | <span data-ttu-id="c0eb4-170">De [MPN-id van de dealer van de record voor het abonnement](#reseller-mpn-id).</span><span class="sxs-lookup"><span data-stu-id="c0eb4-170">The [MPN identifier of the reseller of record for the subscription](#reseller-mpn-id).</span></span> <span data-ttu-id="c0eb4-171">Dit veld komt overeen met de wederverkoper-ID die wordt vermeld voor het specifieke abonnement in partner centrum.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-171">This field corresponds to the reseller ID listed for the specific subscription in Partner Center.</span></span> <span data-ttu-id="c0eb4-172">Wordt alleen weer gegeven voor reconciliatie bestanden voor partners in het indirecte model.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-172">Only appears on reconciliation files for partners in the indirect model.</span></span> |

### <a name="reseller-mpn-id"></a><span data-ttu-id="c0eb4-173">Reseller MPN-ID</span><span class="sxs-lookup"><span data-stu-id="c0eb4-173">Reseller MPN ID</span></span>

<span data-ttu-id="c0eb4-174">Als een CSP-partner het abonnement rechtstreeks aan de klant heeft verkocht, wordt hun **MPN-id** twee keer vermeld, zowel de **MPN-id** als de **wederverkoper MPN-id**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-174">If a CSP partner sold the subscription directly to the customer, their **MPN ID** is listed twice, as both the **MPN ID** and the **Reseller MPN ID**.</span></span>

<span data-ttu-id="c0eb4-175">Als een CSP-partner een wederverkoper heeft zonder **MPN-id**, wordt deze waarde in plaats daarvan ingesteld op de **MPN-id** van de partner.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-175">If a CSP partner has a reseller with no **MPN ID**, this value is set to the partner's **MPN ID** instead.</span></span>

<span data-ttu-id="c0eb4-176">Als de CSP-partner een **wederverkoper MPN-id** verwijdert, wordt deze waarde ingesteld op *-1*.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-176">If the CSP partner removes a **Reseller MPN ID**, this value will be set to *-1*.</span></span>

<span data-ttu-id="c0eb4-177">De **wederverkoper MPN-id** weer geven of bijwerken:</span><span class="sxs-lookup"><span data-stu-id="c0eb4-177">To view or update the **Reseller MPN ID**:</span></span>

1. <span data-ttu-id="c0eb4-178">Meld u aan bij Partnercentrum.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-178">Sign in to Partner Center.</span></span>
2. <span data-ttu-id="c0eb4-179">Selecteer **klanten** in het menu van het partner centrum.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-179">In the Partner Center menu, select **Customers**.</span></span>
3. <span data-ttu-id="c0eb4-180">Kies de klant in de lijst.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-180">Choose the customer from the list.</span></span>
4. <span data-ttu-id="c0eb4-181">Selecteer in het menu klant de optie **abonnementen**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-181">In the customer menu, select **Subscriptions**.</span></span>
5. <span data-ttu-id="c0eb4-182">Kies het abonnement in de lijst.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-182">Choose the subscription from the list.</span></span>
6. <span data-ttu-id="c0eb4-183">Selecteer **bijwerken** om de wederverkoper te wijzigen **(MPN-id)**.</span><span class="sxs-lookup"><span data-stu-id="c0eb4-183">Select **update** to change the **Reseller (MPN ID)**.</span></span>

## <a name="next-steps"></a><span data-ttu-id="c0eb4-184">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="c0eb4-184">Next steps</span></span>

- [<span data-ttu-id="c0eb4-185">Uw factuur & afstemmings bestand lezen</span><span class="sxs-lookup"><span data-stu-id="c0eb4-185">How to read your bill & recon file</span></span>](read-your-bill.md) 