---
unique-page-id: 2359467
description: E-mailprestatierapport - Marketo Docs - Productdocumentatie
title: E-mailprestatierapport
translation-type: tm+mt
source-git-commit: 0f0217a88929661798015b51a26259a973f9f6ea
workflow-type: tm+mt
source-wordcount: '424'
ht-degree: 0%

---


# E-mailprestatierapport {#email-performance-report}

Als u wilt zien hoe goed uw e-mails presteren met stats zoals geleverde, geopende, geklikte, enz., maakt u een e-mailprestatierapport.

1. [Maak een rapport in een ](/help/marketo/product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) programma en selecteer het  **Type** [ E-](/help/marketo/product-docs/reporting/basic-reporting/report-types/report-type-overview.md)mailprestatierapport.
1. [Wijzig het ](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md) frame Tijd rapport en klik op het tabblad  **** Rapporten.
1. Je bent er! Bekijk nu het rapport om te zien hoe uw e-mail(s) zijn uitgevoerd.

   >[!NOTE]
   >
   >Het filter Datum verzenden is gebaseerd op de eerste datum waarop de e-mail is verzonden.

   ![](assets/email-performance-report.png)

   >[!TIP]
   >
   >Klik op de naam van een e-mailbericht om het te openen in de e-mailvoorvertoning.

   >[!NOTE]
   >
   >Een e-mailprestatierapport bevat activiteiten voor alle personen, inclusief personen die zijn verwijderd sinds het e-mailbericht is verzonden. Soms wil je alleen activiteiten voor actieve mensen zien. In dat geval moet u verwijderde personen uit uw rapport filteren. Gebruik **Slimme Lijst** lusje aan [creeer een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) voor het rapport. Als u niet op om het even welk specifiek gebied filtreert, plaats de filter E-mailadres aan: **is niet leeg**.

   [Selecteer Rapportkolommen ](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) voor een e-mailprestatierapport:

   | Kolom | Beschrijving |
   |---|---|
   | Hard geprononceerd | E-mail is geweigerd vanwege een permanente voorwaarde, zoals een niet-bestaand e-mailadres. |
   | Zacht gebogen | E-mail is geweigerd vanwege een tijdelijke voorwaarde, zoals het uitvallen van een server of een volledig inbox. |
   | In behandeling | Dit aantal wordt berekend door het aantal geleverde e-mails, afgeschreven berichten en zachte afrekeningen af te trekken van het totale aantal verzonden. |
   | Klikte koppeling | Aantal e-mailontvangers dat op een koppeling in de e-mail heeft geklikt. |
   | Abonnement opgezegd | Aantal e-mailontvangers die op de koppeling **Abonnement opzeggen** in de e-mail hebben geklikt en het formulier hebben ingevuld. |

   >[!NOTE]
   >
   >Koppelingen en e-mailadressen waarop wordt geklikt opzeggen, worden niet geregistreerd onder Geklikte koppelingen in het rapport.

Over het algemeen proberen we het gezond verstand te gebruiken om deze statistieken op te nemen. Als iemand bijvoorbeeld op een koppeling in een e-mailbericht heeft geklikt, heeft hij of zij het e-mailbericht eerst geopend. We volgen deze specifieke regels voor het e-mailprestatierapport:

* **Regel 1**: Elke e-mailactiviteitenrecord is ingesteld op één van de volgende en slechts één van de volgende records:  _Geleverd_,  _Hard geprononeerd_,  _Zacht geprononceerd_, of in  _afwachting_.

* **Regel 2**: Als de e-mailrecord  *Geopend* toont, wordt deze geteld als  *Opgeleverd*.

* **Artikel 3**: Als in de e-mailrecord  _geklikt_ e-mailadres wordt weergegeven dat  _niet is geabonneerd_, wordt dit meegeteld als  __ afgeleverd en  _geopend_.

* **Artikel 4**: Als het e-mailbericht wordt  _geopend_, worden de grenzen genegeerd. Als het e-mailbericht niet is geopend, heeft _Hard teruggestuurd_ voorrang op _Zacht teruggezet_ en _Afbezorgd_.

>[!NOTE]
>
>Meervoudig verzendt van dezelfde campagne naar dezelfde persoon wordt slechts eenmaal geteld.

>[!MORELIKETHIS]
>
>* [Middelen filteren in e-mailrapporten voor campagnes](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [E-mailkoppelingsprestatierapport](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report.md)

