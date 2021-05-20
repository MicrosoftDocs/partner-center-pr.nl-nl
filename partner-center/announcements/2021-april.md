---
title: Aankondigingen van april 2021
description: Aankondigingen van april 2021 voor Microsoft Partner Center nieuwe mogelijkheden, promoties, aanbiedingen, markten of wijzigingen in bestaande aanbiedingen.
ms.topic: article
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
author: brentserbus
ms.author: brserbus
ms.custom:
- announcement
- references_regions
ms.localizationpriority: high
ms.date: 04/29/2021
ms.openlocfilehash: 13b8ec9ddd82b38a265606809b8c39c07436e548
ms.sourcegitcommit: 7063fdddee77ad2d8e627ab3c806f76d173ab652
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 05/19/2021
ms.locfileid: "110150128"
---
# <a name="april-2021-announcements"></a><span data-ttu-id="70ca5-103">Aankondigingen van april 2021</span><span class="sxs-lookup"><span data-stu-id="70ca5-103">April 2021 announcements</span></span>

<span data-ttu-id="70ca5-104">Deze pagina bevat de aankondigingen voor Microsoft Partner Center voor april 2021.</span><span class="sxs-lookup"><span data-stu-id="70ca5-104">This page provides the announcements for Microsoft Partner Center for April 2021.</span></span>

## <a name="readiness-updated-csp-customer-address-validation-api-going-live-in-june-testing-capability-now-available"></a><a name="10"></a><span data-ttu-id="70ca5-105">Gereedheid: validatie-API voor CSP-klantadressen is in juni live; testmogelijkheid nu beschikbaar</span><span class="sxs-lookup"><span data-stu-id="70ca5-105">Readiness: Updated CSP customer address validation API going live in June; testing capability now available</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-106">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-106">Categories</span></span>

- <span data-ttu-id="70ca5-107">Datum: 2021-04-30</span><span class="sxs-lookup"><span data-stu-id="70ca5-107">Date: 2021-04-30</span></span>
- <span data-ttu-id="70ca5-108">Gereedheid</span><span class="sxs-lookup"><span data-stu-id="70ca5-108">Readiness</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-109">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-109">Summary</span></span>

<span data-ttu-id="70ca5-110">Om partners en klanten te helpen hun bedrijf te runnen op basis van vertrouwen, nodigen we partners uit om wijzigingen in de Adres-API valideren te testen voor alle landen over de hele wereld.</span><span class="sxs-lookup"><span data-stu-id="70ca5-110">To help partners and customers run their business based on trust, we’ll be inviting partners to test changes to the Validate Address API for all countries worldwide.</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-111">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-111">Impacted audience</span></span>

<span data-ttu-id="70ca5-112">CSP-partners voor directe factuur en indirecte providers die nieuwe klantadresgegevens maken of bijwerken</span><span class="sxs-lookup"><span data-stu-id="70ca5-112">CSP direct bill partners and indirect providers who create new or update existing customers’ address details</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-113">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-113">Details</span></span>

<span data-ttu-id="70ca5-114">Microsoft wordt uitgevoerd op vertrouwen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-114">Microsoft runs on trust.</span></span> <span data-ttu-id="70ca5-115">We zetten ons in voor een compatibele, veilige en veilige methode voor validatie van klantadressen voor het uitvoeren van klantabonnementen in het CSP-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-115">We’re committed to providing a compliant, safe, and secure method of customer address validation for transacting customer subscriptions in the CSP program.</span></span> <span data-ttu-id="70ca5-116">Vanaf 31 maart 2021 zijn er wijzigingen aangebracht in de Validate Address-API.</span><span class="sxs-lookup"><span data-stu-id="70ca5-116">As of March 31, 2021, we have introduced changes to the Validate Address API.</span></span> <span data-ttu-id="70ca5-117">We nodigen partners uit om de API vóór de go-live eind juni 2021 te testen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-117">We invite partners to test the API prior to the  go-live at the end of June 2021.</span></span> 

<span data-ttu-id="70ca5-118">Houd er rekening mee dat deze wijzigingen alleen van invloed zijn op de Adres-API valideren.</span><span class="sxs-lookup"><span data-stu-id="70ca5-118">Note that these changes affect the Validate Address API only.</span></span> <span data-ttu-id="70ca5-119">Api's voor klant- en updateprofiel maken worden niet beïnvloed.</span><span class="sxs-lookup"><span data-stu-id="70ca5-119">Create Customer and Update Billing Profile APIs aren’t affected.</span></span> <span data-ttu-id="70ca5-120">Hoewel het voorgestelde adres momenteel niet hoeft te worden gebruikt met de API klant maken, wordt dit ten zeerste aanbevolen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-120">Although the suggested address doesn’t currently have to be used with the Create Customer API, it’s highly recommended.</span></span>

<span data-ttu-id="70ca5-121">Het antwoord retournt een van de volgende statusberichten:</span><span class="sxs-lookup"><span data-stu-id="70ca5-121">The response will return one of the following status messages:</span></span>

| <span data-ttu-id="70ca5-122">Status</span><span class="sxs-lookup"><span data-stu-id="70ca5-122">Status</span></span>     | <span data-ttu-id="70ca5-123">Beschrijving</span><span class="sxs-lookup"><span data-stu-id="70ca5-123">Description</span></span> |    <span data-ttu-id="70ca5-124">Aantal voorgestelde adressen dat wordt geretourneerd</span><span class="sxs-lookup"><span data-stu-id="70ca5-124">Number of suggested addresses returned</span></span> |
|-------|---------------|-------------------|
|<span data-ttu-id="70ca5-125">Geverifieerd verzendbaar</span><span class="sxs-lookup"><span data-stu-id="70ca5-125">Verified shippable</span></span> | <span data-ttu-id="70ca5-126">Het adres wordt geverifieerd en kan worden verzonden naar .</span><span class="sxs-lookup"><span data-stu-id="70ca5-126">Address is verified and can be shipped to.</span></span> | <span data-ttu-id="70ca5-127">Enkelvoudig</span><span class="sxs-lookup"><span data-stu-id="70ca5-127">Single</span></span> |
|<span data-ttu-id="70ca5-128">Geverifieerd</span><span class="sxs-lookup"><span data-stu-id="70ca5-128">Verified</span></span> | <span data-ttu-id="70ca5-129">Het adres wordt geverifieerd.</span><span class="sxs-lookup"><span data-stu-id="70ca5-129">Address is verified.</span></span> | <span data-ttu-id="70ca5-130">Enkelvoudig</span><span class="sxs-lookup"><span data-stu-id="70ca5-130">Single</span></span> |
|<span data-ttu-id="70ca5-131">Interactie vereist</span><span class="sxs-lookup"><span data-stu-id="70ca5-131">Interaction required</span></span> | <span data-ttu-id="70ca5-132">Voorgesteld adres is aanzienlijk gewijzigd en er is een gebruikersbevestiging nodig.</span><span class="sxs-lookup"><span data-stu-id="70ca5-132">Suggested address has been changed significantly and needs user confirmation.</span></span> | <span data-ttu-id="70ca5-133">Enkelvoudig</span><span class="sxs-lookup"><span data-stu-id="70ca5-133">Single</span></span> |
|<span data-ttu-id="70ca5-134">Gedeeltelijk straat</span><span class="sxs-lookup"><span data-stu-id="70ca5-134">Street partial</span></span> | <span data-ttu-id="70ca5-135">De opgegeven straat in het adres is gedeeltelijk en heeft meer informatie nodig.</span><span class="sxs-lookup"><span data-stu-id="70ca5-135">The given street in the address is partial and needs more info.</span></span> | <span data-ttu-id="70ca5-136">Meerdere, maximaal drie</span><span class="sxs-lookup"><span data-stu-id="70ca5-136">Multiple—maximum of three</span></span> |
|<span data-ttu-id="70ca5-137">Gedeeltelijk lokaal</span><span class="sxs-lookup"><span data-stu-id="70ca5-137">Premises partial</span></span> | <span data-ttu-id="70ca5-138">De opgegeven locatie (gebouwnummer, suitenummer en andere) is gedeeltelijk en heeft meer informatie nodig.</span><span class="sxs-lookup"><span data-stu-id="70ca5-138">The given premises (building number, suite number, and others) are partial and need more info.</span></span> | <span data-ttu-id="70ca5-139">Meerdere, maximaal drie</span><span class="sxs-lookup"><span data-stu-id="70ca5-139">Multiple—maximum of three</span></span> |
|<span data-ttu-id="70ca5-140">Meerdere</span><span class="sxs-lookup"><span data-stu-id="70ca5-140">Multiple</span></span> | <span data-ttu-id="70ca5-141">Er zijn meerdere velden die gedeeltelijk in het adres zijn (mogelijk ook gedeeltelijk en gedeeltelijk van de straat).</span><span class="sxs-lookup"><span data-stu-id="70ca5-141">There are multiple fields that are partial in the address (potentially also including street partial and premises partial).</span></span> | <span data-ttu-id="70ca5-142">Meerdere, maximaal drie</span><span class="sxs-lookup"><span data-stu-id="70ca5-142">Multiple—maximum of three</span></span> |
|<span data-ttu-id="70ca5-143">Geen</span><span class="sxs-lookup"><span data-stu-id="70ca5-143">None</span></span> | <span data-ttu-id="70ca5-144">Het adres is onjuist.</span><span class="sxs-lookup"><span data-stu-id="70ca5-144">Address is incorrect.</span></span> | <span data-ttu-id="70ca5-145">Geen</span><span class="sxs-lookup"><span data-stu-id="70ca5-145">None</span></span> |
|<span data-ttu-id="70ca5-146">Niet gevalideerd</span><span class="sxs-lookup"><span data-stu-id="70ca5-146">Not validated</span></span> | <span data-ttu-id="70ca5-147">Het adres kan niet worden verzonden via het validatieproces.</span><span class="sxs-lookup"><span data-stu-id="70ca5-147">Address was not able to be sent through the validation process.</span></span> | <span data-ttu-id="70ca5-148">Geen</span><span class="sxs-lookup"><span data-stu-id="70ca5-148">None</span></span> |

