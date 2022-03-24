---
description: Overzicht van e-mailtracering - Marketo Docs - Productdocumentatie
title: Overzicht van e-mailtracking
exl-id: 89437d22-d739-45ea-8a2e-046a7de80379
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '510'
ht-degree: 0%

---

# Overzicht van e-mailtracking {#email-tracking-overview}

## Hoe Reageren bijhouden werkt {#how-reply-tracking-works}

Voor het bijhouden van antwoorden wordt een bericht-id weergegeven die in elke e-mail staat die u verzendt. Elk e-mailbericht bevat een unieke bericht-id waarmee we een aantal van de beste reacties kunnen bijhouden.

>[!PREREQUISITES]
>
>Verbinding maken met e-mailserver: Sales Connect moet verbonden zijn met uw Postvak IN, zodat we weten wanneer een nieuw antwoord is ontvangen. Uw Sales Connect-account moet zijn verbonden met Gmail. Als u Outlook gebruikt, moeten we uw Exchange-server integreren.

Als Sales Connect het antwoord van uw e-mail met uw vooruitzicht niet kan bijhouden, kan deze geen campagne stoppen op basis van antwoorddetectie of logboek dat het antwoord op Salesforce weergeeft. Wat betekent dat elk e-mailadres kan antwoorden?

Dit betekent dat als u een e-mail verzendt naar flynn@flynnsarcade.com en reageert op kevinf@flynnsarcade.com, we het antwoord kunnen volgen. Bovendien, als u flynn@flynnsarcade.com en CC alan@encom.com e-mailt, en Alan u terug schrijft, zal het ook het antwoord ontdekken en de campagne beëindigen.

## Uw e-mailbijlagen bijhouden {#how-to-track-your-email-attachments}

Met Sales Connect kunt u bijlagen bijhouden (.doc, .ppt, .pdf), zodat u kunt zien wanneer ze zijn geopend/gedownload en kunt u zien welke pagina&#39;s de ontvanger doorzoekt. U kunt de functie voor trackable attachments van beide [webtoepassing](https://toutapp.com/login) en Gmail (of Google Apps).

>[!NOTE]
>
>Bijlagen bijhouden is alleen beschikbaar voor onze teamplannen (te beginnen met ons g3startplan).

**Hoe te om uw eerste Trackable Bijlage te verzenden**

1. Stel een e-mail samen of bewerk een malplaatje, dan klik **Inhoud** knop.

1. Upload uw bijlage en verzend het uit. Wij ondersteunen PDF, Word-documenten en PowerPoint-presentaties.

1. Selecteren **Toevoegen aan e-mail**.

1. Klikken **Verzenden** en vul uw Live Feed in. Ontvangers worden weergegeven terwijl ze worden geopend en door de bijlagen worden gepagineerd.

>[!TIP]
>
>Als u een bijlage niet wilt bijhouden, klikt u gewoon op Bestanden bijvoegen en wordt deze bijlage niet bijgehouden.

## Hoe het Volgen van de Mening werkt {#how-view-tracking-works}

We houden het openen van e-mailberichten bij door een onzichtbare afbeelding in de e-mails te plaatsen die u verzendt.

Als iemand op uw e-mail reageert maar Sales Connect zegt dat deze niet is weergegeven, heeft de ontvanger geen afbeeldingen in zijn e-mailclient ingeschakeld (klik dus op het bericht &quot;Klik hier om afbeeldingen te downloaden&quot; in de e-mail).

Enkele tips voor het volgen van statistieken in je e-mails:

* Neem een afbeelding op in uw e-mails (zoals een logo), zodat de ontvanger wordt aangeraden om afbeeldingen in staat te stellen uw bericht te bekijken.
* Neem een koppeling op als een oproep tot actie in de e-mail.

## E-mail testen niet weergegeven als weergegeven {#test-email-not-showed-as-viewed}

Zelfs als u uw bericht naar een ander e-mailadres hebt verzonden, worden de e-mails die u in Live feed hebt verzonden, niet in het logboek opgenomen. Onze tracering is gebaseerd op apparaten. Als u een computer gebruikt waarmee u zich hebt aangemeld bij Sales Connect, wordt deze activiteit uitgefilterd.

De reden? Sales Connect is slim en onze actieve gebruikers zullen het ons nooit vergeven als hun eigen gegevens elke keer dat ze een e-mail die ze hebben verzonden bekijken, in de Live Feed-activiteit worden weergegeven.
