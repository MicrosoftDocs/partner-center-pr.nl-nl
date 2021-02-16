---
title: Aankondigingen van februari 2021
description: Mede delingen van februari 2021 voor micro soft-partner centrum met nieuwe mogelijkheden, aanbiedingen, aanbiedingen, markten of wijzigingen in bestaande aanbiedingen.
ms.topic: article
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
author: brentserbus
ms.author: brserbus
ms.custom: announcement
ms.localizationpriority: high
ms.date: 02/04/2021
ms.openlocfilehash: 8348179438ad65449ea75cd5ebce8ba0a92d7b9a
ms.sourcegitcommit: 0416562dd89408524f8312a8acd5b6944b6d91c4
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 02/16/2021
ms.locfileid: "100540995"
---
# <a name="february-2021-announcements"></a>Aankondigingen van februari 2021

Op deze pagina vindt u informatie over de aankondigingen voor het micro soft Partner Center voor februari 2021.

________________
## <a name="now-live-docusign-migration-to-adobe-sign-for-partners-under-microsoft-partner-agreements-mpas"></a><a name="9"></a> Nu Live: DocuSign migratie naar Adobe-ondertekenen voor partners onder micro soft-partner overeenkomsten (MPAs)

### <a name="categories"></a>Categorieën

- Datum: 2021-02-16
- Functies

### <a name="summary"></a>Samenvatting

Micro soft gaat de verwerking van de elektronische hand tekening van DocuSign naar Adobe-ondertekening.

### <a name="impacted-audience"></a>Doel groep

Bestaande directe en indirecte CSP-partners (Cloud Solution Provider) onder MPA.

### <a name="details"></a>Details

In februari 2021 gaat micro soft de verwerking van alle elektronische hand tekeningen van DocuSign naar Adobe-ondertekenen voor CSP-partners.

U moet een soepele overgang verwachten. Na de migratie ontvangt u een e-mail bericht van adobesign@adobesign.com in plaats van DocuSign, wanneer uw elektronische hand tekening vereist is. Dit e-mail bericht bevat een koppeling naar de webpagina van Adobe, waar u zich moet aanmelden. Micro soft-partners hoeven bestaande overeenkomsten niet opnieuw te ondertekenen, maar alleen toekomstige kanaal overeenkomsten. Partners in Oekraïne, Rusland en Kazachstan moeten de groen van een jaar fysiek of elektronisch opnieuw ondertekenen.