<span data-ttu-id="70ca5-149">Amerikaanse postcodes retourneren nog eens vier cijfers + afbreekstreetine, bijvoorbeeld 12345-6789.</span><span class="sxs-lookup"><span data-stu-id="70ca5-149">US post codes will return an additional four digits + hyphen, for example, 12345-6789.</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-150">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-150">Next steps</span></span>

- <span data-ttu-id="70ca5-151">Bekijk de technische documentatie en veelgestelde vragen in de [speciale partnerverzameling](https://partner.microsoft.com/resources/collection/additionalfields-csp-customers-selected-geos#/) voor meer gedetailleerde richtlijnen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-151">Review the technical documentation and frequently asked questions in the [dedicated partner collection](https://partner.microsoft.com/resources/collection/additionalfields-csp-customers-selected-geos#/) for more detailed guidance.</span></span>
- <span data-ttu-id="70ca5-152">Bereid u voor op het opnemen van de wijzigingen met behulp Partner Center API en webgebruikerservaring.</span><span class="sxs-lookup"><span data-stu-id="70ca5-152">Prepare to incorporate the changes using the Partner Center API and web user experience.</span></span> 
- <span data-ttu-id="70ca5-153">Deel uw tenant-id voor de sandbox met de expert op het gebied van onderwerp (Ali Wiltki) die moet worden opgenomen in de test flight, zodat u kunt beginnen met het voorbereiden van de update.</span><span class="sxs-lookup"><span data-stu-id="70ca5-153">Share your sandbox tenant ID with the subject matter expert (Ali Khaki) to be included in the test flight, so that you can begin preparing for the update.</span></span> 
- <span data-ttu-id="70ca5-154">Als u een CPV-oplossing (Panel Vendor) gebruikt, raadpleegt u uw CPV.</span><span class="sxs-lookup"><span data-stu-id="70ca5-154">If you’re using a control panel vendor (CPV) solution, consult your CPV.</span></span>

### <a name="questions"></a><span data-ttu-id="70ca5-155">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-155">Questions?</span></span>

<span data-ttu-id="70ca5-156">Als u ondersteuning nodig hebt voor uw bewerkingen met Microsoft, kunt u contact op met uw Yammer-partnerondersteuningsgroep of een [serviceaanvraag openen.](https://partner.microsoft.com/dashboard/support/servicerequests/create?stage=2&topicid=aa679372-d996-73df-e244-cb28bbbf28e8)</span><span class="sxs-lookup"><span data-stu-id="70ca5-156">If you need support for your operations with Microsoft, reach out to your partner support Yammer group or open a [service request](https://partner.microsoft.com/dashboard/support/servicerequests/create?stage=2&topicid=aa679372-d996-73df-e244-cb28bbbf28e8).</span></span>

_______________
## <a name="new-location-for-partner-center-api-swagger-documentation"></a><a name="9"></a><span data-ttu-id="70ca5-157">Nieuwe locatie voor Partner Center API Swagger-documentatie</span><span class="sxs-lookup"><span data-stu-id="70ca5-157">New location for Partner Center API Swagger documentation</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-158">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-158">Categories</span></span>

- <span data-ttu-id="70ca5-159">Datum: 2021-04-26</span><span class="sxs-lookup"><span data-stu-id="70ca5-159">Date: 2021-04-26</span></span>
- <span data-ttu-id="70ca5-160">Functies</span><span class="sxs-lookup"><span data-stu-id="70ca5-160">Capabilities</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-161">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-161">Summary</span></span>

<span data-ttu-id="70ca5-162">Partner Center API Swagger-documenten zijn gemigreerd van de vorige [Swagger-documentatiesite](https://apidocs.microsoft.com/services/partnercenter) naar een nieuwe [site met Swagger-documentatie.](/rest/api/partner-center-rest/)</span><span class="sxs-lookup"><span data-stu-id="70ca5-162">Partner Center API Swagger documents have been migrated from the [previous Swagger Documentation site](https://apidocs.microsoft.com/services/partnercenter) to a [new Swagger Documentation site](/rest/api/partner-center-rest/).</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-163">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-163">Impacted audience</span></span>

<span data-ttu-id="70ca5-164">Directe factuurpartners en indirecte providers die deelnemen aan het Cloud Solution Provider (CSP)-programma dat gebruik maakt van de Partner Center API's</span><span class="sxs-lookup"><span data-stu-id="70ca5-164">Direct bill partners and Indirect Providers participating in the Cloud Solution Provider (CSP) program who are using the Partner Center APIs</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-165">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-165">Details</span></span>

<span data-ttu-id="70ca5-166">Vanaf 26 april 2021 bevindt de Partner Center API Swagger-documentatie, inclusief REST API-inhoud, zich op een [nieuwe site.](/rest/api/partner-center-rest/)</span><span class="sxs-lookup"><span data-stu-id="70ca5-166">As of April 26, 2021 the Partner Center API Swagger documentation, including Rest API content, is located on a [new site](/rest/api/partner-center-rest/).</span></span> <span data-ttu-id="70ca5-167">De oude site is na enkele weken niet meer toegankelijk.</span><span class="sxs-lookup"><span data-stu-id="70ca5-167">The old site will be inaccessible after several weeks.</span></span>

### <a name="benefits"></a><span data-ttu-id="70ca5-168">Voordelen</span><span class="sxs-lookup"><span data-stu-id="70ca5-168">Benefits</span></span>

<span data-ttu-id="70ca5-169">De Partner Center API Swagger-documentatie biedt een **Functie** uitproberen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-169">The Partner Center API Swagger documentation will provide a **Try It** function.</span></span> <span data-ttu-id="70ca5-170">Als u deze functie wilt gebruiken, moet u een Bearer-token hebben, dat u kunt genereren door de stappen te volgen die worden vermeld in [Partner Center Verificatie.](/partner-center/develop/partner-center-authentication#app--user-authentication)</span><span class="sxs-lookup"><span data-stu-id="70ca5-170">To use this function, you’ll need to have a Bearer Token, which you can generate by following the steps listed in [Partner Center Authentication](/partner-center/develop/partner-center-authentication#app--user-authentication).</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-171">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-171">Next steps</span></span>

<span data-ttu-id="70ca5-172">Deel deze informatie binnen uw organisatie, zodat het juiste team de processen kan controleren en bijwerken.</span><span class="sxs-lookup"><span data-stu-id="70ca5-172">Share this information within your organization so that the appropriate team can review and update their processes.</span></span>

### <a name="questions"></a><span data-ttu-id="70ca5-173">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-173">Questions?</span></span>

<span data-ttu-id="70ca5-174">Raadpleeg uw relevante Yammer-community's voor vragen over deze aanbiedingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-174">For questions about these offers, check your relevant Yammer communities.</span></span>

________________
## <a name="cloud-solution-provider-csp-software-return-period-policy-and-download-link-expiry-notice"></a><a name="8"></a><span data-ttu-id="70ca5-175">Cloud Solution Provider (CSP)-beleid voor de retourperiode van software en de vervaldatum van de downloadkoppeling</span><span class="sxs-lookup"><span data-stu-id="70ca5-175">Cloud Solution Provider (CSP) software return period policy and download link expiry notice</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-176">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-176">Categories</span></span>

- <span data-ttu-id="70ca5-177">Datum: 2021-04-21</span><span class="sxs-lookup"><span data-stu-id="70ca5-177">Date: 2021-04-21</span></span>
- <span data-ttu-id="70ca5-178">Functies</span><span class="sxs-lookup"><span data-stu-id="70ca5-178">Capabilities</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-179">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-179">Summary</span></span>

<span data-ttu-id="70ca5-180">Er zijn wijzigingen in het beleid voor de retourperiode van de CSP-software en het verlopen van de downloadkoppeling.</span><span class="sxs-lookup"><span data-stu-id="70ca5-180">There are changes to the CSP software return period policy and download link expiry.</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-181">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-181">Impacted audience</span></span>

<span data-ttu-id="70ca5-182">Partners die aanbiedingen voor permanente software of softwareabonnementen in CSP af te betalen</span><span class="sxs-lookup"><span data-stu-id="70ca5-182">Partners transacting perpetual software or software subscription offers in CSP</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-183">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-183">Details</span></span>

<span data-ttu-id="70ca5-184">Houd rekening met de volgende belangrijke meldingen met betrekking tot continue software- en softwareabonnementen via Partner Center:</span><span class="sxs-lookup"><span data-stu-id="70ca5-184">Note the following important notifications regarding perpetual software and software subscription purchases through Partner Center:</span></span>

#### <a name="software-return-period-policy"></a><span data-ttu-id="70ca5-185">Beleid voor retourperiode van software</span><span class="sxs-lookup"><span data-stu-id="70ca5-185">Software return period policy</span></span>

<span data-ttu-id="70ca5-186">Vanaf 1 juni 2021 verandert de retourperiode voor softwareaanbiedingen in CSP, zoals vermeld in de Microsoft Partner-overeenkomst (MPA), van 60 dagen vanaf de orderdatum in 30 dagen na de orderdatum.</span><span class="sxs-lookup"><span data-stu-id="70ca5-186">From June 1, 2021, the return period for software offers in CSP, as stated in the Microsoft Partner Agreement (MPA), will change from 60 days from order date to 30 days from order date.</span></span>

<span data-ttu-id="70ca5-187">Nadat een order voor een softwareaanbieding is verzonden, hebben partners 30 dagen vanaf de orderdatum de tijd om wijzigingen in een dergelijke volgorde in te dienen:</span><span class="sxs-lookup"><span data-stu-id="70ca5-187">After an order for a software offer is submitted, partners will have 30 days from the order date to submit any revisions to such order:</span></span>

- <span data-ttu-id="70ca5-188">Elke doorlopende softwarelicentie die binnen de retourperiode van 30 dagen wordt geretourneerd, ontvangt een volledig tegoed van de betaalde aankoopprijs.</span><span class="sxs-lookup"><span data-stu-id="70ca5-188">Any perpetual software license returned within the 30-day return period will receive a full credit of the paid purchase price.</span></span>

- <span data-ttu-id="70ca5-189">Elk softwareabonnementsproduct dat binnen de retourperiode van 30 dagen wordt geretourneerd, ontvangt een prorated tegoed van de betaalde aankoopprijs.</span><span class="sxs-lookup"><span data-stu-id="70ca5-189">Any software subscription product returned within the 30-day return period will receive a prorated credit of the paid purchase price.</span></span>

<span data-ttu-id="70ca5-190">Dit bericht is een vervolg op onze e-mailberichten die op december 2020 en april 2021 naar alle CSP-partners zijn verzonden met betrekking tot de retourperiode en andere updates voor de MPA.</span><span class="sxs-lookup"><span data-stu-id="70ca5-190">This message is a follow-up to our email communications sent on December 2020 and April 2021 to all CSP partners regarding the return period and other updates to the MPA.</span></span> <span data-ttu-id="70ca5-191">Raadpleeg deze kennisgevingen voor meer informatie over wijzigingen die van invloed zijn op de MPA.</span><span class="sxs-lookup"><span data-stu-id="70ca5-191">Refer to those notices for full details regarding changes affecting the MPA.</span></span>

#### <a name="software-download-link-expiry"></a><span data-ttu-id="70ca5-192">Het downloaden van software verloopt</span><span class="sxs-lookup"><span data-stu-id="70ca5-192">Software download link expiry</span></span>

<span data-ttu-id="70ca5-193">Vanaf 3 juni 2021 hebben de software downloadkoppelingen voor continue software- en softwareabonnementproductaankopen via Partner Center een vervaldatum van vijf dagen vanaf de eerste download.</span><span class="sxs-lookup"><span data-stu-id="70ca5-193">From June 3, 2021, the software download links for perpetual software and software subscription product purchases through Partner Center will have an expiration date of five days from the initial download.</span></span> <span data-ttu-id="70ca5-194">De verloopperiode is van toepassing op alle aankopen vóór 3 juni 2021, en op of na 3 juni 2021.</span><span class="sxs-lookup"><span data-stu-id="70ca5-194">The expiry period will apply to all purchases before June 3, 2021, as well as on or after June 3, 2021.</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-195">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-195">Next steps</span></span>

<span data-ttu-id="70ca5-196">Bekijk de [CSP-retourperiode en veelgestelde](https://partner.microsoft.com/resources/detail/csp-software-return-period-download-expiry-faq-pdf)vragen over het verlopen van de downloadkoppeling en informeer alle juiste teams binnen uw organisatie over deze wijzigingen:</span><span class="sxs-lookup"><span data-stu-id="70ca5-196">Review the [CSP return period and download link expiry FAQ](https://partner.microsoft.com/resources/detail/csp-software-return-period-download-expiry-faq-pdf), and inform all appropriate teams within your organization of these changes:</span></span>

### <a name="questions"></a><span data-ttu-id="70ca5-197">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-197">Questions?</span></span>

<span data-ttu-id="70ca5-198">Raadpleeg uw relevante Yammer-community's voor vragen over deze aanbiedingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-198">For questions about these offers, check your relevant Yammer communities.</span></span>

________________
## <a name="open-licensing-program-transitioning-resellers-to-the-cloud-solution-provider-csp-program"></a><a name="7"></a><span data-ttu-id="70ca5-199">Licentieprogramma openen: resellers overstappen naar het Cloud Solution Provider (CSP)-programma</span><span class="sxs-lookup"><span data-stu-id="70ca5-199">Open Licensing program: Transitioning resellers to the Cloud Solution Provider (CSP) program</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-200">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-200">Categories</span></span>

- <span data-ttu-id="70ca5-201">Datum: 2021-04-19</span><span class="sxs-lookup"><span data-stu-id="70ca5-201">Date: 2021-04-19</span></span>
- <span data-ttu-id="70ca5-202">Uw bedrijf laten groeien</span><span class="sxs-lookup"><span data-stu-id="70ca5-202">Grow Your Business</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-203">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-203">Summary</span></span>

<span data-ttu-id="70ca5-204">Deze communicatie laat zien hoe u zich voorbereidt op de wijzigingen die binnenkort worden doorgevoerd in het Open Licensing-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-204">This communication details how to prepare for the changes that are coming soon to the Open Licensing program.</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-205">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-205">Impacted audience</span></span>

<span data-ttu-id="70ca5-206">CSP- en Open License-partners</span><span class="sxs-lookup"><span data-stu-id="70ca5-206">CSP and Open License partners</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-207">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-207">Details</span></span>

<span data-ttu-id="70ca5-208">In 2020 heeft [Microsoft](https://blogs.partner.microsoft.com/mpn/general-availability-of-perpetual-software-licenses-in-the-cloud-solution-provider-program/) aangekondigd dat doorlopende softwarelicenties breed beschikbaar zullen zijn voor partners en klanten via het Cloud Solution Provider (CSP)-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-208">In 2020, Microsoft [announced](https://blogs.partner.microsoft.com/mpn/general-availability-of-perpetual-software-licenses-in-the-cloud-solution-provider-program/) that perpetual software licenses will be broadly available to partners and customers through the Cloud Solution Provider (CSP) program.</span></span> <span data-ttu-id="70ca5-209">De eerste mijlpaal is bereikt in januari 2021, toen commerciële doorlopende softwareaanbiedingen beschikbaar werden.</span><span class="sxs-lookup"><span data-stu-id="70ca5-209">The first milestone was reached in January 2021, when commercial perpetual software offers became available.</span></span> <span data-ttu-id="70ca5-210">De volgende belangrijke mijlpaal vindt plaats in juli 2021, wanneer aanbiedingen voor openbare [sectoren](https://aka.ms/openlicensepublicsector) beschikbaar komen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-210">The next key milestone will happen in July 2021, when [public sector](https://aka.ms/openlicensepublicsector) offers become available.</span></span> <span data-ttu-id="70ca5-211">We [hebben](https://blogs.partner.microsoft.com/mpn/expanding-opportunities-for-partners-in-the-cloud-solution-provider-program/) ook gecommuniceerd dat met ingang van 1 januari 2022 geen nieuwe softwarelicentieaankopen of verlengingen van Software Assurance of onlineservices kunnen worden gedaan via het Open License-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-211">We also [communicated](https://blogs.partner.microsoft.com/mpn/expanding-opportunities-for-partners-in-the-cloud-solution-provider-program/) that effective January 1, 2022, no new software license purchases or renewals of Software Assurance or online services can be made through the Open License program.</span></span>

<span data-ttu-id="70ca5-212">De overgang van permanente software naar het CSP-programma in de nieuwe commerce-ervaring helpt partners bij het uitbreiden van de mogelijkheden om diverse oplossingen en beheerde services te bieden.</span><span class="sxs-lookup"><span data-stu-id="70ca5-212">The transition of perpetual software to the CSP program in the new commerce experience will help partners to expand the opportunities to offer diverse solutions and managed services.</span></span> <span data-ttu-id="70ca5-213">Dit versnelt ook de overgang van klanten naar de cloud.</span><span class="sxs-lookup"><span data-stu-id="70ca5-213">This will also accelerate customers’ transition to the cloud.</span></span>  <span data-ttu-id="70ca5-214">Om een soepele overgang voor zowel onze partners als klanten te garanderen, hebben we deze aanpassingen en materialen aangebracht om deze digitale transformatie te versnellen:</span><span class="sxs-lookup"><span data-stu-id="70ca5-214">To help ensure a smooth transition for both our partners and customers, we’ve made these adjustments and materials to accelerate this digital transformation:</span></span>

#### <a name="april-2021"></a><span data-ttu-id="70ca5-215">April 2021</span><span class="sxs-lookup"><span data-stu-id="70ca5-215">April 2021</span></span>

<span data-ttu-id="70ca5-216">[Nu beschikbaar:](https://partner.microsoft.com/resources/collection/reseller-open-license-to-csp-transition-materials#/)Open overgangsmateriaal voor licentie-naar-CSP voor resellers</span><span class="sxs-lookup"><span data-stu-id="70ca5-216">[Now available](https://partner.microsoft.com/resources/collection/reseller-open-license-to-csp-transition-materials#/): Open License-to-CSP transition materials for resellers</span></span>

#### <a name="july-2021"></a><span data-ttu-id="70ca5-217">Juli 2021</span><span class="sxs-lookup"><span data-stu-id="70ca5-217">July 2021</span></span>

##### <a name="csp"></a><span data-ttu-id="70ca5-218">CSP</span><span class="sxs-lookup"><span data-stu-id="70ca5-218">CSP</span></span>

- <span data-ttu-id="70ca5-219">1 juli: Permanent beschikbare softwarelicenties voor klanten in de publieke sector</span><span class="sxs-lookup"><span data-stu-id="70ca5-219">July 1: Perpetual software licenses available to public sector customers</span></span>

- <span data-ttu-id="70ca5-220">7 juli: Visual Studio Pro- en Get Genuine Windows Agreement-softwarelicenties beschikbaar voor alle segmenten</span><span class="sxs-lookup"><span data-stu-id="70ca5-220">July 7: Visual Studio Pro and Get Genuine Windows Agreement  perpetual software licenses available to all segments</span></span>

##### <a name="open-value"></a><span data-ttu-id="70ca5-221">Open waarde</span><span class="sxs-lookup"><span data-stu-id="70ca5-221">Open Value</span></span>

- <span data-ttu-id="70ca5-222">1 juli: Er zijn extra SKU's beschikbaar in het Open Value-programma voor onderwijs en non-profitorganisaties, met vergelijkbare aanbiedingen als het Open License-programma</span><span class="sxs-lookup"><span data-stu-id="70ca5-222">July 1: Additional SKUs available in the Open Value program for education and nonprofit, providing similar offers to the Open License program</span></span>

##### <a name="open-license"></a><span data-ttu-id="70ca5-223">Licentie openen</span><span class="sxs-lookup"><span data-stu-id="70ca5-223">Open License</span></span>

- <span data-ttu-id="70ca5-224">1 juli: Microsoft start geen nieuwe aanbiedingen meer in het open license-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-224">July 1: Microsoft will no longer launch new offers in the Open License program.</span></span>

#### <a name="january-2022"></a><span data-ttu-id="70ca5-225">Januari 2022</span><span class="sxs-lookup"><span data-stu-id="70ca5-225">January 2022</span></span>

- <span data-ttu-id="70ca5-226">1 januari: er kunnen geen nieuwe aankopen of verlengingen worden gedaan via het Open License-programma</span><span class="sxs-lookup"><span data-stu-id="70ca5-226">January 1: No new purchases or renewals can be made through the Open License program</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-227">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-227">Next steps</span></span>

#### <a name="csp-indirect-providers"></a><span data-ttu-id="70ca5-228">Indirecte CSP-providers</span><span class="sxs-lookup"><span data-stu-id="70ca5-228">CSP indirect providers</span></span>

<span data-ttu-id="70ca5-229">Gebruik de komende maanden om resellers met open licenties te helpen zich te oriënteren in het CSP-programma door evenementen van de partner-community te bezoeken en het overgangsmateriaal Open License-to-CSP voor resellers te gebruiken:</span><span class="sxs-lookup"><span data-stu-id="70ca5-229">Use the coming months to help Open License resellers orient into the CSP program by attending partner community events and using the Open License-to-CSP transition materials for resellers:</span></span>

- <span data-ttu-id="70ca5-230">[Open licentie-naar-CSP-overgangsmateriaal voor resellers:](https://partner.microsoft.com/resources/collection/reseller-open-license-to-csp-transition-materials#/)aanpasbare overzichtspresentatie, e-mailsjabloon, onboardinghandleiding voor indirecte CSP-resellers en meer om u te helpen de acceptatie voor uw wederverkopers op schaal te stimuleren.</span><span class="sxs-lookup"><span data-stu-id="70ca5-230">[Open License-to-CSP transition materials for resellers](https://partner.microsoft.com/resources/collection/reseller-open-license-to-csp-transition-materials#/)—Customizable overview presentation, email template, CSP indirect reseller onboarding guide, and more to help you drive the adoption for your resellers at scale.</span></span>

- <span data-ttu-id="70ca5-231">[CSP Partner Community-gebeurtenissen die](https://globalpbocomm.eventbuilder.com/GlobalCSP) worden gehost door Microsoft Business Operations.</span><span class="sxs-lookup"><span data-stu-id="70ca5-231">[CSP Partner Community Events](https://globalpbocomm.eventbuilder.com/GlobalCSP) hosted by Microsoft Business Operations.</span></span>  <span data-ttu-id="70ca5-232">Neem deel aan de verschillende sessies om de basisbeginselen van CSP (basisprincipes van CSP) te leren of blijf up-to-date en stel vragen over Software in CSP (Q&A Sessions).</span><span class="sxs-lookup"><span data-stu-id="70ca5-232">Join the various sessions to learn CSP basics (CSP Fundamentals) or stay up to date, and ask questions regarding Software in CSP (Q&A Sessions).</span></span>

- <span data-ttu-id="70ca5-233">(Binnenkort) Trainingssessie voor indirecte CSP-resellers die worden gehost door Microsoft Business Operations.</span><span class="sxs-lookup"><span data-stu-id="70ca5-233">(Coming soon) CSP indirect reseller–focused training session hosted by Microsoft Business Operations.</span></span>

#### <a name="open-license-resellers"></a><span data-ttu-id="70ca5-234">Licentie-resellers openen</span><span class="sxs-lookup"><span data-stu-id="70ca5-234">Open License resellers</span></span>

- <span data-ttu-id="70ca5-235">Als uw organisatie momenteel niet is ingeschreven bij het CSP-programma, neem dan contact op met uw distributeur voor informatie over hoe u aan de slag kunt gaan.</span><span class="sxs-lookup"><span data-stu-id="70ca5-235">If your organization isn’t currently enrolled in the CSP program, contact your distributor for information on how to get started.</span></span> <span data-ttu-id="70ca5-236">Maak hier verbinding met een indirecte [provider.](https://partner.microsoft.com/membership/cloud-solution-provider/find-a-provider)</span><span class="sxs-lookup"><span data-stu-id="70ca5-236">Connect with an indirect provider [here](https://partner.microsoft.com/membership/cloud-solution-provider/find-a-provider).</span></span>

- <span data-ttu-id="70ca5-237">Als uw organisatie al is ingeschreven bij het CSP-programma, kunt u hier meer informatie vinden over continue software in [CSP.](https://partner.microsoft.com/resources/collection/software-in-csp)</span><span class="sxs-lookup"><span data-stu-id="70ca5-237">If your organization is already enrolled in the CSP program, learn more about perpetual software in CSP [here](https://partner.microsoft.com/resources/collection/software-in-csp).</span></span>

### <a name="questions"></a><span data-ttu-id="70ca5-238">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-238">Questions?</span></span>

<span data-ttu-id="70ca5-239">Raadpleeg uw relevante Yammer-community's voor meer vragen over deze aanbiedingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-239">For further questions about these offers, check your relevant Yammer communities.</span></span>

________________
## <a name="now-live-global-promo-readiness-guide"></a><a name="6"></a><span data-ttu-id="70ca5-240">Nu live: Globale handleiding voor promotie-gereedheid</span><span class="sxs-lookup"><span data-stu-id="70ca5-240">Now live: Global promo readiness guide</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-241">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-241">Categories</span></span>

- <span data-ttu-id="70ca5-242">Datum: 2021-04-16</span><span class="sxs-lookup"><span data-stu-id="70ca5-242">Date: 2021-04-16</span></span>
- <span data-ttu-id="70ca5-243">Functies</span><span class="sxs-lookup"><span data-stu-id="70ca5-243">Capabilities</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-244">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-244">Summary</span></span>

<span data-ttu-id="70ca5-245">Gereedheid starten heeft een nieuwe algemene handleiding voor [gereedheid voor promotie gepubliceerd](https://partner.microsoft.com/resources/detail/operations-promo-guide-pdf) in de operations-gereedheid-resourcegalerie.</span><span class="sxs-lookup"><span data-stu-id="70ca5-245">Launch Readiness has published a new [global promo readiness guide](https://partner.microsoft.com/resources/detail/operations-promo-guide-pdf) on the Operations Readiness resource gallery.</span></span> <span data-ttu-id="70ca5-246">Deze handleiding biedt een geconsolideerde weergave van alle actieve [wereldwijde promoties.](https://partner.microsoft.com/resources/collection/global-promo-readiness-guide-collection#/)</span><span class="sxs-lookup"><span data-stu-id="70ca5-246">This guide provides a consolidated view of all active [global promotions](https://partner.microsoft.com/resources/collection/global-promo-readiness-guide-collection#/).</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-247">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-247">Impacted audience</span></span>

<span data-ttu-id="70ca5-248">Alle volumelicenties (VL), Dynamics Price List (DPL) en Cloud Solution Provider (CSP)-partners</span><span class="sxs-lookup"><span data-stu-id="70ca5-248">All Volume Licensing (VL), Dynamics Price List (DPL), and Cloud Solution Provider (CSP) partners</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-249">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-249">Details</span></span>

<span data-ttu-id="70ca5-250">Microsoft-partners hebben met ons gedeeld dat ze een geconsolideerde weergave moeten bieden van alle wereldwijde promoties met ondersteunende details.</span><span class="sxs-lookup"><span data-stu-id="70ca5-250">Microsoft partners have shared with us the need to provide a consolidated view of all global promotions with supporting details.</span></span> <span data-ttu-id="70ca5-251">U wilde deze geconsolideerde handleiding gebruiken om promoties te gebruiken met het vertrouwen dat alle beschikbare informatie gemakkelijk toegankelijk is op een centrale en handige locatie.</span><span class="sxs-lookup"><span data-stu-id="70ca5-251">You wanted this consolidated guide to help you use promotions with the confidence that all the available information will be readily accessible in a central and convenient location.</span></span>

<span data-ttu-id="70ca5-252">Vanaf april 2021 werkt Microsoft deze handleiding maandelijks bij en is deze beschikbaar in een speciale global promo readiness Guide-verzameling in de resourcegalerie van Operations Readiness.</span><span class="sxs-lookup"><span data-stu-id="70ca5-252">Beginning in April 2021, Microsoft will update this guide on a monthly basis, and it will be available in a dedicated Global Promo Readiness Guide collection in the Operations Readiness resource gallery.</span></span>

<span data-ttu-id="70ca5-253">Koppelingen naar deze handleiding worden ook opgenomen in de volgende verzamelingen:</span><span class="sxs-lookup"><span data-stu-id="70ca5-253">Links to this guide will also be included in the following collections:</span></span>

- <span data-ttu-id="70ca5-254">[Start de agendaverzameling](https://partner.microsoft.com/resources/collection/csp-announcement-calendar#/), die een gecentraliseerde weergave biedt van toekomstige wijzigingen en lanceringen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-254">[Launch calendar collection](https://partner.microsoft.com/resources/collection/csp-announcement-calendar#/), which provides a centralized view of upcoming changes and launches.</span></span>

- <span data-ttu-id="70ca5-255">[Communityverzamelingen,](https://partner.microsoft.com/resources/collection/april-2021-csp-partner-community-content#/)die ondersteunende materialen bevatten voor onze maandelijkse partnergesprekken, waarbij toekomstige wijzigingen en actuele onderwerpen van operationele interesse worden belicht.</span><span class="sxs-lookup"><span data-stu-id="70ca5-255">[Community collections](https://partner.microsoft.com/resources/collection/april-2021-csp-partner-community-content#/), which contain supporting materials for our monthly partner calls, highlighting upcoming changes and timely topics of operational interest.</span></span>

- <span data-ttu-id="70ca5-256">[Partner-nieuwsbrieven,](https://partner.microsoft.com/resources/collection/csp-monthly-update#/)zoals maandelijkse update voor CSP</span><span class="sxs-lookup"><span data-stu-id="70ca5-256">[Partner newsletters](https://partner.microsoft.com/resources/collection/csp-monthly-update#/), such as CSP Monthly Update</span></span>

<span data-ttu-id="70ca5-257">Als maandelijkse herinnering publiceren we ook een Partner Center aankondiging met elk nieuw probleem van de algemene handleiding voor promotie-gereedheid.</span><span class="sxs-lookup"><span data-stu-id="70ca5-257">As a monthly reminder, we will also publish a Partner Center announcement with each new issue of the global promo readiness guide.</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-258">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-258">Next steps</span></span>

<span data-ttu-id="70ca5-259">Aan het begin van elke maand vindt u de meest recente algemene handleiding voor [gereedheid](https://partner.microsoft.com/resources/detail/operations-promo-guide-pdf) voor promotie in de [resourcegalerie van Operations Readiness.](https://partner.microsoft.com/resources)</span><span class="sxs-lookup"><span data-stu-id="70ca5-259">At the start of each month, you will find the latest [global promo readiness guide](https://partner.microsoft.com/resources/detail/operations-promo-guide-pdf) in the [Operations Readiness resource gallery](https://partner.microsoft.com/resources).</span></span>

<span data-ttu-id="70ca5-260">Deel deze informatie met de juiste contactpersonen in uw organisatie en laat ons weten hoe nuttig de handleiding is via de pagina 'Was deze pagina nuttig?'</span><span class="sxs-lookup"><span data-stu-id="70ca5-260">Share this information with the appropriate contacts in your organizations and let us know how helpful the guide is through the “Was this page helpful?”</span></span> <span data-ttu-id="70ca5-261">aan het einde van elke pagina.</span><span class="sxs-lookup"><span data-stu-id="70ca5-261">button at the end of each page.</span></span>

________________
## <a name="april-cloud-solution-provider-csp-community-update-and-reminders"></a><a name="5"></a><span data-ttu-id="70ca5-262">Update en Cloud Solution Provider (CSP) voor de community van april</span><span class="sxs-lookup"><span data-stu-id="70ca5-262">April Cloud Solution Provider (CSP) community update and reminders</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-263">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-263">Categories</span></span>

- <span data-ttu-id="70ca5-264">Datum: 2021-04-16</span><span class="sxs-lookup"><span data-stu-id="70ca5-264">Date: 2021-04-16</span></span>
- <span data-ttu-id="70ca5-265">Community | Uitnodigingen en herinneringen</span><span class="sxs-lookup"><span data-stu-id="70ca5-265">Community | Invites and reminders</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-266">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-266">Summary</span></span>

<span data-ttu-id="70ca5-267">Resources van de CSP-community zijn op aanvraag beschikbaar en maandelijks bijgewerkt om u op de hoogte te houden en u voor te bereiden op veranderingen in het CSP-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-267">CSP community resources are available on demand and updated monthly to keep you informed and prepared for change in the CSP program.</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-268">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-268">Impacted audience</span></span>

<span data-ttu-id="70ca5-269">CSP-partners voor directe factuur en indirecte providers</span><span class="sxs-lookup"><span data-stu-id="70ca5-269">CSP direct bill partners and indirect providers</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-270">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-270">Details</span></span>

<span data-ttu-id="70ca5-271">Deze maand bevatten de resources de volgende belangrijke onderwerpen:</span><span class="sxs-lookup"><span data-stu-id="70ca5-271">This month, the resources include the following key topics:</span></span>

- [<span data-ttu-id="70ca5-272">Wijzigingen in het CSP-programma en open license-programma bijwerken</span><span class="sxs-lookup"><span data-stu-id="70ca5-272">Update to CSP program evolution and Open License program changes</span></span>](https://partner.microsoft.com/resources/collection/csp-open-evolution-to-a-better-experience#/)

- [<span data-ttu-id="70ca5-273">Wijzigingen in de onboardingvereisten voor CSP-klanten in bepaalde regio's</span><span class="sxs-lookup"><span data-stu-id="70ca5-273">Changes to CSP customer onboarding requirements in certain regions</span></span>](https://partner.microsoft.com/resources/collection/additionalfields-csp-customers-selected-geos#/)

- [<span data-ttu-id="70ca5-274">Nieuwe indeling voor de nieuwe PDF-factuur voor commerce in het CSP-programma</span><span class="sxs-lookup"><span data-stu-id="70ca5-274">New format for the new commerce PDF invoice in the CSP program</span></span>](https://partner.microsoft.com/resources/collection/introducing-new-format-for-the-new-commerce-invoice-in-csp#/)

<span data-ttu-id="70ca5-275">In de [CSP-communityverzameling](https://partner.microsoft.com/resources/collection/april-2021-csp-partner-community-content#/)vindt u het volgende:</span><span class="sxs-lookup"><span data-stu-id="70ca5-275">Within the [CSP community collection](https://partner.microsoft.com/resources/collection/april-2021-csp-partner-community-content#/), you’ll find:</span></span>

- <span data-ttu-id="70ca5-276">De downloadbare [CSP Monthly Update-nieuwsbrief,](https://partner.microsoft.com/resources/detail/csp-monthly-update-april-2021-global)waarin recente CSP-aankondigingen, updates, gebeurtenissen en herinneringen worden geaggregeerd in een eenvoudig te lezen document.</span><span class="sxs-lookup"><span data-stu-id="70ca5-276">The downloadable [CSP Monthly Update newsletter](https://partner.microsoft.com/resources/detail/csp-monthly-update-april-2021-global), which aggregates recent CSP announcements, updates, events, and reminders in an easy-to-read document.</span></span>

- <span data-ttu-id="70ca5-277">De [CSP-aankondigings agenda,](https://partner.microsoft.com/resources/detail/csp-announcement-calendar-april-2021)die een tijdlijnweergave biedt van toekomstige wijzigingen die van invloed zijn op het programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-277">The [CSP Announcement Calendar](https://partner.microsoft.com/resources/detail/csp-announcement-calendar-april-2021), which provides a timeline view of upcoming changes affecting the program.</span></span>

- <span data-ttu-id="70ca5-278">De nieuwe [kalender voor productlancering,](https://partner.microsoft.com/resources/detail/product-launch-calendar-april-pdf)waar u toekomstige productlanceringen en aanbiedingen kunt bekijken.</span><span class="sxs-lookup"><span data-stu-id="70ca5-278">The new [product launch calendar](https://partner.microsoft.com/resources/detail/product-launch-calendar-april-pdf), where you can view upcoming product launches and offers.</span></span>

- <span data-ttu-id="70ca5-279">[CSP start updatebronnen](https://partner.microsoft.com/resources/collection/april-2021-csp-launch-topics-collection#/) met eenvoudig te gebruiken inhoud over belangrijke operationele wijzigingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-279">[CSP launch update resources](https://partner.microsoft.com/resources/collection/april-2021-csp-launch-topics-collection#/) with easy-to-consume content on key operational changes.</span></span>

- <span data-ttu-id="70ca5-280">[Vernieuwingen en herinneringen over](https://partner.microsoft.com/resources/detail/csp-april-2021-refreshers-and-reminders-pdf) belangrijke CSP-onderwerpen die interesse en query's ontvangen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-280">[Refreshers and reminders](https://partner.microsoft.com/resources/detail/csp-april-2021-refreshers-and-reminders-pdf) on key CSP topics receiving interest and queries.</span></span>

#### <a name="csp-community-call-qas"></a><span data-ttu-id="70ca5-281">CSP Community Call Q&As</span><span class="sxs-lookup"><span data-stu-id="70ca5-281">CSP Community Call Q&As</span></span>

<span data-ttu-id="70ca5-282">Community Call Q&As zijn beschikbaar om u te helpen met vragen met betrekking tot toekomstige wijzigingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-282">Community Call Q&As are available to help you with questions related to upcoming changes.</span></span> <span data-ttu-id="70ca5-283">Registreer u nu voor CSP Community Call Q&Zoals die plaatsvinden in april, mei en juni.</span><span class="sxs-lookup"><span data-stu-id="70ca5-283">Register now for CSP Community Call Q&As that are taking place in April, May, and June.</span></span> <span data-ttu-id="70ca5-284">Deze zijn gericht op de meest recente lanceringen, belangrijke vernieuwingen en herinneringen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-284">These will focus on the latest launches, important refreshers, and reminders.</span></span>

<span data-ttu-id="70ca5-285">[Registreer u hier.](https://globalpbocomm.eventbuilder.com/GlobalCSP)</span><span class="sxs-lookup"><span data-stu-id="70ca5-285">[Register here](https://globalpbocomm.eventbuilder.com/GlobalCSP).</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-286">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-286">Next steps</span></span>

<span data-ttu-id="70ca5-287">Bekijk de resources van de community en registreer u voor de Q-&A.</span><span class="sxs-lookup"><span data-stu-id="70ca5-287">Review the community resources and register for the Community Call Q&A.</span></span>

<span data-ttu-id="70ca5-288">Om ervoor te zorgen dat u het meeste uit de Community Call Q&A kunt halen, bekijkt u de inhoud van de community op aanvraag en dient u uw vragen maximaal 48 uur vóór de oproep in.</span><span class="sxs-lookup"><span data-stu-id="70ca5-288">To ensure that you get the most from the Community Call Q&A, review the on-demand community content and submit your questions up to 48 hours before the call.</span></span>

### <a name="questions"></a><span data-ttu-id="70ca5-289">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-289">Questions?</span></span>

<span data-ttu-id="70ca5-290">De maandelijkse CSP Community Call Q&A is de beste plek voor vragen met betrekking tot wijzigingen in het CSP-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-290">The monthly CSP Community Call Q&A is the best place for questions related to changes in the CSP program.</span></span> <span data-ttu-id="70ca5-291">Bekijk elke maand het materiaal en dien uw vragen van tevoren in, zodat we de sessie kunnen besteden aan de onderwerpen die voor u het belangrijkst zijn.</span><span class="sxs-lookup"><span data-stu-id="70ca5-291">Each month, review the material and submit your questions in advance so that we can spend the session on the topics that are most important to you.</span></span>

<span data-ttu-id="70ca5-292">Neem contact op met ondersteuning voor [meer informatie.](https://partner.microsoft.com/dashboard/support/csp/servicerequests/create?category=csp)</span><span class="sxs-lookup"><span data-stu-id="70ca5-292">For more information, contact [Support](https://partner.microsoft.com/dashboard/support/csp/servicerequests/create?category=csp).</span></span>

________________
## <a name="final-reminder-deprecation-of-get-qualification-on-may-6-2021"></a><a name="4"></a><span data-ttu-id="70ca5-293">Laatste herinnering: afschaffing van de GET-kwalificatie op 6 mei 2021</span><span class="sxs-lookup"><span data-stu-id="70ca5-293">Final reminder: Deprecation of GET qualification on May 6, 2021</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-294">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-294">Categories</span></span>

- <span data-ttu-id="70ca5-295">Datum: 2021-05-04</span><span class="sxs-lookup"><span data-stu-id="70ca5-295">Date: 2021-05-04</span></span>

- <span data-ttu-id="70ca5-296">Functies</span><span class="sxs-lookup"><span data-stu-id="70ca5-296">Capabilities</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-297">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-297">Impacted audience</span></span>

<span data-ttu-id="70ca5-298">Partners die Academic, Non-profit en Government Community Cloud (GCC) verkopen via het Cloud Solution Provider-programma met behulp van de Partner Center-API</span><span class="sxs-lookup"><span data-stu-id="70ca5-298">Partners selling Academic, Nonprofit, and Government Community Cloud (GCC) offers through the Cloud Solution Provider program using the Partner Center API</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-299">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-299">Details</span></span>

<span data-ttu-id="70ca5-300">Deze aankondiging is een vervolg op de verbeteringen Partner Center [in december zijn uitgebracht.](./2020-december.md#1)</span><span class="sxs-lookup"><span data-stu-id="70ca5-300">This announcement is a follow-up to the Partner Center [enhancements released in December](./2020-december.md#1).</span></span> <span data-ttu-id="70ca5-301">Als onderdeel van deze release zijn nieuwe API's voor GET- en POST-kwalificaties geïmplementeerd. Als gevolg hiervan wordt de bestaande GET-kwalificatie op 6 mei **2021** ingetrokken.</span><span class="sxs-lookup"><span data-stu-id="70ca5-301">As part of that release, new GET and POST Qualifications APIs were deployed and, as a result, **the existing GET qualification will be retired on May 6, 2021**.</span></span> <span data-ttu-id="70ca5-302">Op dat moment moet u zijn overstappen op het gebruik van de nieuwe POST Partner Center API's.</span><span class="sxs-lookup"><span data-stu-id="70ca5-302">By that time, you will need to have transitioned to using the new POST Partner Center APIs.</span></span> <span data-ttu-id="70ca5-303">Met de nieuwe POST-API's kunt u Education-aanbiedingen aanschaffen, terwijl u met de nieuwe GET-API's vooraf gekwalificeerde Non-profit- en GCC-aanbiedingen kunt aanschaffen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-303">The new POST APIs will enable you to purchase Education offers, while the new GET APIs will enable you to purchase pre-qualified Nonprofit and GCC offers.</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-304">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-304">Next steps</span></span>

- <span data-ttu-id="70ca5-305">**Werk bij naar de nieuwe API's** voor een geslaagde en tijdige overgang.</span><span class="sxs-lookup"><span data-stu-id="70ca5-305">**Update to the new APIs** for a successful and timely transition.</span></span>

- <span data-ttu-id="70ca5-306">**Bekijk de nieuwe api Partner Center wijzigingen** en handleiding in de Operations Readiness-resources: verbeteringen van [Partner Center Education-klantvalidatieproces.](https://partner.microsoft.com/resources/collection/partner-center-edu-validation-enhancements#/)</span><span class="sxs-lookup"><span data-stu-id="70ca5-306">**Review the new Partner Center API changes and Guide** in the Operations Readiness resources: [Partner Center Education customer validation process enhancements](https://partner.microsoft.com/resources/collection/partner-center-edu-validation-enhancements#/).</span></span>

- <span data-ttu-id="70ca5-307">Deel deze informatie met de juiste teams binnen uw organisatie en met uw wederverkopers om hen te helpen zich voor te bereiden op deze wijzigingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-307">Share this information with the appropriate teams within your organization and with your resellers to help them prepare for these changes.</span></span>

### <a name="questions"></a><span data-ttu-id="70ca5-308">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-308">Questions?</span></span>

<span data-ttu-id="70ca5-309">Voor vragen met betrekking tot deze melding kunt u contact opnemen [met Partner Center ondersteuning.](https://partner.microsoft.com/dashboard/support/referrals/servicerequests?category=referrals)</span><span class="sxs-lookup"><span data-stu-id="70ca5-309">For any questions related to this notification, contact [Partner Center support](https://partner.microsoft.com/dashboard/support/referrals/servicerequests?category=referrals).</span></span>

### <a name="change-log"></a><span data-ttu-id="70ca5-310">Wijzigingenlogboek</span><span class="sxs-lookup"><span data-stu-id="70ca5-310">Change log</span></span>

- <span data-ttu-id="70ca5-311">4 mei 2021: Laatste herinnering van aanstaande afschaffing van GET-kwalificatie</span><span class="sxs-lookup"><span data-stu-id="70ca5-311">May 4, 2021: Final reminder of upcoming deprecation of GET qualification</span></span>

- <span data-ttu-id="70ca5-312">9 april 2021: Herinnering aan aanstaande afschaffing van GET-kwalificatie</span><span class="sxs-lookup"><span data-stu-id="70ca5-312">April 9, 2021: Reminder of upcoming deprecation of GET qualification</span></span> 

- <span data-ttu-id="70ca5-313">Februari: Bijgewerkte tijdlijnen voor het aftrekken van GET-& PUT-kwalificaties</span><span class="sxs-lookup"><span data-stu-id="70ca5-313">February: Updated timelines for deprecation of GET & PUT qualifications</span></span>

- <span data-ttu-id="70ca5-314">Januari: Herinnering aan aanstaande afschaffingen van GET-& PUT-kwalificaties</span><span class="sxs-lookup"><span data-stu-id="70ca5-314">January: Reminder of upcoming deprecations of GET & PUT qualifications</span></span>

________________
## <a name="new-format-for-the-new-commerce-pdf-invoice-in-csp"></a><a name="3"></a><span data-ttu-id="70ca5-315">Nieuwe indeling voor de nieuwe PDF-factuur voor commerce in CSP</span><span class="sxs-lookup"><span data-stu-id="70ca5-315">New format for the new commerce PDF invoice in CSP</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-316">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-316">Categories</span></span>

- <span data-ttu-id="70ca5-317">Datum: 2021-04-05</span><span class="sxs-lookup"><span data-stu-id="70ca5-317">Date: 2021-04-05</span></span>
- <span data-ttu-id="70ca5-318">Functies</span><span class="sxs-lookup"><span data-stu-id="70ca5-318">Capabilities</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-319">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-319">Summary</span></span>

<span data-ttu-id="70ca5-320">Microsoft introduceert een nieuwe indeling voor de nieuwe PDF-factuur voor commerce in het Cloud Solution Provider-programma (CSP) om factureringsgegevens weer te geven op productdetails in plaats van SKU-beschrijving.</span><span class="sxs-lookup"><span data-stu-id="70ca5-320">Microsoft is introducing a new format for the new commerce PDF invoice in the Cloud Solution Provider (CSP) program to display billing details by product detail instead of SKU description.</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-321">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-321">Impacted audience</span></span>

<span data-ttu-id="70ca5-322">Partners die het CSP-programma gebruiken</span><span class="sxs-lookup"><span data-stu-id="70ca5-322">Partners transacting through the CSP program</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-323">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-323">Details</span></span>

<span data-ttu-id="70ca5-324">Vanaf mei 2021 introduceert Microsoft een nieuwe indeling voor de nieuwe PDF-factuur voor commerce in het CSP-programma om factureringsgegevens weer te geven op productdetails in plaats van SKU-beschrijving.</span><span class="sxs-lookup"><span data-stu-id="70ca5-324">Starting May 2021, Microsoft is introducing a new format for the new commerce PDF invoice in the CSP program to display billing details by product detail instead of SKU description.</span></span> <span data-ttu-id="70ca5-325">Met deze nieuwe update aggregeren we de regelitems op producttype terwijl elk product op een afzonderlijke regel wordt weergegeven.</span><span class="sxs-lookup"><span data-stu-id="70ca5-325">With this new update, we will be aggregating the line items by product type while displaying every product on an individual line.</span></span>

<span data-ttu-id="70ca5-326">Partners zullen deze wijziging van kracht zien in hun factuur van mei voor de factureringsperiode tussen 1 april 2021 en 30 april 2021.</span><span class="sxs-lookup"><span data-stu-id="70ca5-326">Partners will notice this change coming into effect in their May invoice for the billing period between April 1, 2021 and April 30, 2021.</span></span> <span data-ttu-id="70ca5-327">De betrokken aanbiedingen zijn Microsoft Azure gereserveerde instantie, Azure-abonnementen (Azure-abonnement) en Marketplace.</span><span class="sxs-lookup"><span data-stu-id="70ca5-327">The affected offers are Microsoft Azure Reserved Instance, Azure subscriptions (Azure plan), and Marketplace.</span></span>

<span data-ttu-id="70ca5-328">Alle credit-rebill-aanvragen die worden gedaan nadat de factuurindeling is bijgewerkt, worden gegenereerd in de nieuwe indeling.</span><span class="sxs-lookup"><span data-stu-id="70ca5-328">Any credit-rebill requests made after the invoice format has been updated will be generated in the new format.</span></span>

#### <a name="partner-benefits"></a><span data-ttu-id="70ca5-329">Voordelen van partners</span><span class="sxs-lookup"><span data-stu-id="70ca5-329">Partner benefits</span></span>

<span data-ttu-id="70ca5-330">Deze update biedt de volgende verbeteringen in de factureringservaring voor partners:</span><span class="sxs-lookup"><span data-stu-id="70ca5-330">This update will offer the following improvements to the invoicing experience for partners:</span></span>

- <span data-ttu-id="70ca5-331">Gereduceerde factuurgrootte met behoud van kritieke gegevens</span><span class="sxs-lookup"><span data-stu-id="70ca5-331">Reduced invoice size while retaining critical data</span></span>

- <span data-ttu-id="70ca5-332">Afstemming van de indeling op de industriestandaarden voor compacte en gebruiksvriendelijke facturen</span><span class="sxs-lookup"><span data-stu-id="70ca5-332">Alignment of the format to the industry standards for compact and user-friendly invoices</span></span> 

<span data-ttu-id="70ca5-333">De volgende elementen worden niet beïnvloed:</span><span class="sxs-lookup"><span data-stu-id="70ca5-333">The following elements will not be affected:</span></span>

- <span data-ttu-id="70ca5-334">Pagina factureringsoverzicht op de FACTUUR-PDF</span><span class="sxs-lookup"><span data-stu-id="70ca5-334">Billing summary page on the invoice PDF</span></span>

- <span data-ttu-id="70ca5-335">Bestaande facturerings-API's</span><span class="sxs-lookup"><span data-stu-id="70ca5-335">Existing invoicing APIs</span></span>

- <span data-ttu-id="70ca5-336">Afstemmingsbestanden (Recon-bestanden kunnen worden gebruikt voor het ophalen van gedetailleerde gegevens.)</span><span class="sxs-lookup"><span data-stu-id="70ca5-336">Reconciliation files (Recon files can be used for retrieving granular data.)</span></span> 

- <span data-ttu-id="70ca5-337">Facturen voor gebruiks- en licentiekosten</span><span class="sxs-lookup"><span data-stu-id="70ca5-337">Usage and license-based charges invoices</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-338">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-338">Next steps</span></span>

<span data-ttu-id="70ca5-339">Lees de informatie over dit onderwerp in de [resourcegalerie Operations Readiness](https://partner.microsoft.com/resources/collection/introducing-new-format-for-the-new-commerce-invoice-in-csp#/) op de website van de Microsoft-partner.</span><span class="sxs-lookup"><span data-stu-id="70ca5-339">Review the information about this topic in the [Operations Readiness resource gallery](https://partner.microsoft.com/resources/collection/introducing-new-format-for-the-new-commerce-invoice-in-csp#/) on the Microsoft partner website.</span></span> <span data-ttu-id="70ca5-340">Voor meer informatie over facturerings- en belastingonderwerpen, waaronder factureringsresources, facturen, CSP-facturering en belastingen, gaat u naar de sectie Facturering [in](../billing.md) Partner Center.</span><span class="sxs-lookup"><span data-stu-id="70ca5-340">For more information about billing and tax topics including billing resources, invoices, CSP billing, and taxes, visit the [Billing section](../billing.md) in Partner Center.</span></span>

________________
## <a name="changes-to-the-cloud-solution-provider-csp-customer-onboarding-requirements"></a><a name="2"></a><span data-ttu-id="70ca5-341">Wijzigingen in de onboardingvereisten Cloud Solution Provider de klant (CSP)</span><span class="sxs-lookup"><span data-stu-id="70ca5-341">Changes to the Cloud Solution Provider (CSP) customer onboarding requirements</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-342">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-342">Categories</span></span>

- <span data-ttu-id="70ca5-343">Datum: 2021-04-02</span><span class="sxs-lookup"><span data-stu-id="70ca5-343">Date: 2021-04-02</span></span>
- <span data-ttu-id="70ca5-344">Aanbiedingen/markten</span><span class="sxs-lookup"><span data-stu-id="70ca5-344">Offers/Markets</span></span>

### <a name="summary"></a><span data-ttu-id="70ca5-345">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-345">Summary</span></span>

<span data-ttu-id="70ca5-346">Als onderdeel van onze inzet om partners en klanten te helpen hun bedrijf te runnen op basis van vertrouwen, vragen we aanvullende klantgegevens aan, met ingang van 25 maart 2021.</span><span class="sxs-lookup"><span data-stu-id="70ca5-346">As part of our commitment to help partners and customers run their business based on trust, we will request additional customer information, effective March 25, 2021.</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-347">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-347">Impacted audience</span></span>

<span data-ttu-id="70ca5-348">CSP-partners voor directe factuur en indirecte providers die nieuwe of bestaande klanten hebben in de landen die in de volgende sectie worden vermeld</span><span class="sxs-lookup"><span data-stu-id="70ca5-348">CSP direct bill partners and indirect providers who have new or existing customers in the countries listed in the next section</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-349">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-349">Details</span></span>

<span data-ttu-id="70ca5-350">Microsoft wordt uitgevoerd op vertrouwen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-350">Microsoft runs on trust.</span></span> <span data-ttu-id="70ca5-351">We zetten ons in voor een compatibele, veilige en veilige methode voor klantvalidatie voor het transacteren van klantabonnementen in het CSP-programma.</span><span class="sxs-lookup"><span data-stu-id="70ca5-351">We’re committed to providing a compliant, safe, and secure method of customer validation for transacting customer subscriptions in the CSP program.</span></span> <span data-ttu-id="70ca5-352">Op 25 maart 2021 introduceren we verbeteringen van Partner Center API en gebruikersinterface (UI) die van invloed zijn op partners die aan beide van de volgende criteria voldoen:</span><span class="sxs-lookup"><span data-stu-id="70ca5-352">On March 25, 2021, we will be introducing Partner Center API and user interface (UI) enhancements that will affect partners who meet both of the following criteria:</span></span>

- <span data-ttu-id="70ca5-353">De partner heeft een directe factureringsrelatie met Microsoft (wat betekent dat de partner een directe factureringspartner of een indirecte provider is).</span><span class="sxs-lookup"><span data-stu-id="70ca5-353">The partner has a direct billing relationship with Microsoft (which means that the partner is either a direct bill partner or an indirect provider).</span></span>

- <span data-ttu-id="70ca5-354">De partner doet zaken met nieuwe of bestaande klanten in de volgende landen:</span><span class="sxs-lookup"><span data-stu-id="70ca5-354">The partner does business with new or existing customers in the following countries:</span></span>

    - <span data-ttu-id="70ca5-355">Thailand</span><span class="sxs-lookup"><span data-stu-id="70ca5-355">Thailand</span></span>
    - <span data-ttu-id="70ca5-356">Vietnam</span><span class="sxs-lookup"><span data-stu-id="70ca5-356">Vietnam</span></span>
    - <span data-ttu-id="70ca5-357">Turkije</span><span class="sxs-lookup"><span data-stu-id="70ca5-357">Turkey</span></span>
    - <span data-ttu-id="70ca5-358">Polen</span><span class="sxs-lookup"><span data-stu-id="70ca5-358">Poland</span></span>
    - <span data-ttu-id="70ca5-359">Zuid-Afrika</span><span class="sxs-lookup"><span data-stu-id="70ca5-359">South Africa</span></span>
    - <span data-ttu-id="70ca5-360">India</span><span class="sxs-lookup"><span data-stu-id="70ca5-360">India</span></span>
    - <span data-ttu-id="70ca5-361">Brazilië</span><span class="sxs-lookup"><span data-stu-id="70ca5-361">Brazil</span></span>
    - <span data-ttu-id="70ca5-362">Irak</span><span class="sxs-lookup"><span data-stu-id="70ca5-362">Iraq</span></span>
    - <span data-ttu-id="70ca5-363">Myanmar</span><span class="sxs-lookup"><span data-stu-id="70ca5-363">Myanmar</span></span>
    - <span data-ttu-id="70ca5-364">Zuid-Soedan</span><span class="sxs-lookup"><span data-stu-id="70ca5-364">South Sudan</span></span>
    - <span data-ttu-id="70ca5-365">Saoedi-Arabië</span><span class="sxs-lookup"><span data-stu-id="70ca5-365">Saudi Arabia</span></span>
    - <span data-ttu-id="70ca5-366">Verenigde Arabische Emiraten</span><span class="sxs-lookup"><span data-stu-id="70ca5-366">United Arab Emirates</span></span>
    - <span data-ttu-id="70ca5-367">Venezuela</span><span class="sxs-lookup"><span data-stu-id="70ca5-367">Venezuela</span></span>

<span data-ttu-id="70ca5-368">Partners die aan de criteria voldoen, moeten de bedrijfsregistratie-id (ook wel de INN van de organisatie van de klant genoemd) en het telefoonnummer van een klant indienen wanneer ze de volgende keer een abonnement voor die klant bijwerken of maken.</span><span class="sxs-lookup"><span data-stu-id="70ca5-368">Partners who meet the criteria will have to submit a customer's company registration ID (also known as the customer's organization INN) and phone number when they next update or create a subscription for that customer.</span></span> <span data-ttu-id="70ca5-369">Deze partners kunnen ook een optionele middelste naam voor de klant invoeren.</span><span class="sxs-lookup"><span data-stu-id="70ca5-369">These partners can also enter an optional middle name for the customer.</span></span>

<span data-ttu-id="70ca5-370">Houd er rekening mee dat wanneer u uw bedrijfsregistratie-id toevoegt, u uw zakelijke btw-id moet gebruiken en niet de persoonlijke id van de klant.</span><span class="sxs-lookup"><span data-stu-id="70ca5-370">Note that when you add your company registration ID you should use your business tax ID and not the customer personal ID.</span></span>

<span data-ttu-id="70ca5-371">Partners die zaken doen met nieuwe of bestaande klanten in de volgende landen, hebben in november 2020 al een eerdere release gehad.</span><span class="sxs-lookup"><span data-stu-id="70ca5-371">Partners who do business with new or existing customers in the following countries have already been onboarded with a previous release in November 2020.</span></span>

- <span data-ttu-id="70ca5-372">Armenië</span><span class="sxs-lookup"><span data-stu-id="70ca5-372">Armenia</span></span>
- <span data-ttu-id="70ca5-373">Azerbeidzjan</span><span class="sxs-lookup"><span data-stu-id="70ca5-373">Azerbaijan</span></span>
- <span data-ttu-id="70ca5-374">Belarus</span><span class="sxs-lookup"><span data-stu-id="70ca5-374">Belarus</span></span>
- <span data-ttu-id="70ca5-375">Hongarije</span><span class="sxs-lookup"><span data-stu-id="70ca5-375">Hungary</span></span>
- <span data-ttu-id="70ca5-376">Kazachstan</span><span class="sxs-lookup"><span data-stu-id="70ca5-376">Kazakhstan</span></span>
- <span data-ttu-id="70ca5-377">Kirgistan</span><span class="sxs-lookup"><span data-stu-id="70ca5-377">Kyrgyzstan</span></span>
- <span data-ttu-id="70ca5-378">Moldavië</span><span class="sxs-lookup"><span data-stu-id="70ca5-378">Moldova</span></span>
- <span data-ttu-id="70ca5-379">Rusland</span><span class="sxs-lookup"><span data-stu-id="70ca5-379">Russia</span></span>
- <span data-ttu-id="70ca5-380">Tadzjikistan</span><span class="sxs-lookup"><span data-stu-id="70ca5-380">Tajikistan</span></span>
- <span data-ttu-id="70ca5-381">Oekraïne</span><span class="sxs-lookup"><span data-stu-id="70ca5-381">Ukraine</span></span>
- <span data-ttu-id="70ca5-382">Oezbekistan</span><span class="sxs-lookup"><span data-stu-id="70ca5-382">Uzbekistan</span></span>

<span data-ttu-id="70ca5-383">Partners met klanten in de rest van de wereld kunnen eind maart 2021 de bedrijfsregistratie-id, het telefoonnummer en de middelste naam voor klanten invoeren als optionele gegevens.</span><span class="sxs-lookup"><span data-stu-id="70ca5-383">Partners with customers in the rest of the world will have the ability at the end of March 2021 to enter the company registration ID, phone number, and middle name for customers as optional details.</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-384">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-384">Next steps</span></span>

- <span data-ttu-id="70ca5-385">Bekijk de technische documentatie en veelgestelde vragen in de verzameling [toegewezen partners](https://partner.microsoft.com/resources/collection/additionalfields-csp-customers-selected-geos#/) voor meer gedetailleerde richtlijnen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-385">Review the technical documentation and frequently asked questions in the dedicated [partner collection](https://partner.microsoft.com/resources/collection/additionalfields-csp-customers-selected-geos#/) for more detailed guidance.</span></span>
- <span data-ttu-id="70ca5-386">Bereid u voor op het opnemen van de wijzigingen Partner Center api en webgebruikerservaring.</span><span class="sxs-lookup"><span data-stu-id="70ca5-386">Prepare to incorporate the changes using Partner Center API and web user experience.</span></span> <span data-ttu-id="70ca5-387">API's/SDK's zijn beschikbaar voor testen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-387">API/SDKs will be available for testing.</span></span>
- <span data-ttu-id="70ca5-388">Zorg ervoor dat u de aanvullende gegevens indient bij het onboarden van nieuwe klanten of het wijzigen van bestaande klantgegevens.</span><span class="sxs-lookup"><span data-stu-id="70ca5-388">Make sure to submit the additional data when onboarding new customers or modifying existing customer details.</span></span>
- <span data-ttu-id="70ca5-389">Als u een CPV-oplossing (Panel Vendor) gebruikt, raadpleegt u uw CPV.</span><span class="sxs-lookup"><span data-stu-id="70ca5-389">If you’re using a control panel vendor (CPV) solution, consult your CPV.</span></span>

### <a name="questions"></a><span data-ttu-id="70ca5-390">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-390">Questions?</span></span>

<span data-ttu-id="70ca5-391">Neem contact op met uw belastingadviseur of lokale belastingbureau als u vragen hebt met betrekking tot de registratie-id van het bedrijf (ook wel INN of TIN genoemd).</span><span class="sxs-lookup"><span data-stu-id="70ca5-391">Contact your tax advisor or local tax office if you have any questions related to the company registration ID (also called INN or TIN).</span></span> <span data-ttu-id="70ca5-392">Microsoft kan geen richtlijnen geven over belastingzaken.</span><span class="sxs-lookup"><span data-stu-id="70ca5-392">Microsoft cannot provide guidance on tax matters.</span></span>

<span data-ttu-id="70ca5-393">Als u ondersteuning nodig hebt voor uw bewerkingen met Microsoft, opent u een [serviceaanvraag.](https://partner.microsoft.com/dashboard/support/servicerequests/create?stage=2&topicid=aa679372-d996-73df-e244-cb28bbbf28e8)</span><span class="sxs-lookup"><span data-stu-id="70ca5-393">If you need support with your operations with Microsoft, open a [service request](https://partner.microsoft.com/dashboard/support/servicerequests/create?stage=2&topicid=aa679372-d996-73df-e244-cb28bbbf28e8).</span></span>

## <a name="view-this-months-product-launches-and-offers"></a><a name="1"></a><span data-ttu-id="70ca5-394">Productlanceringen en aanbiedingen van deze maand weergeven</span><span class="sxs-lookup"><span data-stu-id="70ca5-394">View this month’s product launches and offers</span></span>

### <a name="categories"></a><span data-ttu-id="70ca5-395">Categorieën</span><span class="sxs-lookup"><span data-stu-id="70ca5-395">Categories</span></span>

- <span data-ttu-id="70ca5-396">Datum: 2021-04-01</span><span class="sxs-lookup"><span data-stu-id="70ca5-396">Date: 2021-04-01</span></span>
- <span data-ttu-id="70ca5-397">Functies</span><span class="sxs-lookup"><span data-stu-id="70ca5-397">Capabilities</span></span>
 
### <a name="summary"></a><span data-ttu-id="70ca5-398">Samenvatting</span><span class="sxs-lookup"><span data-stu-id="70ca5-398">Summary</span></span>

<span data-ttu-id="70ca5-399">De kalender voor productlancering van april 2021 is nu gepubliceerd.</span><span class="sxs-lookup"><span data-stu-id="70ca5-399">The April 2021 product launch calendar is now published.</span></span>

### <a name="impacted-audience"></a><span data-ttu-id="70ca5-400">Beïnvloede doelgroep</span><span class="sxs-lookup"><span data-stu-id="70ca5-400">Impacted audience</span></span>

<span data-ttu-id="70ca5-401">Alle partners die het programma Cloud Solution Provider (CSP)</span><span class="sxs-lookup"><span data-stu-id="70ca5-401">All partners transacting through the Cloud Solution Provider (CSP) program</span></span>

### <a name="details"></a><span data-ttu-id="70ca5-402">Details</span><span class="sxs-lookup"><span data-stu-id="70ca5-402">Details</span></span>

<span data-ttu-id="70ca5-403">De kalender voor productlancering van [april](https://partner.microsoft.com/resources/collection/product-launch-calendar-collection#/) 2021 is nu beschikbaar in de resourcegalerie Operations-gereedheid.</span><span class="sxs-lookup"><span data-stu-id="70ca5-403">The April 2021 [product launch calendar](https://partner.microsoft.com/resources/collection/product-launch-calendar-collection#/) is now available in the Operations readiness resource gallery.</span></span> <span data-ttu-id="70ca5-404">Bekijk hier de komende productlanceringen en aanbiedingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-404">View the upcoming product launches and offers here.</span></span>

### <a name="next-steps"></a><span data-ttu-id="70ca5-405">Volgende stappen</span><span class="sxs-lookup"><span data-stu-id="70ca5-405">Next steps</span></span>

<span data-ttu-id="70ca5-406">Bekijk de [kalender voor productlancering](https://partner.microsoft.com/resources/collection/product-launch-calendar-collection#/)en deel de informatie met de juiste belanghebbenden in uw organisatie.</span><span class="sxs-lookup"><span data-stu-id="70ca5-406">Review the [product launch calendar](https://partner.microsoft.com/resources/collection/product-launch-calendar-collection#/), and share the information with the appropriate stakeholders in your organization.</span></span>  

### <a name="questions"></a><span data-ttu-id="70ca5-407">Vragen?</span><span class="sxs-lookup"><span data-stu-id="70ca5-407">Questions?</span></span>

<span data-ttu-id="70ca5-408">Raadpleeg uw relevante Yammer-community's voor meer vragen over deze aanbiedingen.</span><span class="sxs-lookup"><span data-stu-id="70ca5-408">For any further questions about these offers, check your relevant Yammer communities.</span></span>