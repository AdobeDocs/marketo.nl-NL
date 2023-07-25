---
unique-page-id: 10095307
description: Aangepaste filterregels voor synchronisatie voor een e-mailadres - Marketo Docs - Productdocumentatie
title: Aangepaste filterregels voor synchronisatie voor een e-mailadres
exl-id: d1d51310-0c59-447c-818c-b25aa281c15c
feature: Microsoft Dynamics
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---

# Aangepaste filterregels voor synchronisatie voor een e-mailadres {#custom-sync-filter-rules-for-an-email-address}

Volg deze regels om te voorkomen dat records zonder e-mailadres worden gesynchroniseerd.

* Wanneer er een lead wordt gemaakt OF wanneer het e-mailadresveld van de lead wordt bijgewerkt, controleert u of de lead een e-mailadres heeft en wijzigt u Synchroniseren met Mkto in **Waar**. Anders wijzigen in **Onwaar**

* Wanneer een contactpersoon wordt aangemaakt OF wanneer het veld E-mailadres van de contactpersoon wordt bijgewerkt, controleert u of de contactpersoon een e-mailadres heeft en wijzigt u Synchroniseren naar Mkto in **Waar** en wijzig Sync in Mkto **Waar** in de accountrecord. Anders wijzigt u in **Onwaar**

* Wanneer het gebied van de Naam van het Bedrijf van het contact (ouderlijkeId) wordt bijgewerkt, controleer of de Synchronisatie van het contact aan het gebied van Mkto waar is. Als dit het geval is, wijzigt u Synchroniseren met Mkto op de account in **Waar** ook
* Wanneer het veld Potentiële klant (klant) of Contact (bovenliggende contactpersoon) van de opportuniteit wordt bijgewerkt, controleert u of het veld Synchroniseren met Mkto van de account waar is of of het veld Synchroniseren met Mkto van de contactpersoon waar is. Als dit het geval is, wijzigt u Sync in Mkto wanneer u de gelegenheid krijgt om **Waar** ook
