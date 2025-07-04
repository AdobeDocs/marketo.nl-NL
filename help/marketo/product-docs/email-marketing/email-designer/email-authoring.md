---
description: E-mailontwerp - Marketo Docs - Productdocumentatie
title: E-mailontwerp
level: Beginner, Intermediate
feature: Email Designer
exl-id: 9d9b6cf3-f907-47d4-805d-4f9c73db5a32
source-git-commit: bfa1bc900c2adc263e634a81440b77bef2976d3b
workflow-type: tm+mt
source-wordcount: '1723'
ht-degree: 0%

---

# E-mailontwerp {#email-authoring}

Leer hoe u e-mailberichten kunt maken, personaliseren en bekijken in de nieuwe Marketo Engage Email Designer.

>[!PREREQUISITES]
>
>Om tot de nieuwe e-mailontwerper toegang te hebben, moet uw Marketo Engage abonnement aan het [ Systeem van Identity Management van Adobe (IMS) ](https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview) worden gemigreerd. Als u nog niet bent geweest en u zou willen verzoeken om het wordt bespoedigd, gelieve het Team van de Rekening van Adobe (uw rekeningsmanager), of [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support) te contacteren.

## Een e-mail maken {#create-an-email}

E-mails van de e-mailontwerper kunnen alleen in de Design Studio worden gemaakt en in Slimme campagnes/Lijsten worden vermeld, of kunnen op dit moment rechtstreeks in e-mailprogramma&#39;s worden gemaakt/gebruikt.

>[!BEGINTABS]

>[!TAB  Studio van het Ontwerp ]

