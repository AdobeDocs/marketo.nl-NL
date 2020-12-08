---
unique-page-id: 11385020
description: Predictieve inhoud in e-mails inschakelen - Marketo Docs - Productdocumentatie
title: Voorspelende inhoud in e-mails inschakelen
translation-type: tm+mt
source-git-commit: 3c24395e55c756184615941327e15e050fa7d0ac
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---


# Voorspelende inhoud in e-mails inschakelen {#enable-predictive-content-in-emails}

Maak een of meer afbeeldingen in uw e-mailvoorspellend, waarbij u de ervaring voor elke ontvanger aanpast.

>[!NOTE]
>
>U wordt aangeraden meer dan vijf delen inhoud per categorie en per bron (e-mail, rich media, balk) in te schakelen voordat u de preventieve inhoud gaat testen en gebruiken. Meer inhoud geeft u een beter voorspelbaar resultaat.

>[!PREREQUISITES]
>
>Voordat u voorspellende inhoud inschakelt. u moet:
>
>* [Voorspelende inhoud voorbereiden](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md)
>* [Een titel voor preventieve inhoud goedkeuren](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md)


## Voorspelende inhoud toevoegen met de e-maileditor 2.0 {#adding-predictive-content-using-the-email-editor}

1. Klik op **Marketingactiviteiten**.

   ![](assets/one.png)

1. Selecteer uw e-mail en klik op Concept **** bewerken.

   ![](assets/two.png)

1. Klik op de afbeelding die u voorspelbaar wilt maken. Wanneer het tandwielpictogram verschijnt, klikt u erop en selecteert u Inhoud **`AI`** inschakelen (Inhoud`AI` is de vroegere naam voor Voorspelende inhoud).

   ![](assets/three.png)

1. Als u een of meer categorieën wilt selecteren, klikt u op de vervolgkeuzelijst **Categorieën** , selecteert u een of meer categorieën en klikt u op **Toepassen**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >Het kiezen van specifieke categorieën of het wijzigen van de voorspellende lay-out is optioneel.

1. Uw beeld is nu voorspelbaar. Herhaal stap 3 en 4 voor extra afbeeldingen (indien gewenst).

   ![](assets/five.png)

1. Klik op **Voorvertoning** in de rechterbovenhoek om een voorbeeld van uw e-mail weer te geven.

   ![](assets/six.png)

1. Klik op **Vernieuwen** om de verschillende mogelijke afbeeldingen weer te geven.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >De afbeelding wordt pas geselecteerd **_als de ontvanger het e-mailbericht_** opent. Wat u in de voorvertoning ziet, is slechts een voorbeeld en hoeft niet noodzakelijkerwijs de afbeelding te zijn die de ontvanger ziet.

1. Als u klaar bent met het voorvertonen van uw e-mail, klikt u op de vervolgkeuzelijst **Voorvertoning van handelingen** en selecteert u **Goedkeuren en Sluiten**. Als u nog steeds bewerkingen moet uitvoeren, klikt u rechts op Concept **** bewerken.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Wanneer u een monster verzendt, wordt een willekeurige afbeelding geselecteerd.

Nadat u uw e-mail hebt goedgekeurd, wordt deze voorzien van voorspellende inhoud en kunt u deze verzenden!

>[!CAUTION]
>
>Zodra een ontvanger de e-mail opent, worden de voorspellende beelden gesloten. Als de inhoud later wordt verwijderd, zien ontvangers een verbroken afbeelding waarin de inhoud zich bevindt.

## Voorspelende inhoud toevoegen wanneer de e-maileditor 2.0 niet wordt gebruikt {#adding-predictive-content-when-not-using-the-email-editor}

Als u geen sjabloon voor [e-mail 2.0](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md) gebruikt, kunt u preventieve inhoud aan uw e-mail toevoegen door een afbeelding in uw sjabloon te labelen als een bewerkbaar afbeeldingselement voor Marketo.

Hier [vindt u meer informatie over de syntaxis voor](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements)markeertekens.

Hier is een voorbeeld van hoe de code eruit moet zien (dit is slechts een voorbeeld, kopieer de onderstaande code niet exact).

**Voorbeeld**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="http://www.marketo.com">  
<a><img style="border:10px solid red;"></a>  
</div>
```
