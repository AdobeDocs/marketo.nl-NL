---
unique-page-id: 45417322
description: Begrijp hoe lood en contactschrapping tussen Microsoft Dynamics en Marketo werken. Gebruik de markering Microsoft is verwijderd en de actie Person flow verwijderen als dat nodig is.
title: Een lead of contactpersoon verwijderen
exl-id: d561b424-6a2b-4abe-b9bd-81eb23f1a25b
feature: Microsoft Dynamics
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 0%

---

# Een lead of contactpersoon verwijderen {#deleting-a-lead-or-contact}

Er zijn een paar dingen om te weten wanneer het over het schrappen van lood/contacten in [!DNL Microsoft Dynamics] komt.

* Marketo verwijdert niet automatisch personen alleen omdat leads zijn verwijderd in [!DNL Dynamics] . De markering &#39;&#39;Microsoft is verwijderd&#39;&#39; in plaats daarvan is ingesteld op &#39;&#39;true&#39;&#39;. U kunt dit veld desgewenst uitschakelen om de record in Marketo te verwijderen.

* Handeling voor stroom &quot;Persoon verwijderen&quot;: hiermee verwijdert u alleen een persoon in Marketo (een optie om deze ook te verwijderen in Dynamiek is niet beschikbaar).

* Als een lead wordt verwijderd in Marketo (maar niet in [!DNL Dynamics] ) en vervolgens wordt bijgewerkt in [!DNL Dynamics] , wordt er een nieuwe persoon gemaakt in Marketo (hetzelfde e-mailadres, nieuwe persoon-id).

* Als een lead wordt verwijderd in [!DNL Dynamics] (maar niet in Marketo) en vervolgens wordt uitgevoerd via de flowactie &quot;Persoon synchroniseren met Microsoft&quot;, wordt een nieuwe lead gemaakt in [!DNL Dynamics] .
