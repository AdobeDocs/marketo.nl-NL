---
title: Fragmenten
description: Leer hoe u visuele inhoudsfragmenten maakt en gebruikt als herbruikbare componenten voor e-mails en e-mailsjablonen.
hide: true
hidefromtoc: true
exl-id: abc065a0-cd2f-4f0f-a5f2-228b833b99a8
source-git-commit: f6a8f9ec79240a10549adb12ca8b1b4124f683a3
workflow-type: tm+mt
source-wordcount: '2304'
ht-degree: 0%

---

# Fragmenten

Een fragment is een herbruikbare component waarnaar in een of meer e-mailsjablonen kan worden verwezen. Het is doorgaans een blok inhoud (tekst, afbeelding of beide) dat u kunt maken en snel in uw project kunt invoegen. Met deze functionaliteit kunt u meerdere aangepaste inhoudsblokken vooraf samenstellen om e-mailinhoud samen te stellen voor een verbeterd ontwerpproces. Veelvoorkomende gebruiksgevallen zijn inhoudsblokken voor kop- en voetteksten voor e-mail, uitnodigingsbanners voor gebeurtenissen, seizoensgebonden berichten en meer.

U kunt zo veel mogelijk gebruikmaken van fragmenten in uw workflows:

* _creeer fragmenten_ - creeer visuele fragmenten, of van kras of door inhoud als fragment van de visuele inhoudsredacteur op te slaan.
* _hergebruik fragmenten_ - gebruik hen zo vele tijden zoals nodig in uw inhoud.

## Visuele fragmenten {#visual-fragments}

Visuele fragmenten zijn vooraf gedefinieerde visuele blokken die zijn gemaakt (met de visuele inhoudeditor) en die u kunt hergebruiken in meerdere e-mails of e-mailsjablonen.

## Fragmenten openen en beheren {#access-and-manage-fragments}

Ga naar de Design Studio voor toegang tot visuele fragmenten. Klik in de boomstructuur links op **[!UICONTROL Fragments (New)]** .

SCREENSHOT

Standaard wordt de tabel gesorteerd op de kolom _[!UICONTROL Modified]_. Klik op andere kolomtitels om te wijzigen waarop de tabel wordt gesorteerd. Klik nogmaals om te schakelen tussen oplopend en aflopend.

### Fragmentstatus {#fragment-status}

De fragmentstatus bepaalt de beschikbaarheid voor gebruik in een e-mailsjabloon of e-mailsjabloon en de wijzigingen die u daarin kunt aanbrengen.

<table>
<tbody>
  <tr>
    <td><b>Concept</b></td>
    <td>Wanneer u een fragment maakt, bevindt het zich in de conceptstatus. Het blijft een concept totdat u het publiceert voor gebruik in een e-mail- of e-mailsjabloon.
    <p>Beschikbare acties:
    <li>Alle details bewerken</li>
    <li>Bewerken in visuele ontwerper</li>
    <li>Publish</li>
    <li>Dupliceren</li>
    <li>Verwijderen</li>
  </td>
  <tr>
    <td><b>Gepubliceerd</b></td>
    <td>Wanneer u een fragment publiceert, wordt dit beschikbaar voor gebruik in een e-mail- of e-mailsjabloon. Gepubliceerde fragmentinhoud kan niet worden gewijzigd in de visuele ontwerper.
    <p>Beschikbare acties:
    <li>Beschrijving bewerken</li>
    <li>Toevoegen aan een e-mail of sjabloon</li>
    <li>Conceptversie maken</li>
    <li>Dupliceren</li>
    <li>Verwijderen (indien niet in gebruik)</li>
    </td>
  </tr>
  <tr>
    <td><b>Gepubliceerd met concept</b></td>
    <td>Wanneer u een concept maakt op basis van een gepubliceerd fragment, blijft de gepubliceerde versie beschikbaar voor gebruik in een e-mail- of e-mailsjabloon en kan de conceptinhoud worden gewijzigd in de visuele ontwerper. Als u de ontwerp versie publiceert, vervangt het de huidige gepubliceerde versie en de inhoud wordt bijgewerkt in <i> alle </i> e-mails en e-mailmalplaatjes waar het in gebruik is. 
    <p>Beschikbare acties:
    <li>Beschrijving bewerken</li>
    <li>Toevoegen aan een e-mail of sjabloon</li>
    <li>Conceptenversie bewerken in visuele ontwerper</li>
    <li>Publish-conceptversie</li>
    <li>Dupliceren</li>
    <li>Verwijderen (indien niet in gebruik)</li>
    </td>
  </tr>
