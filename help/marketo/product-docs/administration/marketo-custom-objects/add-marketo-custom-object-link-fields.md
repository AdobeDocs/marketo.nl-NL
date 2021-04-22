---
unique-page-id: 10097613
description: Aangepaste Marketo-objectkoppelingsvelden toevoegen - Marketo Docs - Productdocumentatie
title: Aangepaste Marketo-objectkoppelingsvelden toevoegen
exl-id: e7537d79-9fca-4966-881a-9d7d312008e2
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '601'
ht-degree: 0%

---

# Aangepast Marketo-objectkoppelingsvelden toevoegen {#add-marketo-custom-object-link-fields}

Wanneer u aangepaste objecten maakt, moet u koppelingsvelden opgeven om de aangepaste objectreeks te koppelen aan de juiste bovenliggende record.

* Voor een één-op-vele douanestructuur, gebruik het verbindingsgebied in het douanevoorwerp om het met een persoon of een bedrijf te verbinden.
* Voor een vele-aan-vele structuur, gebruikt u twee verbindingsgebieden, die van een afzonderlijk gecreeerd intermediair voorwerp worden verbonden (dat een type van douanevoorwerp, ook is). Eén koppeling maakt verbinding met personen of bedrijven in uw database en de andere koppeling maakt verbinding met het aangepaste object. In dit geval bevindt het koppelingsveld zich niet in het aangepaste object zelf.

## Creeer een Gebied van de Verbinding voor een Één-aan-Vele Structuur {#create-a-link-field-for-a-one-to-many-structure}

Hieronder wordt beschreven hoe u een koppelingsveld maakt in een aangepast object voor een een-op-een-structuur.

1. Klik **Admin**, en in **Databasebeheer**, selecteer **Aangepaste objecten van Marketo**.

   ![](assets/image2016-1-18-13-3a25-3a11.png)

1. Selecteer het aangepaste object in de lijst.

   ![](assets/image2016-1-14-15-3a6-3a2.png)

1. Klik op het tabblad **Velden** op **Nieuw veld**.

   ![](assets/image2015-9-17-14-3a9-3a19.png)

1. Geef het koppelingsveld een naam en voeg een optionele beschrijving toe. Selecteer het gegevenstype Koppeling.

   ![](assets/image2015-10-5-13-3a24-3a57.png)

   >[!CAUTION]
   >
   >U kunt niet terug gaan en een Verbinding of Dedupe- Gebied creëren uitgeven of schrappen zodra het douanevoorwerp wordt goedgekeurd.

1. Selecteer of het koppelingsobject voor een lead (persoon) of een bedrijf is.

   ![](assets/image2015-10-5-13-3a28-3a1.png)

   >[!NOTE]
   >
   >Als u lood kiest, zult u identiteitskaart, e-mailadres, en om het even welke douanevelden in de lijst zien.
   >
   >Als u bedrijf kiest, ziet u Id en eventuele aangepaste velden in de lijst.

1. Selecteer het koppelingsveld waarmee u verbinding wilt maken als het bovenliggende veld van het nieuwe veld.

   ![](assets/image2015-10-5-13-3a30-3a6.png)

   >[!NOTE]
   >
   >Alleen typen tekenreeksvelden worden ondersteund in het koppelingsveld.

1. Klik **Opslaan.**

   ![](assets/image2015-10-5-13-3a34-3a0.png)

## Creeer een Gebied van de Verbinding voor een Vele-aan-Vele Structuur {#create-a-link-field-for-a-many-to-many-structure}

Hier is hoe te om een verbindingsgebied in een intermediair voorwerp voor gebruik in een vele-aan-vele structuur tot stand te brengen.

>[!PREREQUISITES]
>
>U moet het intermediaire object al hebben gemaakt en alle aangepaste objecten die u wilt koppelen.

1. Klik **Admin**, en in **Databasebeheer**, selecteer **Aangepaste objecten van Marketo**.

   ![](assets/image2016-1-18-9-3a8-3a14.png)

1. Selecteer het intermediaire object waaraan u het veld wilt toevoegen.

   ![](assets/image2016-1-18-9-3a10-3a29.png)

1. Klik op het tabblad **Velden** op **Nieuw veld**.

   ![](assets/image2016-1-18-9-3a31-3a43.png)

1. U moet twee koppelingsvelden maken. Maak ze een voor een. Geef eerst het veld een naam voor de leden van de databaselijst (bijvoorbeeld leadID). Voeg een optionele beschrijving toe. Selecteer het gegevenstype van de koppeling.

   ![](assets/image2016-1-18-9-3a38-3a59.png)

   >[!CAUTION]
   >
   >U kunt niet terug gaan en een Verbinding of Dedupe- Gebied creëren uitgeven of schrappen zodra het douanevoorwerp wordt goedgekeurd.

1. Selecteer het koppelingsobject in uw database, in dit geval Lead.

   ![](assets/image2016-1-18-9-3a50-3a48.png)

1. Selecteer het koppelingsveld waarmee u verbinding wilt maken, in dit geval Id.

   ![](assets/image2016-1-18-9-3a53-3a54.png)

   >[!NOTE]
   >
   >Alleen typen tekenreeksvelden worden ondersteund in het koppelingsveld.

1. Klik **Opslaan.**

   ![](assets/image2016-1-18-9-3a55-3a18.png)

1. Herhaal dit proces voor de tweede koppeling naar uw aangepaste object, in dit voorbeeld, cursusID. De naam van het Object van de Verbinding zal cursus zijn, en het Gebied van de Verbinding zal cursusID zijn. Aangezien u het aangepaste cursusobject al hebt gemaakt en goedgekeurd, zijn deze selecties beschikbaar in de vervolgkeuzemenu&#39;s.

   ![](assets/image2016-1-18-9-3a57-3a46.png)

1. Maak andere velden die u in het intermediaire object wilt gebruiken, zoals inschrijvers-id of rang.

## Aangepaste objecten gebruiken {#using-custom-objects}

De volgende stap bestaat uit het gebruik van deze aangepaste objecten in filters in slimme campagnes. Met een vele-aan-vele verhouding, kunt u veelvoudige mensen/bedrijven en veelvoudige douanevoorwerpen selecteren. In het onderstaande voorbeeld wordt iedereen in de database vermeld die aan deze criteria voldoet. Het cursusnaamveld is afkomstig van het aangepaste cursusobject en de inschrijvingskwaliteit is afkomstig van het tussenliggende object.

![](assets/image2016-1-14-15-3a57-3a59.png)

>[!MORELIKETHIS]
>
>* [Aangepaste Marketo-objectvelden toevoegen](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Een aangepast Marketo-object bewerken en verwijderen](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [Aangepaste Marketo-objecten begrijpen](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
>* [Aangepaste Marketo-objectvelden bewerken en verwijderen](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md)

