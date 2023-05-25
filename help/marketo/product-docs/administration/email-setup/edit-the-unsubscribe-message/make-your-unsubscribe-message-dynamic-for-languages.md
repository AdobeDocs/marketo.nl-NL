---
unique-page-id: 6848782
description: Je abonnement voor talen dynamisch maken - Marketo Docs - Productdocumentatie
title: Bericht voor opzeggen dynamisch maken voor talen
exl-id: 953a7fd8-b1f2-4f3f-b889-87d1f0471e0d
source-git-commit: 81ee349dbbe48c70b040751cae750c3684b71c78
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 1%

---

# Bericht voor opzeggen dynamisch maken voor talen {#make-your-unsubscribe-message-dynamic-for-languages}

Het standaardbericht en de koppeling voor afmelden zijn in het Engels beschikbaar. U kunt dynamische inhoud gebruiken om deze in verschillende talen weer te geven.

>[!NOTE]
>
>Dit artikel is een aanbevolen werkwijze, maar u kunt dit op andere manieren doen.

## Uw gegevens voorbereiden {#prepare-your-data}

1. [Een aangepast veld maken](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md) met de naam &quot;Voorkeurstaal&quot;. (Stel deze in uw CRM in als u wilt dat dit veld wordt gesynchroniseerd).

   >[!TIP]
   >
   >Gebruik dit veld in de toekomst wanneer u [een formulier maken](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md) om taalvoorkeur vast te leggen.

## Segmentatie maken {#create-segmentation}

1. Ga naar de **[!UICONTROL Database]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-1.png)

1. In de **[!UICONTROL New]** vervolgkeuzelijst, klikken **[!UICONTROL New Segmentation]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-2.png)

1. Geef de segmentatie een naam **[!UICONTROL Preferred Language]**. Klik op **[!UICONTROL Add Segment]**. Typ een taal.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-3.png)

   >[!NOTE]
   >
   >Het standaardsegment zal Engels zijn.

1. Blijf segmenten toevoegen totdat alle talen worden weergegeven. Klik op **[!UICONTROL Create]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-4.png)

1. Selecteer een segment.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-5.png)

1. Ga naar de **[!UICONTROL Smart List]** tab. Enter **[!UICONTROL Preferred Language]** in het zoekveld. Sleep het filter naar het canvas.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-6.png)

1. Stel de gewenste taal in.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-7.png)

1. Herhaal dit voor alle verschillende talen. Selecteer vervolgens de **[!UICONTROL Segmentation Actions]** vervolgkeuzelijst en klik op **[!UICONTROL Approve]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-8.png)

## Een fragment maken {#create-a-snippet}

1. Ga naar de **[!UICONTROL Design Studio]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-9.png)

1. In de **[!UICONTROL New]** vervolgkeuzelijst, klikken **[!UICONTROL New Snippet]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-10.png)

1. Het fragment een naam geven **Abonnement opzeggen**. Klik op **[!UICONTROL Create]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-11.png)

1. Typ uw standaard afmeldingsbericht, markeer het en klik op het hyperlinkpictogram.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-12.png)

1. Kopieer en plak deze token: `{{system.unsubscribeLink}}` in de **[!UICONTROL URL]** veld. Klik op **[!UICONTROL Insert]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-13.png)

1. Selecteren **[!UICONTROL Segment By]** in de **[!UICONTROL Segmentation]** sectie.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-14.png)

1. Van de **[!UICONTROL Segmentation]** drop-down, type in **[!UICONTROL Preferred]** en selecteert u **[!UICONTROL Preferred Language]**. Klik op **[!UICONTROL Save]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-15.png)

1. Selecteer een segment in de structuur. Klik op uw abonnement en klik vervolgens op het koppelingspictogram.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-16.png)

1. Controleer of `{{system.unsubscribeLink}}` bevindt zich nog steeds in **[!UICONTROL URL]** veld. Bewerk de **[!UICONTROL Display Text]** in overeenstemming met de taal die u hebt geselecteerd. Klik op **[!UICONTROL Apply]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-17.png)

1. Herhaal dit voor alle segmenten. Ga vervolgens terug naar de **[!UICONTROL Design Studio]** klikt u op de knop **[!UICONTROL Snippet Actions]** en klik op **[!UICONTROL Approve]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-18.png)

Geweldig. Bijna daar!

## Fragment gebruiken in een e-mail {#use-snippet-in-an-email}

1. Klik in de e-maileditor op het bewerkbare element. Klik vervolgens op het tandwielpictogram en selecteer **[!UICONTROL Replace with Snippet]**. Als u een bewerkbaar fragmentelement selecteert, klikt u op het tandwielpictogram en selecteert u **[!UICONTROL Edit]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-19.png)

1. Uw fragment zoeken en selecteren in de keuzelijst en klikken **[!UICONTROL Save]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-20.png)

1. Klik op **[!UICONTROL Back]**...

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-21.png)

1. ...dan de **[!UICONTROL Dynamic]** tab.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-22.png)

1. Klik op de verschillende talen om de fragmentwijziging te zien.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-23.png)

   >[!TIP]
   >
   >Natuurlijk kunt u de rest van uw e-mail ook voor dynamische taal bewerken. Voer dezelfde techniek uit op de pagina voor het opzeggen van het abonnement terwijl u er bent.

## Je abonnementspagina aanpassen met dynamische inhoud {#customizing-your-unsubscribe-page-with-dynamic-content}

Als u wilt dat de mensen naar een pagina komen die hun abonnement opzegt in de taal van hun voorkeur, kunt u dynamische inhoud op de landingspagina en de bevestigingspagina gebruiken.

1. Ga naar de **[!UICONTROL Design Studio]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-24.png)

1. Type in _Abonnement opzeggen_ in het zoekveld en selecteert u de gewenste pagina Abonnement opzeggen.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-25.png)

1. Klik op **[!UICONTROL Edit Draft]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-26.png)

1. Selecteren **[!UICONTROL Segment By]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-27.png)

1. Zoek de **[!UICONTROL Preferred Language]** segment. Klik op **[!UICONTROL Save]**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-28.png)

   Bewerk de inhoud voor elke bestemmingspagina, geef uw toestemming en u kunt het beste gaan!

   >[!NOTE]
   >
   >Meer informatie over [dynamische inhoud](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) en alle coole dingen die je kunt doen.
