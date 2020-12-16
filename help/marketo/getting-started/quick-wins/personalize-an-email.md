---
unique-page-id: 2359422
description: Een e-mail aanpassen - Marketo Docs - Productdocumentatie
title: Een e-mail aanpassen
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---


# Een e-mail aanpassen {#personalize-an-email}

## Opdracht: Je e-mailberichten persoonlijk maken door gegevenstokens toe te voegen {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!PREREQUISITES]
>
>* [Instellen en een persoon toevoegen](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)
>* [Een e-mailschok verzenden](/help/marketo/getting-started/quick-wins/send-an-email.md)
>* [Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)


## Stap 1: Selecteer een e-mailadres dat u wilt aanpassen {#step-select-an-email-to-personalize}

1. Selecteer een van de e-mails die u in de [vorige snelle win](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md) hebt gemaakt en klik op Concept **** bewerken.

   ![](assets/one-4.png)

   >[!NOTE]
   >
   >Hiermee maakt u een kopie van de e-mail als concept. U moet het concept van de wijzigingen goedkeuren om live te gaan.

Als u geen pop-upblokkering hebt ingeschakeld, wordt de e-maileditor geopend in een nieuw tabblad/venster. Klik anders tweemaal op Concept **** bewerken.

## Stap 2: De verkoper de afzender maken {#step-make-the-salesperson-the-sender}

1. Selecteer het veld **Van** , markeer en **verwijder** de huidige naam.

   ![](assets/two-5.png)

1. Klik op het pictogram **Token** rechts van het veld **Van** .

   ![](assets/three-4.png)

1. Zoek en selecteer het **`{{lead.Lead Owner First Name}}`** token.

   ![](assets/four-3.png)

1. Typ uw bedrijfsnaam en een streepje voor de **Standaardwaarde** om ervoor te zorgen dat er iets wordt weergegeven als de voornaam van de verkoopvertegenwoordiger niet beschikbaar is. Klik op **Invoegen**.

   ![](assets/five-4.png)

1. Druk op de spatiebalk in het veld **Van** . De cursor knippert één spatie na het token dat u net hebt ingevoegd. Klik vervolgens nogmaals op het pictogram **Token** .

   ![](assets/six-4.png)

1. Zoek en selecteer het **`{{lead.Lead Owner Last Name}}`** token.

   ![](assets/seven-5.png)

1. Typ &quot;Verkoop&quot; voor de **standaardwaarde** en klik op **Invoegen**.

   ![](assets/eight-3.png)

## Stap 3: De naam van de lead toevoegen aan het e-mailbericht {#step-add-the-leads-name-to-the-email}

1. Selecteer de bovenste bewerkbare sectie, klik op het tandwielpictogram en selecteer **Bewerken**.

   ![](assets/nine-2.png)

1. Voeg een spatie na &quot;Hello&quot;toe en plaats uw curseur voor de komma, dan klik het Symbolische pictogram van het **Tussenvoegsel** .

   ![](assets/ten-4.png)

1. Zoek en selecteer het **`{{lead.First Name}}`** token.

   ![](assets/eleven-4.png)

1. Typ &quot;Vriend&quot; (of een willekeurig label dat u wilt gebruiken) in het veld **Standaardwaarde** en klik op **Invoegen**.

   ![](assets/twelve-3.png)

   >[!TIP]
   >
   >Neem altijd een standaardwaarde voor tokens op. dit zorgt ervoor dat de standaardwaarde in de e-mail wordt weergegeven als een deel van de persoonlijke gegevens ontbreekt.

1. Klik op **Opslaan**.

   ![](assets/thirteen-3.png)

1. Sluit het tabblad/venster van de e-maileditor.

   ![](assets/fourteen-3.png)

1. Selecteer onder **E-mailacties** de optie **Concept** goedkeuren.

   ![](assets/fifteen-3.png)

>[!TIP]
>
>Wilt u snel vernieuwen hoe u uzelf de e-mail kunt sturen? Zie [Een e-mailschoen](/help/marketo/getting-started/quick-wins/send-an-email.md)verzenden.

### Opdracht voltooid {#mission-complete}

Gefeliciteerd, je e-mail is gepersonaliseerd!

<br> 

[◄ Missie 6: Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[Missie 8: De verkoper waarschuwen ►](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
