---
unique-page-id: 10097202
description: Start voor e-mailprogramma's - Marketo Docs - Productdocumentatie
title: Begin voor e-mailprogramma's
exl-id: f7c8b082-4d83-4e3b-8aa4-7b252e3dacd3
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '408'
ht-degree: 0%

---

# Begin voor e-mailprogramma&#39;s {#head-start-for-email-programs}

>[!PREREQUISITES]
>
>[Een e-mailprogramma maken](/help/marketo/product-docs/email-marketing/email-programs/creating-an-email-program/create-an-email-program.md)

Wanneer u een datum/tijd kiest voor een e-mailprogramma, bepaalt dit wanneer het programma wordt verwerkt. Als u wilt dat uw e-mails op het geselecteerde tijdstip worden gestart, kunt u deze optie kiezen door het programma vooraf te verwerken.

## Standaardbeginpunt {#standard-head-start}

1. Klikken **Marketingactiviteiten**.

   ![](assets/one-1.png)

1. Zoek en selecteer uw e-mailprogramma.

   ![](assets/selectemailprogram-4.jpg)

   >[!NOTE]
   >
   >Kop Start kan niet worden gebruikt met A/B-tests.

1. In de tegel Planning plant u uw e-mail en selecteert u vervolgens de optie **Begin kop** doos.

   ![](assets/three-1.png)

   Als Begin is geselecteerd, begint het programma ongeveer 12 uur voor de geplande tijd te worden verwerkt. Nadat de verwerking is gestart, is het programma vergrendeld.

   >[!CAUTION]
   >
   >Iedereen uit uw publiek die zich na de programmavergrendeling afmeldt, ontvangt de e-mail nog steeds. We raden je aan je afmeldingsbericht aan te passen om aan te geven dat het 1-2 werkdagen kan duren voordat je afmeldt.

1. Klikken **Programma goedkeuren**.

   ![](assets/four-1.png)

   Na de goedkeuring van het programma zijn er vier verschillende statussen die u kunt zien op de goedkeuringstegel.

   * **Wachten op uitvoeren:** Nadat het programma is goedgekeurd.
   * **Verwerking gestart, wachten op uitvoering:** De verwerking wordt uitgevoerd.
   * **Verwerking voltooid, wachten op uitvoering:** Verwerking voltooid. E-mail wacht nu op geplande starttijd.
   * **Voltooid:** Programma voltooid.

   >[!TIP]
   >
   >Wilt u annuleren nadat het programma is vergrendeld, maar voordat de e-mail wordt verzonden? Geen probleem! Eenvoudig klikken **Programma afbreken** in de rechterbenedenhoek van de goedkeuringstegel.

   >[!NOTE]
   >
   >Als u uw e-mailprogramma minder dan 12 uur vóór de geplande runtime niet goedkeurt, maar u dan van gedachten verandert, moet u een nieuwe datum/tijd kiezen die minstens 12 uur voor is wanneer u het goedkeurt.

## Begin met ontvangende tijdzone {#head-start-with-recipient-time-zone}

Het programma moet ten minste 12 uur van tevoren worden gepland voor onze bestaande functie voor starten. Wat betekent dat voor de ontvangende tijdzone? Zoals u weet, wordt het e-mailprogramma uitgevoerd in de vroegste tijdzone (UTC +14:00) wanneer de tijdzone voor ontvangers actief is. Om **beide** Tijdzone van begin en ontvanger, programma&#39;s moeten worden gepland **ten minste 12 uur voor de vroegste tijdzone (UTC +14:00**.)

Dit betekent dat als u in Amerika/Los Angeles bent en zowel HoofdBegin als Ontvankelijke Tijdzone wilt toelaten, u het programma moet plannen **34 uur** vooraf. Hoe hebben we dit getal bereikt?

![](assets/image2017-12-5-13-3a11-3a46.png)

[Meer informatie](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md) over hoe te om e-mailprogramma&#39;s met de Gebied van de Tijd van de Ontvanger te plannen.

>[!MORELIKETHIS]
>
>* [Uw e-mailprogramma plannen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/schedule-your-email-program.md)
>* [E-mailprogramma&#39;s met tijdzone voor ontvangers plannen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [Tijdzone van ontvanger](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)

