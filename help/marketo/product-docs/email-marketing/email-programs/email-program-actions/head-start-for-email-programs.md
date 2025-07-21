---
unique-page-id: 10097202
description: Start voor e-mailprogramma's - Marketo Docs - Productdocumentatie
title: Begin voor e-mailprogramma's
exl-id: f7c8b082-4d83-4e3b-8aa4-7b252e3dacd3
feature: Email Programs
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---

# Begin voor e-mailprogramma&#39;s {#head-start-for-email-programs}

>[!PREREQUISITES]
>
>[ creeer een E-mailprogramma ](/help/marketo/product-docs/email-marketing/email-programs/creating-an-email-program/create-an-email-program.md)

Wanneer u een datum/tijd voor een E-mailprogramma kiest, bepaalt het wanneer het programma met de verwerking begint. Als u wilt dat uw e-mails op het geselecteerde tijdstip worden gestart, kunt u deze optie kiezen door het programma vooraf te verwerken.

## Standaardbeginpunt {#standard-head-start}

1. Klik op **[!UICONTROL Marketing Activities]**.

   ![](assets/one-1.png)

1. Zoek en selecteer uw e-mailprogramma.

   ![](assets/selectemailprogram-4.jpg)

   >[!NOTE]
   >
   >Kop Start kan niet worden gebruikt met A/B-tests.

1. In de [!UICONTROL Schedule] -tegel plant u uw e-mail en selecteert u het vakje **[!UICONTROL Head Start]** .

   ![](assets/three-1.png)

   Als [!UICONTROL Head Start] is geselecteerd, begint het programma ongeveer 12 uur voor de geplande tijd te verwerken. Nadat de verwerking is gestart, is het programma vergrendeld.

   >[!CAUTION]
   >
   >Iedereen uit uw publiek die zich na de programmavergrendeling afmeldt, ontvangt de e-mail nog steeds. We raden je aan je afmeldingsbericht aan te passen om aan te geven dat het 1-2 werkdagen kan duren voordat je afmeldt.

1. Klik op **[!UICONTROL Approve Program]**.

   ![](assets/four-1.png)

   Na de goedkeuring van het programma zijn er vier verschillende statussen die u kunt zien op de goedkeuringstegel.

   * **[!UICONTROL Waiting to run]:** nadat het programma is goedgekeurd.
   * **[!UICONTROL Processing started, waiting to run]:** de verwerking wordt uitgevoerd.
   * **[!UICONTROL Processing finished, waiting to run]:** verwerking voltooid, e-mail nu wachtend op geplande tijd om te lanceren.
   * **[!UICONTROL Finished]:** Programma voltooid.

   >[!TIP]
   >
   >Wilt u annuleren nadat het programma is vergrendeld, maar voordat de e-mail wordt verzonden? Geen probleem! Klik gewoon op **[!UICONTROL Abort Program]** rechtsonder in de goedkeuringstegel.

   >[!NOTE]
   >
   >Als u uw e-mailprogramma minder dan 12 uur vóór de geplande runtime niet goedkeurt, maar u dan van gedachten verandert, moet u een nieuwe datum/tijd kiezen die minstens 12 uur voor is wanneer u het goedkeurt.

## Begin met ontvangende tijdzone {#head-start-with-recipient-time-zone}

Het programma moet ten minste 12 uur van tevoren worden gepland voor onze bestaande functie voor starten. Wat betekent dat voor de ontvangende tijdzone? Rappel dat wanneer de Ontvankelijke Tijdzone actief is, beginnen wij het e-mailprogramma bij middernacht in de vroegste tijdzone (UTC +14 :00) in werking te stellen. Zo, om **zowel** HoofdBegin als Ontvankelijke Streek van de Tijd toe te laten, moeten de programma&#39;s **minstens 12 uren vóór de vroegste tijdzone (UTC +14:00** worden gepland.)

Dit betekent dat als u in Amerika/Los Angeles bent en zowel HoofdBegin als Ontvankelijke Tijdzone wilt toelaten, u het programma **34 uren** vooraf moet plannen. Hoe hebben we dit getal bereikt?

![](assets/image2017-12-5-13-3a11-3a46.png)

[ leer meer ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md) over hoe te om e-mailprogramma&#39;s met de Ontvankelijke Zone van de Tijd te plannen.

>[!MORELIKETHIS]
>
>* [ Plan Uw E-mailprogramma ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/schedule-your-email-program.md)
>* [ E-mailprogramma&#39;s van het Programma met de Ontvankelijke Streek van de Tijd ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [ Begrijpend Ontvankelijke Tijdzone van de Tijd ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
