---
description: Stap 1 van 3 - Voeg Marketo-velden toe aan Salesforce (Enterprise/Unlimited) - Marketo Docs - Productdocumentatie
title: Stap 1 van 3 - Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt)
hide: true
hidefromtoc: true
feature: Salesforce Integration
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

---

# Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt) {#step-of-add-marketo-fields-to-salesforce-enterprise-unlimited}

>[!PREREQUISITES]
>
>U moet toegang hebben tot Salesforce API&#39;s om te kunnen synchroniseren tussen Marketo Engage en Salesforce.

Marketo gebruikt een set velden om bepaalde soorten marketinggerelateerde informatie vast te leggen. Volg onderstaande instructies als je deze gegevens in Salesforce wilt bewaren.

1. Maak drie aangepaste velden in Salesforce voor de lead- en contactobjecten: Score, Acquisition Program en Acquisition Date.
1. Wijs deze douanevelden tussen lood en contacten toe zodat bij omzetting in Salesforce, de waarden overnemen.
1. U kunt desgewenst andere aanvullende velden maken (zie de tabel hieronder).

Al deze aangepaste velden zijn optioneel en zijn niet vereist voor het synchroniseren van Marketo en Salesforce. Als beste praktijken, adviseren wij dat u gebieden voor Score, het Programma van de Aankoop, en de Datum van de Aankoop creeert.

## Marketo-velden toevoegen aan Salesforce {#add-marketo-fields-to-salesforce}

Voeg drie aangepaste velden toe aan de objecten lead en contact in Salesforce die hierboven worden vermeld. Zie de tabel met beschikbare velden aan het einde van deze sectie voor meer informatie.

Voer de volgende stappen uit voor elk van de drie aangepaste velden om deze toe te voegen. Begin met score.

1. Meld u aan bij Salesforce en klik op Setup.

   SCREENSHOT

1. Zoek in de Snelle zoekopdracht naar het woord &quot;Object&quot;

   SCREENSHOT

1. Klik op Objectmanagers en zoek naar &#39;Leads&#39;

   SCREENSHOT

1. Klik op Lead onder ETIKET, en klik dan Gebieden en Verhoudingen op de linkerzijde.

   SCREENSHOT

1. Klik op de knop Nieuw op de pagina &quot;Velden en relaties&quot;

   SCREENSHOT

1. Kies het juiste veldtype (voor Score - nummer; Verwervingsprogramma - tekst; Aankoopdatum - Datum/tijd).

   SCREENSHOT

1. Klik op Volgende.

   SCREENSHOT

1. Voer het veldlabel, de lengte en de veldnaam voor het veld in, zoals in de onderstaande tabel wordt weergegeven.

   TABEL

   >[!NOTE]
   >
   >Salesforce voegt __c aan Veldnamen toe wanneer het hen gebruikt om API Namen tot stand te brengen.

   SCREENSHOT

   >[!NOTE]
   >
   >Tekst- en nummervelden vereisen een lengte, maar datum-/tijdvelden niet. Een beschrijving is optioneel.

1. Klik op Volgende.

   SCREENSHOT

1. Geef de toegangsinstellingen op en klik op Volgende:

   Alle rollen instellen op Zichtbaar en Alleen-lezen

   Schakel het selectievakje Alleen-lezen uit voor het profiel van de synchronisatiegebruiker:

   Als u een gebruiker hebt met het profiel van een systeembeheerder als synchronisatiegebruiker, schakelt u het selectievakje Alleen-lezen voor het beheerprofiel van het systeem uit (zoals hieronder wordt weergegeven)
Als u een aangepast profiel voor de synchronisatiegebruiker hebt gemaakt, schakelt u het selectievakje Alleen-lezen voor dat aangepaste profiel uit

   SCREENSHOT

1. Kies de paginalay-outs die het veld moeten weergeven.

   SCREENSHOT

1. Klik op Opslaan en nieuw om terug te gaan en elk van de andere twee aangepaste velden te maken. Klik met u op Opslaan als u klaar bent met alle drie.

   SCREENSHOT

* Zoek in Objectbeheer naar &quot;Contactpersonen&quot;. Klik op Velden en relaties.
* Voer stap 5 door 12 voor de gebieden van de Score, van de Verwervingsdatum, en van het Programma van de Verwerving op het contactvoorwerp uit, enkel zoals u voor het loodvoorwerp deed.
* U kunt de bovenstaande procedure ook gebruiken voor extra aangepaste velden uit deze tabel.

  TABEL

  >[!NOTE]
  >
  >Waarden in de velden die automatisch door Marketo worden toegewezen, zijn niet direct beschikbaar in Salesforce wanneer het nieuwe veld is gemaakt. Marketo synchroniseert de gegevens met Salesforce bij de volgende update van de record op beide systemen (een update van een van de velden die synchroon is tussen Marketo en Salesforce).

## Aangepaste velden toewijzen voor conversies {#map-custom-fields-for-conversions}

Een aangepast veld op het hoofdobject in Salesforce moet worden toegewezen aan een contactveld op het contactobject, zodat gegevens worden overgedragen wanneer een conversie plaatsvindt.

1. Klik in de rechterbovenhoek op Instellen.

   SCREENSHOT

1. Zoek in de Snelle zoekopdracht naar het woord &quot;Object&quot;

   SCREENSHOT

1. Ga naar de sectie Aangepaste velden en relaties voor lead en klik op Velden voor lead toewijzen

   SCREENSHOT

1. Klik op de vervolgkeuzelijst naast het veld dat u wilt toewijzen, onder de bijbehorende tabbladaccount, contactpersoon of opportuniteit.

   SCREENSHOT

1. Selecteer het overeenkomende aangepaste veld voor de contactpersoon.

   SCREENSHOT

1. Herhaal bovenstaande stappen voor alle andere velden die u hebt gemaakt.

1. Klik op Opslaan als u klaar bent.
