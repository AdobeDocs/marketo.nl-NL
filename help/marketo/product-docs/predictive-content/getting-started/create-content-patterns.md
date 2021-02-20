---
unique-page-id: 11385579
description: Inhoudspatronen maken - Marketo Docs - Productdocumentatie
title: Inhoudspatronen maken
translation-type: tm+mt
source-git-commit: 06e0f5489e6375a97e2fe77834bf45fa41f23ea6
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 0%

---


# Inhoudspatronen maken {#create-content-patterns}

Wanneer u inhoudspatronen instelt, wordt de inhoud automatisch gedetecteerd wanneer een webbezoeker op de HTML-webpagina klikt die relevant is voor het inhoudspatroon. Hiermee worden HTML-pagina&#39;s (blogberichten, persberichten, nieuwsartikelen) toegevoegd als inhoudsonderdelen op de pagina Alle inhoud. Wanneer automatisch detecteren is gebaseerd op inhoudspatronen, worden HTML-pagina&#39;s gedetecteerd en bijgehouden die verwant zijn aan het gedefinieerde URL-patroon wanneer een webbezoeker een koppeling naar de pagina weergeeft of klikt. Dit inhoudsonderdeel (de URL, de paginanaam en de metagegevens inclusief de URL en beschrijving van de afbeelding) wordt toegevoegd aan de pagina Alle inhoud om voorspellende inhoud voor te bereiden. Voor automatische detectie van andere inhoud, zoals PDF&#39;s en ingesloten video, moet u [detectie van inhoud inschakelen](/help/marketo/product-docs/predictive-content/getting-started/enable-content-discovery.md).

1. Ga naar **Inhoudsinstellingen**.

   ![](assets/settings-dropdown-hand-2.png)

1. Klik **URL-patronen**.

   ![](assets/click-url-patterns-hand.png)

1. Klik **+** om een rij te openen waar u uw informatie kunt ingaan.

   ![](assets/content-settings-create-patterns-hand.png)

1. Voeg de URL-extensie toe van het domein waar de webpagina bestaat. Selecteer de categorie (bijvoorbeeld Blog, Artikel, Gegevensblad, Persbericht).

   ![](assets/content-settings-create-content-patterns-dm-hands.png)

   >[!NOTE]
   >
   >De punten in de drop-down lijst op het recht wijzen op de categorieën u opstelling wanneer u [categorieën ](/help/marketo/product-docs/predictive-content/getting-started/set-up-categories.md) creeerde.

1. Klik **+** om een ander pad toe te voegen.

   ![](assets/url-patterns-add2.png)

1. Voeg de extensie en de categorie voor het extra pad toe en klik op **Opslaan**.

   ![](assets/url-patterns-save.png)

## Regels voor inhoudspatroon {#content-pattern-rules}

* U kunt een jokerteken overal in een expressie gebruiken (voorbeeld: _domain.com/*_, _domain.com/*blog*_)

* We raden aan /* aan het einde van een expressie te gebruiken om de detectie van patronen voort te zetten (bijvoorbeeld: _domain.com/blog/*_ ontdekt alle berichten in de omslag van Blog)
* Inhoudspatronen zijn niet hoofdlettergevoelig (bijvoorbeeld: _domain.com/Blog/*_ ontdekt alle HTML-pagina&#39;s op _domain.com/Blog_ en _domain.com/blog_)

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
   <td><img alt="—" width="80" src="assets/image2017-3-24-10-3a38-3a46.png" data-linked-resource-id="12976559" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="11385579" title="—"></td> 
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
