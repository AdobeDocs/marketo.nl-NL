---
unique-page-id: 42762794
description: Het gebruiken van Bulkacties in  [!DNL Salesforce]  Klassiek - de Documentatie van Marketo - de Documentatie van het Product
title: Het gebruiken van Bulkacties in  [!DNL Salesforce]  Klassiek
exl-id: f676ba65-6bc9-41e5-aa70-0f10bceedab7
feature: Marketo Sales Connect
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '311'
ht-degree: 0%

---

# Bulkhandelingen gebruiken in [!DNL Salesforce] Klassiek {#using-bulk-actions-in-salesforce-classic}

Leer hoe u bulkacties kunt uitvoeren, zoals het toevoegen van leads aan een campagne, het verzenden van een grote e-mail of het verplaatsen van leads van [!DNL Salesforce] naar [!DNL Sales Connect] .

>[!PREREQUISITES]
>
>Update naar de nieuwste versie van het [!DNL Sales Connect] -pakket en installeer de bulkactieknoppen in de weergave voor lead/contact. [ klik hier voor instructies ](https://s3.amazonaws.com/tout-user-store/salesforce/assets/Marketo+Sales+Engage+For+Salesforce_+Installation+and+Success+Guide.pdf).

>[!NOTE]
>
>Voordat u de beschreven stappen uitvoert, moet u zich aanmelden bij uw Marketo Sales Connect-account.

## Bulkmail {#bulk-email}

1. Klik in [!DNL Salesforce] op de tab **[!UICONTROL Leads]** en vervolgens op de knop **[!UICONTROL Go]** .

   ![](assets/one-5.png)

1. Kies de gewenste leads en klik op de knop **[!UICONTROL Email with MSC (Classic)]** .

   ![](assets/two-5.png)

1. Er verschijnt een MSC-e-mailbericht. Het bevat de volgende functies:

   a. &quot;[!UICONTROL To]&quot;gebied toont &quot;[!UICONTROL All Recipients]&quot; - dit beantwoordt aan de lijst van lood u in de Mening van de Lijst van de Leiding hebt gekozen
b. Deze lijst is zichtbaar op het linkerpaneel genoemd &quot;[!UICONTROL Bulk Compose]&quot; - u kunt ontvangers hier toevoegen/verwijderen
c. U kunt een sjabloon kiezen of uw eigen e-mail maken
d. U kunt dynamische velden voorvertonen die in uw e-mail worden ingevuld
e. U kunt het e-mailbericht direct verzenden of plannen om het op een later tijdstip te verzenden

   ![](assets/three-4.png)

## Toevoegen aan campagne {#add-to-campaign}

1. Klik in [!DNL Salesforce] op de tab **[!UICONTROL Leads]** en vervolgens op de knop **[!UICONTROL Go]** .

   ![](assets/four-3.png)

1. Kies de gewenste leads en klik op de knop **[!UICONTROL Add to MSC Campaign (Classic)]** .

   ![](assets/five-3.png)

1. Er verschijnt een pop-up &quot;[!UICONTROL Add People to Your Campaign]&quot;. Klik **[!UICONTROL Next]** en ga door de typische campagnestroom om een MSC campagne teweeg te brengen.

   ![](assets/six.png)

## Push to Marketo Sales Connect {#push-to-marketo-sales-connect}

1. Klik in [!DNL Salesforce] op de tab **[!UICONTROL Leads]** en vervolgens op de knop **[!UICONTROL Go]** .

   ![](assets/seven-1.png)

1. Kies de gewenste leads en klik op de knop **[!UICONTROL Push to MSC (Classic)]** .

   ![](assets/eight-1.png)

1. Er wordt een nieuw tabblad met de naam &quot;[!UICONTROL Salesforce Bridge]&quot; geopend. Klik op **[!UICONTROL Proceed to Group →]** .

   ![](assets/nine-1.png)

1. U zult naar uw rekening MSC worden verzonden waar u een groep zult zien die met datum/tijdstempel wordt gecreeerd. U ontvangt een melding als de synchronisatie is voltooid en de groep de leads bevat die zijn gesynchroniseerd vanuit [!DNL Salesforce] .

   ![](assets/ten.png)

>[!NOTE]
>
>U kunt de zelfde stappen volgen om bulkacties in de Mening van de Lijst van het Contact eveneens te gebruiken.

>[!MORELIKETHIS]
>
>* [ verzendend E-mails via E-mail van de Groep ](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/sending-emails-via-group-email.md)
>* [ Samenstellend Bulk E-mail met Uitgezocht en verzendt ](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md#sending-emails)
