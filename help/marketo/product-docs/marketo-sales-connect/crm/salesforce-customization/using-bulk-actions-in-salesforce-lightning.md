---
unique-page-id: 42762825
description: Bulkacties gebruiken in Salesforce Lightning - Marketo Docs - Productdocumentatie
title: Bulkhandelingen gebruiken in Salesforce Lightning
exl-id: 72022507-6568-4cc2-b3b5-c1703a1493ad
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '416'
ht-degree: 0%

---

# Bulkhandelingen gebruiken in Salesforce Lightning {#using-bulk-actions-in-salesforce-lightning}

Leer hoe u bulkacties kunt uitvoeren, zoals het toevoegen van leads aan een campagne, het verzenden van een grote hoeveelheid e-mail of het doorsturen van leads van Salesforce naar Sales Connect.

>[!PREREQUISITES]
>
>Update naar de nieuwste versie van het Sales Connect-pakket en installeer de bulkactieknoppen in de weergave voor lead/contact. [Klik hier voor instructies](https://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf).

>[!NOTE]
>
>Controleer voordat u de onderstaande stappen uitvoert of u bent aangemeld bij uw Marketo Sales Connect-account.

## Bulkmail {#bulk-email}

1. Klik in Salesforce op de knop **Leads** en kiest u vervolgens de lijst met de gewenste leads.

   ![](assets/one-6.png)

   >[!NOTE]
   >
   >Als u reeds op de lijst bent u zult gebruiken, zult u het opnieuw moeten uitvoeren door het van drop-down te kiezen om de MSC bulkactieknopen te verzekeren verschijnen. Dit is Salesforce-gedrag dat niet kan worden gewijzigd.

1. Klik op de pijl in de vervolgkeuzelijst (uiterst rechts op het scherm) en selecteer **E-mailen met MSC**.

   ![](assets/two-6.png)

1. Er verschijnt een MSC-e-mailbericht. Het bevat de volgende functies:

   a. In het veld Aan staat &quot;Alle ontvangstbewijzen&quot;. Dit komt overeen met de lijst met leads die u hebt gekozen in de weergave Lijst met leads\
   b. Deze lijst is zichtbaar in het linkerdeelvenster met de naam &quot;Samenstellen met opsommingstekens&quot;. U kunt hier ontvangers toevoegen of verwijderen\
   c. U kunt een sjabloon kiezen of uw eigen e-mail maken\
   d. U kunt het e-mailbericht meteen verzenden of plannen om het later te verzenden

   ![](assets/three-5.png)

## Toevoegen aan campagne {#add-to-campaign}

1. Klik in Salesforce op de knop **Leads** en kiest u vervolgens de lijst met de gewenste leads.

   ![](assets/four-4.png)

1. Klik op de pijl in de vervolgkeuzelijst (uiterst rechts op het scherm) en selecteer **Toevoegen aan MSC-campagne**.

   ![](assets/five-4.png)

1. Het pop-upvenster Personen toevoegen aan uw campagne wordt weergegeven. Klikken **Volgende** en doorloopt de typische campagnestroom om een MSC-campagne te starten.

   ![](assets/six-1.png)

## Push to Marketo Sales Connect {#push-to-marketo-sales-connect}

1. Klik in Salesforce op de knop **Leads** en kiest u vervolgens de lijst met de gewenste leads.

   ![](assets/seven-2.png)

1. Klik op de pijl in de vervolgkeuzelijst (uiterst rechts op het scherm) en selecteer **Naar MSC duwen**.

   ![](assets/eight-2.png)

1. Er wordt een nieuw tabblad met de naam &quot;Salesforce Bridge&quot; geopend. Klik op de knop **Ga door naar groep →** knop.

   ![](assets/nine-2.png)

1. U zult naar uw rekening MSC worden verzonden waar u een groep zult zien die met datum/tijdstempel wordt gecreeerd. U ontvangt een melding als de synchronisatie is voltooid en de groep de leads bevat die zijn gesynchroniseerd via Salesforce.

   ![](assets/ten-1.png)

>[!NOTE]
>
>U kunt de zelfde stappen volgen om bulkacties in de Mening van de Lijst van het Contact eveneens te gebruiken.

>[!MORELIKETHIS]
>
>* [E-mailberichten verzenden via e-mail voor groep](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/sending-emails-via-group-email.md)
>* [Bulke-mails samenstellen met Selecteren en Verzenden](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md#sending-emails)
