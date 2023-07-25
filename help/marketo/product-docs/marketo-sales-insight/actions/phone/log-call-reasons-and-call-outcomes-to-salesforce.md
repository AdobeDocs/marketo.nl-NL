---
description: De Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce - de Documenten van Marketo - de Documentatie van het Product
title: De Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce
exl-id: cfe71388-282b-45e5-a817-45a951f613bc
feature: Sales Insight Actions
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '464'
ht-degree: 0%

---

# De Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce {#log-call-reasons-and-call-outcomes-to-salesforce}

Als u vraagresultaten en vraagredenen aan Salesforce voor het melden of zichtbaarheidsdoeleinden wilt registreren, kunt u een gebied van de douaneactiviteit voor elk tot stand brengen. Voor elk veld moet een specifieke API-naam worden gebruikt (in Salesforce wordt &#39;&#39;veldnaam&#39;&#39; genoemd).

* De Naam van het Gebied van Resultaten van de vraag: mktosales_call_result
* Naam veld Redenen aanroepen: mktosales_call_reason

Als u deze velden wilt gebruiken, moet u het veld eerst maken als een veld voor aangepaste activiteit. Als u deze zichtbaar wilt maken voor gebruikers, moet u deze toevoegen aan de pagina-indeling van het taakobject.

## Salesforce Classic {#salesforce-classic}

### Aangepast activiteitsveld maken in Salesforce Classic  {#create-custom-activity-field-in-salesforce-classic}

1. Klik in Salesforce op **Instellen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-1.png)

1. Typ &quot;Activiteiten&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-2.png)

1. Klikken **Aangepaste velden activiteit**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-3.png)

1. Klikken **Nieuw**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-4.png)

1. Selecteer het gegevenstype &quot;Tekst&quot; en klik op **Volgende**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-5.png)

1. Geef het aangepaste veld de veldnaam zoals hierboven gedefinieerd. De veldlengte mag niet langer zijn dan 255 tekens. Het Etiket van het gebied zal het gebied zichtbaar aan uw verkoopteam zijn en kan worden aangepast om aan de behoeften van uw team te voldoen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-6.png)

1. De overige instellingen zijn optioneel. Zodra u de configuratie hebt voltooid, klik **Volgende**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-7.png)

1. Selecteer de gewenste beveiligingsinstellingen op veldniveau voor dit veld en klik op **Volgende** (De onderstaande afbeelding is slechts een voorbeeld).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-8.png)

   >[!NOTE]
   >
   >Zorg ervoor het douanegebied aan het profiel zichtbaar is uw gebruikers van de Acties van het Inzicht van de Verkoop, samen met om het even welk ander u het zichtbaar zou willen.

1. Selecteer de paginalay-outs waaraan u het veld wilt toevoegen en klik op **Opslaan** (U kunt desgewenst op **Opslaan en nieuw** en herhaal het proces voor het gebied van de Reden van de Vraag).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-9.png)

### Aangepast activiteitenveld toevoegen aan taakpaginalay-out in Salesforce Classic {#add-custom-activity-field-to-task-page-layout-in-salesforce-classic}

>[!NOTE]
>
>U hoeft deze stappen alleen uit te voeren als u in Stap 9 hierboven de gewenste paginalay-out niet hebt geselecteerd.

1. Klik in Salesforce op **Instellen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-10.png)

1. Typ &quot;Taak&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-11.png)

1. Klikken **Taakpagina-indelingen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-12.png)

1. Klikken **Bewerken** naast de indeling van de taakpagina waaraan u dit veld wilt toevoegen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-13.png)

1. Sleep het veld naar het gewenste gedeelte van de taakpaginalay-out.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-14.png)

1. Klikken **Opslaan**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-15.png)

## Salesforce Lightning {#salesforce-lightning}

### Aangepast activiteitenveld maken in Salesforce Lightning {#create-custom-activity-field-in-salesforce-lightning}

1. Klik in Salesforce op het tandwielpictogram rechtsboven en selecteer **Instellen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-16.png)

1. Klikken **Objectbeheer**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-17.png)

1. Typ &quot;Activiteit&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-18.png)

1. Klik op de knop **Activiteit** label.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-19.png)

1. Klikken **Velden en relaties**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-20.png)

1. Klikken **Nieuw**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-21.png)

### Aangepast activiteitenveld toevoegen aan taakpaginalay-out in Salesforce Lightning {#add-custom-activity-field-to-task-page-layout-in-salesforce-lightning}

1. Klik in Salesforce op het tandwielpictogram rechtsboven en selecteer **Instellen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-22.png)

1. Klikken **Objectbeheer**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-23.png)

1. Typ &quot;Taak&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-24.png)

1. Klik op de knop **Taak** label.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-25.png)

1. Klikken **Pagina-indelingen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-26.png)

1. Klik op de taakpaginalay-out waaraan u dit veld wilt toevoegen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-27.png)

1. Sleep het veld naar het gewenste gedeelte van de taakpaginalay-out.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-28.png)

1. Klikken **Opslaan**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-29.png)

>[!MORELIKETHIS]
>
>* [Resultaten bellen](/help/marketo/product-docs/marketo-sales-insight/actions/phone/call-outcomes.md)
>* [Redenen voor oproepen](/help/marketo/product-docs/marketo-sales-insight/actions/phone/call-reasons.md)
