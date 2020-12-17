---
unique-page-id: 10095307
description: Aangepaste filterregels voor synchronisatie voor een e-mailadres - Marketo Docs - Productdocumentatie
title: Aangepaste filterregels voor synchronisatie voor een e-mailadres
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---


# Aangepaste filterregels voor synchronisatie voor een e-mailadres {#custom-sync-filter-rules-for-an-email-address}

Volg deze regels om te voorkomen dat records zonder e-mailadres worden gesynchroniseerd.

* Wanneer een lead OR wordt gemaakt wanneer het e-mailadresveld van de lead wordt bijgewerkt, controleert u of de lead een e-mailadres heeft en wijzigt u Synchronisatie in Mkto in **True** als dit het geval is. Anders wijzigen in **Onwaar**

* Wanneer een contact wordt gecreeerd OF wanneer het de e-mailadresgebied van het contact wordt bijgewerkt, controleer als het contact een e-mailadres heeft en als het, verandering Synchronisatie in Mkto in **True** en verander Synchronisatie in Mkto in **True** op het verslag van de Rekening. Anders verandert u in **Onwaar**

* Wanneer het gebied van de Naam van het Bedrijf van het contact (ouderlijkeId) wordt bijgewerkt, controleer of de Synchronisatie van het contact aan het gebied van Mkto waar is. Als dit het geval is, wijzigt u Sync in Mkto op de account in **True** ook
* Wanneer het veld Potentiële klant (klant) of Contact (bovenliggende contactpersoon) van de opportuniteit wordt bijgewerkt, controleert u of het veld Synchroniseren met Mkto van de account waar is of of het veld Synchroniseren met Mkto van de contactpersoon waar is. Als dit zo is, wijzigt u Sync in Mkto bij de gelegenheid in **True** ook

