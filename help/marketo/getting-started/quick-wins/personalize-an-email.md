---
unique-page-id: 2359422
description: Een e-mail personaliseren - Marketo Docs - Productdocumentatie
title: Een e-mail aanpassen
exl-id: 1562796e-da47-4305-b950-3bed1d36d339
source-git-commit: 8aa2f3069c0168f57ac00dfc7270484a9045584c
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---

# Een e-mail aanpassen {#personalize-an-email}

## Opdracht: Je e-mailberichten persoonlijk maken door gegevenstokens toe te voegen {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!PREREQUISITES]
>
>* [Instellen en een persoon toevoegen](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target=&quot;_blank&quot;}
>* [Een e-mailschok verzenden](/help/marketo/getting-started/quick-wins/send-an-email.md){target=&quot;_blank&quot;}
>* [Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target=&quot;_blank&quot;}


## Stap 1: Selecteer een e-mailadres dat u wilt aanpassen {#step-select-an-email-to-personalize}

1. Selecteer een van de e-mails die u voor de verpleging hebt gemaakt in het dialoogvenster [vorige quick win](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target=&quot;_blank&quot;} en klik op **Concept maken**.

   ![](assets/personalize-an-email-1.png)

   >[!NOTE]
   >
   >Hiermee maakt u een kopie van de e-mail als concept. Vergeet niet het concept voor de wijzigingen goed te keuren om live te gaan.

Als u geen pop-upblokkering hebt ingeschakeld, wordt de e-maileditor geopend in een nieuw tabblad/venster. Anders klikt u op **Concept maken** twee keer.

## Stap 2: De verkoper de afzender maken {#step-make-the-salesperson-the-sender}

1. Selecteer **Van** veld, markering en **delete** de huidige naam.

   ![](assets/personalize-an-email-2.png)

1. Klik op de knop **Token** pictogram rechts van **Van** veld.

   ![](assets/personalize-an-email-3.png)

1. Zoek en selecteer de **`{{lead.Lead Owner First Name}}`** token.

   ![](assets/personalize-an-email-4.png)

1. Typ uw bedrijfsnaam en een streepje voor de **Standaardwaarde** om ervoor te zorgen dat er iets wordt weergegeven als de voornaam van de verkoopvertegenwoordiger niet beschikbaar is. Klikken **Invoegen**.

   ![](assets/personalize-an-email-5.png)

1. De spatiebalk in het dialoogvenster **Van** , zorgt u ervoor dat de cursor één spatie knippert na het token dat u zojuist hebt ingevoegd. Klik vervolgens op de knop **Token** weer.

   ![](assets/personalize-an-email-6.png)

1. Zoek en selecteer de **`{{lead.Lead Owner Last Name}}`** token.

   ![](assets/personalize-an-email-7.png)

1. Typ &quot;Verkoop&quot; voor de **Standaardwaarde** en klik op **Invoegen**.

   ![](assets/personalize-an-email-8.png)

## Stap 3: De naam van de lead toevoegen aan het e-mailbericht {#step-add-the-leads-name-to-the-email}

1. Selecteer de bovenste bewerkbare sectie, klik op het tandwielpictogram en selecteer **Bewerken**.

   ![](assets/personalize-an-email-9.png)

1. Voeg een spatie na &quot;Hello&quot;toe en plaats uw curseur voor de komma, dan klik **Token invoegen** pictogram.

   ![](assets/personalize-an-email-10.png)

1. Zoek en selecteer de **`{{lead.First Name}}`** token.

   ![](assets/personalize-an-email-11.png)

1. Voer &quot;Vriend&quot; (of elk gewenst label) in het dialoogvenster **Standaardwaarde** veld en klik op **Invoegen**.

   ![](assets/personalize-an-email-12.png)

   >[!TIP]
   >
   >Neem altijd een standaardwaarde voor tokens op. dit zorgt ervoor dat de standaardwaarde in de e-mail wordt weergegeven als een deel van de persoonlijke gegevens ontbreekt.

1. Klikken **Opslaan**.

   ![](assets/personalize-an-email-13.png)

1. Onder **E-mailhandelingen** en selecteert u **Goedkeuren en Sluiten**.

   ![](assets/personalize-an-email-14.png)

>[!TIP]
>
>Wilt u snel vernieuwen hoe u uzelf de e-mail kunt sturen? Zie [Een e-mailschok verzenden](/help/marketo/getting-started/quick-wins/send-an-email.md){target=&quot;_blank&quot;}.

### Opdracht voltooid {#mission-complete}

Gefeliciteerd, je e-mail is gepersonaliseerd!

<br> 

[◄ Missie 6: Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[Missie 8: De verkoper waarschuwen ►](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
