---
unique-page-id: 11385020
description: Predictieve inhoud in e-mails inschakelen - Marketo Docs - Productdocumentatie
title: Voorspelende inhoud in e-mails inschakelen
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
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

1. Klik **Marketingactiviteiten**.

   ![](assets/one.png)

1. Selecteer uw e-mail en klik **Concept** uitgeven.

   ![](assets/two.png)

1. Klik op de afbeelding die u voorspelbaar wilt maken. Wanneer het tandwielpictogram verschijnt, klikt u erop en selecteert u **Inhoud inschakelen`AI`** (Inhoud`AI` is de vroegere naam voor voorspellende inhoud).

   ![](assets/three.png)

1. Als u een of meer categorieën wilt selecteren, klikt u op de vervolgkeuzelijst **Categorieën**, maakt u uw selectie(s) en klikt u op **Toepassen**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >Het kiezen van specifieke categorieën of het wijzigen van de voorspellende lay-out is optioneel.

1. Uw beeld is nu voorspelbaar. Herhaal stap 3 en 4 voor extra afbeeldingen (indien gewenst).

   ![](assets/five.png)

1. Klik op **Voorvertoning** in de rechterbovenhoek om een voorbeeld van uw e-mail te bekijken.

   ![](assets/six.png)

1. Als u verschillende mogelijke afbeeldingen wilt weergeven, klikt u op **Vernieuwen**.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >De afbeelding wordt pas geselecteerd **_wanneer de ontvanger het e-mailbericht_** opent. Wat u in de voorvertoning ziet, is slechts een voorbeeld en hoeft niet noodzakelijkerwijs de afbeelding te zijn die de ontvanger ziet.

1. Als u klaar bent met het voorvertonen van uw e-mail, klikt u op de vervolgkeuzelijst **Handelingen voorvertonen** en selecteert u **Goedkeuren en Sluiten**. Of als u nog het uitgeven moet doen, klik **geef Ontwerp** op het recht uit.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Wanneer u een monster verzendt, wordt een willekeurige afbeelding geselecteerd.

Nadat u uw e-mail hebt goedgekeurd, wordt deze voorzien van voorspellende inhoud en kunt u deze verzenden!

>[!CAUTION]
>
>Zodra een ontvanger de e-mail opent, worden de voorspellende beelden gesloten. Als de inhoud later wordt verwijderd, zien ontvangers een verbroken afbeelding waarin de inhoud zich bevindt.

## Voorspelende inhoud toevoegen wanneer de E-maileditor 2.0 {#adding-predictive-content-when-not-using-the-email-editor} niet wordt gebruikt

Als u geen [E-mail 2.0](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md) malplaatje gebruikt, kan het toevoegen van Voorspelende Inhoud aan uw e-mail eenvoudig worden gedaan door een beeld in uw malplaatje als Marketo editable beeldelement te etiketteren.

Meer informatie over de [Marketo-specifieke syntaxis hier](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements).

Hier is een voorbeeld van hoe de code eruit moet zien (dit is slechts een voorbeeld, kopieer de onderstaande code niet exact).

**Voorbeeld**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com">  
<a><img style="border:10px solid red;"></a>  
</div>
```