</tbody></table>

### De lijst met fragmenten filteren {#filter-the-fragments-list}

Gebruik de zoekbalk om een fragment op naam te zoeken. Klik het _pictogram van de Filter_ ( ![ tonen of verbergen filterpictogram ](assets/icon-filter.svg)) om de beschikbare filteropties te tonen en de gewenste montages te kiezen.

![ filter de getoonde fragmenten ](assets/fragments-list-filtered.png){width="700" zoomable="yes"}

### De kolomweergave aanpassen {#customize-the-column-display}

Pas de kolommen aan u in de lijst wilt tonen door _te klikken aanpassen lijst_ pictogram ( ![ aanpassen lijstpictogram ](assets/icon-column-settings.svg)) bij het hoogste recht.

Selecteer de gewenste kolommen in het dialoogvenster en klik op **[!UICONTROL Apply]** .

SCREENSHOT

## Fragmenten maken {#create-fragments}

Maak een nieuw visueel fragment door op **[!UICONTROL Create fragment]** rechtsboven te klikken.

1. Voer in het dialoogvenster _[!UICONTROL Create fragment]_een **[!UICONTROL Name]**en een optioneel **[!UICONTROL Description]**in.

   Fragmentvereisten:

   * Naam - max. 100 tekens, moet uniek en hoofdlettergevoelig zijn
   * Beschrijving - max. 300 tekens
   * Alpha, numerieke tekens en speciale tekens zijn oké
   * Gereserveerde karakters zijn **_niet toegestaan_**: `\ / : * ? " < > |`

SCREENSHOT

1. Klik op **[!UICONTROL Create]**.

   De visuele ontwerper wordt geopend met een leeg canvas.

