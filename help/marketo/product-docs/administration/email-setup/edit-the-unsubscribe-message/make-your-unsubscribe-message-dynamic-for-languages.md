---
unique-page-id: 6848782
description: Je abonnement voor talen dynamisch maken - Marketo Docs - Productdocumentatie
title: Bericht voor opzeggen dynamisch maken voor talen
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '548'
ht-degree: 0%

---


# Bericht voor opzeggen dynamisch maken voor talen {#make-your-unsubscribe-message-dynamic-for-languages}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

Het standaardbericht en de koppeling voor afmelden zijn in het Engels beschikbaar. U kunt dynamische inhoud gebruiken om deze in verschillende talen weer te geven.

>[!NOTE]
>
>We hebben hieronder een mooie kleine zelfstudie voor je opgezet. Het vertegenwoordigt een beste praktijk, maar dit kan andere manieren worden verwezenlijkt.

1. Uw gegevens voorbereiden
1. [Maak een aangepast](../../../../product-docs/administration/field-management/create-a-custom-field-in-marketo.md)veld met de naam &quot;Voorkeurstaal&quot;. (Stel deze in uw CRM in als u wilt dat dit veld wordt gesynchroniseerd).

   >[!TIP]
   >
   >In de toekomst kunt u dit veld gebruiken wanneer u een formulier [](../../../../product-docs/demand-generation/forms/creating-a-form/create-a-form.md) maakt om taalvoorkeur vast te leggen.

1. Segmentatie maken
1. Ga naar de **database**.
** ![](assets/db.png)

   **

1. Klik in het keuzemenu **Nieuw** op **Nieuwe segmentatie**.

   ![](assets/two.png)

1. Geef de **voorkeurstaal** voor segmentatie een naam. Klik op Segment **toevoegen**. Typ een taal.

   ![](assets/image2015-3-9-8-3a33-3a44.png)

   >[!NOTE]
   >
   >Het standaardsegment zal Engels zijn.

1. Blijf segmenten toevoegen totdat alle talen worden weergegeven. Klik op **Maken**.

   ![](assets/image2015-3-9-8-3a38-3a5.png)

1. Selecteer een segment.

   ![](assets/image2015-3-9-8-3a38-3a17.png)

1. Ga naar het tabblad **Slimme lijst** . Typ **Voorkeurstaal** in het zoekveld. Sleep het filter naar het canvas.

   ![](assets/six.png)

1. Stel de gewenste taal in.

   ![](assets/seven.png)

1. Herhaal dit voor alle verschillende talen. Selecteer vervolgens de vervolgkeuzelijst **Segmentatiehandelingen** en klik op **Goedkeuren**.

   ![](assets/image2015-3-9-8-3a39-3a36.png)

1. Een fragment maken
1. Ga naar de **Studio** van het Ontwerp.

   ![](assets/ds.png)

1. Klik in het vervolgkeuzemenu **Nieuw** op **Nieuw fragment**.

   ** ![](assets/ten.png)

   **

1. Geef het fragment een naam voor **Unsubscribe Message**. Klik op **Maken**.

   ![](assets/image2015-3-9-8-3a40-3a54.png)

1. Typ uw standaard afmeldingsbericht, markeer het en klik op het hyperlinkpictogram.

   ![](assets/image2015-3-9-8-3a41-3a47.png)

1. Kopieer en plak deze token: **`{{system.unsubscribeLink}}`** in het veld **Koppelings-URL** . Klik op **Invoegen**.

   ![](assets/image2015-3-9-8-3a43-3a17.png)

1. Selecteer **Segment door** in de sectie Segmentatie.

   ![](assets/image2015-3-9-8-3a44-3a16.png)

1. Typ in het keuzemenu Segmentatie de optie **Voorkeur** en selecteer **Voorkeurstaal**. Klik op **Opslaan**.

   ![](assets/image2015-3-9-8-3a44-3a32.png)

1. Selecteer een segment in de structuur. Typ uw afmeldingsbericht in die taal.

   ![](assets/image2015-3-9-8-3a45-3a43.png)

1. Hetzelfde token kopiëren en plakken: **`{{system.unsubscribeLink}}`** in het veld **Koppelings-URL** . Klik op **Invoegen**.

   ![](assets/image2015-3-9-8-3a47-3a4.png)

1. Herhaal dit voor alle segmenten. Dan, ga terug naar de Studio van het Ontwerp, klik de drop-down Acties **van het** Fragment, en klik **goedkeuren**.

   ![](assets/image2015-3-9-8-3a47-3a34.png)

   Geweldig. Bijna.

1. Fragment gebruiken in een e-mail
1. Klik in de e-maileditor op het bewerkbare element. Klik vervolgens op het tandwielpictogram en selecteer **Vervangen door fragment**. Als u een bewerkbaar fragmentelement selecteert, klikt u op het tandwielpictogram en selecteert u **Bewerken**.

   ![](assets/4.1.png)

1. Zoek en selecteer het fragment in de keuzelijst en klik op **Opslaan**.

   ![](assets/image2015-3-9-8-3a50-3a16.png)

1. Klik op **Vorige** om het bestand te testen...

   ![](assets/4.3.png)

1. ...dan het **Dynamische** lusje.

   ![](assets/4.4.png)

1. Klik op de verschillende talen om de fragmentwijziging te zien.

   ![](assets/4.5.png)

   >[!TIP]
   >
   >Natuurlijk kunt u de rest van uw e-mail ook voor dynamische taal bewerken. Voer dezelfde techniek uit op de pagina voor het opzeggen van het abonnement terwijl u er bent.

1. Je abonnementspagina aanpassen met dynamische inhoud

   Als u wilt dat de mensen naar een pagina komen die hun abonnement opzegt in de taal van hun voorkeur, kunt u dynamische inhoud op de landingspagina en de bevestigingspagina gebruiken.

   Navigeer naar de Design Studio.

   ![](assets/ds.png)

   Typ Afmelden in het zoekveld. Je moet je afmeldingspagina&#39;s vinden.

   ![](assets/image2015-3-9-8-3a51-3a53.png)

   Klik op Concept bewerken.

   ![](assets/image2015-3-9-8-3a52-3a23.png)

   Selecteer Segment op.

   ![](assets/image2015-3-9-8-3a52-3a57.png)

   Zoek het segment Voorkeurstaal. Klik op Opslaan.

   ![](assets/image2015-3-9-8-3a53-3a54.png)

   Bewerk de inhoud voor elke bestemmingspagina, geef uw toestemming en u kunt het beste gaan!

   >[!NOTE]
   >
   >**Diep duiken**
   >
   >
   >Meer weten over [dynamische inhoud](../../../../product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) en alles wat u kunt doen?

