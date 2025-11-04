---
solution: Marketo Engage
product: marketo
title: Sjabloon importeren
description: Leer hoe u uw bestaande e-mailsjablonen vanuit de klassieke editor importeert in de nieuwe e-mailversie van Designer.
level: Beginner, Intermediate
feature: Email Designer
badge: Beta
hide: true
hidefromtoc: true
source-git-commit: 3923ddfdffc21b5afd196c413bcf0ea3e2b806f5
workflow-type: tm+mt
source-wordcount: '759'
ht-degree: 0%

---

# Sjabloon importeren {#template-import}

Importeer uw bestaande e-mailsjablonen eenvoudig van de klassieke editor naar de nieuwe e-mailtoepassing, zodat uw ontwerpen behouden blijven en het maken van sjablonen sneller verloopt met vertrouwde, herbruikbare structuren. Het overzicht [&#x200B; beste praktijken &#x200B;](#best-practices) en leert over [&#x200B; beperkingen en oplossingen &#x200B;](#limitations-and-remedies).

>[!NOTE]
>
>De klassieke e-mailsjablonen zijn ontwikkeld met freestyle HTML, zodat deze importer niet altijd perfect elk onderdeel kan importeren. Controleer de geïmporteerde sjablonen om ervoor te zorgen dat alle secties bewerkbaar en correct toegewezen zijn. Als een gebied niet selecteerbaar is, ontspant het voor beste resultaten.

## Een sjabloon importeren {#import-a-template}

1. Ga naar de **Studio van het Ontwerp**.

   ![](assets/import-template-1.png)

1. Klik **E-mailMalplaatjes** en selecteer **E-mailMalplaatjes (Nieuw)**.

   ![](assets/import-template-2.png)

1. Klik **creëren Malplaatje**.

   ![](assets/import-template-3.png)

1. Ga a _Naam_ en (facultatieve) _Beschrijving_ in.

   ![](assets/import-template-4.png)

1. Klik het **lusje van de Malplaatjes van Marketo** en kies van de bestaande Malplaatjes die in de klassieke e-mailredacteur worden gecreeerd.

   ![](assets/import-template-5.png)

   >[!NOTE]
   >
   >Alleen goedgekeurde sjablonen en sjablonen die met de huidige werkruimte zijn gedeeld, kunnen worden geïmporteerd.

1. Klik **Gebruik dit malplaatje**.

   ![](assets/import-template-6.png)

1. De geïmporteerde sjabloon wordt geopend in de e-mail-Designer.

1. Controleer de componenten voor correcte omzetting en breng om het even welke gewenste aanpassingen aan gebruikend Designer. Als je tevreden bent met de template, moet je deze goedkeuren voor gebruik in e-mails.

## Fragmenten maken {#create-fragments}

Het is raadzaam fragmenten van herhaalbare secties te maken die u later kunt gebruiken.

1. Klik **...Meer** knoop bovenop en selecteer **sparen als fragment**.

   ![](assets/import-template-7.png)

1. Selecteer een component of een structuur en klik **creëren**.

   ![](assets/import-template-8.png)

1. Ga een naam (en facultatieve beschrijving) in en klik **sparen**.

   ![](assets/import-template-9.png)

## Best practices {#best-practices}

* De klassieke e-mailsjablonen zijn ontwikkeld met freestyle HTML, zodat deze importer niet altijd perfect elk onderdeel kan importeren. Controleer de geïmporteerde sjablonen om ervoor te zorgen dat alle secties bewerkbaar en correct toegewezen zijn. Als een gebied niet selecteerbaar is, ontspant het voor beste resultaten.

* Na het importeren kunt u herbruikbare secties opslaan als fragmenten en deze goedkeuren voor gebruik door e-mailauteurs. Handtekeningthema&#39;s toepassen om consistentie en naleving te behouden.

* U kunt het scripting van de Snelheid blijven gebruiken, en overwegen het opnieuw uitvoeren van oudere fragmenten gebruikend een combinatie fragmenten en voorwaardelijke inhoud voor betere flexibiliteit en controle.

## Beperkingen en rechtsmiddelen {#limitations-and-remedies}

<table><thead>
  <tr>
    <th>Beperking</th>
    <th>Reden</th>
    <th>Oplossing</th>
  </tr></thead>
<tbody>
  <tr>
    <td>De variabelen die zijn gedefinieerd in de klassieke e-maileditor zijn niet beschikbaar op e-mailniveau.</td>
    <td>De variabelen waren oorspronkelijk ontworpen om het bewerken van e-mail te vereenvoudigen toen de redacteur nog geen mogelijkheden van WYSIWYG aanbood. In de e-mail Designer kunnen gebruikers een vergelijkbare flexibiliteit bereiken via de beschikbare besturingselementen. De importer onderhoudt de structuur en onderdelen van uw bestaande sjabloon, zodat u deze efficiënt opnieuw kunt maken in de e-mail Designer.</td>
    <td>De gebruikers zouden dit in de Designer moeten kunnen bereiken. <p>
    Voor modules kunt u verschillende segmenten opslaan als fragmenten. Goedgekeurde fragmenten zijn beschikbaar voor gebruik op e-mailniveau.</td>
  </tr>
  <tr>
    <td>Als de bron-HTML geneste blokken bevat, kunnen de diepere lagen niet in de Designer worden benaderd.</td>
    <td>De e-mail-Designer biedt geen ondersteuning voor geneste opmerkingen.</td>
    <td>Hoewel de Designer het bewerken van geneste structuren niet toestaat, moet deze correct worden weergegeven. Vergeet niet de sjabloon eerst te testen.<p>
    Maak de structuur opnieuw met behulp van raster.</td>
  </tr>
  <tr>
    <td>Soms worden knoppen geïmporteerd als eenvoudige containers met tekst erin.</td>
    <td>Sommige implementatiestijlen met HTML kunnen tijdens het importeren verkeerd worden geïnterpreteerd.</td>
    <td>Maak de knop opnieuw in de Designer.</td>
  </tr>
  <tr>
    <td>De knoppen kunnen soms te groot zijn.</td>
    <td>Conflict tussen CSS van Marketo e-mail met andere elementen op laag niveau (<code>&lt;span&gt;</code>)</td>
    <td>Pas de marges en vullingen van de knop in de Designer aan.</td>
  </tr>
  <tr>
    <td>Opsommingspunten worden standaard niet ondersteund.</td>
    <td>De e-mail Designer biedt momenteel geen opsommingstekens.</td>
    <td>Overweeg opsommingstekens opnieuw te maken met alternatieve technieken.</td>
  </tr>
  <tr>
    <td>Verticale uitlijning wordt vervormd wanneer de inhoud van de container de waarde van het geldige kenmerk niet respecteert.</td>
    <td><code>valign</code> werkt niet binnen containers die in het malplaatje worden bepaald.</td>
    <td>Pas de marges en opvullingen van de knop aan in de e-mailtoepassing van de Designer.</td>
  </tr>
  <tr>
    <td>Personalization Tokens (My Tokens) op programmaniveau op sjabloonniveau kunnen worden omgezet in validatiefouten.</td>
    <td>E-mailsjablonen ondersteunen tokens op programmaniveau niet.</td>
    <td>Vervang deze door andere tokentypen in sjablonen en vervang deze door Mijn tokens in de afzonderlijke e-mails.</td>
  </tr>
  <tr>
    <td>Scheidingscomponenten kunnen niet selecteerbaar zijn.</td>
    <td>Scheidingscomponenten worden niet behandeld in de release.</td>
    <td>nvt</td>
  </tr>
  <tr>
    <td>Als de oorspronkelijke HTML een slecht gevormde structuur heeft, zullen deze waarschijnlijk worden overgenomen.</td>
    <td>Problemen met de oorspronkelijke HTML.</td>
    <td>De problemen moeten vóór de invoer worden opgelost.</td>
  </tr>
  <tr>
    <td>Voor de geïmporteerde inhoud is het gebruik van de voorvertoning van de inhoud geen betrouwbare indicator.</td>
    <td>De voorvertoningsfunctie van Designer biedt geen ondersteuning voor aangepaste HTML.</td>
    <td>Het wordt geadviseerd om uw e-mail te testen gebruikend <b> verzend proef </b> optie in het <i> Simuleer inhoud </i> scherm.</td>
  </tr>
  <tr>
    <td>Fragmenten in de oude sjabloon werken niet in de Designer-mailtoepassing.</td>
    <td>De e-mailtoepassing Designer biedt geen ondersteuning voor fragmenten.</td>
    <td>U kunt uw fragmenten opnieuw maken als fragmenten die zijn gekoppeld aan voorwaardelijke inhoud.</td>
  </tr>
</tbody></table>
