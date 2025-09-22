---
description: Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce - Marketo Docs - de Documentatie van het Product
title: Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce
exl-id: b35acdc2-8ec7-4dec-92b8-58ba7a1ad858
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 2%

---

# Redenen van de Vraag van het logboek en de Resultaten van de Vraag van de Vraag [!DNL Salesforce] {#log-call-reasons-and-call-outcomes-to-salesforce}

Als u vraagresultaten en vraagredenen aan [!DNL Salesforce] voor het melden of zicht doeleinden wilt registreren, kunt u een gebied van de douaneactiviteit voor elk tot stand brengen. Voor elk veld moet een specifieke API-naam worden gebruikt (in [!DNL Salesforce] wordt &#39;&#39;veldnaam&#39;&#39; genoemd).

* De Naam van het Gebied van Resultaten van de vraag: mktosales_call_result
* De Naam van het Gebied van de Redenen van de vraag: mktosales_call_reason

Als u deze velden wilt gebruiken, moet u het veld eerst maken als een veld voor aangepaste activiteit. Als u deze zichtbaar wilt maken voor gebruikers, moet u deze toevoegen aan de pagina-indeling van het taakobject.

## [!DNL Salesforce] Klassiek {#salesforce-classic}

### Aangepast activiteitsveld maken in [!DNL Salesforce] Klassiek  {#create-custom-activity-field-in-salesforce-classic}

1. Klik in [!DNL Salesforce] op **[!UICONTROL Setup]** .

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-1.png)

1. Typ &quot;Activiteiten&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-2.png)

1. Klik op **[!UICONTROL Activity Custom Fields]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-3.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-4.png)

1. Selecteer het gegevenstype &quot;[!UICONTROL Text]&quot; en klik op **[!UICONTROL Next]** .

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-5.png)

1. Geef het aangepaste veld de veldnaam zoals hierboven gedefinieerd. De veldlengte mag niet langer zijn dan 255 tekens. Het Etiket van het gebied zal het gebied zichtbaar aan uw verkoopteam zijn en kan worden aangepast om aan de behoeften van uw team te voldoen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-6.png)

1. De overige instellingen zijn optioneel. Klik op **[!UICONTROL Next]** nadat u de configuratie hebt voltooid.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-7.png)

1. Selecteer de gewenste beveiligingsinstellingen op veldniveau voor dit veld en klik op **[!UICONTROL Next]** (de onderstaande afbeelding is slechts een voorbeeld).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-8.png)

   >[!NOTE]
   >
   >Zorg ervoor dat het aangepaste veld zichtbaar is voor het profiel dat uw [!DNL Sales Connect] -gebruikers gebruiken, en ook voor alle andere elementen die u wilt zien.

1. Selecteer welke paginalay-outs u het gebied aan wilt toevoegen en **[!UICONTROL Save]** klikken (facultatief, kunt u **[!UICONTROL Save & New]** klikken en het proces voor het gebied van de Reden van de Vraag herhalen).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-9.png)

### Aangepast activiteitenveld toevoegen aan taakpaginalayout in [!DNL Salesforce] Klassiek {#add-custom-activity-field-to-task-page-layout-in-salesforce-classic}

>[!NOTE]
>
>U hoeft deze stappen alleen uit te voeren als u in Stap 9 hierboven de gewenste paginalay-out niet hebt geselecteerd.

1. Klik in [!DNL Salesforce] op **[!UICONTROL Setup]** .

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-10.png)

1. Typ &quot;Taak&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-11.png)

1. Klik op **[!UICONTROL Task Page Layouts]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-12.png)

1. Klik op **[!UICONTROL Edit]** naast de indeling van de taakpagina waaraan u dit veld wilt toevoegen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-13.png)

1. Sleep het veld naar het gewenste gedeelte van de taakpaginalay-out.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-14.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-15.png)

## [!DNL Salesforce] Lightning {#salesforce-lightning}

### Veld voor aangepaste activiteit maken in [!DNL Salesforce] bliksemschicht {#create-custom-activity-field-in-salesforce-lightning}

1. Klik in [!DNL Salesforce] op het tandwielpictogram rechtsboven en selecteer **[!UICONTROL Setup]** .

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-16.png)

1. Klik op **[!UICONTROL Object Manager]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-17.png)

1. Typ &quot;[!UICONTROL Activity]&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-18.png)

1. Klik op het label **[!UICONTROL Activity]** .

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-19.png)

1. Klik op **[!UICONTROL Fields & Relationships]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-20.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-21.png)

### Veld voor aangepaste activiteit toevoegen aan taakpaginalayout in [!DNL Salesforce] bliksemschicht {#add-custom-activity-field-to-task-page-layout-in-salesforce-lightning}

1. Klik in [!DNL Salesforce] op het tandwielpictogram rechtsboven en selecteer **[!UICONTROL Setup]** .

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-22.png)

1. Klik op **[!UICONTROL Object Manager]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-23.png)

1. Typ &quot;[!UICONTROL Task]&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-24.png)

1. Klik op het label **[!UICONTROL Task]** .

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-25.png)

1. Klik op **[!UICONTROL Page Layouts]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-26.png)

1. Klik op de taakpaginalay-out waaraan u dit veld wilt toevoegen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-27.png)

1. Sleep het veld naar het gewenste gedeelte van de taakpaginalay-out.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-28.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-29.png)

>[!MORELIKETHIS]
>
>[ installeer de Gebieden van de Gebeurtenis van de Verkoop Connect op de Geschiedenis van de Activiteit ](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/install-sales-connect-event-fields-on-activity-history.md)
