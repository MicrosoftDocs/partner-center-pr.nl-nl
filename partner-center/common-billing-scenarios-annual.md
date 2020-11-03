---
title: Jaarlijkse facturering-algemene scenario's
ms.topic: article
ms.date: 05/05/2020
description: 'Facturerings centrum per jaar: wanneer u nieuwe abonnementen toevoegt, licenties toevoegt vóór de factuur datum, de licentie hoeveelheid wijzigt of de abonnementen uitstellen/opnieuw inschakelt.'
author: sodeb
ms.author: sodeb
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 086a7d359e1b903684af4ecddac37eda584e55f8
ms.sourcegitcommit: 7153f0b8c67efd35f58695ca2a7e00e70da1c5e9
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 07/17/2020
ms.locfileid: "92527509"
---
# <a name="common-annual-billing-scenarios-in-partner-center"></a>Algemene scenario's voor jaarlijkse facturering in het partner centrum

**Juiste rollen**

- Beheer agent
- Factureringsbeheerder
- Helpdesk medewerker
- Verkoop agent

Deze voorbeeld [scenario's](common-billing-scenarios.md) zijn van toepassing op het gebruik van jaarlijkse facturering in Partner Center.

## <a name="new-annual-subscription"></a>Nieuw jaar abonnement

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u jaarlijkse facturering. Het op de licentie gebaseerde afstemmings bestand van 15 januari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Tarief vergoedingen bij aankoop|48,00|1|48,00

## <a name="add-license-after-subscription-anniversary-date-but-before-billing-date"></a>Licentie toevoegen na datum van abonnement, maar vóór factuur datum

U koopt een nieuw abonnement op 2/11/17 met één licentie voor $211.20/jaar. De jubileum van uw abonnement wordt ingesteld als de elfde van elke maand. Het micro soft-facturerings systeem maakt de volgende facturerings regels:

- $211,20 kosten voor periode 2/11/17 – 2/10/18.

Op 2/12/17 u een tweede licentie aanschaffen. Uw factuur datum is 2/14/17. Er wordt een factuur-en afstemmings bestand gegenereerd. Het afstemmings bestand bevat de volgende facturerings regels:

|Begin datum van kosten  |Eind datum van de lading  |Kosten type  |Prijs per eenheid |Aantal | Aantal |
|      :---:   |      :---:   |      :---:   |      :---:   |:---:   |:---:   |
|2/11/2017 |2/10/2018 |Tarief vergoedingen bij aankoop |211,20 |1 | 211,20 |

Op de jubileum van uw abonnement, 3/11/17, maakt het micro soft-facturerings systeem de volgende facturerings regels voor de licentie verhoging op 2/12/17:

- $211,20 tegoed voor periode 2/11/17 – 2/10/18.
- $0,58 gratis prijs per licentie voor 1 licentie voor periode 2/11/17 – 2/11/17.
- $15,62 per licentie voor twee licenties, voor de periode 2/12/17 – 3/10/2017.
- $195,00 per licentie voor twee licenties, voor de periode 3/11/2017 – 2/10/2018.

Op 2/11/17 koopt u een abonnement. Op 2/12/17 kunt u een licentie toevoegen. Uw factuur datum is 2/14/17. Op 2/11/18 uw abonnement wordt vernieuwd.

De volgende factuur datum is 3/14/17 en er wordt een factuur & afstemmings bestand gegenereerd. Het afstemmings bestand bevat de volgende facturerings regels:

|Begin datum van kosten  |Eind datum van de lading  |Kosten type  |Prijs per eenheid |Aantal | Aantal |
|      :---:   |      :---:   |      :---:   |      :---:   |:---:   |:---:   |
|2/11/2017 |2/10/2018 |Cyclus exemplaar prorente |-211,20 |1 |-211,20 |
|2/11/2017 |2/11/2017 |Cyclus exemplaar prorente |0,58 |1 |0,58 |
|2/12/2017 |3/10/2017 |Cyclus exemplaar prorente |15,62 |2 |31,25 |
|3/11/2017 |2/10/2018 |Cyclus exemplaar prorente |195,00 |2 |390,00 |

Op 2/11/18 wordt het abonnement vernieuwd voor een andere periode van 12 maanden.

## <a name="change-license-quantity"></a>Licentieaantal wijzigen

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u jaarlijkse facturering. Het op de licentie gebaseerde afstemmings bestand van 15 januari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Tarief vergoedingen bij aankoop|48,00|1|48,00

Op 1 februari verhoogt u het aantal licenties van een tot twee. Het op de licentie gebaseerde afstemmings bestand van 15 februari bevat de volgende facturerings regels:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Cyclus exemplaar prorente|-48,00|1|-48,00
1/13/2018|1/31/2018|Cyclus exemplaar prorente|2,47|1|2,47
1-2-2018|1/12/2019|Cyclus exemplaar prorente|44,98|2|89,96

De jaarlijkse prijs is 48,00, die gelijk is aan de dagelijkse prijs van 0,13 (48.00/365).

Eenheids prijs = dagen in service periode x dagelijkse prijs x aantal licenties.

Er zijn 19 dagen in de service periode 1/13/2018 – 1/31/2018.

Daarom is eenheids prijs = 2,47 (19x 0.13 x1)

Er zijn 346 dagen in de service periode 2/1/2018 – 1/12/2019.

Daarom is eenheids prijs = 44,98 (346x 0.13 x2)

## <a name="suspend-before-30-days"></a>Uitstellen vóór 30 dagen

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u jaarlijkse facturering. Het op de licentie gebaseerde afstemmings bestand van 15 januari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Tarief vergoedingen bij aankoop|48,00|1|48,00

Op 1 februari wordt uw abonnement opgeschort. Het op de licentie gebaseerde afstemmings bestand van 15 februari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Annulerings kosten|-48,00|1|-48,00

## <a name="suspend-after-30-days"></a>Uitstellen na 30 dagen

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u jaarlijkse facturering. Het op de licentie gebaseerde afstemmings bestand van 15 januari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Tarief vergoedingen bij aankoop|48,00|1|48,00

Het op een licentie gebaseerd afstemmings bestand van de 15 februari bevat geen facturerings regels voor dit abonnement.
Op 1 maart wordt uw abonnement opgeschort. Het op 15 maart op licentie gebaseerde afstemmings bestand bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
3/1/2018|1/12/2019|Annulerings kosten|-41,34|1|-41,34

De jaarlijkse prijs is 48,00, die gelijk is aan de dagelijkse prijs van 0,13 (48.00/365).

Eenheids prijs = dagen in service periode x dagelijkse prijs x aantal licenties.

Er zijn 318 dagen in de service periode 3/1/2018 – 1/12/2019.

Daarom is eenheids prijs = 41,34 (318x 0.13 x1). Omdat dit een tegoed is, is de eenheids prijs-41,34.

## <a name="suspend-and-reactivate"></a>Onderbreken en opnieuw activeren

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u jaarlijkse facturering. Het op de licentie gebaseerde afstemmings bestand van 15 januari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Tarief vergoedingen bij aankoop|48,00|1|48,00

Op 1 februari wordt uw abonnement opgeschort. Het op de licentie gebaseerde afstemmings bestand van 15 februari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|Annulerings kosten|-48,00|1|-48,00

Activeer uw abonnement op 1 maart. Het op 15 maart op licentie gebaseerde afstemmings bestand bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Aantal |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
3/1/2018|1/12/2019|Tarief vergoedingen bij aankoop|41,34|1|41,34

De jaarlijkse prijs is 48,00, die gelijk is aan de dagelijkse prijs van 0,13 (48.00/365).

Eenheids prijs = dagen in service periode x dagelijkse prijs x aantal licenties.

Er zijn 318 dagen in de service periode 3/1/2018 – 1/12/2019.

Daarom is eenheids prijs = 41,34 (318x 0.13 x1).
