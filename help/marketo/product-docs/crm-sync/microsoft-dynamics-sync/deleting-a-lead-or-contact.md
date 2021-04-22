---
unique-page-id: 45417322
description: Een lead of contactpersoon verwijderen - Marketo Docs - Productdocumentatie
title: Een lead of contactpersoon verwijderen
exl-id: d561b424-6a2b-4abe-b9bd-81eb23f1a25b
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---

# Een lead of contactpersoon verwijderen {#deleting-a-lead-or-contact}

Er zijn een paar dingen om te weten wanneer het over het schrappen van lood/contacten in de Dynamiek van Microsoft komt.

* Marketo verwijdert niet automatisch mensen alleen omdat leads zijn verwijderd in Dynamics. De markering &#39;&#39;Microsoft wordt verwijderd&#39;&#39; van een veld is ingesteld op &#39;&#39;true&#39;&#39;. U kunt dit veld desgewenst uitschakelen om de record in Marketo te verwijderen.

* Handeling in de flow &quot;Persoon verwijderen&quot;: Hiermee verwijdert u alleen een persoon in Marketo (een optie om deze ook te verwijderen in Dynamics is niet beschikbaar).

* Als een lood in Marketo (maar niet in Dynamiek) wordt geschrapt en in Dynamiek daarna wordt bijgewerkt, zou het tot een nieuwe persoon in Marketo (zelfde e-mailadres, nieuwe persoonsidentiteitskaart) leiden.

* Als een lood in Dynamiek (maar niet in Marketo) wordt geschrapt en dan door de &quot;Persoon van de Synchronisatie aan de stroomactie van Microsoft&quot;loopt, zou het tot een nieuwe lood in Dynamiek leiden.
