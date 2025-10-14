---
unique-page-id: 4720232
description: Een nieuwe accountlijst maken - Marketo Docs - Productdocumentatie
title: Een nieuwe accountlijst maken
exl-id: 644c5b3b-852a-4dd9-8e55-b434505504ea
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 1%

---

# Een nieuwe accountlijst maken {#create-a-new-account-list}

Maak en upload een lijst met organisatie- en domeinnamen om deze sleutelaccounts te richten op gepersonaliseerde campagnes.

>[!NOTE]
>
>Dit artikel is erfenisWeb ABM slechts klanten van toepassing. Als u het Web ABM na September van 2016 verwierf, te volgen gelieve de stappen in [&#x200B; dit artikel &#x200B;](https://docs.marketo.com/display/DOCS/Account+Lists#AccountLists-CreateaNewAccountList) in plaats daarvan.

## Een nieuwe accountlijst maken {#create-a-new-account-list-1}

1. Ga naar **[!UICONTROL Account Lists]** .

   ![](assets/dropdown-account-lists-hand.jpg)

1. Selecteer **[!UICONTROL Create New]**.

   ![](assets/create-new-account-list-hand.jpg)

1. Selecteer **[!UICONTROL Browse]** en upload uw CSV-bestand (controleer of het CSV-bestand voldoet aan de criteria). Voeg een lus **[!UICONTROL List Name]** en **[!UICONTROL Description]** toe. Klik op **[!UICONTROL Save]**.

   ![](assets/create-account-list-hands.jpg)

   >[!NOTE]
   >
   >**wat is het formaat voor het Csv- Dossier?**
   >
   >Zorg ervoor dat het CSV-bestand van de benoemde account aan de volgende vereisten voldoet:
   >
   >* Opgeslagen als CSV-indeling
   >* Niet groter dan 10 MB
   >* Slechts vier kolommen met de koptekst Kolom A: Naam, Kolom B: Domein, Kolom C: Land, Kolom D: Staat VS.
   >* Het uploaden van een bestand kan maximaal twee werkdagen duren voordat het is goedgekeurd.
   >* U ontvangt een goedkeuringsbericht per e-mail of de status van het bestand op de pagina Benoemde accounts.
   >* Het totale aantal records/rijen dat voor al uw geüploade lijsten is geaccumuleerd, begint bij 10K, met het grootste pakket in totaal 100K.

   >[!NOTE]
   >
   >**Voorbeeld van het Csv- dossier**
   >
   >* Rij 1 kolom A waarde = Organisatie
   >* Rij 1 kolom B waarde = Domein
   >* Rij 1 kolom C waarde = Land
   >* Rij 1 kolom D waarde = staat VS
   >* Een van de kolomwaarden is verplicht. Nochtans, verbetert het verstrekken van zowel Organisatie als de namen van het Domein de gelijke tarieven van de Lijst van de Rekening.
   >* Land en staat zijn optionele waarden.
   >
   >   * Gebruik voor de naam van het land de volledige naam van het land of de afkorting. Eg. Verenigde Staten of VS.
   >   * Voor een Amerikaanse staat gebruikt u de 2-letterige afkorting code, d.w.z. CA. Alleen staten in de VS worden herkend.
   >
   >![](assets/image2015-2-25-12-3a19-3a10.png)

## Een accountlijst bewerken {#edit-an-account-list}

Voor de **pagina van de Lijsten van de Rekening**, klik **uitgeven** pictogram op de lijst.

![](assets/create-new-account-list-edit.jpg)

Selecteer **[!UICONTROL Browse...]** en upload uw nieuw CSV-bestand. Dit bestand vervangt het oorspronkelijke bestand. Klik op **[!UICONTROL Save]**. Het nieuwe geüploade bestand bevindt zich in een status die in behandeling is totdat het is goedgekeurd door Marketo Support. In een status die in behandeling is, blijft het oorspronkelijke bestand actief.

![](assets/set-account-list-edit-hands.jpg)

Het bestaande bestand wordt vervangen door het CSV-bestand. De bestaande lijst blijft actief totdat de verwerking van het nieuwe bestand is voltooid.

## Een lijst met benoemde accounts verwijderen {#delete-a-named-account-list}

1. Klik op de pagina **[!UICONTROL Account Lists]** op het pictogram Verwijderen van de lijst die u wilt verwijderen.

   ![](assets/create-new-account-list-delete.jpg)

1. Er wordt een bericht weergegeven ter bevestiging dat u de lijst wilt verwijderen. Klik op **[!UICONTROL OK]**.

   ![](assets/delete-notification-hand.jpg)

>[!MORELIKETHIS]
>
>[&#x200B; creeer een Segment Gebruikend een Lijst van de Rekening &#x200B;](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-segment-using-an-account-list.md)
