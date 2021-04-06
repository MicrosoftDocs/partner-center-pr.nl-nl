---
title: Algemene maandelijkse facturerings scenario's
ms.topic: article
ms.date: 05/13/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: "Algemene scenario's in Partner Center wanneer u maandelijkse facturering gebruikt: omvat het toevoegen van nieuwe abonnementen, het wijzigen van de licentie hoeveelheid en het uitstellen van abonnementen."
author: sodeb
ms.author: sodeb
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 4fe5c33fe549604f25500dd333d187e6b70ad73e
ms.sourcegitcommit: 3d7d5064c5e021079ed7e6f93f03869cbf425a32
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/06/2021
ms.locfileid: "106502511"
---
# <a name="sample-monthly-billing-scenarios-for-new-subscriptions-changing-license-amounts-or-suspensions"></a>Voor beelden van maandelijkse facturerings scenario's voor nieuwe abonnementen, wijziging van licentie bedragen of onderbrekingen

**Juiste rollen**

- Beheer agent
- Factureringsbeheerder
- Helpdesk medewerker
- Verkoop agent

Deze [veelvoorkomende facturerings scenario's](common-billing-scenarios.md) zijn van toepassing als u maandelijkse facturering gebruikt in het partner centrum.

## <a name="new-monthly-subscription"></a>Nieuw maandelijks abonnement

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u maandelijkse facturering. Het afstemmings bestand op basis van de licentie van 15 januari bevat de volgende facturerings regels:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|1/13/2018         |2/12/2018    |Cyclus kosten   |4,00       |1        |4,00 |

Het afstemmings bestand op basis van de licentie voor 15 februari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|2/13/2018         |3/12/2018    |Cyclus kosten   |4,00       |1        |4,00 |

## <a name="change-license-quantity"></a>Licentieaantal wijzigen

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u maandelijkse facturering. Het afstemmings bestand op basis van de licentie van 15 januari bevat de volgende facturerings regels:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|1/13/2018         |2/12/2018    |Cyclus kosten   |4,00       |1        |4,00    |

Op 1 februari verhoogt u het aantal licenties van een tot twee. Het afstemmings bestand op basis van de licentie voor 15 februari bevat de volgende facturerings regels:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
| 1/13/2018        |2/12/2018    |Cyclus exemplaar prorente   |-4,00       |1        |-4,00   |
|1/13/2018         |1/31/2018    | Cyclus exemplaar prorente   |2.45       |1        |2.45    |
|1-2-2018         |2/12/2018    | Cyclus exemplaar prorente   |1,55       |2        |3.10    |
|2/13/2018         |3/12/2018    | Cyclus exemplaar prorente   |4,00       |2        |8,00    |

De maandelijkse prijs is 4,00 en er zijn 31 dagen in de service periode 1/13/2018 – 2/12/2018. Dit is gelijk aan een dagelijkse prijs van 0,129 (4/31).

Er zijn 19 dagen in de verhoudings periode 1/13/2018 – 1/31/2018.

Prijs van rato eenheid = 2,451 = 19 x 0,129

Er zijn 12 dagen in de verhoudings periode 2/1/2018 – 2/12/2018.

Prijs van rato eenheid = 1,54 = 12 x 0,129

## <a name="suspend-before-30-days"></a>Uitstellen vóór 30 dagen

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u maandelijkse facturering. Het afstemmings bestand op basis van de licentie van 15 januari bevat de volgende facturerings regels:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|1/13/2018         |2/12/2018    |Cyclus kosten   |4,00       |1        |4,00    |

Op 1 februari schorst u een abonnement. Het afstemmings bestand op basis van de licentie voor 15 februari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|2/12/2018|Annulerings kosten|-4,00|1|-4,00

## <a name="suspend-after-30-days"></a>Uitstellen na 30 dagen

Uw factuur datum is de 15e van elke maand. Op 13 januari koopt u een nieuw abonnement met één licentie voor $4/maand en selecteert u maandelijkse facturering. Het afstemmings bestand op basis van de licentie van 15 januari bevat de volgende facturerings regels:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|2/12/2018|Cyclus kosten|4,00|1|4,00

Het afstemmings bestand op basis van de licentie voor 15 februari bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
2/13/2018|3/12/2018|Cyclus kosten|4,00|1|4,00

Op 1 maart wordt het abonnement onderbroken. Het afstemmings bestand van 15 maart op basis van licentie bevat de volgende facturerings regel:

|Begin datum van kosten |Eind datum van de lading |Kosten type |Prijs per eenheid |Aantal |Bedrag |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
3/1/2018|3/12/2018|Annulerings kosten|-1,72|1|-1,72

De maandelijkse prijs is 4,00 en er zijn 28 dagen in de service periode 2/13/2018 – 3/12/2018. Dit is gelijk aan een dagelijkse prijs van 0,143 (4/28).

Eenheids prijs = dagen in service periode x dagelijkse prijs x aantal licenties.

Er zijn 12 dagen in de annulerings periode 3/1/2018 – 3/12/2018.

Daarom is de eenheids prijs =-1,716 (12 x 0,143 x (-1)).

## <a name="next-steps"></a>Volgende stappen

- [Facturerings scenario's voor eenmalige en geselecteerde terugkerende aankopen](common-billing-scenarios-onetime-recurring.md)