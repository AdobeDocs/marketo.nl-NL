---
unique-page-id: 11385020
description: Predictieve inhoud in e-mails inschakelen - Marketo Docs - Productdocumentatie
title: Voorspelende inhoud in e-mails inschakelen
exl-id: 7eaefee1-23e8-47ee-afff-adcf49096aa7
source-git-commit: 4b1b91a933a7a6d103fe0d44ece9ea95759edc5f
workflow-type: tm+mt
source-wordcount: '399'
ht-degree: 0%

---

# Voorspelende inhoud in e-mails inschakelen {#enable-predictive-content-in-emails}

Maak een of meer afbeeldingen in uw e-mailvoorspellend, waarbij u de ervaring voor elke ontvanger aanpast.

>[!NOTE]
>
>U wordt aangeraden meer dan vijf delen inhoud per categorie en per bron (e-mail, rich media, balk) in te schakelen voordat u de preventieve inhoud gaat testen en gebruiken. Meer inhoud geeft u een beter voorspelbaar resultaat.

>[!PREREQUISITES]
>
>Voordat u voorspellende inhoud inschakelt, moet u:
>
>* **Voorspelende inhoud voorbereiden**
   >
   >   * [Voorspelende inhoud voor e-mails bewerken](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md){target=&quot;_blank&quot;} of
   >   * [Predictieve inhoud voor rijke media bewerken](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md){target=&quot;_blank&quot;} of
   >   * [Voorspelende inhoud voor de balk met aanbevelingen bewerken](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md){target=&quot;_blank&quot;}
>
>* [Een titel voor preventieve inhoud goedkeuren](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md){target=&quot;_blank&quot;}


## Voorspelende inhoud toevoegen met de e-maileditor 2.0 {#adding-predictive-content-using-the-email-editor}

1. Klikken **Marketingactiviteiten**.

   ![](assets/one.png)

1. Selecteer uw e-mail en klik op **Concept bewerken**.

   ![](assets/two.png)

1. Klik op de afbeelding die u voorspelbaar wilt maken. Wanneer het tandwielpictogram verschijnt, klikt u erop en selecteert u **ContentAI inschakelen** (ContentAI is de vroegere naam voor voorspellende inhoud).

   ![](assets/three.png)

1. Als u een of meer categorieën wilt selecteren, klikt u op de knop **Categorieën** selecteert, selecteert of selecteert of selecteert of selecteert of klikt **Toepassen**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >Het kiezen van specifieke categorieën of het wijzigen van de voorspellende lay-out is optioneel.

1. Uw beeld is nu voorspelbaar. Herhaal stap 3 en 4 voor extra afbeeldingen (indien gewenst).

   ![](assets/five.png)

1. Klik op **Voorvertoning** in de rechterbovenhoek.

   ![](assets/six.png)

1. Klik op **Vernieuwen**.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >De afbeelding is niet geselecteerd **_totdat de ontvanger het e-mailbericht opent_**. Wat u in de voorvertoning ziet, is slechts een voorbeeld en hoeft niet noodzakelijkerwijs de afbeelding te zijn die de ontvanger ziet.

1. Klik op de knop **Handelingen voorvertonen** vervolgkeuzelijst en selecteer **Goedkeuren en Sluiten**. Als u nog steeds bewerkingen moet uitvoeren, klikt u op **Concept bewerken** rechts.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Wanneer u een monster verzendt, wordt een willekeurige afbeelding geselecteerd.

Nadat u uw e-mail hebt goedgekeurd, wordt deze voorzien van voorspellende inhoud en kunt u deze verzenden!

>[!CAUTION]
>
>Zodra een ontvanger de e-mail opent, worden de voorspellende beelden gesloten. Als de inhoud later wordt verwijderd, zien ontvangers een verbroken afbeelding waarin de inhoud zich bevindt.

## Voorspelende inhoud toevoegen wanneer de e-maileditor 2.0 niet wordt gebruikt {#adding-predictive-content-when-not-using-the-email-editor}

Als u geen [E-mail 2.0](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md){target=&quot;_blank&quot;} -sjabloon: u kunt preventieve inhoud aan uw e-mail toevoegen door een afbeelding in uw sjabloon te labelen als een bewerkbaar Marketo-afbeeldingselement.

Meer informatie over de [Marketo-specifieke syntaxis hier](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements){target=&quot;_blank&quot;}.

Hier is een voorbeeld van hoe de code eruit moet zien (dit is slechts een voorbeeld, kopieer de onderstaande code niet exact).

**Voorbeeld**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com">  
<a><img style="border:10px solid red;"></a>  
</div>
```
