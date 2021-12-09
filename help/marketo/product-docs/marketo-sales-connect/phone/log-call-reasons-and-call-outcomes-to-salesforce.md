---
description: De Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce - de Documenten van Marketo - de Documentatie van het Product
title: De Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce
hide: true
hidefromtoc: true
exl-id: b35acdc2-8ec7-4dec-92b8-58ba7a1ad858
source-git-commit: 0fc2551ffc85260a282b64995c698098846eb10c
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

1. Klik in Salesforce op **Instellen**.

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

1. De overige instellingen zijn optioneel. Nadat u de configuratie hebt voltooid, klikt u op **Volgende**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-7.png)

1. Selecteer de gewenste beveiligingsinstellingen op veldniveau voor dit veld en klik op **Volgende** (De onderstaande afbeelding is slechts een voorbeeld).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-8.png)

   >[!NOTE]
   >
   >Zorg ervoor dat het aangepaste veld zichtbaar is voor het profiel dat uw gebruikers van Sales Connect gebruiken, en ook voor alle andere gebruikers die het wilt weergeven.

1. Selecteer de paginalay-outs waaraan u het veld wilt toevoegen en klik op **Opslaan** (U kunt desgewenst op **Opslaan en nieuw** en herhaal het proces voor het gebied van de Reden van de Vraag).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-9.png)

### Aangepast activiteitenveld toevoegen aan taakpaginalay-out in Salesforce Classic {#add-custom-activity-field-to-task-page-layout-in-salesforce-classic}

1. Klik in Salesforce op **Instellen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-10.png)

1. Typ &quot;Taak&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-11.png)

1. Klikken **Taakpagina-indelingen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-12.png)

1. Klikken **Bewerken** naast de indeling van de taakpagina waaraan u dit veld wilt toevoegen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-13.png)

1. Sleep het veld naar de indeling van de taakpagina.

   PICC

1. Klikken **Opslaan**.

   PICC

## Salesforce Lightning {#salesforce-lightning}

### Aangepast activiteitenveld maken in Salesforce Lightning {#create-custom-activity-field-in-salesforce-lightning}

1. Klik in Salesforce op het tandwielpictogram rechtsboven.

PICC

1. Klikken **Instellen**.

PICC

1. Klikken **Objectbeheer**.

PICC

1. Voer Activiteit in het vak Snel zoeken in en klik op het label Activiteit om de instelling van het object te openen.

PICC

1. Klik links op **Velden en relaties**.

PICC

1. Klikken **Nieuw**.

PICC

## Aangepast activiteitenveld toevoegen aan taakpaginalay-out in Salesforce Lightning {#add-custom-activity-field-to-task-page-layout-in-salesforce-lightning}

1. Klik in Salesforce op het tandwielpictogram rechtsboven.

PICC

1. Klikken **Instellen**.

PICC

1. Ga naar Setup??????????

PICC

1. Typ &quot;Taak&quot; in het vak Snel zoeken.

PICC

1. Klik op Taak.

PICC

1. Klik op Pagina-indelingen.

PICC

1. Klik op de taakpaginalay-out waaraan u dit veld wilt toevoegen.

PICC

1. Sleep het veld naar de indeling van de taakpagina.

PICC

1. Klik op Opslaan.

PICC

>[!MORELIKETHIS]
>
>[Verkoop Connect-gebeurtenisvelden installeren in activiteitenoverzicht](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/install-sales-connect-event-fields-on-activity-history.md)
