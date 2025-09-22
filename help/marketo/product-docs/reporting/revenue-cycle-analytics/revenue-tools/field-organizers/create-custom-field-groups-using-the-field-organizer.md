---
unique-page-id: 10094404
description: Aangepaste veldgroepen maken met de veldOrganizer - Marketo Docs - Productdocumentatie
title: Aangepaste veldgroepen maken met de veldOrganizer
exl-id: 0425a446-2c92-4a2a-85c4-e05c22118035
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '951'
ht-degree: 1%

---

# Aangepaste veldgroepen maken met de veldOrganizer {#create-custom-field-groups-using-the-field-organizer}

Voordat u aangepaste veldgroepen kunt inschakelen voor rapportage in het gebied Modelprestatie-analyse (Leads) van Inkoopcyclusverkenner, moet u standaard- of aangepaste velden indelen in groepen voor rapportage via de veldOrganizer in Marketo Lead Management. Dit geldt alleen voor lood- en bedrijfskenmerken.
Wanneer u een standaard- of aangepast veld selecteert in de vervolgkeuzelijst Veld in het dialoogvenster Nieuwe veldOrganizer, wijst het systeem het gegevenstype Marketo Lead Management toe dat is gekoppeld aan het veld dat u wilt groeperen met een van de drie beschikbare editors in de veldOrganizer: tekenreeks, geheel getal of datum.

| Gegevenstype voor Marketo-beheer voor leads | Gegevenstype van de veldeditor |
|---|---|
| String | String |
| E-mail | String |
| Geheel | Geheel |
| Tekst | String |
| URL | String |
| Referentie | Niet ondersteund |
| Valuta | Geheel |
| DateTime | Datum |
| Boolean | Niet ondersteund |
| Telefoonnummer | String |
| Datum | Datum |
| Float | Geheel |
| Berekend | Niet ondersteund |

In de volgende drie secties wordt beschreven hoe u een aangepaste veldgroep maakt voor een tekenreeks, geheel getal of datumtype.

## Aangepaste veldgroep maken - tekenreekseditor {#create-custom-field-group-string-editor}

1. Klik op **[!UICONTROL Lead Database]**.

   ![](assets/one.png)

1. Klik op **[!UICONTROL New]** en selecteer **[!UICONTROL New Field Organizer]** .

   ![](assets/two.png)

1. Klik op **[!UICONTROL Field]** en selecteer een standaard- of aangepast veld met een gegevenstype dat is toegewezen aan de tekenreekseditor (zie tabel in vorige sectie). [!UICONTROL Country] wordt hier gebruikt.

   ![](assets/three.png)

1. Klik op **[!UICONTROL Create]**.

   ![](assets/four.png)

   De nieuwe aangepaste groep wordt weergegeven in de databasestructuur voor leads, weergegeven als Veldnaam > Veldnaamgroep (bijvoorbeeld: Land > Landgroep).

   ![](assets/4.5.png)

1. Klik op het potloodpictogram om de naam aan te passen. U kunt bijvoorbeeld de naam &quot;Landgroep&quot; wijzigen in &quot;Continent&quot;. Typ de gewenste nieuwe naam en klik buiten het vak om deze automatisch op te slaan.

   ![](assets/five.png)

1. Door gebrek, worden alle gegevenswaarden geplaatst in &quot;[!UICONTROL Other]&quot;subgroep. Als u de gegevenswaarden wilt categoriseren, klikt u op **[!UICONTROL Add Group]** om een subgroep te maken en geeft u deze een naam.

   >[!NOTE]
   >
   >U kunt maximaal tien subgroepen toevoegen om de gegevenswaarden te categoriseren. Aan elke gemaakte subgroep wordt een id-nummer toegewezen.

   In dit voorbeeld zijn groepen gemaakt voor de meeste continenten.

   ![](assets/six.png)

   >[!NOTE]
   >
   >Als u een subgroep wilt verwijderen, klikt u op de rode X naast de naam van de subgroep. Als de groep gegevenswaarden bevat, worden de gegevenswaarden verplaatst naar de standaardgroep [!UICONTROL Other] .

1. Markeer een gegevenswaarde(n) op het canvas en sleep de gegevenswaarde(n) naar de juiste subgroep.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >Als u een gegevenswaarde uit een subgroep wilt verwijderen, wijst u de gegevenswaarde toe aan de standaardgroep Overige.

1. Gebruik de filteroptie in de linkerbovenhoek direct boven het canvas om de gegevenswaarden in een of meer subgroepen te selecteren en weer te geven. De gegevenswaarden op basis van de filterselectie worden op het canvas weergegeven.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Nadat de groepen zijn gedefinieerd, kunt u de aangepaste veldgroep voor rapportage inschakelen in het tabblad Analyse van de inkomstencyclus in Marketo Lead Management (Modelprestatie-analyse).

## Aangepaste veldgroep maken - Integer-editor {#create-custom-field-group-integer-editor}

1. Klik op **[!UICONTROL Lead Database]**.

   ![](assets/one.png)

1. Klik op **[!UICONTROL New]** en selecteer **[!UICONTROL New Field Organizer]** .

   ![](assets/two.png)

