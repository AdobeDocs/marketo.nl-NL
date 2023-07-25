---
unique-page-id: 42762794
description: Bulkacties gebruiken in Salesforce Classic - Marketo Docs - Productdocumentatie
title: Bulkhandelingen gebruiken in Salesforce Classic
exl-id: f676ba65-6bc9-41e5-aa70-0f10bceedab7
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 0%

---

# Bulkhandelingen gebruiken in Salesforce Classic {#using-bulk-actions-in-salesforce-classic}

Leer hoe u bulkacties kunt uitvoeren, zoals het toevoegen van leads aan een campagne, het verzenden van een grote hoeveelheid e-mail of het doorsturen van leads van Salesforce naar Sales Connect.

>[!PREREQUISITES]
>
>Update naar de nieuwste versie van het Sales Connect-pakket en installeer de bulkactieknoppen in de weergave voor lead/contact. [Klik hier voor instructies](https://s3.amazonaws.com/tout-user-store/salesforce/assets/Marketo+Sales+Engage+For+Salesforce_+Installation+and+Success+Guide.pdf).

>[!NOTE]
>
>Voordat u de beschreven stappen uitvoert, moet u zich aanmelden bij uw Marketo Sales Connect-account.

## Bulkmail {#bulk-email}

1. Klik in Salesforce op de knop **Leads** en vervolgens de **Ga** knop.

   ![](assets/one-5.png)

1. Kies de gewenste leads en klik op de knop **E-mail met MSC (Klassiek)** knop.

   ![](assets/two-5.png)

1. Er verschijnt een MSC-e-mailbericht. Het bevat de volgende functies:

   a. In het veld Aan staat &quot;Alle ontvangstbewijzen&quot;. Dit komt overeen met de lijst met leads die u hebt gekozen in de weergave Lijst met leads\
   b. Deze lijst is zichtbaar in het linkerdeelvenster met de naam &quot;Samenstellen met opsommingstekens&quot;. U kunt hier ontvangers toevoegen of verwijderen\
   c. U kunt een sjabloon kiezen of uw eigen e-mail maken\
   d. U kunt dynamische velden voorvertonen die in uw e-mail worden ingevuld\
   e. U kunt het e-mailbericht meteen verzenden of plannen om het later te verzenden

   ![](assets/three-4.png)

## Toevoegen aan campagne {#add-to-campaign}

1. Klik in Salesforce op de knop **Leads** en vervolgens de **Ga** knop.

   ![](assets/four-3.png)

1. Kies de gewenste leads en klik op de knop **Toevoegen aan MSC-campagne (klassiek)** knop.

   ![](assets/five-3.png)

1. Het pop-upvenster Personen toevoegen aan uw campagne wordt weergegeven. Klikken **Volgende** en doorloopt de typische campagnestroom om een MSC-campagne te starten.

   ![](assets/six.png)

## Push to Marketo Sales Connect {#push-to-marketo-sales-connect}

1. Klik in Salesforce op de knop **Leads** en vervolgens de **Ga** knop.

   ![](assets/seven-1.png)

1. Kies de gewenste leads en klik op de knop **Verschuiven naar MSC (klassiek)** knop.

   ![](assets/eight-1.png)

1. Er wordt een nieuw tabblad met de naam &quot;Salesforce Bridge&quot; geopend. Klik op de knop **Ga door naar groep →** knop.

   ![](assets/nine-1.png)

1. U zult naar uw rekening MSC worden verzonden waar u een groep zult zien die met datum/tijdstempel wordt gecreeerd. U ontvangt een melding als de synchronisatie is voltooid en de groep de leads bevat die zijn gesynchroniseerd via Salesforce.

   ![](assets/ten.png)

>[!NOTE]
>
>U kunt de zelfde stappen volgen om bulkacties in de Mening van de Lijst van het Contact eveneens te gebruiken.

>[!MORELIKETHIS]
>
>* [E-mailberichten verzenden via e-mail voor groep](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/sending-emails-via-group-email.md)
>* [Bulke-mails samenstellen met Selecteren en Verzenden](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md#sending-emails)
