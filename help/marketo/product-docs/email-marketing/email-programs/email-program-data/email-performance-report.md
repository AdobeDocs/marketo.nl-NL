---
unique-page-id: 2359467
description: E-mailprestatierapport - Marketo Docs - Productdocumentatie
title: E-mailprestatierapport
exl-id: 327d4c0e-951f-4782-989d-4a4c6a513ebc
feature: Email Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '424'
ht-degree: 0%

---

# E-mailprestatierapport {#email-performance-report}

Als u wilt zien hoe goed uw e-mails presteren met stats zoals geleverde, geopende, geklikte, enz., maakt u een e-mailprestatierapport.

1. [Een rapport maken in een programma](/help/marketo/product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) en selecteert u de **E-mailprestaties** [Rapporttype](/help/marketo/product-docs/reporting/basic-reporting/report-types/report-type-overview.md).
1. [Het tijdkader van het rapport wijzigen](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md) en klik op de knop **Rapport** tab.
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
   >Een e-mailprestatierapport bevat activiteiten voor alle personen, inclusief personen die zijn verwijderd sinds het e-mailbericht is verzonden. Soms wil je alleen activiteiten voor actieve mensen zien. In dat geval moet u verwijderde personen uit uw rapport filteren. Gebruik de **Slimme lijst** tab naar [een slimme lijst maken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) voor het verslag. Als u niet op om het even welk specifiek gebied filtreert, plaats de filter E-mailadres aan: **is niet leeg**.

   [Rapportkolommen selecteren](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) voor een e-mailprestatierapport:

   | Kolom | Beschrijving |
   |---|---|
   | Hard geprononceerd | E-mail is geweigerd vanwege een permanente voorwaarde, zoals een niet-bestaand e-mailadres. |
   | Zacht gebogen | E-mail is geweigerd vanwege een tijdelijke voorwaarde, zoals het uitvallen van een server of een volledig inbox. |
   | In behandeling | Dit aantal wordt berekend door het aantal geleverde e-mails, afgeschreven berichten en zachte afrekeningen af te trekken van het totale aantal verzonden. |
   | Klikte koppeling | Aantal e-mailontvangers dat op een koppeling in de e-mail heeft geklikt. |
   | Niet geabonneerd | Aantal e-mailontvangers dat op het **Abonnement opzeggen** in de e-mail en het formulier invullen. |

   >[!NOTE]
   >
   >Koppelingen en e-mailadressen waarop wordt geklikt opzeggen, worden niet geregistreerd onder Geklikte koppelingen in het rapport.

Over het algemeen proberen we het gezond verstand te gebruiken om deze statistieken op te nemen. Als iemand bijvoorbeeld op een koppeling in een e-mailbericht heeft geklikt, heeft hij of zij het e-mailbericht eerst geopend. We volgen deze specifieke regels voor het e-mailprestatierapport:

* **Artikel 1**: Elke e-mailactiviteitenrecord is ingesteld op één van de volgende en slechts één van de volgende records: _Geleverd_, _Hard geprononceerd_, _Zacht gebogen_, of _In behandeling_.

* **Artikel 2**: Als de e-mailrecord wordt weergegeven *Geopend*, wordt het meegeteld als *Geleverd*.

* **Artikel 3**: Als de e-mailrecord wordt weergegeven _Op e-mail geklikt_ of _Abonnement opgezegd_, wordt het meegeteld als _Geleverd_ en _Geopend_.

* **Artikel 4**: Als het e-mailbericht _Geopend_, worden grenzen genegeerd. Als het e-mailbericht niet is geopend, _Hard geprononceerd_ heeft voorrang boven _Zacht gebogen_ en _Geleverd_.

>[!NOTE]
>
>Meervoudig verzendt van dezelfde campagne naar dezelfde persoon wordt slechts eenmaal geteld.

>[!MORELIKETHIS]
>
>* [Middelen filteren in e-mailrapporten voor campagnes](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [E-mailkoppelingsprestatierapport](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report.md)
