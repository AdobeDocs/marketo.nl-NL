---
title: Werken met Experience Manager Assets
description: Leer hoe u afbeeldingselementen van een verbonden AEM Assets-opslagplaats kunt gebruiken bij het ontwerpen van inhoud in Adobe Marketo Engage.
hide: true
hidefromtoc: true
source-git-commit: c6132bf5b393df38700ad9dd6f0c6414860e8bb6
workflow-type: tm+mt
source-wordcount: '550'
ht-degree: 0%

---

# Werken met Experience Manager-elementen

Wanneer Adobe Experience Manager Assets as a Cloud Service is geïntegreerd met Adobe Marketo Engage, kunt u eenvoudig digitale middelen vinden en openen voor gebruik in uw marketinginhoud. Terwijl u de inhoud ontwerpt, zijn de elementen toegankelijk via het _[!UICONTROL Assets]_-item in de linkernavigatie en wanneer u e-mailinhoud ontwerpt voor een accountreis. U kunt ook rechtstreeks vanuit Adobe Journey Optimizer B2B edition middelen uploaden naar de verbonden AEM Assets as a Cloud Service-opslagplaats.

>[!NOTE]
>
>Momenteel worden alleen afbeeldingselementen van Adobe Experience Manager Assets ondersteund in Adobe Journey Optimizer B2B edition. Wijzigingen in de activa moeten worden aangebracht vanuit de centrale gegevensbank van Adobe Experience Manager Assets. [Meer informatie](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/manage/manage-digital-assets)

Als u deze digitale elementen gebruikt, worden de meest recente wijzigingen in Assets as a Cloud Service automatisch doorgegeven aan live e-mailcampagnes via gekoppelde verwijzingen. Als afbeeldingen worden verwijderd in Adobe Experience Manager Assets as a Cloud Service, worden de afbeeldingen weergegeven met een verbroken verwijzing in de e-mails. Wanneer de activa die momenteel binnen rekeningreizen worden gebruikt worden gewijzigd of geschrapt, worden de reisauteurs op de hoogte gebracht van de beeldveranderingen en de lijst van reizen die het beeld gebruiken. Alle wijzigingen in de activa moeten plaatsvinden in de centrale gegevensbank van Adobe Experience Manager Assets.

## AEM Assets gebruiken als afbeeldingsbron

Als uw omgeving een of meer verbindingen met Assets-opslagruimten heeft, kunt u AEM Assets aanwijzen als bron voor elementen wanneer u gegevens voor een e-mail, e-mailsjabloon of visueel fragment maakt of bekijkt.

* Wanneer u nieuwe inhoud maakt, kiest u `AEM Assets` als het **[!UICONTROL Image Source]** -item in het dialoogvenster.

SCREENSHOT

* Wanneer u een bestaande inhoudsbron opent, kiest u `AEM Assets` in het _[!UICONTROL Body]_-deelvenster aan de rechterkant.

SCREENSHOT

## Elementen openen voor ontwerpen

>[!IMPORTANT]
>
>Een beheerder moet gebruikers die toegang tot Assets nodig hebben, toevoegen aan de profielen Assets Consumer Users of/and Assets Users Product. [Meer informatie](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/security/ims-support#managing-products-and-user-access-in-admin-console)

In de visuele inhoudsredacteur, klik het _selecteur van Activa_ pictogram in linkerzijbalk. Hiermee wijzigt u het deelvenster Gereedschappen in een lijst met beschikbare middelen in de geselecteerde opslagplaats.

SCREENSHOT

Als u meer dan één aangesloten AEM opslagplaatsen hebt, klikt u op de menupijl voor **[!UICONTROL Repository]** om de opslagplaats te kiezen die u wilt gebruiken.

SCREENSHOT

Er zijn meerdere methoden om een afbeeldingselement toe te voegen aan het visuele canvas:

* Sleep een afbeeldingsminiatuur vanuit de linkernavigatie en zet deze neer.

SCREENSHOT

* Voeg een afbeeldingscomponent toe aan het canvas en klik op **[!UICONTROL Browse]** om het dialoogvenster _[!UICONTROL Select Assets]_te openen.

  In het dialoogvenster kunt u een afbeelding kiezen in de geselecteerde opslagplaats.

  Er zijn meerdere gereedschappen beschikbaar om u te helpen de middelen te vinden die u nodig hebt.

SCREENSHOT

* Wijzig de **[!UICONTROL Repository]** rechtsboven.

* Klik op **[!UICONTROL Manage assets]** rechtsboven om de Assets-opslagplaats te openen in een ander browsertabblad en AEM Assets-beheergereedschappen te gebruiken.

* Klik het _type van Mening_ selecteur bij het hoogste recht om de vertoning in **[!UICONTROL List View]**, **[!UICONTROL Grid View]**, **[!UICONTROL Gallery View]**, of **[!UICONTROL Waterfall View]** te veranderen.

* Klik het _pictogram van de Sorteervolgorde_ om de sorteervolgorde tussen het stijgen en het dalen te veranderen.

* Klik op de menupijl **[!UICONTROL Sort by]** om de sorteercriteria te wijzigen in **[!UICONTROL Name]** , **[!UICONTROL Size]** of **[!UICONTROL Modified]** .

* Klik het _pictogram van de Filter_ op de bovenkant verlaten om de getoonde punten volgens uw criteria te filtreren.

* Typ tekst in het veld Zoeken om de weergegeven items te filteren op een overeenkomst met de elementnaam.

SCREENSHOT
