---
title: Werken met Experience Manager Assets
description: Leer hoe u afbeeldingselementen van een verbonden AEM Assets-opslagplaats kunt gebruiken bij het ontwerpen van inhoud in Adobe Marketo Engage.
exl-id: c2172042-a35c-4179-bf81-6e96323bd4d4
source-git-commit: fddc2f24d9a66146f567c762305ab2825c2f29ae
workflow-type: tm+mt
source-wordcount: '767'
ht-degree: 0%

---

# Werken met Experience Manager-middelen {#work-with-experience-manager-assets}

Verbind uw _Adobe Experience Manager Assets as a Cloud Service_ rekening met uw instantie van Adobe Marketo Engage zodat kunt u hefboomwerking uw bewaarplaats van de Activa van AEM in Marketo Engage e-mail Designer.

>[!NOTE]
>
>Momenteel, slechts worden de beeldactiva van _Adobe Experience Manager Assets_ gesteund in Marketo Engage. Wijzigingen in de activa moeten worden aangebracht vanuit de centrale gegevensbank van Adobe Experience Manager Assets. [Meer informatie](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/assets/manage/manage-digital-assets){target="_blank"}

## Koppeling maken naar uw AEM Cloud Services {#link-to-your-aem-cloud-services}

Voordat u deze mogelijkheid kunt gebruiken, moet u eerst AEM Cloud Services koppelen aan Adobe Marketo Engage.

+++Link AEM Cloud Services en Marketo Engage

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. In Marketo Engage, ga naar het **Admin** gebied en selecteer **Adobe Experience Manager** in de linkernavigatieboom.

   ![ Uitgezochte Adobe Experience Manager in de Admin sectie ](assets/access-the-ai-assistant-content-accelerator-1.png){width="800" zoomable="yes"}

1. Klik **uitgeven** naast _de Diensten van de Wolk van Adobe Experience Manager_.

   ![ klik uitgeven ](assets/access-the-ai-assistant-content-accelerator-2.png){width="400" zoomable="yes"}

1. Selecteer een of meer opslagruimten.

   ![ selecteer een bewaarplaats ](assets/access-the-ai-assistant-content-accelerator-3.png){width="800" zoomable="yes"}

   >[!NOTE]
   >
   >Alleen opslagplaatsen die zijn gekoppeld in dezelfde IMS-org als uw Marketo Engage-abonnement worden vermeld.

