---
unique-page-id: 11373011
description: Overschakelen naar e-maileditor 2.0 - Marketo Docs - Productdocumentatie
title: Overschakelen naar e-maileditor 2.0
exl-id: eb9ec8cc-d6e8-4839-a4d9-608d2f264cbb
source-git-commit: 64ff6900a761b9df796a9a7f417cca1ddc628cce
workflow-type: tm+mt
source-wordcount: '631'
ht-degree: 0%

---

# Overschakelen naar e-maileditor 2.0 {#transitioning-to-email-editor}

Vanaf de release van 19 juni zijn alle Marketo-abonnementen overgezet naar E-maileditor 2.0. [Meer informatie](https://nation.marketo.com/docs/DOC-7038) informatie over de e-maileditor 1.0 afgekeurd.

E-mails en e-mailsjablonen in uw abonnement moeten een versienummer hebben. De versie staat op de overzichtspagina van het element.

![](assets/five-5.png)

Standaard worden al uw bestaande e-mails en e-mailsjablonen gemarkeerd als v1.0 als deze zijn gemaakt vóór de release van lente 16 of na de release wanneer e-maileditor 2.0 is uitgeschakeld. Als E-maileditor 2.0 nu automatisch is ingeschakeld, wordt het volgende gedrag weergegeven:

* Wanneer u een nieuwe e-mail maakt, [E-mailsjabloonkiezer](email-template-picker-overview.md) wordt weergegeven en u kunt een e-mailsjabloon van versie 2.0 kiezen.
* Telkens wanneer u een e-mail maakt of bewerkt met e-maileditor 2.0, wordt de resulterende e-mail **altijd** worden gemarkeerd als v2.0 (zelfs als u een e-mailsjabloon van versie 1.0 hebt gebruikt).

Als uw abonnement v1.0-e-mails heeft voordat u naar de e-maileditor 2.0 gaat, wordt het volgende gedrag ervaren op basis van de huidige status van het element:

**Goedgekeurd** - Als u op Concept bewerken klikt, wordt een v2.0-concept van de goedgekeurde e-mail gemaakt. Als u vervolgens het concept v2.0 goedkeurt, wordt de goedgekeurde status van de e-mail v2.0 en kan niet worden teruggezet naar v1.0.\
**Concept** - Als u op Concept bewerken klikt, wordt dat concept automatisch gemarkeerd als v2.0. Op dit moment is het niet mogelijk om versie 1.0 te verwijderen en terug te keren omdat er geen goedgekeurde versie van het element is.
**Goedgekeurd met concept** - Als u op Concept bewerken klikt, wordt dat concept automatisch gemarkeerd als v2.0. Daarom is er ook geen manier om het concept terug te zetten naar versie 1.0.

Als uw abonnement e-mailsjablonen van versie 1.0 heeft voordat u naar de e-maileditor 2.0 gaat, functioneert het volgende:

**Goedgekeurd** - Als u op Concept bewerken klikt, wordt een v2.0-concept van de bestaande e-mailsjabloon gemaakt.
**Concept** - Als u op Concept bewerken klikt, wordt dat concept automatisch gemarkeerd als v2.0. Op dit moment is het niet mogelijk om versie 1.0 te verwijderen en terug te keren omdat er geen goedgekeurde versie van het element is.
**Goedgekeurd met concept** - Als u op Concept bewerken klikt, wordt dat concept automatisch gemarkeerd als v2.0. Daarom is er ook geen manier om het concept terug te zetten naar versie 1.0.

Als u een e-mailsjabloon goedkeurt die eerder v1.0 was (in een van de bovenstaande staten), ziet u het volgende gedrag:

Voor bestaande e-mailberichten van versie 1.0 die de (vorige v1.0) sjabloon gebruikten:\
**Goedgekeurde e-mail v1.0** - Voor deze e-mail wordt een concept van versie 2.0 gemaakt, waarbij nog steeds de nieuw goedgekeurde v2.0-sjabloon wordt gebruikt. Ook eventuele sjabloonwijzigingen worden ontvangen.\
**Concept v1.0-e-mail** - Het concept blijft v1.0 totdat u op Concept bewerken klikt. Hierna wordt de code automatisch gemarkeerd als v2.0 en worden eventuele sjabloonwijzigingen ontvangen.\
**Goedgekeurd met concept v1.0-e-mail** - Het concept blijft v1.0 totdat u op Concept bewerken klikt. Hierna wordt de code automatisch gemarkeerd als v2.0 en worden eventuele sjabloonwijzigingen ontvangen.

Voor bestaande e-mailberichten van v2.0 die de (vorige v1.0) sjabloon gebruikten:\
**Goedgekeurde e-mail v2.0** - Voor deze e-mail wordt een concept van versie 2.0 gemaakt, waarbij nog steeds de zojuist goedgekeurde sjabloon wordt gebruikt, en alle sjabloonwijzigingen worden ontvangen.\
**Concept v2.0-e-mail** - Het concept blijft ongewijzigd (v2.0) en ontvangt eventuele sjabloonwijzigingen.\
**Goedgekeurd met e-mail met conceptversie 2.0** - Het concept blijft ongewijzigd (v2.0) en ontvangt eventuele sjabloonwijzigingen.

>[!CAUTION]
>
>Als u ooit het v2.0- ontwerp van een v1.0 e-mailmalplaatje goedkeurt, zal het malplaatje v2.0 worden. Er is **geen weg** om terug te keren naar v1.0.

Notities

* Goedgekeurde e-mails zijn **nooit** gewijzigd.

* Goedgekeurde e-mailsjablonen zijn **nooit** gewijzigd.

* In enkele **zeldzaam** In dergelijke gevallen kan een e-mailbericht met versie 1.0 niet worden geopend in E-maileditor 2.0. Als dit gebeurt, verwijdert u het concept en neemt u contact op met de Technische Ondersteuning van Marketo.

>[!MORELIKETHIS]
>
>* [E-maileditor 2.0 - Overzicht](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md)
>* [E-mailsjabloonsyntaxis](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md)