U vindt een voor beeld van een e-mail bericht voor de hand tekening van Adobe-ondertekening in [de resource galerie](https://partner.microsoft.com/resources/detail/adobe-sign-signature-request-email-pdf).

Voor de beste ervaring moet u het volgende doen:

1. Voeg toe adobesign@adobesign.com aan de lijst met veilige afzenders om e-mail berichten van dit account rechtstreeks naar uw map Ongewenste e-mail te sturen.
2. Werk samen met uw IT-afdeling voor het volgende:
    - Voeg het adobesign@adobesign.com e-mail adres toe aan de lijst met veilige afzenders om ervoor te zorgen dat deze niet is opgenomen in een vooraf ingestelde phishing-regel.
    - Werk het bestaande beveiligings beleid bij om ervoor te zorgen dat alle vereiste ontvangers de documentatie kunnen ondertekenen onder uw Adobe Sign Enter prise-licentie.

Bronnen die betrekking hebben op onboarding-, functionaliteits-en bedrijfsproces vragen, vindt u op de [pagina de migratie partner van Adobe Sign](https://aka.ms/eSignature/External).

Adobe Sign is de voor Keurs-oplossing voor elektronische hand tekeningen (ESS) van micro soft. De overgang naar Adobe Sign zorgt voor een veilige en efficiënte elektronische hand tekening waarmee klanten en partners meerwaarde kunnen bieden.

Raadpleeg de volgende zelf studies voor meer informatie over het elektronisch ondertekenen van documenten en het overdragen van elektronische hand tekeningen:

- [Een document elektronisch ondertekenen | Zelf studies voor Adobe-ondertekening](https://helpx.adobe.com/sign/how-to/adobe-for-signers.html?playlist=/ccx/v1/collection/product/sign/segment/designer/explevel/beginner/applaunch/continuinged/collection.ccx.js&ref=helpx.adobe.com)
- [Iemand anders delegeren om een document te ondertekenen | Zelf studies voor Adobe-ondertekening](https://helpx.adobe.com/sign/how-to/use-the-delegator-role.html?playlist=/ccx/v1/collection/product/sign/segment/designer/explevel/beginner/applaunch/orientation/collection.ccx.js&ref=helpx.adobe.com)

### <a name="next-steps"></a>Volgende stappen

Deel deze informatie met de juiste belanghebbenden in uw organisatie.

### <a name="questions"></a>Vragen?

Als u vragen hebt, neemt u contact op met uw regionale Operations Center met het [hulp programma voor oproep registratie (CLT)](https://clt.partners.extranet.microsoft.com/CLT) of op [Verken MS](https://www.explore.ms/). Volg het standaard CLT-proces nauw keurig zodat we zo snel mogelijk uw query kunnen omzetten.

### <a name="change-log"></a>Wijzigingslogboek

- 15 januari 2021: oorspronkelijke publicatie 
- 16 februari 2021: nu live, nieuwe resource: Adobe Sign migratie partner (pagina) 

_____________

## <a name="reminder-introducingapithrottlingtopartners-calling-partner-centerapis"></a><a name="8"></a> Herinnering: Inleiding tot de API-beperking voor partners die partner Center-Api's aanroepen

### <a name="categories"></a>Categorieën

- Datum: 2021-02-16
- Uw bedrijf laten groeien

### <a name="summary"></a>Samenvatting

Micro soft implementeert de API-beperking om een meer consistente prestaties te bieden binnen een tijds Panne voor partners die de Api's van het partner centrum aanroepen.

### <a name="impacted-audience"></a>Doel groep

Alle partners communiceren via het CSP-programma (Cloud Solution Provider)  

### <a name="details"></a>Details

Vanaf februari 2021 heeft micro soft de API-beperking geïmplementeerd, zodat er meer consistentie is binnen een tijds Panne voor partners die de Api's van het partner centrum aanroepen.Met beperking wordt het aantal aanvragen van een service in een bepaalde periode beperkt om te voor komen dat bronnen worden gevermijdd.Wanneer een drempel waarde voor bandbreedte beperking wordt overschreden, beperkt het partner centrum voor een bepaalde periode verdere aanvragen van die client.

**Voor delen van partner:**

Het partner centrum is ontworpen om een groot aantal aanvragen af te handelen, maar als er veel aanvragen worden gedaan door een aantal partners, helpt het beperken van de optimale prestaties en betrouw baarheid van alle partners.  

- Beperking zorgt voor minimale downtime.
- Met beperking wordt het aantal aanvragen voor grote volumes verminderd, waardoor er consistente prestaties zijn voor alle partners.

**Api's die moeten worden beperkt:**

| Bewerking | Documentatie voor Partnercentrum |
| ------ | ------- |
|{baseURL}/v1/Customers/{customer_id}/Subscriptions  | [Alles-van-een-een-klant-s-abonnementen](/partner-center/develop/get-all-of-a-customer-s-subscriptions&data) |
|{baseURL}/v1/Customers/{customer_id}/Subscriptions/{subscription_id}  | [Een abonnement ophalen op basis van id](/partner-center/develop/get-a-subscription-by-id) |
|{baseURL}/v1/Customers/{customer_id}/orders  | [Alle klant orders ophalen](/partner-center/develop/get-all-of-a-customer-s-orders) |
|{baseURL}/v1/Customers/{customer_id}/orders/{order_id}  | [Een bestelling ophalen op basis van id](/partner-center/develop/get-an-order-by-id) |
|{baseURL}/v1/Customers/{customer_id}/orders/{order_id}/provisioningstatus  | [De inrichtingsstatus van het abonnement ophalen](/partner-center/develop/get-subscription-provisioning-status) |
|{baseURL}/v1/Customers/{customer_id}/Subscriptions/{subscription_id}  | [Orders beheren en een abonnement beheren](/partner-center/develop/manage-orders#manage-a-subscription) |
|{baseURL}/v1/Customers/{customer_id}/Subscriptions/{subscription_id}/addons  | [Een lijst met invoegtoepassingen voor een abonnement ophalen](/partner-center/develop/get-a-list-of-add-ons-for-a-subscription) |
|{baseURL}/v1/Customers/{customer_id}/Subscriptions/{subscription_id}/azureEntitlements | [Een lijst met Azure-rechten voor een abonnement ophalen](/partner-center/develop/get-a-list-of-azure-entitlements-for-subscription) |
|{baseURL}/v1/Customers/{customer_id}/Subscriptions/{subscription_id}/registrationstatus  | [De registratiestatus van het abonnement ophalen](/partner-center/develop/get-subscription-registration-status) |
|{baseURL}/v1/customers/{customer-tenant-id}/transfers  | [Alle overdrachten van een klant ophalen](/partner-center/develop/get-all-of-a-customer-s-transfers) |
|{baseURL}/v1/productUpgrades/{upgrade-id}/status  | [Upgradestatus van product ophalen](/partner-center/develop/get-product-upgrade-status) |
|{baseURL}/v1/customers/{customer-id}/subscriptions/{subscription-id}/conversions   | [Een lijst met aanbiedingen voor omzetten van de proefversie ophalen](/partner-center/develop/get-a-list-of-trial-conversion-offers) |
 
We raden u ten zeerste aan dat partners gebruikmaken van de API voor het activiteiten logboek voor meer efficiëntie en om te voor komen dat deze wordt beperkt.Raadpleeg de Details [voor meer informatie](/partner-center/develop/api-throttling-guidance)over deze functie.  

### <a name="next-steps"></a>Volgende stappen

Bekijk de [bronnen](/partner-center/develop/api-throttling-guidance)   voor dit onderwerp en voer de benodigde stappen uit.  

_______________

## <a name="introducing-microsoft-viva-topics"></a><a name="7"></a>Inleiding tot micro soft Viva-onderwerpen

### <a name="categories"></a>Categorieën

- Datum: 12 februari 2021
- Functies

### <a name="affected-audience"></a>Betrokken doel groep

Alle partners communiceren via het CSP-programma (Cloud Solution Provider)

### <a name="details"></a>Details

Micro soft Vivae-onderwerpen zijn van toepassing op kunst matige intelligentie (AI) om kennis en expertise van uw organisatie te identificeren en deze in gedeelde onderwerpen, zoals producten, klanten of projecten, aan te duiden. Met insluitende onderwerpen over kaarten en onderwerpen vindt u kennis in de context van uw teams, projecten en documenten. AI en mensen werken samen om de kennis en het Opper vlak ervan te verbeteren in de apps die u dagelijks gebruikt. 

Gebruikers moeten een van de volgende licenties hebben om in aanmerking te komen voor Viva-onderwerpen:   
- Microsoft 365 F1, F3, E3, a3, E5 of A5 
- Office 365 F3, E1, a1, E3, a3, E5 of A5 
- Microsoft 365 Business Basic, Standard of Premium 
- Share point K, abonnement 1 of Plan2 

**Details van aanbieding**

Deze aanbiedingen hebben de ' Topics ' in hun aanbiedings namen in de prijs lijsten van 1 februari. Deze aanbiedings namen worden bijgewerkt met ' Viva-onderwerpen ' wanneer de prijs lijsten worden bijgewerkt op 1 maart.

|**Naam van aanbieding**|**Aanbiedings-id**|**Materiaal-ID**|
|------------------|:--------------------|:------------------|
|Viva-onderwerpen|b9ef0c81-9ca6-45fd-a6c1-627745ba8b8a|1JV-00005|
|Viva-onderwerpen voor faculteiten|8c930d38-db61-4afa-83f9-77c595c5cdfc|1TK-00006|
|Viva-onderwerpen voor studenten|5de461d5-8ccc-4a8e-98ae-58a3ad400a57|1TK-00007|

### <a name="next-steps"></a>Volgende stappen

- Bekijk de resources voor dit onderwerp en deel deze informatie met de juiste belanghebbenden in uw organisatie.  
- Meer informatie vindt u in het [Viva-onderwerpen Resource Center](https://resources.techcommunity.microsoft.com/viva-topics).

_______________

## <a name="microsoft-365-e3-price-changes-coming-for-march-2021"></a><a name="6"></a>Prijs wijzigingen voor Microsoft 365 E3 voor maart 2021

### <a name="categories"></a>Categorieën

- Datum: 11 februari 2021
- Aanbiedingen/markten

### <a name="affected-audience"></a>Betrokken doel groep

Alle partners handelen via het programma Cloud Solution Provider (CSP) in EUR, AUD, GBP en JPY.

### <a name="details"></a>Details

De prijs lijst voor de preview-versie van de licentie voor maart 2021 is bijgewerkt, zodat de prijs wijzigingen voor Microsoft 365 E3 worden meegenomen. De betrokken aanbieding en valuta's worden hieronder weer gegeven. 
 
Naam van aanbieding: Microsoft 365 E3-aanbiedings-ID: 2b3b8d2d-10aa-4be4-b5fd-7f2feb0c3091 material ID: AAA-35638

Deze Microsoft 365 E3-Prijs updates zijn beperkt tot deze valuta's: JPY (Japanse yen), GBP (geweldig Britse pond), EUR (Europese Unie), AUD (Australische dollar). Er zijn andere prijs wijzigingen in het maart-bestand en partners moeten de nieuwste preview-versie krijgen om de andere verwachte wijzigingen weer te geven.

### <a name="next-steps"></a>Volgende stappen

Partners moeten de nieuwste prijs lijst bestanden downloaden van het partner centrum om de nieuwste prijzen voor maart te krijgen. 

_______________

## <a name="license-based-preview-price-list-updated-for-norwegian-krone"></a><a name="5"></a>Prijs lijst voor preview van licentie is bijgewerkt voor Noorse kroon

### <a name="categories"></a>Categorieën

- Datum: 10 februari 2021
- Aanbiedingen/markten

### <a name="affected-audience"></a>Betrokken doel groep

Alle partners communiceren via het CSP-programma (Cloud Solution Provider)

### <a name="summary"></a>Samenvatting

De prijs lijst voor de preview-versie van de licentie is bijgewerkt voor de prijs van Noorse kroon voor 1 maart 2021.

### <a name="details"></a>Details

De FX-tarief wijzigingen voor maart waren niet opgenomen in de vorige prijs lijsten op basis van een licentie van maart. Dit bestand is bijgewerkt met de verwachte prijs wijzigingen voor Noorse kroon. Partners moeten het meest recente preview-prijs bestand ophalen om te zien of deze wijzigingen worden verwacht voor 1 maart 2021. Deze wijzigingen gelden alleen voor prijzen voor Noorse kroon-valuta's.

### <a name="next-steps"></a>Volgende stappen

Partners moeten het huidige prijslijst voorbeeld bestand downloaden voor de verwachte wijzigingen voor 1 maart 2021.

_______________

## <a name="premium-assessments-an-add-on-to-compliance-manager-is-coming-on-march-1-2021"></a><a name="4"></a>Premium-evaluaties, een invoeg toepassing voor Compliance Manager, is beschikbaar op 1 maart 2021

### <a name="categories"></a>Categorieën

- Datum: 5 februari 2021
- Functies

### <a name="affected-audience"></a>Betrokken doel groep

Alle partners communiceren via het CSP-programma (Cloud Solution Provider)

### <a name="summary"></a>Samenvatting

Premium-analyses worden in februari opgenomen in de preview van de prijs lijst en zijn vanaf 1 maart 2021 beschikbaar.

### <a name="details"></a>Details

Premium-evaluaties zijn een optionele invoeg toepassing voor Compliance Manager en kunnen klanten helpen bij de naleving van nationale, regionale en branchespecifieke vereisten die het verzamelen en gebruiken van gegevens regelen. Premium-evaluaties zijn gereserveerd voor Office 365 E5, A5 en G5, en Microsoft 365 E5-, A5-en G5-klanten.

|**Naam van aanbieding**|**Aanbiedings-id**|**Materiaal-ID**|
|------------------|:--------------------|:------------------|
|CSP-Corp-invoeg toepassing|[76be61a7-2c03-4b3e-8330-63b11bd904ed](https://commoffertool.catalog.cp.microsoft.com/Prod/Office365/offer/details/76be61a7-2c03-4b3e-8330-63b11bd904ed)|8JA-00003|
|CSP-Corp-proef versie|[f2f6ae44-24fe-450c-9cd7-529e7c8cfcb4](https://commoffertool.catalog.cp.microsoft.com/Prod/Office365/offer/details/f2f6ae44-24fe-450c-9cd7-529e7c8cfcb4)|8JA-00004|
|CSP-educatieve-faculteiten-invoeg toepassing|[fa7f5773-063a-48cf-b3e2-de509ea1262f](https://commoffertool.catalog.cp.microsoft.com/Prod/Office365/offer/details/fa7f5773-063a-48cf-b3e2-de509ea1262f)|8JB-00003|
|CSP-educatieve-faculteiten-proef versie|[828cecbd-8728-4339-b0c2-51e009a67d88](https://commoffertool.catalog.cp.microsoft.com/Prod/Office365/offer/details/828cecbd-8728-4339-b0c2-51e009a67d88)|8JB-00004|

### <a name="next-steps"></a>Volgende stappen

Bekijk de volgende bronnen voor dit onderwerp en deel de informatie met de juiste belanghebbenden in uw organisatie.   

- [Microsoft 365 E5 beveiliging en naleving](https://www.microsoft.com/licensing/product-licensing/microsoft-365-enterprise?rtc=1&activetab=m365-enterprise:primaryr5)
- [Evaluaties bouwen en beheren in micro soft Compliance Manager](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-assessments&preserve-view=true=o365-worldwide)

_________________________________________________________

## <a name="responding-to-covid-19-microsoft-partner-network-update"></a><a name="3"></a> Reageren op COVID-19: Microsoft Partner Network update

### <a name="categories"></a>Categorieën

- Datum: 4 februari 2021
- Functies

### <a name="impacted-audience"></a>Doel groep

Alle partners

### <a name="details"></a>Details

Micro soft biedt competentie-uitbrei ding (met uitzonde ring van de Cloud Business Applications competentie) en geavanceerde specialisatie-uitbrei ding voor partners met jubileum datums (AD) van 1 januari 2021 tot en met 30 juni 2021. Raadpleeg het [blog](https://blogs.partner.microsoft.com/mpn/responding-to-covid-19-microsoft-partner-network/) bericht over partners voor meer informatie.
________________
## <a name="new-updates-to-the-referrals-module-in-partner-center"></a><a name="2"></a> Nieuwe updates voor de module referrals in Partner Center

### <a name="categories"></a>Categorieën

- Datum: 5 februari 2021
- Functies
 
### <a name="impacted-audience"></a>Doel groep

- Partners met kant-en-klare aanbiedingen voor de verkoop
- Partners met een transactable-aanbieding die in aanmerking komt voor een Azure-oplossing voor prikkel in de commerciële Marketplace
- Alle partners die gebruikmaken van de module referrals in Partner Center.

### <a name="details"></a>Details

Naarmate we in het nieuwe jaar overstappen, voegen we mogelijkheden toe om de ervaring van de verkoop in partner centrum te verbeteren en te verrijken. Deze nieuwe functies helpen u bij het versnellen van de deal snelheid, het uitbreiden van de toegang tot de verkoper en het beter schalen van uw bedrijf. Deze nieuwe toevoegingen worden geïntroduceerd in de module referrals en helpen u bij het bereiken van meer klanten via andere micro soft-partners of micro soft-verkopers, en tegelijk met het beheer van uw pijp lijn met micro soft op één locatie.  

Hier is what's nieuw in de module Partner Center Referrals:

#### <a name="all-partners-using-the-referrals-module-in-partner-center"></a>Alle partners die gebruikmaken van de module referrals in Partner Center  

- [Nieuwe SMB-verbindingen maken](https://docs.microsoft.com/partner-center/connect-with-your-customers): mede verkopen en samen werken met micro soft-verkopers om binnenkomende verkoop kansen te verkrijgen die betrekking hebben op SMB-klanten.

- [Machtigingen voor verwijzingen uitvouwen](https://docs.microsoft.com/partner-center/permissions-overview#manage-referrals): wijs machtigingen toe aan gebruikers, op basis van het feit of u wilt dat ze beschikken over beheerders machtigingen (toegang tot alle verkoop kansen) of gebruikers machtigingen (toegang tot de specifieke verkoop kansen van de gebruiker).

- [Partner Sales Connect-gebruikers migratie](https://docs.microsoft.com/partner-center/psc-to-pc#user-migration): wijs bestaande partner Sales Connect-gebruikers machtigingen toe aan de bijbehorende Partner Center-referentie beheerder en wijs gebruikers machtigingen toe en pas vervolgens de nieuwe machtigingen op de gebruikers toe. Raadpleeg de [documentatie voor machtigingen voor verwijzingen](https://docs.microsoft.com/partner-center/permissions-overview#manage-referrals) voor meer informatie over het beheer van verwijzingen.  

#### <a name="partners-with-co-sell-ready-offers"></a>Partners met kant-en-klare aanbiedingen voor de verkoop

- [Verkoop samen met andere partners](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities): vraag een andere partner aan bij ons krachtige partner ecosysteem om mee te verkopen en de toegang tot meer doel groepen van de klant te ontgrendelen.  

#### <a name="partners-with-a-transactable-offer-using-an-azure-incentive-eligible-solution-in-the-commercial-marketplace"></a>Partners met een transactable-aanbieding die in aanmerking komt voor een Azure-oplossing voor prikkel in de commerciële Marketplace

- [Automatische registratie van deals gebruiken](https://docs.microsoft.com/partner-center/register-deals): Bespaar tijd en zorg voor nauw keurigheid door het registreren van Transactable micro soft Commercial Marketplace Azure aanbiedingen met behulp van het selectie vakje ' deze deal of Win is al dan niet via Azure Marketplace of AppSource. ' Zolang uw transactie datum juist is, wordt de informatie voor de registratie van deals direct opgehaald uit de micro soft Commercial Marketplace.

### <a name="questions"></a>Vragen?

Als u hulp nodig hebt bij het gebruik van een van de nieuwe functies, raadpleegt u de [sectie referrals](https://docs.microsoft.com/partner-center/referrals) in de Knowledge Base of onze informatie over het ondersteunen van materialen die beschikbaar zijn in de [Galerie met webervaringen](https://aka.ms/CoSellExperience) (aanmelden is vereist).

U kunt [een ticket openen met het ondersteunings team van partners](https://partner.microsoft.com/support/?stage=1) voor ondersteuning.

________________
## <a name="deprecation-and-retirement-of-put-qualification-apis-for-the-education-customer-validation-process-by-february-25-2021-and-get-qualification-by-may-4-2021"></a><a name="1"></a> Het afnemen en buiten gebruik stellen van de kwalificatie-Api's voor het validatie proces van de opleidings klant op 25 februari 2021 en het verkrijgen van een kwalificatie van 4 mei 2021.

### <a name="categories"></a>Categorieën

- Datum: 4 februari 2021
- Functies

### <a name="impacted-audience"></a>Doel groep

Partners die academische, non-profit en GCC-aanbiedingen verkopen via het Cloud Solution Provider-programma met behulp van de Partner Center-API

### <a name="details"></a>Details

Deze aankondiging is een follow-up van de verbeteringen van het partner centrum, [uitgebracht in december](https://docs.microsoft.com/partner-center/announcements/2020-december#1). Als onderdeel van deze release zijn de nieuwe GET-en POST-kwalificaties-Api's geïmplementeerd. als gevolg hiervan zijn **de bestaande put-kwalificaties Api's Partner Center api's buiten gebruik gesteld op 25 februari 2021 en krijgen ze een kwalificatie van 4 mei 2021**. Op dat moment moet u overstappen op het gebruik van de nieuwe Api's van het POST Partner Center om opleidings aanbiedingen en de nieuwe kwalificaties-API te kunnen kopen om vooraf gekwalificeerde non-profit en GCC-aanbiedingen aan te schaffen.

### <a name="next-steps"></a>Volgende stappen

- **Bijwerken naar de nieuwe api's** voor een geslaagde en tijdige overgang
- **Bekijk de nieuwe partner centrum-API-wijzigingen en richt lijnen** in de resources voor de plannings gereedheids: de verbeteringen voor het [validatie proces van het klanten centrum](https://partner.microsoft.com/resources/collection/partner-center-edu-validation-enhancements#/)
- **Deel deze informatie met de juiste teams** binnen uw organisatie en met uw wederverkopers om hen te helpen deze wijzigingen voor te bereiden.

### <a name="questions"></a>Vragen?

Voor vragen met betrekking tot deze melding kunt u contact opnemen met [Partner Center-ondersteuning](https://partner.microsoft.com/dashboard/support/referrals/servicerequests?category=referrals).

### <a name="change-log"></a>Wijzigingenlogboek

- Februari: bijgewerkte tijd lijnen voor afschaffing van & plaatsen-kwalificaties
- Januari: herinnering voor toekomstige afschaffing van de GET-kwalificaties van & plaatsen