1. U moet het certificaat van de a [ dienstcredentie ](https://experienceleague.adobe.com/nl/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials) toevoegen om de bewaarplaats te vormen. Klik op de knop **+ Certificaat toevoegen** .

   ![ voeg een certificaat toe ](assets/access-the-ai-assistant-content-accelerator-4.png){width="800" zoomable="yes"}

1. Sleep het certificaat (alleen JSON-bestand) en zet het neer of selecteer het op uw computer. Klik **toevoegen** wanneer gedaan.

   ![ plaats van het certificaat op uw machine ](assets/access-the-ai-assistant-content-accelerator-5.png){width="600" zoomable="yes"}

1. De geconfigureerde opslagplaats wordt hieronder samen met de status en de vervaldatum weergegeven. Klik op de knop voor weglatingsteken (**...** ) om het certificaat weer te geven. Anders ben je klaar.

   ![ het certificaat is toegevoegd ](assets/access-the-ai-assistant-content-accelerator-6.png){width="700" zoomable="yes"}

Alle afbeeldingen uit de bibliotheek voor digitaal middelenbeheer in die opslagplaats zijn nu toegankelijk via de Marketo Engage Email Designer.

+++

## Werken met AEM-middelen {#working-with-aem-assets}

Wanneer u deze digitale activa gebruikt, verspreiden de recentste veranderingen in _Assets as a Cloud Service_ automatisch aan levende e-mailcampagnes door verbonden verwijzingen. Als de beelden in _Adobe Experience Manager Assets as a Cloud Service_ worden geschrapt, verschijnen de beelden met een gebroken verwijzing in uw e-mails. Wanneer elementen die momenteel in Marketo Engage worden gebruikt, worden gewijzigd of verwijderd, krijgen de auteurs van de e-mail een melding over de wijzigingen in de afbeelding. Alle wijzigingen in de activa moeten plaatsvinden in de centrale gegevensbank van Adobe Experience Manager Assets.

### AEM Assets gebruiken als afbeeldingsbron {#use-aem-assets-as-the-image-source}

Als uw omgeving een of meer verbindingen met de opslagplaats voor middelen heeft, kunt u AEM Assets aanwijzen als bron voor elementen wanneer u gegevens voor een e-mail, e-mailsjabloon of visueel fragment maakt of bekijkt.

* Wanneer u nieuwe inhoud maakt, kiest u `AEM Assets` als het **[!UICONTROL Image Source]** -item in het dialoogvenster.

![ Uitgezochte AEM Assets als beeldbron in creeer dialoog ](assets/work-with-experience-manager-assets-1.png){width="400" zoomable="yes"}

* Wanneer u een bestaande inhoudsbron opent, kiest u `AEM Assets` in de _[!UICONTROL Body]_-sectie aan de rechterkant.

![ Uitgezochte AEM Assets als beeldbron in de eigenschappen ](assets/work-with-experience-manager-assets-2.png){width="700" zoomable="yes"}

### Elementen openen voor ontwerpen {#access-assets-for-authoring}

>[!IMPORTANT]
>
>Een beheerder moet gebruikers die toegang tot elementen nodig hebben, toevoegen aan de profielen Assets Consumer Users en/of Assets Users-producten. [Meer informatie](https://experienceleague.adobe.com/nl/docs/experience-manager-cloud-service/content/security/ims-support#managing-products-and-user-access-in-admin-console)

In de visuele inhoudsredacteur, klik het _selecteur van Activa van Experience Manager_ pictogram in linkerzijbalk. Hiermee wijzigt u het deelvenster Gereedschappen in een lijst met beschikbare middelen in de geselecteerde opslagplaats.

![ klik het de selecteurspictogram van Assets om tot de beeldactiva ](assets/work-with-experience-manager-assets-3.png){width="700" zoomable="yes"} toegang te hebben

Als u meer dan één aangesloten AEM-opslagplaats hebt, klikt u op de knop **[!UICONTROL Manage as]** om de opslagplaats te kiezen die u wilt gebruiken.

![ kies een bewaarplaats van AEM Assets om tot de beeldactiva ](assets/work-with-experience-manager-assets-4.png){width="700" zoomable="yes"} toegang te hebben

Kies de gewenste opslagplaats.

![ kies een bewaarplaats van AEM Assets om tot de beeldactiva ](assets/work-with-experience-manager-assets-5.png){width="500" zoomable="yes"} toegang te hebben

Er zijn meerdere methoden om een afbeeldingselement toe te voegen aan het visuele canvas:

* Sleep een afbeeldingsminiatuur vanuit de linkernavigatie en zet deze neer.

![ kies een bewaarplaats van AEM Assets om tot de beeldactiva ](assets/work-with-experience-manager-assets-6.png){width="700" zoomable="yes"} toegang te hebben

* Voeg een afbeeldingscomponent toe aan het canvas en klik op **[!UICONTROL Browse]** om het dialoogvenster _[!UICONTROL Select Assets]_&#x200B;te openen.

  In het dialoogvenster kunt u een afbeelding kiezen in de geselecteerde opslagplaats.

  Er zijn meerdere gereedschappen beschikbaar om u te helpen de middelen te vinden die u nodig hebt.

![ hulpmiddel van het Gebruik in de Uitgezochte dialoog van Assets om een beeldactiva ](assets/work-with-experience-manager-assets-7.png){width="700" zoomable="yes"} te vinden en te selecteren

* Wijzig de **[!UICONTROL Repository]** rechtsboven.

* Klik op **[!UICONTROL Manage assets]** rechtsboven om de Assets-opslagplaats te openen in een ander browsertabblad en AEM Assets-beheergereedschappen te gebruiken.

* Klik het _type van Mening_ selecteur bij het hoogste recht om de vertoning in **[!UICONTROL List View]**, **[!UICONTROL Grid View]**, **[!UICONTROL Gallery View]**, of **[!UICONTROL Waterfall View]** te veranderen.

* Klik het _pictogram van de Sorteervolgorde_ om de sorteervolgorde tussen het stijgen en het dalen te veranderen.

* Klik op de menupijl **[!UICONTROL Sort by]** om de sorteercriteria te wijzigen in **[!UICONTROL Name]** , **[!UICONTROL Size]** of **[!UICONTROL Modified]** .

* Klik het _pictogram van de Filter_ op de bovenkant verlaten om de getoonde punten volgens uw criteria te filtreren.

* Typ tekst in het veld Zoeken om de weergegeven items te filteren op een overeenkomst met de elementnaam.

![ Gebruik de filters en het onderzoeksgebied om van de activa ](assets/work-with-experience-manager-assets-8.png){width="700" zoomable="yes"} de plaats te bepalen
