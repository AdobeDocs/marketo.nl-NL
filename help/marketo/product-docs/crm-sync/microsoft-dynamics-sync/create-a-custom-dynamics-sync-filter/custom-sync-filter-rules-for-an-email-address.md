---
unique-page-id: 10095307
description: Aangepaste filterregels voor synchronisatie voor een e-mailadres - Marketo Docs - Productdocumentatie
title: Aangepaste filterregels voor synchronisatie voor een e-mailadres
exl-id: d1d51310-0c59-447c-818c-b25aa281c15c
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---

# Aangepaste filterregels voor synchronisatie voor een e-mailadres {#custom-sync-filter-rules-for-an-email-address}

Volg deze regels om te voorkomen dat records zonder e-mailadres worden gesynchroniseerd.

* Wanneer een lead OR wordt gemaakt wanneer het e-mailadresveld van de lead wordt bijgewerkt, controleert u of de lead een e-mailadres heeft en wijzigt u Synchroniseren in Mkto in **[!UICONTROL True]** als dit het geval is. Anders wijzigen in **[!UICONTROL False]**

* Wanneer een contactpersoon wordt aangemaakt OF wanneer het veld E-mailadres van de contactpersoon wordt bijgewerkt, controleert u of de contactpersoon een e-mailadres heeft en wijzigt u Synchroniseren naar Mkto in **[!UICONTROL True]** en wijzigt u Synchroniseren naar Mkto in **[!UICONTROL True]** in de accountrecord. Anders verandert u in **[!UICONTROL False]**

* Wanneer het gebied van de Naam van het Bedrijf van het contact (ouderlijkeId) wordt bijgewerkt, controleer of de Synchronisatie van het contact aan het gebied van Mkto waar is. Als dit het geval is, wijzigt u Synchroniseren naar Mkto voor de account in **[!UICONTROL True]** ook
* Wanneer het veld Potentiële klant (klant) of Contact (bovenliggende contactpersoon) van de opportuniteit wordt bijgewerkt, controleert u of het veld Synchroniseren met Mkto van de account waar is of of het veld Synchroniseren met Mkto van de contactpersoon waar is. Als dat het geval is, wijzigt u Synchroniseren naar Mkto bij de gelegenheid in **[!UICONTROL True]** .
