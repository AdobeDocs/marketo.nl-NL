---
unique-page-id: 11385579
description: Inhoudspatronen maken - Marketo Docs - Productdocumentatie
title: Inhoudspatronen maken
translation-type: tm+mt
source-git-commit: f28ff1acb0090892bdb92b75ef90d489db7abf20
workflow-type: tm+mt
source-wordcount: '411'
ht-degree: 0%

---


# Inhoudspatronen maken {#create-content-patterns}

>[!NOTE]
>
>Afhankelijk van de aankoopdatum kan uw abonnement op Marketo de optie Voorspelende inhoud of Inhoud`<sup>AI</sup>`markeren bevatten. Marketo schakelt de functie Content`<sup>AI</sup>` Analytics voor gebruikers die gebruikmaken van voorspellende inhoud in tot 30 april 2018. Als u deze functies na die datum wilt behouden, neemt u contact op met de manager Succes bij Marketo-klanten om te upgraden naar Marketo-inhoud`<sup>AI</sup>`.

Wanneer u inhoudspatronen instelt, wordt de inhoud automatisch gedetecteerd wanneer een webbezoeker op de HTML-webpagina klikt die relevant is voor het inhoudspatroon. Hiermee worden HTML-pagina&#39;s (blogberichten, persberichten, nieuwsartikelen) toegevoegd als inhoudsonderdelen op de pagina Alle inhoud. Wanneer automatisch detecteren is gebaseerd op inhoudspatronen, worden HTML-pagina&#39;s gedetecteerd en bijgehouden die verwant zijn aan het gedefinieerde URL-patroon wanneer een webbezoeker een koppeling naar de pagina weergeeft of klikt. Dit inhoudsonderdeel (de URL, de paginanaam en de metagegevens inclusief de URL en beschrijving van de afbeelding) wordt toegevoegd aan de pagina Alle inhoud om voorspellende inhoud voor te bereiden. Als u andere inhoud automatisch wilt detecteren, zoals PDF&#39;s en ingesloten video, moet u [detectie](enable-content-discovery.md)van inhoud inschakelen.

1. Ga naar **Inhoud-instellingen**.

   ![](assets/settings-dropdown-hand-2.png)

1. Klik op **URL-patronen**.

   ![](assets/click-url-patterns-hand.png)

1. Klik op **+ ** om een rij te openen waarin u uw gegevens kunt invoeren.

   ![](assets/content-settings-create-patterns-hand.png)

1. Voeg de URL-extensie toe van het domein waar de webpagina bestaat. Selecteer de categorie (bijvoorbeeld Blog, Artikel, Gegevensblad, Persbericht).

   ![](assets/content-settings-create-content-patterns-dm-hands.png)

   >[!NOTE]
   >
   >De items in de vervolgkeuzelijst aan de rechterkant weerspiegelen de categorieën die u hebt ingesteld toen u categorieën [](set-up-categories.md)maakte.

1. Klik op **+ ** om een ander pad toe te voegen.

   ![](assets/url-patterns-add2.png)

1. Voeg de extensie en categorie voor het extra pad toe en klik op **Opslaan**.

   ![](assets/url-patterns-save.png)

## Regels voor inhoudspatronen {#content-pattern-rules}

* U kunt een jokerteken overal in een expressie gebruiken (voorbeeld: *domain.com/**, *domain.com/*blog**)

* We raden aan /* aan het einde van een expressie te gebruiken om de detectie van patronen voort te zetten (bijvoorbeeld: *domain.com/blog/** ontdekt alle berichten in de omslag van Blog)
* Inhoudspatronen zijn niet hoofdlettergevoelig (bijvoorbeeld: *domain.com/Blog/** ontdekt alle HTML-pagina&#39;s op *domain.com/Blog* en *domain.com/blog*)

* URL-parameters worden niet gedetecteerd (dit voorkomt het detecteren van meerdere items met dezelfde URL voor inhoud, maar met verschillende parameters)

## Voorbeelden {#examples}

Voor *domain.com*:

<table> 
 <tbody> 
  <tr> 
   <th>URL-patroon</th> 
   <th>Resultaat</th> 
  </tr> 
  <tr> 
   <td>blog/*</td> 
   <td><p>Hiermee wordt alle inhoud gevonden die overeenkomt met het patroon domain.com/blog/:</p><p>domain.com/blog/5-top-tricks</p><p>domain.com/blog/2017/new-year-solutions</p><p>domain.com/Blog/3-best-recipes</p></td> 
  </tr> 
  <tr> 
   <td>artikel 2017/*</td> 
   <td><p>Hiermee wordt alle inhoud gevonden die overeenkomt met het patroon domain.com/article/2017/:</p><p>domain.com/article/2017/5-top-tricks</p></td> 
  </tr> 
  <tr> 
   <td><img alt="--" width="80" src="assets/image2017-3-24-10-3a38-3a46.png" data-linked-resource-id="12976559" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="11385579" title="--"></td> 
   <td><p>Ontdekt om het even welke URL die het woord "datasheets bevat:"</p><p>domain.com/datasheets/5-top-tricks</p><p>domain.com/blog/5-top-datasheets</p></td> 
  </tr> 
  <tr> 
   <td>persbericht</td> 
   <td><p>Er is slechts één exact overeenkomende HTML-pagina gedetecteerd:</p><p>domain.com/press-release</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> </td> 
   <td colspan="1"><p>Als de URL-expressie leeg is, wordt met het URL-patroon alleen de startpagina gedetecteerd:</p><p>domain.com</p></td> 
  </tr> 
 </tbody> 
</table>

