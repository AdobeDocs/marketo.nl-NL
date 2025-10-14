---
unique-page-id: 11385020
description: Predictieve inhoud in e-mails inschakelen - Marketo Docs - Productdocumentatie
title: Voorspelende inhoud in e-mails inschakelen
exl-id: 7eaefee1-23e8-47ee-afff-adcf49096aa7
feature: Predictive Content
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '375'
ht-degree: 0%

---

# Voorspelende inhoud in e-mails inschakelen {#enable-predictive-content-in-emails}

Maak een of meer afbeeldingen in uw e-mailvoorspellend, waarbij u de ervaring voor elke ontvanger kunt aanpassen.

>[!NOTE]
>
>U wordt aangeraden meer dan vijf delen inhoud per categorie en per bron (e-mail, rich media, balk) in te schakelen voordat u de voorspellende inhoud gaat testen en gebruiken. Meer inhoud geeft u een beter voorspelbaar resultaat.

>[!PREREQUISITES]
>
>Voordat u voorspellende inhoud inschakelt, moet u:
>
>* **bereidt uw Predictieve Inhoud** voor
>
>   * [&#x200B; geef Voorspelende Inhoud voor E-mail &#x200B;](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md){target="_blank"} uit of
>   * [&#x200B; geef Voorspelende Inhoud voor Rijke Media &#x200B;](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md){target="_blank"} uit of
>   * [&#x200B; geef Voorspelende Inhoud voor de Bar van de Aanbeveling uit &#x200B;](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md){target="_blank"}
>
>* [&#x200B; keur een Titel voor Voorspelende Inhoud &#x200B;](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md){target="_blank"} goed

## Voorspelende inhoud toevoegen met de e-maileditor 2.0 {#adding-predictive-content-using-the-email-editor}

1. Klik op **[!UICONTROL Marketing Activities]**.

   ![](assets/one.png)

1. Selecteer uw e-mail en klik op **[!UICONTROL Edit Draft]** .

   ![](assets/two.png)

1. Klik op de afbeelding die u voorspelbaar wilt maken. Wanneer het tandwielpictogram verschijnt, klikt u erop en selecteert u **[!UICONTROL Enable ContentAI]** (ContentAI is de vroegere naam voor voorspellende inhoud).

   ![](assets/three.png)

1. Als u een of meer categorieën wilt selecteren, klikt u op de vervolgkeuzelijst **[!UICONTROL Categories]** , selecteert u of selecteert u een of meer categorieën en klikt u op **[!UICONTROL Apply]** .

   ![](assets/four.png)

   >[!NOTE]
   >
   >Het kiezen van specifieke categorieën of het wijzigen van de voorspellende lay-out is optioneel.

1. Uw beeld is nu voorspelbaar. Herhaal stap 3 en 4 voor extra afbeeldingen (indien gewenst).

   ![](assets/five.png)

1. Klik op **[!UICONTROL Preview]** in de rechterbovenhoek om een voorbeeld van uw e-mail weer te geven.

   ![](assets/six.png)

1. Klik op **[!UICONTROL Refresh]** als u andere mogelijke afbeeldingen wilt weergeven.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >Het beeld wordt niet geselecteerd **_tot de ontvanger e-mail_** opent. Wat u in de voorvertoning ziet, is slechts een voorbeeld en hoeft niet noodzakelijkerwijs de afbeelding te zijn die de ontvanger ziet.

1. Als u klaar bent met het voorvertonen van uw e-mail, klikt u op de vervolgkeuzelijst **[!UICONTROL Preview Actions]** en selecteert u **[!UICONTROL Approve and Close]** . Als u nog steeds bewerkingen moet uitvoeren, klikt u op **[!UICONTROL Edit Draft]** aan de rechterkant.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Wanneer u een monster verzendt, wordt een willekeurige afbeelding geselecteerd.

Nadat u uw e-mail hebt goedgekeurd, wordt deze voorzien van voorspellende inhoud en kunt u deze verzenden!

>[!CAUTION]
>
>Zodra een ontvanger de e-mail opent, worden de voorspellende beelden gesloten. Als de inhoud later wordt verwijderd, zien ontvangers een verbroken afbeelding waarin de inhoud zich bevindt.

## Voorspelende inhoud toevoegen wanneer de e-maileditor 2.0 niet wordt gebruikt {#adding-predictive-content-when-not-using-the-email-editor}

Als u geen [&#x200B; E-mail 2.0 &#x200B;](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md){target="_blank"} malplaatje gebruikt, kan het toevoegen van Voorspelende Inhoud aan uw e-mail eenvoudig worden gedaan door een beeld in uw malplaatje als bewerkbaar Marketo beeldelement te etiketteren.

Leer over de [&#x200B; Marketo-Specifieke syntaxis hier &#x200B;](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements){target="_blank"}.

Hier is een voorbeeld van hoe de code eruit moet zien (dit is slechts een voorbeeld, kopieer de onderstaande code niet exact).

**Voorbeeld**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com">
<a><img style="border:10px solid red;"></a>
</div>
```
