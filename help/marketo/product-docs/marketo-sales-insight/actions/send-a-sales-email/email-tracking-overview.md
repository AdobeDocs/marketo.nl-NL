---
description: Overzicht van e-mailtracering - Marketo Docs - Productdocumentatie
title: Overzicht van e-mailtracking
exl-id: 89437d22-d739-45ea-8a2e-046a7de80379
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '482'
ht-degree: 0%

---

# Overzicht van e-mailtracking {#email-tracking-overview}

## Hoe Reageren bijhouden werkt {#how-reply-tracking-works}

Voor het bijhouden van antwoorden wordt een bericht-id weergegeven die in elke e-mail staat die u verzendt. Elk e-mailbericht bevat een unieke bericht-id waarmee we een aantal van de beste reacties kunnen bijhouden.

>[!PREREQUISITES]
>
>Verbinding maken met e-mailserver: [!DNL Sales Connect] moet zijn verbonden met uw Postvak IN, zodat we weten wanneer een nieuw antwoord is binnengekomen. Uw [!DNL Sales Connect] -account moet zijn aangesloten op Gmail. Als u Outlook gebruikt, moeten we uw Exchange-server integreren.

Als [!DNL Sales Connect] het antwoord van uw e-mail met uw vooruitzicht niet kan bijhouden, kan het geen campagne stoppen op basis van antwoorddetectie of logboek dat het antwoord op Salesforce weergeeft. Wat betekent dat elk e-mailadres kan antwoorden?

Dit betekent dat als u een e-mail <flynn@flynnsarcade.com> verzendt en hij reageert met <kevinf@flynnsarcade.com> , we het antwoord kunnen volgen. Als u bovendien een e-mail verzendt naar <flynn@flynnsarcade.com> en CC <alan@encom.com> en Alan terugschrijft, detecteert het ook het antwoord en beëindigt het de campagne.

## Uw e-mailbijlagen bijhouden {#how-to-track-your-email-attachments}

[!DNL Sales Connect] biedt tracering op uw bijlagen (.doc, .ppt, .pdf), zodat u kunt zien wanneer deze zijn geopend/gedownload en kunt zien welke pagina&#39;s de ontvanger doorzoekt. Wij zullen u toestaan om onze volgbare gehechtheid van zowel de [ Webtoepassing ](https://toutapp.com/login) als Gmail (of de Apps van Google) te gebruiken.

>[!NOTE]
>
>Bijlagen bijhouden is alleen beschikbaar voor onze teamplannen (te beginnen met ons g3startplan).

**hoe te om Uw Eerste TrackableBijlage** te verzenden

1. Stel een e-mail samen of bewerk een malplaatje, dan klik de **[!UICONTROL Content]** knoop.

1. Upload uw bijlage en verzend het uit. Wij ondersteunen PDF&#39;s, [!DNL Word] -documenten en [!DNL Powerpoint] -presentaties.

1. Selecteer **[!UICONTROL Add to Email]**.

1. Klik op **[!UICONTROL Send]** en vul uw Live feed in. Ontvangers worden weergegeven terwijl ze worden geopend en door de bijlagen worden gepagineerd.

>[!TIP]
>
>Als u een bijlage niet wilt bijhouden, klikt u gewoon op Bestanden bijvoegen en wordt deze bijlage niet bijgehouden.

## Hoe het Volgen van de Mening werkt {#how-view-tracking-works}

We houden het openen van e-mailberichten bij door een onzichtbare afbeelding in de e-mails te plaatsen die u verzendt.

Als iemand op uw e-mail reageert maar [!DNL Sales Connect] zegt dat deze niet is weergegeven, heeft de ontvanger geen afbeeldingen in zijn e-mailclient ingeschakeld (klik dus op het bericht &quot;Klik hier om afbeeldingen te downloaden&quot; in de e-mail).

Enkele tips voor het volgen van statistieken in je e-mails:

* Neem een afbeelding op in uw e-mails (zoals een logo), zodat de ontvanger wordt aangeraden om afbeeldingen in staat te stellen uw bericht te bekijken.
* Neem een koppeling als call to action op in de e-mail.

## E-mail testen niet weergegeven als weergegeven {#test-email-not-showed-as-viewed}

Zelfs als u uw bericht naar een ander e-mailadres hebt verzonden, worden de e-mails die u in Live feed hebt verzonden, niet in het logboek opgenomen. Onze tracering is gebaseerd op apparaten. Zolang u een computer gebruikt waarmee u zich hebt aangemeld bij [!DNL Sales Connect] , wordt deze activiteit uitgefilterd.

De reden? [!DNL Sales Connect] is slim en onze actieve gebruikers zullen ons nooit vergeven als hun eigen informatie in de Actief-diervoederactiviteit opduikt telkens als ze naar een e-mail keken die ze hadden verzonden.
