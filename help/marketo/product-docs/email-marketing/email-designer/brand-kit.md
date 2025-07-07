---
solution: Marketo Engage
product: marketo
title: TITEL
description: Leer hoe u richtlijnen voor uw merk kunt maken en beheren.
level: Beginner, Intermediate
feature: Email Designer
hide: true
hidefromtoc: true
source-git-commit: 1bb3bfdef8a74c0f990c5e274391348c9c111f28
workflow-type: tm+mt
source-wordcount: '1178'
ht-degree: 0%

---

# Uw merken maken en beheren {#brands}

>[!AVAILABILITY]
>
>U moet met de [ gebruikersovereenkomst ](https://www.adobe.com/legal/licenses-terms/adobe-dx-gen-ai-user-guidelines.html){target="_blank"} akkoord gaan alvorens u de Medewerker AI in Adobe Marketo Engage kunt gebruiken. Neem voor meer informatie contact op met het Adobe-accountteam (uw accountmanager).

Merkrichtlijnen zijn een gedetailleerde reeks regels en normen die de visuele en verbale identiteit van een merk bepalen. Zij fungeren als referentie om een consistente merkweergave te behouden op alle marketing- en communicatieplatforms.

In [!DNL Marketo Engage] hebt u nu de optie om uw merkdetails handmatig in te voeren en in te delen of documenten met brandrichtlijnen te uploaden voor automatische informatie-extractie.

## Handelsmerken {#generative-access}

Gebruikers die het menu **[!UICONTROL Brands]** in [!DNL Adobe Marketo Engage] willen openen, moeten de machtigingen **[!UICONTROL Manage brand kit]** of **[!UICONTROL Enable AI assistant]** hebben. MEER INFORMATIE OVER KOPPELING

+++  Leer hoe u merkgerelateerde machtigingen kunt toewijzen

Voer de volgende stappen uit om machtigingen voor merken toe te wijzen:

1. In het **product van Toestemmingen**, ga naar het **lusje van Rollen** en selecteer de gewenste **Rol**.

1. Klik **uitgeven** om de toestemmingen te wijzigen.

1. Voeg het **AI Medewerker** middel toe, dan uitgezocht **merkKit** of **[!UICONTROL Enable Ai assistant]** van het drop-down menu beheert.

   **[!UICONTROL Enable Ai assistant]** geeft alleen alleen alleen-lezen toegang tot het menu **[!UICONTROL Brands]** .

   SCREENSHOT

1. Klik **sparen** om veranderingen toe te passen.

   Voor alle gebruikers die al zijn toegewezen aan deze rol, worden hun machtigingen automatisch bijgewerkt.

1. Om deze rol aan nieuwe gebruikers toe te wijzen, navigeer aan het **lusje van Gebruikers** binnen het **dashboard van Rollen** en klik **toevoegen Gebruiker**.

1. Ga de naam van de gebruiker, e-mailadres in, of kies van de lijst, dan klik **sparen**.

1. Als de gebruiker niet eerder werd gecreeerd, verwijs naar [ deze documentatie ](https://experienceleague.adobe.com/nl/docs/experience-platform/access-control/abac/permissions-ui/users).

+++

## Uw merk maken en beheren {#create-brand-kit}

Als u de richtlijn voor uw merk wilt maken en beheren, kunt u de details zelf invoeren of het document met uw merkenrichtlijnen uploaden om de informatie automatisch te laten ophalen:

1. Klik in het menu **[!UICONTROL Brands]** op **[!UICONTROL Create brand]** .

   SCREENSHOT

1. Voer een **[!UICONTROL Name]** in voor uw merk.

1. Sleep of selecteer het bestand om de richtlijnen van uw merk te uploaden en automatisch relevante merkgegevens te extraheren. Klik op **[!UICONTROL Create brand]**.

   Het uitpakken van informatie begint nu. Het kan enkele minuten duren voordat de bewerking is voltooid.

   SCREENSHOT

1. Uw standaarden voor het maken van inhoud en visuele weergave worden nu automatisch ingevuld. Blader door de verschillende tabbladen om de informatie naar wens aan te passen. [Meer informatie](#personalize)

1. Vanuit het geavanceerde menu van elke sectie of categorie kunt u automatisch verwijzingen toevoegen om relevante merkgegevens te extraheren.

   Gebruik de opties **[!UICONTROL Clear section]** of **[!UICONTROL Clear category]** om bestaande inhoud te verwijderen.

   SCREENSHOT

1. Als u de configuratie hebt voltooid, klikt u op **[!UICONTROL Save]** en vervolgens op **[!UICONTROL Publish]** om uw merkenhulplijn beschikbaar te maken in AI Assistant.

1. Klik op **[!UICONTROL Edit brand]** om wijzigingen aan te brengen in uw gepubliceerde merk.

   >[!NOTE]
   >
   >Er wordt dan een tijdelijke kopie gemaakt in de bewerkingsmodus, waarbij de live versie wordt vervangen nadat deze is gepubliceerd.

   SCREENSHOT

1. Open het geavanceerde menu op het dashboard van **[!UICONTROL Brands]** door op het pictogram LEGE om te klikken:

   * Merk weergeven
   * Bewerken
   * Dupliceren
   * Publiceren
   * Publiceren ongedaan maken
   * Verwijderen

   SCREENSHOT

De richtlijnen voor uw merk zijn nu beschikbaar in het keuzemenu **[!UICONTROL Brand]** in AI Assistant, waarmee u inhoud en elementen kunt genereren die zijn afgestemd op uw specificaties. Meer informatie over AI Assistant - LINK

SCREENSHOT

### Een standaardmerk instellen {#default-brand}

U kunt een standaardmerk aanwijzen dat automatisch moet worden toegepast bij het genereren van inhoud en het berekenen van uitlijningsscores tijdens het maken van de campagne.

Als u een standaardmerk wilt instellen, gaat u naar het **[!UICONTROL Brands]** -dashboard. Open het geavanceerde menu door op het pictogram ![](assets/do-not-localize/Smock_More_18_N.svg) te klikken en **[!UICONTROL Mark as default brand]** te selecteren.

SCREENSHOT

## Uw merk aanpassen {#personalize}

### Informatie over het merk {#about-brand}

Gebruik het tabblad **[!UICONTROL About the brand]** om de belangrijkste identiteit van uw merk vast te stellen: het doel, de persoonlijkheid, de taglijn en andere definiërende kenmerken.

1. Begin door de basisinformatie voor uw merk in te vullen in de categorie **[!UICONTROL Key details]** :

   * **[!UICONTROL Brand Kit Name]**: voer de naam van de merkkit in.

   * **[!UICONTROL When to Use]**: geef scenario&#39;s of contexten op waarop deze merkkit moet worden toegepast.

   * **[!UICONTROL Brand Name]**: voer de officiële naam van het merk in.

   * **[!UICONTROL Brand Description]**: geef een overzicht van wat dit merk vertegenwoordigt.

   * **[!UICONTROL Default Tagline]**: voeg de primaire coderegel toe die aan het merk is gekoppeld.

   SCREENSHOT

1. Geef in de categorie **[!UICONTROL Guiding principles]** uitleg over de kernrichting en filosofie van uw merk:

   * **[!UICONTROL Mission]**: Geef het doel van uw merk op.

   * **[!UICONTROL Vision]**: beschrijf uw langetermijndoel of gewenste toekomstige staat.

   * **[!UICONTROL Market Positioning]**: leg uit hoe uw merk zich op de markt bevindt.

   SCREENSHOT

1. Klik in de categorie **[!UICONTROL Core brand values]** op Pictogram toevoegen om de kernwaarden van een merk toe te voegen en de details in te vullen:

   * **[!UICONTROL Value]**: geef een naam op voor een kernmerk.

   * **[!UICONTROL Description]**: leg uit wat deze waarde aan uw merk betekent.

   * **[!UICONTROL Behaviors]**: schets de handelingen of houdingen die deze waarde in de praktijk weerspiegelen.

   * **[!UICONTROL Manifestations]**: geef voorbeelden van hoe deze waarde wordt uitgedrukt in echte branding.

   SCREENSHOT

1. Klik zo nodig op het pictogram Bewerken om een van uw kernmerkwaarden bij te werken of te verwijderen.

   SCREENSHOT

U kunt uw merk verder personaliseren of [ uw merk ](#create-brand-kit) publiceren.

### Schrijfstijl {#writing-style}

In de sectie **[!UICONTROL Writing style]** worden de standaarden voor het schrijven van inhoud beschreven, met een gedetailleerde beschrijving van de manier waarop taal, opmaak en structuur moeten worden gebruikt voor het behoud van helderheid, coherentie en consistentie in alle materialen.

+++ Beschikbare categorie en voorbeelden

<table>
  <thead>
    <tr>
      <th>Categorie</th>
      <th>Subcategorie</th>
      <th>Voorbeeld van richtlijnen</th>
      <th>Voorbeeld van uitsluitingen</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4">Normen voor het maken van inhoud</td>
      <td>Merk Messaging-standaarden</td>
      <td>Benadruk innovatie en klant-eerste overseinen.</td>
      <td>U mag de productmogelijkheden niet overbelasten.</td>
    </tr>
    <tr>
      <td>Taglinegebruik</td>
      <td>Plaats de tag onder het logo op alle digitale marketingmiddelen.</td>
      <td>Wijzig of vertaal de taglijn niet.</td>
    </tr>
    <tr>
      <td>Core Messaging</td>
      <td>Benadruk de belangrijkste voordeel verklaring-zulke als verbeterde productiviteit.</td>
      <td>Gebruik geen ongerelateerde waardevoorstellen.</td>
    </tr>
    <tr>
      <td>Naamgevingsstandaarden</td>
      <td>Gebruik eenvoudige, beschrijvende namen, zoals "ProScheduler".</td>
      <td>Gebruik geen complexe termen of speciale tekens.</td>
    </tr>
    <tr>
      <td rowspan="5">Merk Communication-stijl</td>
      <td>Merk Persoonlijke kenmerken</td>
      <td>Vriendelijk en toegankelijk.</td>
      <td>Wees geen nederlaag.</td>
    </tr>
    <tr>
      <td>Schrijfmiddelen</td>
      <td>Zorgt dat zinnen kort en ondoeltreffend blijven.</td>
      <td>Gebruik geen overdreven jargon.</td>
    </tr>
    <tr>
      <td>Situatietoon</td>
      <td>Houd een professionele toon in crisiscommunicatie.</td>
      <td>Wees niet afwijzend bij het ondersteunen van communicatie.</td>
    </tr>
    <tr>
      <td>Richtlijnen voor woordkeuze</td>
      <td>Gebruik woorden als "innovatief" en "slim".</td>
      <td>Vermijd woorden als "goedkoop" of "hack".</td>
    </tr>
    <tr>
      <td>Taalstandaarden</td>
      <td>Volg de Amerikaanse conventies in het Engels.</td>
      <td>Vermeng Brits en Amerikaans spelletje niet.</td>
    </tr>
    <tr>
      <td rowspan="3">Normen voor juridische naleving</td>
      <td>Handelsmerkstandaarden</td>
      <td>Gebruik altijd het symbool ™ of ®.</td>
      <td>Laat juridische symbolen niet weg wanneer dat nodig is.</td>
    </tr>
    <tr>
      <td>Copyrightstandaarden</td>
      <td>Inclusief copyrightkennisgevingen over marketingmaterialen.</td>
      <td>Gebruik geen inhoud van derden zonder toestemming.</td>
    </tr>
    <tr>
      <td>Disclaimingstandaarden</td>
      <td>Dislaimers leesbaar weergeven op digitale middelen.</td>
      <td>Verberg disclaimers niet in onzichtbare gebieden.</td>
    </tr>
</table>

+++

</br>

U past de **[!UICONTROL Writing Style]** als volgt aan:

1. Klik op het tabblad **[!UICONTROL Writing Style]** op DIT PICTOGRAM om een hulplijn, uitzondering of uitsluiting toe te voegen.

1. Voer uw hulplijn, uitzondering of uitsluiting in en klik op **[!UICONTROL Add]** .

   SCREENSHOT

1. Selecteer een van de hulplijnen of uitsluitingen die u wilt bijwerken of verwijderen.

1. Klik op Bewerken om het voorbeeld te bewerken of op Verwijderen om het te verwijderen.

   SCREENSHOT

U kunt uw merk verder personaliseren of [ uw merk ](#create-brand-kit) publiceren.

### Visuele inhoud {#visual-content}

In de sectie **[!UICONTROL Visual Content]** worden de standaarden voor afbeeldingen en ontwerpen gedefinieerd, waarin de specificaties worden beschreven die nodig zijn om een uniform en consistent merkgebruik te behouden.

+++ Beschikbare categorieën en voorbeelden

<table>
  <thead>
    <tr>
      <th>Categorie</th>
      <th>Voorbeeld van richtlijnen</th>
      <th>Voorbeeld van uitsluitingen</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fotostandaarden</td>
      <td>Gebruik natuurlijke belichting voor buitenschoten.</td>
      <td>Vermijd te veel bewerkte of gepixeleerde afbeeldingen.</td>
    </tr>
    <tr>
      <td>Illustratienormen</td>
      <td>Gebruik schone, minimalistische stijlen.</td>
      <td>Vermijd al te complex.</td>
    </tr>
    <tr>
      <td>Pictogramstandaarden</td>
      <td>Gebruik een consistent rastersysteem van 24 px.</td>
      <td>U kunt pictogramafmetingen niet mengen, inconsistente lijndikten gebruiken of van rasterregels afwijken.</td>
    </tr>
    <tr>
      <td>Richtlijnen voor gebruik</td>
      <td>Kies levensstijlafbeeldingen die overeenkomen met echte klanten die het product in professionele omgevingen gebruiken.</td>
      <td>Gebruik geen afbeeldingen die de toon van het merk tegenspreken of die uit de context vallen.</td>
    </tr>
</table>

+++

</br>

U past de **[!UICONTROL Visual content]** als volgt aan:

1. Klik op het tabblad **[!UICONTROL Visual content]** op LEGE om een hulplijn, uitsluiting of voorbeeld toe te voegen.

1. Voer uw hulplijn, uitsluitingsvoorbeeld of voorbeeld in en klik op **[!UICONTROL Add]** .

   SCREENSHOT

1. Als u een afbeelding met het juiste gebruik wilt toevoegen, selecteert u **[!UICONTROL Example]** en klikt u op **[!UICONTROL Select image]** . U kunt ook een afbeelding toevoegen waarin onjuist gebruik wordt getoond als uitsluitingsvoorbeeld.

   SCREENSHOT

1. Selecteer een van de hulplijnen of uitsluitingen die u wilt bijwerken of verwijderen.

1. Selecteer een van uw richtlijnen of uitsluitingen om deze bij te werken. Klik op het pictogram Verwijderen om het te verwijderen.

   SCREENSHOT

U kunt uw merk verder personaliseren of [ uw merk ](#create-brand-kit) publiceren.
