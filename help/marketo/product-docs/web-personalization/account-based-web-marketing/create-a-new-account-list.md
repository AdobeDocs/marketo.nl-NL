---
unique-page-id: 4720232
description: Een nieuwe accountlijst maken - Marketo Docs - Productdocumentatie
title: Een nieuwe accountlijst maken
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---


# Een nieuwe accountlijst maken {#create-a-new-account-list}

Maak en upload een lijst met organisatie- en domeinnamen om deze sleutelaccounts te richten op gepersonaliseerde campagnes.

>[!NOTE]
>
>Dit artikel is erfenisWeb ABM slechts klanten van toepassing. Als u Web ABM na september 2016 hebt aangeschaft, volgt u in plaats daarvan de stappen in [dit artikel](http://docs.marketo.com/display/DOCS/Account+Lists#AccountLists-CreateaNewAccountList) .

## Een nieuwe accountlijst maken {#create-a-new-account-list-1}

1. Ga naar **accountlijsten**.

   ![](assets/dropdown-account-lists-hand.jpg)

1. Selecteer **Nieuw** maken.

   ![](assets/create-new-account-list-hand.jpg)

1. Selecteer **Bladeren** en upload uw CSV-bestand (controleer of het CSV-bestand voldoet aan de criteria). Voeg een **Naam** en een **Beschrijving** toe. Klik op **Opslaan**.

   ![](assets/create-account-list-hands.jpg)

   >[!NOTE]
   >
   >**Wat is de indeling voor het CSV-bestand?**
   >
   >
   >Zorg ervoor dat het CSV-bestand van de benoemde account aan de volgende vereisten voldoet:
   >
   >* Opgeslagen als CSV-indeling
   >* Niet groter dan 10 MB
   >* Slechts 4 kolommen met kopkolom A: Naam, kolom B: Domein, kolom C: Land, kolom D: Amerikaanse staat.
   >* Het uploaden van een bestand kan maximaal twee werkdagen duren voordat het is goedgekeurd.
   >* U ontvangt een goedkeuringsbericht per e-mail of de status van het bestand op de pagina Benoemde accounts.
   >* Het totale aantal records/rijen dat voor al uw geüploade lijsten is geaccumuleerd, begint bij 10K, met het grootste pakket in totaal 100K.


   >[!NOTE]
   >
   >**Voorbeeld**
   >
   >**Voorbeeld van het CSV-bestand**
   >
   >* Rij 1 kolom A waarde = Organisatie
   >* Rij 1 kolom B waarde = Domein
   >* Rij 1 kolom C waarde = Land
   >* Rij 1 kolom D waarde = staat VS
   >* Een van de kolomwaarden is verplicht. Nochtans, verbetert het verstrekken van zowel Organisatie als de namen van het Domein de gelijke tarieven van de Lijst van de Rekening.
   >* Land en staat zijn optionele waarden.

      >
      >  
   * Gebruik voor de naam van het land de volledige naam van het land of de afkorting. Eg. Verenigde Staten of VS.
   >  * Voor een Amerikaanse staat gebruikt u de 2-letterige afkorting code, d.w.z. CA. Alleen staten in de VS worden herkend.

   >    
   >![](assets/image2015-2-25-12-3a19-3a10.png)

## Een accountlijst bewerken {#edit-an-account-list}

Klik op de pagina **Accountlijsten** op het pictogram **Bewerken **Bewerken in de lijst.

![](assets/create-new-account-list-edit.jpg)

Selecteer **Bladeren** en upload uw nieuwe CSV-bestand. Dit bestand vervangt het oorspronkelijke bestand. Klik op **Opslaan**. Het nieuwe geüploade bestand bevindt zich in de wachtrij totdat het is goedgekeurd door Marketo Support. In een status in behandeling blijft het oorspronkelijke bestand actief.

![](assets/set-account-list-edit-hands.jpg)

Het bestaande bestand wordt vervangen door het CSV-bestand. De bestaande lijst blijft actief totdat de verwerking van het nieuwe bestand is voltooid.

## Een lijst met benoemde accounts verwijderen {#delete-a-named-account-list}

1. Klik op de pagina **Accountlijsten **op het pictogram **Verwijderen **van de lijst die u wilt verwijderen.

   ![](assets/create-new-account-list-delete.jpg)

1. Er wordt een bericht weergegeven ter bevestiging dat u de lijst wilt verwijderen. Klik op **OK**.

   ![](assets/delete-notification-hand.jpg)

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Een segment maken met een accountlijst](create-a-segment-using-an-account-list.md)
>* [Een lijst met benoemde accounts weergeven](http://docs.marketo.com/pages/viewpage.action?pageid=4720244)

