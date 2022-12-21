---
unique-page-id: 11385579
description: Inhoudspatronen maken - Marketo Docs - Productdocumentatie
title: Inhoudspatronen maken
exl-id: 963529fb-1b30-486c-b97d-3ff697f91258
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 0%

---

# Inhoudspatronen maken {#create-content-patterns}

Wanneer u inhoudspatronen instelt, wordt de inhoud automatisch gedetecteerd wanneer een webbezoeker op de HTML-webpagina klikt die relevant is voor het inhoudspatroon. Hiermee worden HTML-pagina&#39;s (blogberichten, persberichten, nieuwsartikelen) toegevoegd als inhoudsonderdelen aan de pagina Alle inhoud. Wanneer automatische detectie is gebaseerd op inhoudspatronen, worden HTML-pagina&#39;s die verwant zijn aan het gedefinieerde URL-patroon, gedetecteerd en bijgehouden wanneer een webbezoeker een koppeling naar de pagina weergeeft of klikt. Dit inhoudsonderdeel (de URL, de paginanaam en de metagegevens inclusief de URL en beschrijving van de afbeelding) wordt toegevoegd aan de pagina Alle inhoud om voorspellende inhoud voor te bereiden. Voor automatische detectie van andere inhoud, zoals PDF en ingesloten video, moet u [detectie van inhoud inschakelen](/help/marketo/product-docs/predictive-content/getting-started/enable-content-discovery.md).

1. Ga naar **Inhoudsinstellingen**.

   ![](assets/settings-dropdown-hand-2.png)

1. Klikken **URL-patronen**.

   ![](assets/click-url-patterns-hand.png)

1. Klik op de knop **+** om een rij te openen waarin je je gegevens kunt invoeren.

   ![](assets/content-settings-create-patterns-hand.png)

1. Voeg de URL-extensie toe van het domein waar de webpagina bestaat. Selecteer de categorie (bijvoorbeeld Blog, Artikel, Gegevensblad, Persbericht).

   ![](assets/content-settings-create-content-patterns-dm-hands.png)

   >[!NOTE]
   >
   >De items in de vervolgkeuzelijst aan de rechterkant weerspiegelen de categorieën die u instelt wanneer u [gemaakte categorieën](/help/marketo/product-docs/predictive-content/getting-started/set-up-categories.md).

1. Klikken **+** om een ander pad toe te voegen.

   ![](assets/url-patterns-add2.png)

1. Voeg de extensie en de categorie voor het extra pad toe en klik op **Opslaan**.

   ![](assets/url-patterns-save.png)

## Regels voor inhoudspatronen {#content-pattern-rules}

* U kunt een jokerteken overal in een expressie gebruiken (voorbeeld: _domain.com/&#42;_, _domain.com/&#42;blog&#42;_)

* We raden u aan /&#42; aan het einde van een expressie om de patroondetectie voort te zetten (Voorbeeld: _domain.com/blog/&#42;_ ontdekt alle berichten in de omslag van Blog)
* Inhoudspatronen zijn niet hoofdlettergevoelig (bijvoorbeeld: _domain.com/Blog/&#42;_ ontdekt alle HTML- pagina&#39;s op _domain.com/Blog_ en _domain.com/blog_)

* URL-parameters worden niet gedetecteerd (dit voorkomt het detecteren van meerdere items met dezelfde URL voor inhoud, maar met verschillende parameters)

## Voorbeelden {#examples}

Voor _domain.com_:

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
   <td><img alt="—" width="80" src="assets/image2017-3-24-10-3a38-3a46.png" data-linked-resource-id="12976559" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="11385579" title="--"></td> 
   <td><p>Ontdekt om het even welke URL die het woord "datasheets bevat:"</p><p>domain.com/datasheets/5-top-tricks</p><p>domain.com/blog/5-top-datasheets</p></td> 
  </tr> 
  <tr> 
   <td>persbericht</td> 
   <td><p>Er wordt slechts één exact overeenkomende HTML-pagina gevonden:</p><p>domain.com/press-release</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> </td> 
   <td colspan="1"><p>Als de URL-expressie leeg is, wordt met het URL-patroon alleen de startpagina gedetecteerd:</p><p>domain.com</p></td> 
  </tr> 
 </tbody> 
</table>
