---
unique-page-id: 11373011
description: Overschakelen naar e-maileditor 2.0 - Marketo Docs - Productdocumentatie
title: Overschakelen naar e-maileditor 2.0
exl-id: eb9ec8cc-d6e8-4839-a4d9-608d2f264cbb
hide: true
hidefromtoc: true
feature: Email Editor
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '618'
ht-degree: 0%

---

# Overschakelen naar [!DNL Email Editor 2.0] {#transitioning-to-email-editor}

Vanaf de release van 19 juni zijn alle Marketo-abonnementen overgezet naar [!DNL Email Editor 2.0] . [&#x200B; leer meer &#x200B;](https://nation.marketo.com/docs/DOC-7038) over de [!DNL Email Editor 1.0] veroudering.

E-mails en e-mailsjablonen in uw abonnement moeten een versienummer hebben. De versie staat op de overzichtspagina van het element.

![](assets/five-5.png)

Standaard worden al uw bestaande e-mails en e-mailsjablonen gemarkeerd als v1.0 als ze zijn gemaakt vóór de release van lente 16 of na de release wanneer e-maileditor 2.0 is uitgeschakeld. Als E-maileditor 2.0 nu automatisch is ingeschakeld, wordt het volgende gedrag weergegeven:

* Wanneer u een nieuwe e-mail creeert, zal de [&#x200B; Plukker van het E-mailMalplaatje &#x200B;](email-template-picker-overview.md) tonen en u zult een v2.0 e-mailmalplaatje kunnen kiezen.
* Wanneer u creeert of een e-mail met [!DNL Email Editor 2.0] uitgeeft, zal de resulterende e-mail **altijd** als v2.0 (zelfs als u een v1.0 e-mailmalplaatje gebruikte) worden gemerkt.

Als uw abonnement v1.0-e-mails heeft voordat u naar [!DNL Email Editor 2.0] gaat, wordt het volgende gedrag ervaren op basis van de huidige status van het element:

**Goedgekeurd** - het klikken &quot;geeft Ontwerp&quot;uit zal tot een v2.0- ontwerp van goedgekeurde e-mail leiden. Als u vervolgens het concept v2.0 goedkeurt, wordt de goedgekeurde status van de e-mail v2.0 en kan niet worden teruggezet naar v1.0.
**Ontwerp** - het klikken &quot;geeft Ontwerp&quot;uit zal automatisch dat ontwerp als v2.0 merken. Op dit moment is het niet mogelijk om versie 1.0 te verwijderen en terug te keren omdat er geen goedgekeurde versie van het element is.
**goedgekeurd met Ontwerp** - het klikken &quot;geeft Ontwerp&quot;zal dan automatisch dat ontwerp als v2.0 merken. Daarom is er ook geen manier om het concept terug te zetten naar versie 1.0.

Als uw abonnement e-mailsjablonen van versie 1.0 heeft voordat u naar [!DNL Email Editor 2.0] gaat, kunt u het volgende doen:

**Goedgekeurd** - het klikken &quot;geeft Ontwerp&quot;uit zal tot een v2.0- ontwerp van het bestaande e-mailmalplaatje leiden.
**Ontwerp** - het klikken &quot;geeft Ontwerp&quot;uit zal automatisch dat ontwerp als v2.0 merken. Op dit moment is het niet mogelijk om versie 1.0 te verwijderen en terug te keren omdat er geen goedgekeurde versie van het element is.
**goedgekeurd met Ontwerp** - het klikken &quot;geeft Ontwerp&quot;uit zal automatisch dat ontwerp als v2.0 merken. Daarom is er ook geen manier om het concept terug te zetten naar versie 1.0.

Als u een e-mailsjabloon goedkeurt die eerder v1.0 was (in een van de bovenstaande staten), ziet u het volgende gedrag:

Voor bestaande e-mailberichten van versie 1.0 die de (vorige v1.0) sjabloon gebruikten:
**Goedgekeurde v1.0 e-mail** - Het ontwerp van A v2.0 zal voor dit e-mail worden gecreeerd, nog gebruikend het onlangs goedgekeurde v2.0 malplaatje. De toepassing ontvangt ook alle sjabloonwijzigingen.
**Ontwerp v1.0 e-mail** - het ontwerp zal v1.0 blijven tot u &quot;Concept uitgeeft.&quot;klikt Hierna wordt de code automatisch gemarkeerd als v2.0 en worden eventuele sjabloonwijzigingen ontvangen.
**goedgekeurd met Ontwerp v1.0 e-mail** - het ontwerp zal v1.0 blijven tot u &quot;Concept uitgeeft.&quot;klikt Hierna wordt de code automatisch gemarkeerd als v2.0 en worden eventuele sjabloonwijzigingen ontvangen.

Voor bestaande e-mailberichten van v2.0 die de (vorige v1.0) sjabloon gebruikten:
**Goedgekeurde v2.0 e-mail** - het ontwerp van A v2.0 zal voor dit e-mail worden gecreeerd, nog &quot;gebruikend&quot;het onlangs goedgekeurde malplaatje, en zal om het even welke malplaatjeveranderingen ontvangen.
**Ontwerp v2.0 e-mail** - het ontwerp zal ongewijzigd blijven (v2.0) en om het even welke malplaatjeveranderingen ontvangen.
**Goedgekeurd met Ontwerp v2.0 e-mail** - het ontwerp zal ongewijzigd blijven (v2.0) en om het even welke malplaatjeveranderingen ontvangen.

>[!CAUTION]
>
>Als u ooit het v2.0- ontwerp van een v1.0 e-mailmalplaatje goedkeurt, zal het malplaatje v2.0 worden. Er is **geen manier** om het terug naar v1.0 terug te keren.

Notities

* Goedgekeurde e-mails worden **nooit** veranderd.

* Goedgekeurde e-mailmalplaatjes worden **nooit** veranderd.

* In enkele **zeldzame** gevallen, kan a v1.0 E-mail niet in [!DNL Email Editor 2.0] worden geopend. Als dit gebeurt, verwijdert u het concept en neemt u contact op met de Marketo Support.

>[!MORELIKETHIS]
>
>* [[!DNL Email Editor 2.0] Overzicht](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md)
>* [&#x200B; Syntaxis van het Malplaatje E-mail &#x200B;](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md)
