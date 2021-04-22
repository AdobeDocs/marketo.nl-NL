---
unique-page-id: 2359422
description: Een e-mail personaliseren - Marketo Docs - Productdocumentatie
title: Een e-mail aanpassen
exl-id: 1562796e-da47-4305-b950-3bed1d36d339
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---

# Een e-mail aanpassen {#personalize-an-email}

## Opdracht: Uw e-mails persoonlijk maken door gegevenstokens toe te voegen {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!PREREQUISITES]
>
>* [Instellen en een persoon toevoegen](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)
>* [Een e-mailschok verzenden](/help/marketo/getting-started/quick-wins/send-an-email.md)
>* [Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)


## Stap 1: Selecteer een e-mail om {#step-select-an-email-to-personalize} aan te passen

1. Selecteer een van de e-mails die u hebt gemaakt in de [vorige snelle win](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md) en klik op **Concept bewerken**.

   ![](assets/one-4.png)

   >[!NOTE]
   >
   >Hiermee maakt u een kopie van de e-mail als concept. U moet het concept van de wijzigingen goedkeuren om live te gaan.

Als u geen pop-upblokkering hebt ingeschakeld, wordt de e-maileditor geopend in een nieuw tabblad/venster. Klik anders tweemaal **Concept** bewerken.

## Stap 2: Van Salesperson de Afzender {#step-make-the-salesperson-the-sender} maken

1. Selecteer **Van** gebied, benadruk en **schrapping** de huidige naam.

   ![](assets/two-5.png)

1. Klik op het pictogram **Token** rechts van het veld **Van**.

   ![](assets/three-4.png)

1. Zoek en selecteer de token **`{{lead.Lead Owner First Name}}`**.

   ![](assets/four-3.png)

1. Typ uw bedrijfsnaam en een streepje voor **Standaardwaarde** om ervoor te zorgen dat er iets wordt weergegeven voor het geval de voornaam van de verkoopvertegenwoordiger niet beschikbaar is. Klik **Invoegen**.

   ![](assets/five-4.png)

1. Druk op de spatiebalk in het veld **Van** om te zorgen dat de cursor één spatie knippert na het token dat u net hebt ingevoegd. Klik vervolgens nogmaals op het pictogram **Token**.

   ![](assets/six-4.png)

1. Zoek en selecteer de token **`{{lead.Lead Owner Last Name}}`**.

   ![](assets/seven-5.png)

1. Typ &quot;Sales&quot; voor de **Standaardwaarde** en klik op **Invoegen**.

   ![](assets/eight-3.png)

## Stap 3: De naam van de lead toevoegen aan het e-mailbericht {#step-add-the-leads-name-to-the-email}

1. Selecteer de bovenste bewerkbare sectie, klik op het tandwielpictogram en selecteer **Bewerken**.

   ![](assets/nine-2.png)

1. Voeg een spatie na &quot;Hello&quot;toe en plaats uw curseur voor de komma, dan klik het **Symbolische van het Tussenvoegsel** pictogram.

   ![](assets/ten-4.png)

1. Zoek en selecteer de token **`{{lead.First Name}}`**.

   ![](assets/eleven-4.png)

1. Typ &quot;Vriend&quot; (of een willekeurig label dat u wilt) in het veld **Standaardwaarde** en klik op **Invoegen**.

   ![](assets/twelve-3.png)

   >[!TIP]
   >
   >Neem altijd een standaardwaarde voor tokens op. dit zorgt ervoor dat de standaardwaarde in de e-mail wordt weergegeven als een deel van de persoonlijke gegevens ontbreekt.

1. Klik **Opslaan**.

   ![](assets/thirteen-3.png)

1. Sluit het tabblad/venster van de e-maileditor.

   ![](assets/fourteen-3.png)

1. Selecteer **Concept** goedkeuren onder **E-mailhandelingen**.

   ![](assets/fifteen-3.png)

>[!TIP]
>
>Wilt u snel vernieuwen hoe u uzelf de e-mail kunt sturen? Zie [Een e-mailschoen verzenden](/help/marketo/getting-started/quick-wins/send-an-email.md).

### Opdracht voltooid {#mission-complete}

Gefeliciteerd, je e-mail is gepersonaliseerd!

<br> 

[◄ Missie 6: Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[Missie 8: De verkoper waarschuwen ►](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
