---
unique-page-id: 2359422
description: Een e-mail aanpassen - Marketo Docs - Productdocumentatie
title: Een e-mail aanpassen
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# Een e-mail aanpassen {#personalize-an-email}

## Opdracht: Je e-mailberichten persoonlijk maken door gegevenstokens toe te voegen {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!NOTE]
>
>**Vereisten**
>
>* [Instellen en een persoon toevoegen](get-set-up-and-add-a-person.md)
>* [Een e-mailschok verzenden](send-an-email.md)
>* [Drip, Drip, Nurture](drip-drip-nurture.md)


## Stap 1: Selecteer een e-mailadres dat u wilt aanpassen {#step-select-an-email-to-personalize}

1. Selecteer een van de e-mails die u in de [vorige snelle win](drip-drip-nurture.md) hebt gemaakt en klik op Concept **** bewerken.

   ![](assets/one-4.png)

   >[!NOTE]
   >
   >Hiermee maakt u een kopie van de e-mail als concept. U moet het concept van de wijzigingen goedkeuren om live te gaan.

   **Concept bewerken**

Als u geen pop-upblokkering hebt ingeschakeld, wordt de e-maileditor geopend in een nieuw tabblad/venster. Anders klikt u tweemaal.

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
>Wilt u snel vernieuwen hoe u uzelf de e-mail kunt sturen? Zie [Een e-mailschoen](send-an-email.md)verzenden.

### Een video bekijken {#watch-a-video}

`<iframe width="630" height="470" src="//play.vidyard.com/iRnqxMyJg6VKyuPeuxmHFb.html?v=3.1.1" frameborder="0" allowfullscreen></iframe>`

### Opdracht voltooid {#mission-complete}

Gefeliciteerd, je e-mail is gepersonaliseerd!

<br> 

[◄ Missie 6: Drip, Drip, Nurture](drip-drip-nurture.md) [Mission 8: De verkoper waarschuwen ►](alert-the-sales-rep.md)