1. Klik op **[!UICONTROL Field]** en selecteer een standaard- of aangepast veld met een gegevenstype dat is toegewezen aan de tekenreekseditor (zie tabel in vorige sectie). [!UICONTROL Annual Revenue] wordt hier gebruikt.

   ![](assets/nine.png)

1. Klik op **[!UICONTROL Create]**.

   ![](assets/9.5.png)

   De nieuwe aangepaste groep wordt weergegeven in de databasestructuur voor leads, weergegeven als Veldnaam > Veldnaamgroep (bijvoorbeeld: Jaarlijkse inkomsten > Jaarlijkse inkomstengroep).

   ![](assets/9.6.png)

1. Klik op de standaardnaam van de aangepaste groep boven de editor voor gehele getallen om de naam aan te passen. U kunt bijvoorbeeld de naam &quot;Jaarlijkse inkomstengroep&quot; wijzigen in &quot;Jaarlijkse inkomsten op grootte&quot;. Klik op **[!UICONTROL Save]**.

   ![](assets/eleven.png)

   Met de editor voor gehele getallen kunt u meerdere subgroepen maken om elke subgroep op grootte te definiëren. In dit voorbeeld worden drie groepen gemaakt voor kleine, Medium- en Enterprise-bedrijven.

1. Als u de eerste groep wilt toevoegen, typt u een naam in het veld **[!UICONTROL Group Name]** (bijvoorbeeld Klein) en geeft u een maximale waarde op in het veld **[!UICONTROL Group Range]** (bijvoorbeeld: 200000). Klik op **[!UICONTROL Add Group]**.

   ![](assets/twelve.png)

   Een leeg groepsitem wordt weergegeven onder de zojuist ingevoerde groep. In het onderstaande voorbeeld ziet u een vermelding voor kleine, Medium- en Enterprise-bedrijven.

   >[!NOTE]
   >
   >U kunt maximaal tien subgroepen toevoegen om de gegevenswaarden te categoriseren. Elke ingang van de Waaier van de Groep bouwt op de vorige ingang voort. Als u de laatste ingang van de Waaier van de Groep voor de laatste douanesubgroep leeg verlaat u creeert, wordt een maximumgegevenswaarde niet geplaatst.

1. Klik op het tabblad Overzicht om uw instellingen op te slaan en te bekijken.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >Klik op de rode X naast de naam van de subgroep om een subgroep te verwijderen.

1. Controleer uw instellingen op de pagina Overzicht.

   ![](assets/13.5.png)

   >[!NOTE]
   >
   >Nadat de groepen zijn gedefinieerd, kunt u de aangepaste veldgroep voor rapportage inschakelen in het tabblad Analyse van de inkomstencyclus in Marketo Lead Management (Modelprestatie-analyse).

## Aangepaste veldgroep maken - Datumeditor {#create-custom-field-group-date-editor}

1. Klik op **[!UICONTROL Lead Database]**.

   ![](assets/one.png)

1. Klik op **[!UICONTROL New]** en selecteer **[!UICONTROL New Field Organizer]** .

   ![](assets/two.png)

1. Klik op **[!UICONTROL Field]** en selecteer een standaard- of aangepast veld met een gegevenstype dat is toegewezen aan de tekenreekseditor (zie tabel in vorige sectie). [!UICONTROL Acquisition Date] wordt hier gebruikt.

   ![](assets/fourteen.png)

1. Klik op **[!UICONTROL Create]**.

   ![](assets/14.5.png)

   De nieuwe aangepaste groep wordt weergegeven in de databasestructuur voor leads, die wordt weergegeven als Veldnaam > Veldnaamgroep (bijvoorbeeld: Verhaaldatum > Groep verwervingsdatum).

   ![](assets/14.6.png)

1. Klik op de standaardnaam van de aangepaste groep boven de datumeditor om de naam aan te passen. U kunt bijvoorbeeld de naam &quot;Groep met overnamedatum&quot; wijzigen in &quot;Categorieën overnamedatum&quot;. Klik op **[!UICONTROL Save]**.

   ![](assets/fifteen.png)

   Met de datumeditor kunt u meerdere subgroepen maken en elke subgroep op datum definiëren. In dit voorbeeld worden drie groepen gemaakt: Q1-15 Leads, Q2-15 Leads en Q3-15 Leads.

1. Als u de eerste groep wilt toevoegen, voert u een naam in het veld **[!UICONTROL Group Name]** in (bijvoorbeeld: Q1-15 leads) en voert u in het datumveld een datum in die de datum vertegenwoordigt waarop de lead is verworven op of eerder (bijvoorbeeld: 3/31/2015 voor de laatste dag van Q1-15). Klik op **[!UICONTROL Add Group]**.

   ![](assets/sixteen.png)

   >[!NOTE]
   >
   >U kunt maximaal tien subgroepen toevoegen om de gegevenswaarden te categoriseren. Elke [!UICONTROL Group Range] -vermelding is gebaseerd op de vorige vermelding. Als u de laatste [!UICONTROL Group Range] -vermelding leeg laat voor de laatste aangepaste subgroep die u maakt, wordt geen einddatumwaarde ingesteld.

   In het onderstaande voorbeeld ziet u een vermelding voor de leads van het eerste kwartaal van 2015 tot en met het derde kwartaal.

   ![](assets/16.5.png)

   En dat is het! Goed werk.
