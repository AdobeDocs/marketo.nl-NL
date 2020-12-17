---
unique-page-id: 2359467
description: E-mailprestatierapport - Marketo Docs - Productdocumentatie
title: E-mailprestatierapport
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '437'
ht-degree: 0%

---


# E-mailprestatierapport {#email-performance-report}

Als u wilt zien hoe goed uw e-mails presteren met stats zoals geleverde, geopende, geklikte, enz., maakt u een e-mailprestatierapport.

1. [Maak een rapport in een ](../../../../product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) programma en selecteer het  **Type** [ E-](../../../../product-docs/reporting/basic-reporting/report-types/report-type-overview.md)mailprestatierapport.
1. [Wijzig het ](../../../../product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md) frame Tijd rapport en klik op het tabblad  **** Rapporten.
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
   >
   >Een e-mailprestatierapport bevat activiteiten voor alle personen, inclusief personen die zijn verwijderd sinds het e-mailbericht is verzonden. Soms wil je alleen activiteiten voor actieve mensen zien. In dat geval moet u verwijderde personen uit uw rapport filteren. Gebruik **Slimme Lijst** lusje aan [creeer een slimme lijst](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) voor het rapport. Als u niet op om het even welk specifiek gebied filtreert, plaats de filter E-mailadres aan: **is niet leeg**.

   [Selecteer Rapportkolommen ](../../../../product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) voor een e-mailprestatierapport:

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

* **Regel 1**: Elke e-mailactiviteitenrecord is ingesteld op één van de volgende en slechts één van de volgende records:  *Geleverd*,  *Hard geprononeerd*,  *Zacht geprononceerd*, of in  *afwachting*.

* **Regel 2**: Als de e-mailrecord  *Geopend* toont, wordt deze geteld als  *Opgeleverd*.

* **Artikel 3**: Als in de e-mailrecord  *geklikt* e-mailadres wordt weergegeven dat  *niet is geabonneerd*, wordt dit meegeteld als  ** afgeleverd en  *geopend*.

* **Artikel 4**: Als het e-mailbericht wordt  *geopend*, worden de grenzen genegeerd. Als het e-mailbericht niet is geopend, heeft *Hard teruggestuurd* voorrang op *Zacht teruggezet* en *Afbezorgd*.

>[!NOTE]
>
>Meervoudig verzendt van dezelfde campagne naar dezelfde persoon wordt slechts eenmaal geteld.

>[!MORELIKETHIS]
>
>* [Middelen filteren in e-mailrapporten voor campagnes](../../../../product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [E-mailkoppelingsprestatierapport](email-link-performance-report.md)

>



>[!NOTE]
>
>**Diep duiken**
>
>Meer informatie vindt u in [Basisrapportage](http://docs.marketo.com/display/docs/basic+reporting).

