---
unique-page-id: 10096679
description: Voorbeeld ON24-gebeurtenisintegratie - Marketo Docs - productdocumentatie
title: Voorbeeld ON24-gebeurtenisintegratie
exl-id: 9d34d1bf-1ff8-4b26-906e-4a6bb9d5f3f6
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '387'
ht-degree: 0%

---

# Voorbeeld ON24-gebeurtenisintegratie {#example-on-event-integration}

Hier is een voorbeeldgebeurtenis, inclusief campagnes, voor een ON24 webinar. Wanneer u uw gebeurtenis maakt, moet u uw campagnes testen voordat u deze uitvoert.

## Nieuwe gebeurtenis maken in marketingactiviteiten {#create-a-new-event-in-marketing-activities}

1. Selecteren **Nieuw** > **Nieuw programma**.

   ![](assets/image2015-12-22-15-3a35-3a15.png)

1. Selecteer een **Campagnemap** waar de gebeurtenis zal plaatsvinden.

   ![](assets/image2015-12-22-15-3a39-3a51.png)

1. Voer een **Naam** voor de gebeurtenis.

   ![](assets/image2015-12-22-15-3a43-3a4.png)

1. Selecteren **Gebeurtenis** als de **Type programma**.

   ![](assets/image2015-12-22-15-3a44-3a41.png)

1. Selecteren **Webinar** als de **Kanaal** voor de gebeurtenis.

   ![](assets/image2015-12-22-15-3a46-3a34.png)

1. Klikken **Maken**.

   ![](assets/image2015-12-22-15-3a48-3a20.png)

## Uitnodigen (batchcampagne)  {#invite-batch-campaign}

* **Slimme lijst** - Bepaal wie u wilt uitnodigen voor de gebeurtenis.
* **Stroom**

   * E-mail verzenden - Als dit een e-mail met lokale middelen is, is de volgende naamgevingsconventie van toepassing: EventName.EmailName. Je kunt ook wereldwijde e-mails gebruiken.
   * Status wijzigen in Progressie - Instellen op Webinar > Uitgenodigd.

* **Schema** - Stel de datum in waarop de uitnodiging moet worden verzonden.

## Registratie/bevestiging (Trigger-campagne) {#registration-confirmation-trigger-campaign}

* **Slimme lijst**

   * De campagne activeren op basis van **Formulier wordt ingevuld**. Zorg ervoor dat u de landingspagina opneemt waarop het formulier zich bevindt door het te gebruiken **Restrictie toevoegen**, vooral als het formulier op meerdere bestemmingspagina&#39;s wordt gebruikt.

>[!CAUTION]
>
>U moet een Marketo-formulier gebruiken om personen voor de gebeurtenis te registreren, of een niet-Marketo-formulier met de juiste API-integratie om registratiegegevens naar Marketo te verzenden. Dit is kritiek aan het succes van uw integratie van de Partner van de Gebeurtenis. **OPMERKING**: Als u een Marketo-formulier gebruikt op een landingspagina die geen Marketo is, wordt de trigger **Formulier wordt ingevuld** met de naam van het formulier.

![](assets/image2015-12-22-15-3a50-3a22.png)

* **Stroom**

   * **Status wijzigen in Progressie** - Instellen op Webinar > Geregistreerd. **VOORZIENING**: Deze stroomstap is vereist voor het instellen van uw onderliggende campagne. Wanneer de progressiestatus van een persoon verandert in **Geregistreerd**, plaatst Marketo de registratiegegevens op ON24.

   * **E-mail verzenden** - Bevestigingse-mail (ingesteld op **Operationeel** zodat niet-geabonneerde personen die zich hebben geregistreerd, deze nog steeds ontvangen).

![](assets/image2015-12-22-15-3a52-3a9.png)

**OPMERKING**: Als de persoon wordt geretourneerd met een registratiefout, wordt de e-mailbevestiging niet ontvangen.

## Herinnering (batchcampagne) {#reminder-batch-campaign}

* **Slimme lijst** - Filteren met **Lid van het programma** en stel de status in op **Geregistreerd**.

* **Stroom** - E-mail verzenden (e-mail herinnering).

**OPMERKING**: U kunt een vergelijkbare campagne gebruiken om een *verschillend* e-mail volgen naar mensen die zijn uitgenodigd maar zich nog niet hebben geregistreerd.

## Follow-upcampagne (campagne voor batchverwerking of activering) {#follow-up-campaign-batch-or-trigger-campaign}

* **Slimme lijst** - Trigger op basis van wijzigingen in de status van het programma.

![](assets/image2015-12-22-15-3a57-3a25.png)

* **Stroom** - E-mail verzenden. Gebruik keuzen om verschillende e-mails te verzenden op basis van de status van het programma.

![](assets/ten.png)

>[!MORELIKETHIS]
>
>[Marketo ON24-adaptergebeurtenissen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target=&quot;_blank&quot;}
