---
unique-page-id: 1900597
description: Een publiek definiëren door een lijst - Marketo Docs - Productdocumentatie te importeren
title: Een publiek definiëren door een lijst te importeren
exl-id: 9a63f4a5-1d76-4671-9622-19eb368d196f
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 0%

---

# Een publiek definiëren door een lijst te importeren {#define-an-audience-by-importing-a-list}

>[!PREREQUISITES]
>
>[Een e-mail maken voor een e-mailprogramma](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/create-an-email-for-an-email-program.md)

Als u eenmaal een e-mailprogramma hebt gemaakt, wilt u het weten naar wie de e-mail moet worden verzonden. U kunt dit doen door [een slimme lijst maken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) of door een lijst te importeren. Hieronder wordt beschreven hoe u dit kunt bereiken door een lijst te importeren.

>[!NOTE]
>
>Het definiëren van uw publiek werkt alleen wanneer het e-mailprogramma niet is goedgekeurd.
>
>Alle datum-/tijdvelden die worden geïmporteerd, worden behandeld als Central Time. Als u datum-/tijdgebieden in een verschillende tijdzone hebt, kunt u een formule van Excel gebruiken om het in Centrale Tijd (Amerika/Chicago) om te zetten.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-1.png)

1. Selecteer het e-mailprogramma en klik vervolgens op Lijst importeren onder de tegel Publiek.

   ![](assets/importlist.png)

1. Het venster voor het importeren van de lijst wordt geopend. Klik op **Bladeren** en selecteer het bestand dat u wilt importeren. Nadat u de lijst met personen hebt geselecteerd, klikt u op **Volgende**.

   ![](assets/importlist1.png)

   >[!CAUTION]
   >
   >Controleer of de lijst UTF-8, UTF-16, Shift-JIS of EUC-JP heeft gecodeerd en of de bestandsgrootte niet groter is dan 50 MB.

1. Controleer of de velden in uw bestand correct zijn toegewezen en klik op **Volgende**.

   ![](assets/image2014-9-12-11-3a10-3a7.png)

   >[!TIP]
   >
   >Marketo zal zich de toewijzingen voor toekomstige import herinneren!

1. Voer een **Naam** voor uw lijst en klik op **Importeren**.

   ![](assets/image2014-9-12-11-3a10-3a13.png)

1. Wanneer het importeren is voltooid, gaat u terug naar het hoofdprogrammatabblad. Je zult zien hoeveel mensen in aanmerking komen.

   ![](assets/myemailprogram-1.jpg)

>[!NOTE]
>
>**Definitie**
>
>Heb je het geblokkeerde nummer gezien? Dit nummer is een subset van de gekwalificeerde personen en vertegenwoordigt personen die dit e-mailbericht niet kunnen verzenden omdat ze:
>
>* Niet geabonneerd
>* Marketing opgeschort
>* Gevoegd op lijst van gewenste personen
>* E-mail ongeldig
>* Lege e e e-mail
>
>Klik op het nummer voor een gedetailleerde lijst met personen die zijn geblokkeerd voor verzending.
>
>Gebruik de ![—](assets/image2014-10-23-16-3a32-3a36-1.png) op de knop **Publiek** tegel om te zien hoeveel mensen in aanmerking kwamen om de e-mail te ontvangen op basis van de criteria van de slimme lijst. Trek het geblokkeerde nummer van het Personen-nummer af om het totale aantal personen op te halen dat het e-mailbericht ontvangt.

>[!TIP]
>
>U hoeft niet te wachten tot de import van de lijst is voltooid. U kunt blijven werken als u wilt.

Fantastisch! Nu is het tijd om een bestaande e-mail te kiezen of een nieuwe e-mail te maken om naar deze mensen te verzenden.

>[!MORELIKETHIS]
>
>* [Bestaande e-mail kiezen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/choose-an-existing-email.md)
>* [Een e-mail maken voor een e-mailprogramma](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/create-an-email-for-an-email-program.md)

