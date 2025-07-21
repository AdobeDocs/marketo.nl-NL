---
unique-page-id: 42762825
description: Bulkhandelingen gebruiken in Salesforce Lightning - Marketo Docs - Productdocumentatie
title: Bulkhandelingen gebruiken in Salesforce Lightning
exl-id: 72022507-6568-4cc2-b3b5-c1703a1493ad
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 0%

---

# Handelingen met opsommingstekens gebruiken in [!DNL Salesforce Lightning] {#using-bulk-actions-in-salesforce-lightning}

Leer hoe u bulkacties kunt uitvoeren, zoals het toevoegen van leads aan een campagne, het verzenden van een grote e-mail of het verplaatsen van leads van [!DNL Salesforce] naar [!DNL Sales Connect] .

>[!PREREQUISITES]
>
>Update naar de nieuwste versie van het [!DNL Sales Connect] -pakket en installeer de bulkactieknoppen in de weergave voor lead/contact. [ klik hier voor instructies ](https://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf).

>[!NOTE]
>
>Controleer voordat u de onderstaande stappen uitvoert of u bent aangemeld bij uw [!DNL Marketo Sales Connect] -account.

## Bulkmail {#bulk-email}

1. Klik in [!DNL Salesforce] op de tab **[!UICONTROL Leads]** en kies vervolgens de lijst met de gewenste leads.

   ![](assets/one-6.png)

   >[!NOTE]
   >
   >Als u reeds op de lijst bent u zult gebruiken, zult u het opnieuw moeten uitvoeren door het van drop-down te kiezen om de MSC bulkactieknopen te verzekeren verschijnen. Dit is [!DNL Salesforce] gedrag dat niet kan worden gewijzigd.

1. Klik op de vervolgkeuzelijst met pijlen (uiterst rechts op het scherm) en selecteer **[!UICONTROL Email with MSC]** .

   ![](assets/two-6.png)

1. Er verschijnt een MSC-e-mailbericht. Het bevat de volgende functies:

   a. &quot;[!UICONTROL To]&quot;gebied toont &quot;Alle ontvangstbewijzen&quot; - dit beantwoordt aan de lijst van lood u in de Mening van de Lijst van de Leiding hebt gekozen\
   b. Deze lijst is zichtbaar in het linkerdeelvenster met de naam &quot;Samenstellen met opsommingstekens&quot;. U kunt hier ontvangers toevoegen of verwijderen\
   c. U kunt een sjabloon kiezen of uw eigen e-mail maken\
   d. U kunt het e-mailbericht meteen verzenden of plannen om het later te verzenden

   ![](assets/three-5.png)

## Toevoegen aan campagne {#add-to-campaign}

1. Klik in [!DNL Salesforce] op de tab **[!UICONTROL Leads]** en kies vervolgens de lijst met de gewenste leads.

   ![](assets/four-4.png)

1. Klik op de vervolgkeuzelijst met pijlen (uiterst rechts op het scherm) en selecteer **[!UICONTROL Add to MSC Campaign]** .

   ![](assets/five-4.png)

1. Er verschijnt een pop-up &quot;[!UICONTROL Add People to Your Campaign]&quot;. Klik **[!UICONTROL Next]** en ga door de typische campagnestroom om een MSC campagne teweeg te brengen.

   ![](assets/six-1.png)

## Naar [!DNL Marketo Sales Connect] duwen {#push-to-marketo-sales-connect}

1. Klik in [!DNL Salesforce] op de tab **[!UICONTROL Leads]** en kies vervolgens de lijst met de gewenste leads.

   ![](assets/seven-2.png)

1. Klik op de vervolgkeuzelijst met pijlen (uiterst rechts op het scherm) en selecteer **[!UICONTROL Push to MSC]** .

   ![](assets/eight-2.png)

1. Er wordt een nieuw tabblad met de naam &quot;[!DNL Salesforce] Bridge&quot; geopend. Klik op de knop **[!UICONTROL Proceed to Group]→** .

   ![](assets/nine-2.png)

1. U zult naar uw rekening MSC worden verzonden waar u een groep zult zien die met datum/tijdstempel wordt gecreeerd. U ontvangt een melding als de synchronisatie is voltooid en de groep de leads bevat die zijn gesynchroniseerd vanuit [!DNL Salesforce] .

   ![](assets/ten-1.png)

>[!NOTE]
>
>U kunt de zelfde stappen volgen om bulkacties in de Mening van de Lijst van het Contact eveneens te gebruiken.

>[!MORELIKETHIS]
>
>* [ verzendend E-mails via E-mail van de Groep ](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/sending-emails-via-group-email.md)
>* [ Samenstellend Bulk E-mail met Uitgezocht en verzendt ](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md#sending-emails)
