---
description: Een e-mail maken - Marketo Docs - Productdocumentatie
title: Een e-mail maken
hide: true
hidefromtoc: true
feature: Email Editor
source-git-commit: ef1cb0b67deb935b67a56076ed9ed0a14f449662
workflow-type: tm+mt
source-wordcount: '1064'
ht-degree: 0%

---

# Een e-mail maken {#create-an-email}

Hier tekst starten.

>[!IMPORTANT]
>
>Dit artikel is alleen bedoeld voor leden van de gesloten bètaversie van de Nieuwe Marketo Engage-e-maileditor. Verspreid niet.

1. Login aan Marketo Engage via [ Adobe Experience Cloud ](https://experiencecloud.adobe.com/) {target="_blank"}.

1. In Mijn Marketo, uitgezochte **Studio van het Ontwerp**.

   ![](assets/create-an-email-1.png)

1. In de boom, uitgezochte **E-mail (Nieuwe Redacteur)**.

   ![](assets/create-an-email-2.png)

1. Klik **creëren e-mail** knoop.

   ![](assets/create-an-email-3.png)

1. Voer een e-mailnaam en een onderwerpregel in. Klik **creëren**.

   ![](assets/create-an-email-4.png)

Dat is het. Nu is het tijd om je e-mail te ontwerpen.

## Kies uw inhoudstype {#choose-your-content-type}

1. Klik in het net gemaakte e-mailbericht op **+ E-mailinhoud toevoegen** .

   SCREENSHOT

1. De pagina &#39;Uw e-mailadres maken&#39; wordt geladen. U kunt uit een paar opties kiezen:

* [ Ontwerp van kras ](#design-from-scratch) gebruikend de E-mailredacteur

* [ voer uw eigen HTML ](#import-html) via een HTML of zip dossier in

* [ selecteer een bestaand malplaatje ](#choose-a-template) (één van onze steekproeven of één u reeds bewaarde)

### Ontwerpen vanaf nul {#design-from-scratch}

Wanneer u helemaal niets begint in de e-maileditor, gebruikt u de onderstaande opties om uw inhoud te definiëren.

1. In het Ontwerp uw malplaatjehomepage, uitgezochte **Ontwerp van kras**.

Voeg structuur en inhoud toe aan uw e-mail.

Voeg afbeeldingen toe.

Pas uw inhoud aan.

Koppelingen controleren en bijwerken.

### HTML importeren {#import-html}

U kunt bestaande HTML-inhoud importeren om uw e-mailsjablonen te ontwerpen. De inhoud kan zijn:

* Een HTML-bestand met een opgenomen stijlblad

* Een zip-bestand dat een HTML-bestand, de stijlpagina (.css) en afbeeldingen bevat

>[!NOTE]
>
>Er gelden geen beperkingen voor de .zip-bestandsstructuur. Verwijzingen moeten echter relatief zijn en passen bij de boomstructuur van de ZIP-map.

1. In het Ontwerp uw malplaatjepagina, uitgezochte **HTML van de Invoer**.

   SCREENSHOT

1. De belemmering en laat vallen het gewenste HTML of .zip dossier en klikt **Invoer**.

   SCREENSHOT

>[!NOTE]
>
>Wanneer de HTML-inhoud wordt geüpload, wordt de inhoud in de compatibiliteitsmodus uitgevoerd. In deze modus kunt u alleen uw tekst aanpassen, koppelingen toevoegen of elementen aan uw inhoud toevoegen.

U kunt gewenste veranderingen in de ingevoerde inhoud aanbrengen gebruikend de [ hulpmiddelen van de e-mailredacteur ](#add-structure-and-content).

### Een sjabloon kiezen {#choose-a-template}

Er zijn twee typen sjablonen waaruit u kunt kiezen.

* Voorbeeldsjablonen: Marketo Engage bevat vier e-mailsjablonen die buiten de box vallen.

* Opgeslagen sjablonen: dit zijn geheel nieuwe sjablonen die u hebt gemaakt via het menu Sjablonen of via een e-mail die u hebt gemaakt en die u als sjabloon hebt opgeslagen.

>[!BEGINTABS]

>[!TAB  malplaatjes van de Steekproef ]

Kies een van onze out-of-the-box sjablonen voor een head start in uw e-mailontwerp.

1. In Create uw e-mailpagina, uitgezochte **malplaatjes van de Steekproef**.

   SCREENSHOT

1. Selecteer de gewenste sjabloon.

   SCREENSHOT

1. Er wordt een voorbeeld weergegeven. Om uw selectie te bevestigen, klik **Gebruik dit malplaatje**.

   SCREENSHOT

>[!TAB  Bewaarde malplaatjes ]

Kies een van de eerder gemaakte sjablonen.

1. Selecteer Opgeslagen sjablonen op de pagina Uw e-mailbericht maken.

   SCREENSHOT

1. Selecteer de gewenste sjabloon.

   SCREENSHOT

1. Er wordt een voorbeeld weergegeven. Om uw selectie te bevestigen, klik **Gebruik dit malplaatje**.

   SCREENSHOT

>[!ENDTABS]

## Structuur en inhoud toevoegen {#add-structure-and-content}

1. Als u wilt beginnen met het maken of wijzigen van inhoud, sleept u een item van Structuren naar het canvas. Bewerk de instellingen in het deelvenster aan de rechterkant.

   >[!TIP]
   >
   >Selecteer de n:n kolomcomponent om het aantal kolommen van uw keus (tussen drie en 10) te bepalen. U kunt ook de breedte van elke kolom definiëren door de pijlen onder de kolom te verplaatsen.

   SCREENSHOT

   >[!NOTE]
   >
   >Elke kolomgrootte mag niet kleiner zijn dan 10% van de totale breedte van de structuurcomponent. Alleen lege kolommen kunnen worden verwijderd.

1. Sleep in het gedeelte Inhoud over de gewenste items en zet deze neer in een of meer structuurcomponenten.

   SCREENSHOT

1. Elke component kan worden aangepast via de tabbladen Instellingen of Stijl. Wijzig het lettertype, de tekststijl, de marge en meer.

SCREENSHOT

### Assets toevoegen {#add-assets}

Vanuit de elementkiezer kunt u rechtstreeks elementen selecteren die zijn opgeslagen in de Assets-bibliotheek. Dubbelklik op de map met uw elementen. Sleep en zet ze neer in een structuurcomponent.

Voeg verpersoonlijkingsgebieden in om uw inhoud van profielattributen, publiekslidmaatschappen, Contextuele attributen, en meer aan te passen.

Klik op Voorwaardelijke inhoud inschakelen om dynamische inhoud toe te voegen en de inhoud aan te passen aan de doelprofielen op basis van voorwaardelijke regels.

Klik op het tabblad Koppelingen in het linkerdeelvenster om alle URL&#39;s weer te geven van de inhoud die wordt bijgehouden. U kunt het type of label voor bijhouden wijzigen en indien nodig codes toevoegen.

Indien nodig, kunt u uw e-mail verder personaliseren door Overschakelen naar code redacteur van het geavanceerde menu te klikken. Op deze manier kunt u de broncode van de e-mail bewerken, bijvoorbeeld door tags voor bijhouden of aangepaste HTML toe te voegen.

VOORZIENING
U kunt niet terugkeren naar de visuele ontwerper voor deze e-mail na het schakelen naar de coderedacteur.

Wanneer de inhoud gereed is, klikt u op de knop Inhoud simuleren om de rendering te controleren. U kunt kiezen voor de weergave Computer of Mobiel.

Klik, indien gereed, op Opslaan





## Waarschuwingen controleren {#check-alerts}

Terwijl u de inhoud ontwerpt, worden waarschuwingen weergegeven in de interface (rechtsboven in het scherm) wanneer er geen sleutelinstellingen aanwezig zijn.

Er zijn twee typen waarschuwingen:

**Waarschuwingen**

De waarschuwingen verwijzen naar aanbevelingen en beste praktijken zoals:

* **de opt-out verbinding is niet aanwezig in het e-maillichaam**: Terwijl unsubscribe verbindingen een vereiste zijn, is het toevoegen van hen aan het lichaam van uw e-mail een beste praktijk.

>[!NOTE]
>
>Het toevoegen van een unsubscribe optie wordt niet vereist voor [ Operationele E-mail ](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md) (niet-marketing).

* **de versie van de Tekst van HTML is leeg**: U moet een tekstversie van uw e-maillichaam bepalen voor wanneer de inhoud van de HTML niet kan worden getoond.

* **Lege verbinding is aanwezig in e-maillichaam**: Verifieer alle verbindingen in uw e-mail correct zijn.

* **e-mailgrootte heeft de grens van 100KB** overschreden: Voor optimale levering, zorg ervoor de grootte van uw e-mail niet 100KB overschrijdt.

**Fouten**

Fouten verhinderen dat u de e-mail verzendt of test totdat deze is opgelost:

* **Onderwerpregel mist**: Een e-mailonderwerpregel wordt vereist.

* **E-mailversie van het bericht is leeg**: Deze fout komt voor wanneer de e-mailinhoud niet is gevormd.

## Uw e-mail testen

Wanneer de inhoud van uw bericht is gedefinieerd, kunt u testprofielen gebruiken om deze voor te vertonen, proefdrukken te verzenden en om te bepalen hoe deze wordt weergegeven in populaire desktops, mobiele clients en webclients. Als u gepersonaliseerde inhoud opnam, kunt u controleren hoe het in het bericht wordt getoond gebruikend de gegevens van het testprofiel.

Om uw e-mailinhoud voor te vertonen, klik **inhoud** simuleren, dan voeg een testprofiel toe om uw bericht te controleren gebruikend de gegevens van het testprofiel.

SCREENSHOT

## Verwijzen naar een e-mail {#reference-an-email}

Nadat u een e-mail in de nieuwe redacteur hebt gecreeerd, kunt u het in Slimme Campagnes en/of Slimme Lijsten van verwijzingen voorzien zoals u met een andere e-mail.

* Verwijzing het in een Slimme Lijst door [ na de gebruikelijke stappen ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md).

* Verwijzing het in een Slimme Campagne door [ na de gebruikelijke stappen ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md).

>[!NOTE]
>
>Er kan alleen naar opgeslagen e-mails worden verwezen. De nieuwe e-maileditor bevat geen status &quot;goedgekeurd&quot;.
