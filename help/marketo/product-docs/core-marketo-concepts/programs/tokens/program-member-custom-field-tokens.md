---
unique-page-id: 1147114
description: Aangepaste veldtokens voor programmaleden - Marketo Docs - Productdocumentatie
title: Aangepaste veldtokens voor programmaleden
exl-id: 3046dec8-b885-4b08-baa9-896bcf3594b2
feature: Tokens
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '435'
ht-degree: 0%

---

# Aangepaste veldtokens voor programmaleden {#program-member-custom-field-tokens}

## Token Support voor aangepaste velden voor programmalid {#token-support-for-program-member-custom-fields}

Op de rug van de eigenschappen van de Gebieden van de Douane van het Lid van het Programma, wordt de steun uitgebreid voor de Gebieden van de Douane van het Lid van het Programma in symbolische kaders.

De PMCF-tokens worden ondersteund onder het liddomein van de tokens-familie.

Lid Tokens worden gebruikt voor gebieden die onder het werkingsgebied van het Lid van het Programma vallen. Vanaf huidige staat, worden de Tokens van het Lid ook gebruikt om unieke waarden van geïntegreerde de dienstenpartners op te nemen. `{{member.webinar url}}` de unieke bevestiging-URL die door de serviceprovider is gegenereerd, wordt automatisch opgelost. {{member.registration code}} wordt omgezet in de registratiecode die door de dienstverlener wordt verstrekt.

>[!NOTE]
>
>* Aangepaste velden voor programmalid kunnen alleen worden gebruikt in de context van een programma.
>* Tokens voor aangepaste velden voor programmalid kunnen niet worden gebruikt in: e-mailpreheader, Datumtokens in Wachtstappen of Fragmenten.
>* De status van het programma Lid wordt niet gesteund in de Tokens van de Lidstaten.

## Aangepaste veldtokens van programmalid gebruiken in elementen {#using-program-member-custom-field-tokens-in-assets}

U kunt de Tokens van de Gebieden van het Lid van het Programma in e-mail, het Bestaan van Pagina&#39;s, SMS, dupberichten en Webhooks opnemen.

**E-mails**

1. Selecteer het gewenste e-mailbericht en klik op **Concept bewerken**.

   ![](assets/program-member-custom-field-tokens-1.png)

1. Klik op het pictogram Token invoegen.

   ![](assets/program-member-custom-field-tokens-2.png)

1. Zoek en selecteer het gewenste Token van het Gebied van het Lid van het Programma, ga een standaardwaarde in, en klik **Invoegen**.

   ![](assets/program-member-custom-field-tokens-3.png)

1. Klikken **Opslaan**.

   ![](assets/program-member-custom-field-tokens-4.png)

>[!NOTE]
>
>Vergeet niet uw e-mail goed te keuren.

**Landingspagina&#39;s**

1. Selecteer uw bestemmingspagina en klik **Concept bewerken**.

   ![](assets/program-member-custom-field-tokens-5.png)

   >[!NOTE]
   >
   >De landende paginaontwerper opent in een nieuw venster.

1. Dubbelklik op het tekstvak Rich waaraan u het token wilt toevoegen.

   ![](assets/program-member-custom-field-tokens-6.png)

1. Klik op de plaats waar de token moet komen en klik vervolgens op het pictogram Token invoegen.

   ![](assets/program-member-custom-field-tokens-7.png)

1. Zoek en selecteer het gewenste token.

   ![](assets/program-member-custom-field-tokens-8.png)

1. Voer een standaardwaarde in en klik op **Invoegen**.

   ![](assets/program-member-custom-field-tokens-9.png)

1. Klikken **Opslaan**.

   ![](assets/program-member-custom-field-tokens-10.png)

**SMS**

1. Selecteer het gewenste SMS en klik op **Concept bewerken**.

   ![](assets/program-member-custom-field-tokens-11.png)

1. Klik op de knop **`{{ Token`** knop.

   ![](assets/program-member-custom-field-tokens-12.png)

1. Zoek en selecteer de gewenste token voor het aangepaste veld voor programmalid. Voer een standaardwaarde in en klik op Invoegen.

   ![](assets/program-member-custom-field-tokens-13.png)

1. Klik op de vervolgkeuzelijst SMS-handelingen en selecteer **Goedkeuren en sluiten**.

   ![](assets/program-member-custom-field-tokens-14.png)

**Pushmeldingen**

1. Selecteer de gewenste pushmelding en klik op **Concept bewerken**.

   ![](assets/program-member-custom-field-tokens-15.png)

1. Klikken **Pushmelding**.

   ![](assets/program-member-custom-field-tokens-16.png)

1. Klik op het bericht in de editor en klik op de knop `{{` om de tokenkiezer op te halen.

   ![](assets/program-member-custom-field-tokens-17.png)

1. Zoek en selecteer de gewenste token voor het aangepaste veld voor programmalid. Voer een standaardwaarde in en klik op **Invoegen**.

   ![](assets/program-member-custom-field-tokens-18.png)

1. Klikken **Voltooien** om op te slaan en af te sluiten (of **Volgende** eerst controleren).

   ![](assets/program-member-custom-field-tokens-19.png)

>[!NOTE]
>
>Als het veld Aangepast voor programmalid voor een lid van het programma geen waarde heeft, wordt de token vervangen door de standaardwaarde als deze is opgegeven.

## Aangepaste veldtokens van programmalid gebruiken in campagnes {#using-program-member-custom-field-tokens-in-campaigns}

Aangepaste veldtokens van programmalid kunnen worden gebruikt in:

* Taak maken
* Taak maken in Microsoft
* Interesserende momenten
* Handelingen voor gegevenswaardemomloop wijzigen
* Webhaken