1. Gebruik de gereedschappen voor inhoudsontwerp om de visuele fragmentinhoud te maken:

   * [Structuur en inhoud toevoegen](#add-structure-and-content)
   * [Assets toevoegen](#add-assets)
   * [Navigeren door de lagen, instellingen en stijlen](#navigate-the-layers-settings-and-styles)
   * [Inhoud personaliseren](#personalize-content)
   * [Gekoppelde URL-tracking bewerken](#edit-linked-url-tracking)

1. Klik op **[!UICONTROL Save]** om het conceptfragment op te slaan.

1. Als u het fragment beschikbaar wilt maken voor gebruik in een e-mailsjabloon of e-mailsjabloon, klikt u op **[!UICONTROL Publish]** .

### Structuur en inhoud toevoegen {#add-structure-and-content}

{{$include /help/marketo/_includes/content-design-components.md}}

### Elementen toevoegen

{{$include /help/_includes/content-design-assets.md}}

### Navigeren door de lagen, instellingen en stijlen

{{$include /help/_includes/content-design-navigation.md}}

### Inhoud personaliseren

{{$include /help/_includes/content-design-personalization.md}}

### Gekoppelde URL-tracking bewerken

{{$include /help/_includes/content-design-links.md}}

## Fragmentdetails weergeven {#view-fragment-details}

Klik op de naam van een fragment in de lijstpagina om de pagina met fragmentdetails te openen. U kunt het fragment bewerken, de naam van het fragment wijzigen of de fragmentbeschrijving bijwerken. Voer updates uit en klik buiten het naam- of beschrijvingsveld om wijzigingen automatisch op te slaan.

>[!NOTE]
>
>Als een gepubliceerd fragment wordt gebruikt door een e-mailsjabloon, kunt u de naam van het fragment niet wijzigen of de inhoud ervan bewerken. U kunt een conceptversie maken als u wijzigingen in het fragment wilt aanbrengen.

![ de details van de Mening voor een gepubliceerd fragment ](assets/fragment-details-published.png){width="600" zoomable="yes"}

Klik op **[!UICONTROL Edit fragment]** om het fragment te openen in de visuele inhoudeditor.

Ga de mening op elk ogenblik weg door de _Achter_ pijl bij de hoogste linkerzijde te klikken, die u aan de _pagina van de de 3} lijst van Fragmenten {terugkeert._

## Fragment weergeven dat wordt gebruikt door verwijzingen {#view-fragment-used-by-references}

Klik op de pagina met fragmentdetails op het tabblad **[!UICONTROL Used By]** om details weer te geven van de plaats waar het fragment wordt gebruikt in het Marketo Engage.

>[!IMPORTANT]
>
>Een fragment dat momenteel wordt gebruikt door een e-mailsjabloon of e-mailsjabloon kan niet worden verwijderd.

De verwijzingen worden getoond volgens categorie: _E-mail_ of _E-mailmalplaatje_. E-mails in Journey Optimizer B2B edition worden ingesloten en geschreven binnen accountreizen. De bovenliggende reis van de e-mail die het fragment gebruikt, wordt daarom weergegeven in verwijzingen. &lt;— OVER DIT ONDERDEEL, NILESH

![ Gebruikt door verwijzingen voor het fragment ](assets/fragment-used-by-published.png){width="600" zoomable="yes"}

Klik op de koppeling om de bijbehorende sjabloon voor e-mail of e-mail te openen waarin het fragment wordt gebruikt.

## Fragmenten verwijderen {#delete-fragments}

Omdat een fragment dat momenteel in gebruik door een e-mail of e-mailmalplaatje is niet kan worden geschrapt, ben zeker om _te controleren gebruikt-door_ verwijzingen alvorens een fragmentverwijdering in werking te stellen. Een verwijdering kan ook niet ongedaan worden gemaakt. Controleer dit voordat u een verwijderactie start.

U kunt een fragment op een van de volgende manieren verwijderen:

* Klik op **[!UICONTROL Delete]** in de fragmentdetails aan de rechterkant.
* Klik op de aanbiedingspagina van _[!UICONTROL Fragments]_op de ovaal naast het fragment en kies **[!UICONTROL Delete]**.

Met deze handeling wordt een bevestigingsvenster geopend. U kunt het proces afbreken door op **[!UICONTROL Cancel]** te klikken of op **[!UICONTROL Delete]** te klikken om het verwijderen te bevestigen.

![ de fragmentdialoog van de Schrapping ](assets/fragment-delete-dialog.png){width="400"}

## Fragmenten bewerken {#edit-fragments}

Bewerkingen aan een fragment zijn afhankelijk van de huidige status:

* Wanneer een fragment in _de status van het Ontwerp_ is, kunt u om het even welk van zijn details en de visuele inhoud uitgeven.
* Wanneer een fragment in _Gepubliceerde_ status is, kunt u de fragmentbeschrijving uitgeven, maar niet de naam. U kunt de visuele inhoud niet bewerken.
* Wanneer een fragment in _met ontwerp_ status wordt gepubliceerd, is het uitgeven van de details beperkt tot de beschrijving. U kunt ook de visuele inhoud van de conceptversie bewerken.

>[!BEGINTABS]

>[!TAB  Ontwerp ]

1. Klik op de aanbiedingspagina van _[!UICONTROL Fragments]_op de fragmentnaam om deze te openen.

   Er wordt een voorvertoning van de visuele inhoud weergegeven, met de fragmentdetails aan de rechterkant.

1. Breng de gewenste wijzigingen aan.

   ![ Details voor kader met de status van het Ontwerp ](assets/fragment-draft-details.png){width="600" zoomable="yes"}

1. Als u de inhoud in de visuele ontwerper wilt wijzigen, klikt u op **[!UICONTROL Edit fragment]** .

   Gebruik de gereedschappen voor visuele ontwerpen naar wens:

   * [Structuur en inhoud toevoegen](#add-structure-and-content)
   * [Assets toevoegen](#add-assets)
   * [Navigeren door de lagen, instellingen en stijlen](#navigate-the-layers-settings-and-styles)
   * [Inhoud personaliseren](#personalize-content)
   * [Gekoppelde URL-tracking bewerken](#edit-linked-url-tracking)

   Klik op **[!UICONTROL Save]** of **[!UICONTROL Save & close]** om terug te keren naar de fragmentdetails.

1. Als het fragment voldoet aan de criteria en u wilt het beschikbaar maken voor gebruik in een e-mailsjabloon of e-mailsjabloon, klikt u op **[!UICONTROL Publish]** .

>[!TAB  Gepubliceerd ]

1. Klik op de aanbiedingspagina van _[!UICONTROL Fragments]_op de fragmentnaam om deze te openen.

   Er wordt een voorvertoning van de visuele inhoud weergegeven, met de fragmentdetails aan de rechterkant.

1. Wijzig, indien nodig, de beschrijving.

   Voor een gepubliceerd fragment kunnen niet alle andere details worden gewijzigd.

1. Als u de inhoud wilt bijwerken, klikt u op **[!UICONTROL Create draft version]** rechtsboven.

   Klik op **[!UICONTROL OK]** in het dialoogvenster om de conceptversie te openen in de visuele ontwerper. U kunt de `image source` KG - KOPPELING HIER desgewenst wijzigen.

   ![ creeer de dialoog van de ontwerp versie ](assets/fragments-create-draft-version.png){width="300"}

   Gebruik de gereedschappen voor visuele ontwerpen naar wens:

   * [Structuur en inhoud toevoegen](#add-structure-and-content)
   * [Assets toevoegen](#add-assets)
   * [Navigeren door de lagen, instellingen en stijlen](#navigate-the-layers-settings-and-styles)
   * [Inhoud personaliseren](#personalize-content)
   * [Gekoppelde URL-tracking bewerken](#edit-linked-url-tracking)

   Klik op **[!UICONTROL Save]** of **[!UICONTROL Save & close]** om terug te keren naar de fragmentdetails.

1. Als het concept van het fragment voldoet aan de criteria en u wilt de wijzigingen beschikbaar maken voor gebruik in een e-mailsjabloon of e-mailsjabloon, klikt u op **[!UICONTROL Publish]** .

   Wanneer u de conceptversie publiceert, vervangt deze de huidige gepubliceerde versie en wordt de inhoud bijgewerkt in de e-mails en e-mailsjablonen waar deze al in gebruik is.

>[!TAB  Gepubliceerd met ontwerp ]

U kunt de conceptversie op twee manieren openen om te bewerken op de pagina met _[!UICONTROL Fragments]_-aanbiedingen:

* Klik het _Meer_ pictogram (**..**) naast de fragmentnaam en kies **[!UICONTROL Open draft version]**.

  ![ Open ontwerp versie ](assets/fragments-create-draft-version.png){width="300"}

* Klik op de fragmentnaam om deze te openen. Klik vervolgens rechtsboven op **[!UICONTROL Open draft version]** .

  Er wordt een voorbeeld van de visuele inhoud voor de conceptversie weergegeven, met de fragmentdetails aan de rechterkant.

De inhoud bijwerken:

1. Klik op **[!UICONTROL Edit fragment]** rechtsboven. Gebruik de gereedschappen voor visuele ontwerpen naar wens:

   * [Structuur en inhoud toevoegen](#add-structure-and-content)
   * [Assets toevoegen](#add-assets)
   * [Navigeren door de lagen, instellingen en stijlen](#navigate-the-layers-settings-and-styles)
   * [Inhoud personaliseren](#personalize-content)
   * [Gekoppelde URL-tracking bewerken](#edit-linked-url-tracking)

   Klik op **[!UICONTROL Save]** of **[!UICONTROL Save & close]** om terug te keren naar de fragmentdetails.

1. Als het concept van het fragment voldoet aan de criteria en u wilt de wijzigingen beschikbaar maken voor gebruik in een e-mailsjabloon of e-mailsjabloon, klikt u op **[!UICONTROL Publish]** .

   Wanneer u de conceptversie publiceert, vervangt deze de huidige gepubliceerde versie en wordt de inhoud bijgewerkt in de e-mails en e-mailsjablonen waar deze al in gebruik is.

>[!ENDTABS]

## Fragmenten dupliceren {#duplicate-fragments}

U kunt een fragment op een van de volgende manieren dupliceren:

* Van de _[!UICONTROL Fragments]_lijstpagina, klik het_ Meer _pictogram (**...**) naast de fragmentnaam en kies **[!UICONTROL Duplicate]**.
* Klik rechtsboven op de pagina met fragmentdetails op **[!UICONTROL ... More]** en kies **[!UICONTROL Duplicate]** .

![ dupliceer het fragment ](assets/fragment-details-duplicate.png){width="600" zoomable="yes"}

Voer in het dialoogvenster een unieke naam en een optionele beschrijving in. Klik op **[!UICONTROL Duplicate]** om de handeling te voltooien.

![ ga een naam en een beschrijving voor het gedupliceerde fragment ](assets/fragment-duplicate-dialog.png){width="400"} in

Het gedupliceerde fragment verschijnt dan in de _lijst van Fragmenten_.

## Een nieuw fragment opslaan vanuit e-mail- of sjablooninhoud {#save-a-new-fragment-from-email-or-template-content}

Wanneer u een e-mail- of e-mailsjabloon maakt/bewerkt in de visuele inhoudeditor, kunt u de inhoud geheel of gedeeltelijk opslaan als een fragment, zodat deze opnieuw kan worden gebruikt.

1. Als u inhoud als een fragment wilt opslaan, klikt u op **[!UICONTROL More]** en kiest u **[!UICONTROL Save as Fragment]** .

1. Selecteer de verschillende elementen die u in het fragment wilt opnemen.

   Selecteer meerdere structuren door de knop Shift of Control ingedrukt te houden.

   U kunt alleen structuren selecteren die aan elkaar grenzen en met de interface kunt u geen niet-aangrenzende elementen selecteren.

1. Selecteer de inhoud en klik op **[!UICONTROL Create]** rechtsboven.

1. Voer in het dialoogvenster een naam en een optionele beschrijving voor het fragment in. Klik vervolgens op **[!UICONTROL Create]** .

   Het fragment wordt dan getoond in de _Fragmenten_ het vermelden pagina en is ook beschikbaar voor gebruik binnen e-mail en e-mailmalplaatjes.

## Visuele fragmenten toevoegen aan uw e-mail- of sjablooninhoud {#add-visual-fragments-to-your-email-or-template-content}

Fragmenten zijn ontworpen voor hergebruik en u kunt maximaal 30 fragmenten toevoegen in een e-mailsjabloon of e-mailsjabloon. Fragmenten kunnen tot één niveau worden genest.

>[!BEGINTABS]

>[!TAB  voegt fragmenten aan e-mail ] toe

1. Navigeer naar **[!UICONTROL Account Journeys]** en open een bestaande reis of maak een nieuwe reis. &lt;— DUBBELE CONTROLE

—HIER GESTOPT BEWERKEN—

1. Creeer een [_[!UICONTROL Send Email]_knoop ](./email-authoring.md#add-an-email-action-in-an-account-journey).

1. Creeer of geef [ e-mailinhoud voor de knoop ](./email-authoring.md#create-the-email-content) uit.

1. De belemmering en laat vallen een punt van het **[!UICONTROL Components]** menu om a _structuur_ voor het fragment te verstrekken.

1. Om de lijst van gepubliceerde fragmenten te openen, klik het _pictogram van Fragmenten_.

   U kunt:
   * Sorteer de aanbieding.
   * Blader naar de lijst, zoek de lijst en filter deze.
   * Schakelen tussen kaart- (miniatuur) en lijstweergaven.
   * Vernieuw de lijst om een van de onlangs gemaakte fragmenten weer te geven.

SCREENSHOT

1. Sleep een van de fragmenten naar de tijdelijke aanduiding voor het structuuronderdeel.

   De editor geeft het fragment weer binnen de sectie/het element van de e-mailstructuur.

De inhoud van het fragment wordt dynamisch bijgewerkt binnen de structuur om een visuele weergave te geven van hoe de inhoud in de e-mail wordt weergegeven.

>[!TIP]
>
>Als u wilt dat het fragment de volledige horizontale lay-out binnen de e-mail in beslag neemt, voegt u een [!UICONTROL 1:1 column] -structuur toe en sleept u het fragment er vervolgens in.

Nadat het e-mailbericht is opgeslagen, wordt het weergegeven op de pagina met fragmentdetails wanneer het tabblad _[!UICONTROL Used By]_is geselecteerd. Fragmenten die aan een e-mail zijn toegevoegd, kunnen niet worden bewerkt in de e-mail of sjabloon. Het gepubliceerde bronfragment definieert de inhoud.

>[!TAB  voegt fragmenten aan een e-mailmalplaatje ] toe

1. Klik in de linkernavigatie op **[!UICONTROL Content Management]** > **[!UICONTROL Templates]** .

1. Maak een nieuwe sjabloon of open een bestaande e-mailsjabloon en klik op **[!UICONTROL Edit Email Template]** .

1. De belemmering en laat vallen een punt van het **[!UICONTROL Components]** menu om a _structuur_ voor het fragment te verstrekken.

1. Om de fragmenten lijst te openen, klik het _pictogram van Fragmenten_.

   U kunt:
   * Sorteer de aanbieding.
   * Blader naar de lijst, zoek de lijst en filter deze.
   * Schakelen tussen kaart- (miniatuur) en lijstweergaven.
   * Vernieuw de lijst om een van de onlangs gemaakte fragmenten weer te geven.

SCREENSHOT

1. Sleep een van de fragmenten naar de tijdelijke aanduiding voor het structuuronderdeel.

   De editor geeft het fragment weer binnen de sectie/het element van de sjabloonstructuur voor e-mail.

1. Sleep een van de fragmenten naar de tijdelijke aanduiding voor het structuuronderdeel.

   De editor geeft het fragment weer binnen de sectie/het element van de sjabloonstructuur voor e-mail.

>[!TIP]
>
>Als u wilt dat het fragment de volledige horizontale lay-out binnen de e-mailsjabloon beslaat, voegt u een _[!UICONTROL 1:1 column]_-structuur toe en sleept u het fragment er vervolgens in.

Nadat de e-mailsjabloon is opgeslagen, wordt deze weergegeven op de pagina met fragmentdetails wanneer het tabblad _[!UICONTROL Used By]_is geselecteerd. Fragmenten die aan een e-mailsjabloon zijn toegevoegd, kunnen niet worden bewerkt in de sjabloon. Het gepubliceerde bronfragment definieert de inhoud.

>[!ENDTABS]

## Fragmentacties tijdens het ontwerpen van e-mail- en sjablonen

Wanneer een fragment aan een e-mailsjabloon of e-mailsjabloon wordt toegevoegd, kan de fragmentinhoud niet worden bewerkt in de e-mail of sjabloon. U kunt echter de volgende handelingen toepassen:

* **[!UICONTROL Delete]** - Deze actie verwijdert het fragment uit de huidige e-mail- of e-mailsjablooninhoud (de fragmentbron blijft ongewijzigd).
* **[!UICONTROL Refresh]** - Met deze handeling wordt de inhoud van het fragment in de huidige e-mailsjabloon of de huidige e-mailsjabloon vernieuwd. Vernieuwen is handig als u recente bewerkingen aan het fragment wilt spiegelen nadat u het fragment hebt toegevoegd aan de e-mailsjabloon of de e-mailsjabloon.
* **[!UICONTROL Duplicate]** - Met deze actie wordt het fragment binnen dezelfde e-mail- of e-mailsjabloon in de editor gedupliceerd, met dezelfde afmetingen en net eronder toegevoegd.
* **[!UICONTROL Open Fragment]** - Met deze actie opent u een nieuw browsertabblad met de pagina voor de fragmenteditor en details.
* **[!UICONTROL Break inheritance]** - Met deze actie wordt de overerving van het fragment (en de wijzigingen ervan) van de bron verbroken. Gebruik deze handeling om de fragmentinhoud beschikbaar te maken als onafhankelijke en bewerkbare inhoud binnen de e-mail- of e-mailsjabloon. Deze actie verwijdert ook het e-mail of e-mailmalplaatje uit _Gebruikt door_ verwijzing voor het originele fragment.

Wanneer u het fragment op de editorpagina selecteert, zijn deze acties beschikbaar bij de contexttoolbar en het eigenschappenpaneel op het recht.

![ pas acties op het geselecteerde fragment ](assets/fragment-actions-email-authoring.png){width="600" zoomable="yes"} toe