1. Login aan Marketo Engage via [ Adobe Experience Cloud ](https://experiencecloud.adobe.com/){target="_blank"}.

1. In Mijn Marketo, uitgezochte **Studio van het Ontwerp**.

   ![](assets/create-an-email-1.png)

1. In de boom, uitgezochte **E-mail (Nieuwe Redacteur)**.

   ![](assets/create-an-email-2.png)

1. Klik **creëren e-mail** knoop.

   ![](assets/create-an-email-3.png)

1. Voer een e-mailnaam en een onderwerpregel in. Klik **creëren**.

   ![](assets/create-an-email-4.png)

>[!TAB  E-mailprogramma ]

1. Login aan Marketo Engage via [ Adobe Experience Cloud ](https://experiencecloud.adobe.com/){target="_blank"}.

1. Uw e-mailprogramma zoeken en selecteren (of maken).

   ![](assets/create-an-email-5.png)

1. U hebt twee opties om een nieuwe e-mail te maken. Klik op de naam van uw E-mailprogramma met de rechtermuisknop aan en selecteer **Nieuwe lokale activa**, of klik **+ Nieuwe E-mail** knoop in het E-mailvakje op het dashboard. In dit voorbeeld doen we het eerste.

   ![](assets/create-an-email-6.png)

1. Selecteer **E-mail (Nieuwe Redacteur)**.

   ![](assets/create-an-email-7.png)

1. Voer een e-mailnaam en een onderwerpregel in. Klik **creëren**.

   ![](assets/create-an-email-8.png)

>[!ENDTABS]

Dat is het. Nu is het tijd om je e-mail te ontwerpen.

## Kies uw inhoudstype {#choose-your-content-type}

1. In e-mail u enkel creeerde, klik **toevoegen e-mailinhoud**.

   ![](assets/choose-your-content-type-1.png)

1. _creeer uw e-mail_ pagina laadt. U kunt uit een paar opties kiezen:

* [ Ontwerp van kras ](#design-from-scratch) gebruikend de visuele e-mailredacteur

* [ voer uw eigen HTML ](#import-html) via een HTML of zip dossier in

* [ selecteer een bestaand malplaatje ](#choose-a-template) (één van onze steekproeven of één u reeds bewaarde)

### Ontwerpen vanaf nul {#design-from-scratch}

Wanneer u helemaal niets begint in de e-maileditor, gebruikt u de onderstaande opties om uw inhoud te definiëren.

1. In _creeer uw e-mail_ pagina, uitgezocht **Ontwerp van kras**.

1. Voeg [ structuur en inhoud ](#add-structure-and-content) aan uw e-mail toe.

1. Voeg [ beelden ](#add-assets) toe.

1. [ Personaliseer ](#personalize-content) uw inhoud.

1. De verbindingen van het overzicht en [ geven het volgen ](#edit-url-tracking) uit.

### HTML importeren {#import-html}

U kunt bestaande HTML-inhoud importeren om uw e-mail te ontwerpen. De inhoud kan zijn:

* Een HTML-bestand met een ingebouwde stijlpagina

* Een zip-bestand dat een HTML-bestand, de stijlpagina (.css) en afbeeldingen bevat

>[!NOTE]
>
>Er gelden geen beperkingen voor de .zip-bestandsstructuur. Verwijzingen moeten echter relatief zijn en passen bij de boomstructuur van de ZIP-map.

1. In het Ontwerp uw malplaatjepagina, uitgezochte **Invoer HTML**.

1. Sleep en laat vallen het gewenste HTML of .zip dossier (of selecteer een dossier van uw computer) en klik **de Invoer**.

   ![](assets/authoring-import-your-html-1.png)

>[!NOTE]
>
>Wanneer de HTML-inhoud wordt geüpload, wordt de compatibiliteitsmodus gebruikt voor uw inhoud. In deze modus kunt u alleen uw tekst aanpassen, koppelingen toevoegen of elementen aan uw inhoud toevoegen.

U kunt gewenste veranderingen in de ingevoerde inhoud aanbrengen gebruikend de [ visuele e-mailredacteurshulpmiddelen ](#add-structure-and-content).

### Een sjabloon kiezen {#choose-a-template}

Er zijn twee typen sjablonen waaruit u kunt kiezen.

* **malplaatjes van de Steekproef**: Marketo Engage biedt vier uit-van-de-doos e-mailmalplaatjes aan.

* **Bewaarde malplaatjes**: Dit zijn malplaatjes u van kras gebruikend het menu van Malplaatjes creeerde, of e-mail u creeerde en verkoos om als malplaatje te bewaren.

>[!BEGINTABS]

>[!TAB  malplaatjes van de Steekproef ]

Kies een van de out-of-the-box sjablonen voor een head start op uw sjabloonontwerp voor e-mail.

1. Het tabblad Voorbeeldsjablonen is standaard geopend.

1. Selecteer de sjabloon die u wilt gebruiken.

   ![](assets/authoring-sample-templates-1.png)

1. Klik **Gebruik dit malplaatje**.

   ![](assets/authoring-sample-templates-2.png)

1. Bewerk de inhoud naar wens met de visuele ontwerper van de inhoud.

>[!TAB  Bewaarde malplaatjes ]

1. Klik het **Bewaarde malplaatjes** lusje en selecteer het gewenste malplaatje.

   ![](assets/authoring-saved-templates-1.png)

1. Klik **Gebruik dit malplaatje**.

   ![](assets/authoring-saved-templates-2.png)

1. Bewerk de inhoud naar wens met de visuele ontwerper van de inhoud.

>[!ENDTABS]

## Structuur en inhoud toevoegen {#add-structure-and-content}

1. Als u wilt beginnen met het maken of wijzigen van inhoud, sleept u een item van Structuren naar het canvas. Bewerk de instellingen in het deelvenster aan de rechterkant.

   >[!TIP]
   >
   >Selecteer de n:n kolomcomponent om het aantal kolommen van uw keus (tussen drie en 10) te bepalen. U kunt ook de breedte van elke kolom definiëren door de pijlen onder de kolom te verplaatsen.

   ![](assets/authoring-add-structure-and-content-1.png)

   >[!NOTE]
   >
   >Elke kolomgrootte mag niet kleiner zijn dan 10% van de totale breedte van de structuurcomponent. Alleen lege kolommen kunnen worden verwijderd.

1. Sleep in het gedeelte Inhoud over de gewenste items en zet deze neer in een of meer structuurcomponenten.

   ![](assets/authoring-add-structure-and-content-2.png)

1. Elke component kan worden aangepast via de tabbladen Instellingen of Stijl. Wijzig het lettertype, de tekststijl, de marge en meer.

### Fragmenten toevoegen {#add-fragments}

1. Om tot uw fragmenten toegang te hebben, selecteer het _pictogram van Fragmenten_ ( ![ pictogram van Fragmenten ](assets/icon-fragments.svg)) in de linkernavigatie.

   ![ selecteer een fragment ](assets/add-fragments-1.png){width="700" zoomable="yes"}

1. Sleep een van de fragmenten naar de tijdelijke aanduiding voor het structurele onderdeel.

De editor geeft het fragment weer binnen de sectie/het element van de e-mailstructuur. De inhoud van het fragment wordt dynamisch bijgewerkt in de structuur om te tonen hoe de inhoud in de e-mail wordt weergegeven.

>[!TIP]
>
>Als u wilt dat het fragment de volledige horizontale lay-out binnen de e-mail in beslag neemt, voegt u een 1:1-kolomstructuur toe en sleept u het fragment er vervolgens in.

Nadat de e-mail is opgeslagen, wordt deze weergegeven op het tabblad _[!UICONTROL Used By]_&#x200B;van de pagina met fragmentdetails. Fragmenten die aan een e-mailsjabloon zijn toegevoegd, kunnen niet worden bewerkt in de sjabloon. Het bronfragment definieert de inhoud.

### Assets toevoegen {#add-assets}

Voeg beelden toe die in de [ sectie van Beelden en van Dossiers ](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md){target="_blank"} van uw instantie van Marketo Engage worden opgeslagen.

>[!NOTE]
>
>U kunt alleen afbeeldingen toevoegen in de nieuwe ontwerper, momenteel geen andere bestandstypen.

1. Klik op het pictogram Asset Selector om uw afbeeldingen te openen.

   ![](assets/authoring-add-assets-1.png)

1. Sleep de gewenste afbeelding naar een structuurcomponent.

   ![](assets/authoring-add-assets-2.png)

   >[!NOTE]
   >
   >Om een bestaand beeld te vervangen, selecteer het, dan klik **selecteer een activa** in het lusje van Montages op het recht.

### Lagen, instellingen en stijlen {#layers-settings-styles}

Open de navigatieboom om tot specifieke structuren en hun kolommen/componenten voor meer korrelige het uitgeven toegang te hebben. Klik op het pictogram Navigatieboom om toegang te krijgen.

![](assets/authoring-layers-settings-styles-1.png)

In het onderstaande voorbeeld worden de stappen beschreven voor het aanpassen van de opvulling en de verticale uitlijning binnen een structuurcomponent die uit kolommen bestaat.

1. Selecteer de kolom in de structuurcomponent direct in het canvas of gebruikend de _boom van de Navigatie_ die bij de linkerzijde wordt getoond.

1. Klik in de kolomwerkbalk op het gereedschap _[!UICONTROL Select a column]_&#x200B;en kies het gereedschap dat u wilt bewerken.

   U kunt deze ook selecteren in de boomstructuur. De bewerkbare parameters voor die kolom worden weergegeven op de tabbladen _[!UICONTROL Settings]_&#x200B;en&#x200B;_[!UICONTROL Styles]_ rechts.

   ![](assets/authoring-layers-settings-styles-2.png)

1. Als u de kolomeigenschappen wilt bewerken, klikt u op de tab _[!UICONTROL Styles]_&#x200B;aan de rechterkant en wijzigt u deze naar wens:

   * Wijzig voor **[!UICONTROL Background]** de achtergrondkleur zo nodig.

     Schakel het selectievakje voor een transparante achtergrond uit. Schakel de instelling **[!UICONTROL Background image]** in om een afbeelding te gebruiken als achtergrond in plaats van als een effen kleur.

   * Voor **[!UICONTROL Alignment]**, selecteer de _Hoogste_, _Midden_, of _Onderste_ pictogram.
   * Definieer bij **[!UICONTROL Padding]** de opvulling voor alle zijden.

     Selecteer **[!UICONTROL Different padding for each side]** als u de opvulling wilt aanpassen. Klik het __ pictogram van het Slot &lbrace;om synchronisatie te breken.

   * Vouw de sectie **[!UICONTROL Advanced]** uit om inline stijlen voor de kolom te definiëren.

   ![](assets/authoring-layers-settings-styles-3.png)

1. Herhaal deze stappen zo nodig om de uitlijning en opvulling voor de andere kolommen in de component aan te passen.

1. Sla uw wijzigingen op.

### Inhoud personaliseren {#personalize-content}

Tokens werken in de nieuwe redacteur de zelfde manier zij in het oude, maar het pictogram ziet er anders uit. In het onderstaande voorbeeld wordt een voornaamtoken toegevoegd met terugvaltekst.

1. Selecteer de tekstcomponent. Plaats de curseur waar u het teken wilt verschijnen en **klikken verpersoonlijking** pictogram toevoegt.

   ![](assets/authoring-personalize-content-1.png)

1. Klik het gewenste [ symbolische type ](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"}.

   ![](assets/authoring-personalize-content-2.png)

1. Zoek het gewenste token en klik op het pictogram **...** (als u op het pictogram + klikt, wordt in plaats daarvan een token zonder terugvaltekst toegevoegd).

   ![](assets/authoring-personalize-content-3.png)

   >[!NOTE]
   >
   >De &quot;tekst van de reserve&quot;is de nieuwe redacteurstermijn voor standaardwaarde. Voorbeeld: ``{{lead.First Name:default=Friend}}`` . Het wordt aanbevolen als er geen waarde is voor de persoon in het veld dat u kiest.

1. Plaats uw reservetekst en klik **toevoegen**.

   ![](assets/authoring-personalize-content-4.png)

1. Klik **sparen**.

### URL-tracking bewerken {#edit-url-tracking}

Soms wilt u de URL voor het bijhouden van Marketo niet inschakelen voor een koppeling in een e-mailbericht. Dit is handig wanneer de doelpagina geen URL-parameters ondersteunt en een verbroken koppeling tot gevolg kan hebben.

1. Klik op het pictogram Koppelingen om alle URL&#39;s in uw e-mail weer te geven.

   ![](assets/authoring-edit-url-tracking-1.png)

1. Klik op het potloodpictogram om de tekstspatiëring voor de gewenste koppelingen te bewerken.

1. Klik het **Volgen Type** drop-down en maak uw selectie.

   ![](assets/authoring-edit-url-tracking-2.png)

   <table><tbody>
     <tr>
       <td><b>Track zonder mkt_tok</b></td>
       <td>Activeert het volgen op URL zonder het gebruik van de parameter van het mkt_tok vraagkoord in bestemmingsURL</td>
     </tr>
     <tr>
       <td><b>Bijhouden met mkt_tok</b></td>
       <td>Activeert het volgen op URL met gebruik van de markt_tok parameter van het vraagkoord in bestemmingsURL</td>
     </tr>
     <tr>
       <td><b>Niet bijhouden</b></td>
       <td>Hiermee wordt het bijhouden van de URL uitgeschakeld</td>
     </tr>
   </tbody>
   </table>

1. U kunt desgewenst een label aan de URL geven of tags toevoegen.

1. Klik **sparen** wanneer gedaan.

## Waarschuwingen controleren {#check-alerts}

Terwijl u de inhoud ontwerpt, worden waarschuwingen rechtsboven op het scherm weergegeven wanneer er geen toetseninstellingen aanwezig zijn.

Er zijn twee typen waarschuwingen:

**Waarschuwingen**

De waarschuwingen verwijzen naar aanbevelingen en beste praktijken zoals:

* **de opt-out verbinding is niet aanwezig in het e-maillichaam**: Terwijl unsubscribe verbindingen een vereiste zijn, is het toevoegen van hen aan het lichaam van uw e-mail een beste praktijk.

>[!NOTE]
>
>Het toevoegen van een unsubscribe optie wordt niet vereist voor [ Operationele E-mail ](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md) (niet-marketing).

* **de versie van de Tekst van HTML is leeg**: U moet een tekstversie van uw e-maillichaam bepalen voor wanneer de inhoud van HTML niet kan worden getoond.

* **Lege verbinding is aanwezig in e-maillichaam**: Verifieer alle verbindingen in uw e-mail correct zijn.

* **e-mailgrootte heeft de grens van 100KB** overschreden: Voor optimale levering, zorg ervoor de grootte van uw e-mail niet 100KB overschrijdt.

**Fouten**

Fouten verhinderen dat u de e-mail verzendt of test totdat deze is opgelost:

* **Onderwerpregel mist**: Een e-mailonderwerpregel wordt vereist.

* **E-mailversie van het bericht is leeg**: Deze fout komt voor wanneer de e-mailinhoud niet is gevormd.

## Uw e-mail testen {#test-your-email}

Wanneer de inhoud van uw bericht is gedefinieerd, kunt u testprofielen gebruiken om deze voor te vertonen, proefdrukken te verzenden en om te bepalen hoe deze wordt weergegeven in populaire desktops, mobiele clients en webclients. Als u gepersonaliseerde inhoud opnam, kunt u controleren hoe het in het bericht wordt getoond gebruikend de gegevens van het testprofiel.

Om uw e-mailinhoud voor te vertonen, klik **inhoud** simuleren, dan voeg een testprofiel toe om uw bericht te controleren gebruikend de gegevens van het testprofiel.

![](assets/test-your-email-1.png)

## Verwijzen naar een e-mail {#reference-an-email}

E-mailberichten van Designer zijn toegankelijk via e-mail-, betrokkenheid-, standaard- en gebeurtenisprogramma&#39;s (met uitzondering van interactieve webinar-programma&#39;s). Als u uw e-mail in de Studio van het Ontwerp creeerde, kan het van Slimme Campagnes en/of Slimme Lijsten worden van verwijzingen voorzien zoals u met een andere e-mail zou doen.

* Verwijzing het in een Slimme Lijst door [ na de gebruikelijke stappen ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md).

* Verwijzing het in een Slimme Campagne door [ na de gebruikelijke stappen ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md).

>[!NOTE]
>
>Er kan alleen naar opgeslagen e-mails worden verwezen. De nieuwe e-mailontwerper heeft geen status &quot;goedgekeurd&quot;.

>[!MORELIKETHIS]
>
>[ E-mailmalplaatjes ](/help/marketo/product-docs/email-marketing/email-designer/email-template-authoring.md){target="_blank"}: Leer hoe te om, tot een e-mailmalplaatje in de nieuwe ontwerper te leiden te ontwerpen en toegang te hebben.
