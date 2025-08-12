---
solution: Marketo Engage
product: marketo
title: TITEL
description: Leer hoe u het maken van e-mail kunt stroomlijnen met herbruikbare thema's en modules, zodat u verzekerd bent van consistentie en efficiëntie bij het ontwerp.
feature: Email Designer
role: User
level: Beginner, Intermediate
hide: true
hidefromtoc: true
source-git-commit: 1cfb28f47ba3c168292b298e1fc7ab2ff638b412
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 0%

---

# Thema&#39;s toepassen op uw e-mailinhoud {#apply-email-themes}

>[!AVAILABILITY]
>
>Deze mogelijkheid is momenteel beschikbaar in bètaversie en alleen voor bètaklanten. Neem contact op met uw Adobe-vertegenwoordiger als u wilt deelnemen aan het bètaprogramma.

Met thema&#39;s, hebben de niet-technische gebruikers de capaciteit om herbruikbare inhoud tot stand te brengen die een specifiek merk en een ontwerptaal door douanemateriaal bovenop de standaardmalplaatjes <!-- to achieve brand specific results--> toe te voegen past.

Deze functie stelt marketers in staat visueel aantrekkelijke, merkgebonden e-mails sneller en met minder moeite te gebruiken en biedt geavanceerde aanpassingsopties voor unieke ontwerpbehoeften.

<!--What is the Enhanced Email Authoring Experience?

This feature introduces two key components to simplify and enhance email creation:

* **Theme Management System**: A centralized system for creating, customizing, and applying reusable themes to emails. Themes ensure consistent styling across campaigns and eliminate the need for repetitive manual styling.

* **Modules**: Pre-designed, reusable content blocks that abstract common email elements (e.g., titles, descriptions, images, and links). Modules are built using customizable low-level components, offering flexibility while maintaining design standards.

Key Benefits:

- **Consistency**: Ensure all emails align with your brand's design guidelines.
- **Efficiency**: Save time by reusing themes and modules across campaigns.
- **Customization**: Add custom CSS and mobile-specific styles for advanced designs.
- **Scalability**: Eliminate repetitive styling tasks, enabling faster email creation.-->

## Afvoerkanalen en beperkingen {#themes-guardrails}

* Wanneer u een volledig nieuw e-mailbericht maakt, kunt u uw inhoud op basis van een thema maken en snel een specifieke stijl toepassen die past bij uw merk en ontwerp.

  Als u de _Handmatige het Stileren_ wijze kiest, zult u geen thema&#39;s kunnen toepassen tenzij u uw e-mail terugstelt.

* [ de Fragmenten ](/help/marketo/product-docs/email-marketing/email-designer/fragments.md) zijn niet dwars-compatibel tussen de _Thema&#39;s van het Gebruik_ en _Handmatige het Stileren_ wijzen.

  Om een fragment in een inhoud te kunnen gebruiken waar een thema wordt toegepast, moet dit fragment op _wijze van de Thema&#39;s van het Gebruik_ worden gecreeerd.

* Als het gebruiken van inhoud die in HTML wordt gecreeerd, zult u op [ verenigbaarheidswijze ](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#import-html) zijn en kan geen thema&#39;s op deze inhoud toepassen.

  Om alle mogelijkheden van e-mail Designer, met inbegrip van thema&#39;s volledig te hefboomwerking, moet u of nieuwe inhoud op _de wijze van de Thema&#39;s van het Gebruik_ tot stand brengen, of uw [ ingevoerde inhoud van HTML ](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#import-html) omzetten.

<!--If using a content created in Manual Styling mode or HTML, you cannot apply themes to this content. You must create a new content in Use Themes mode.

If you apply a theme to a content using a [fragment](../content-management/fragments.md) created in Manual Styling mode, the rendering may not be optimal.-->

## Een thema maken {#create-and-edit-themes}

Volg onderstaande stappen om een thema te definiëren dat u in uw toekomstige e-mailinhoud kunt gebruiken.

1. Om begonnen te worden, creeer een nieuw [ e-mailmalplaatje ](/help/marketo/product-docs/email-marketing/email-designer/email-template-authoring.md#create-an-email-template).

1. Selecteer de optie **[!UICONTROL Create or edit themes]** .

   `![](assets/theme-create.png)`

1. U kunt het standaardthema selecteren of een Adobe- of aangepaste sjabloon gebruiken. Selecteer in dit voorbeeld het standaardthema en klik op **[!UICONTROL Create]** .

   `![](assets/theme-select.png)`

1. Definieer op het tabblad **[!UICONTROL General settings]** het thema door het een specifieke naam voor uw merk te geven. U kunt de standaardbreedte voor uw e-mails aanpassen en ook het huidige thema exporteren om het over sandboxen te delen.

   `<!--![](assets/theme-general-settings.png)-->`

1. Gebruik de rail rechts om door de verschillende lusjes te navigeren en uw ontwerpmontages bij te werken.

   `![](assets/theme-right-pane.png)`

1. Op het tabblad **[!UICONTROL Colors]** :

   * Gebruik de knop **[!UICONTROL Edit]** om een **[!UICONTROL Color palette]** met standaardkleuren voor uw merk in te stellen. Selecteer een **[!UICONTROL Preset]** om snel een kleurenschema te maken of pas elke kleur van uw thema afzonderlijk aan. U kunt ook een combinatie van beide gebruiken.

     `![](assets/theme-colors.gif)`

   * Klik op **[!UICONTROL Add variant]** om meerdere kleurvarianten te maken, zoals de modus Licht en Donker, waarbij elke variant een eigen kleurpalet en een eigen nuantiebesturingspunt heeft.

     `![](assets/theme-colors-variant.png)`

   * Klik voor elke variant op het pictogram Bewerken om elk afzonderlijk element te bewerken. U kunt het standaardpalet gebruiken dat u hebt gemaakt, of aangepaste kleuren.

     `![](assets/theme-colors-edit-variant.gif)`

1. In **[!UICONTROL Text settings]** kunt u het algemene lettertype instellen dat u voor het hele thema wilt gebruiken. Voor meer korrelige besturingselementen kunt u ook elk kop- en alineatekst bewerken om het lettertype, de grootte, de stijl enzovoort aan te passen.

   `![](assets/theme-text.png)`

1. Selecteer op het tabblad **[!UICONTROL Spacing]** een afzonderlijk element in de lijst om de ruimte tussen de verschillende componenten op de juiste wijze te bepalen.

   `<!--![](assets/theme-spacing.png)-->`

1. Met de andere tabbladen aan de rechterkant kunt u elk knopelement, elke scheidingslijn, elke extra afbeeldingsopmaak en de ruimte tussen de rasterlay-outs voor dit thema afzonderlijk beheren.

   `<!--![](assets/theme-buttons.png)-->`

1. Klik op **[!UICONTROL Save]** om dit thema op te slaan voor toekomstig gebruik.

## Thema&#39;s toepassen op een e-mail {#apply-themes}

Volg onderstaande stappen om standaardthema&#39;s of aangepaste opmaakthema&#39;s toe te passen op een e-mail.

1. `In [!DNL Marketo Engage], [add an email](create-email.md) action to a journey or campaign, and [edit your email body](get-started-email-design.md#key-steps).`

1. U kunt een van de volgende handelingen selecteren:

   * `Select a built-in [email template](use-email-templates.md) to open the Email Designer. A default theme specific to each template is automatically applied.`

   * `Design a [new content from scratch](content-from-scratch.md) and select **[!UICONTROL Use Themes]** to start with a predefined styling theme.`

     `![](assets/theme-from-scratch.png)`

     >[!CAUTION]
     >
     >Als u de _Handmatige het Stileren_ wijze kiest, zult u geen thema&#39;s kunnen toepassen tenzij u uw e-mail terugstelt.
     >
     >Om a [ fragment ](/help/marketo/product-docs/email-marketing/email-designer/fragments.md) in _wijze van Thema&#39;s van het Gebruik_ te gebruiken, moet dit fragment zelf gecreeerd zijn gebruikend de _wijze van Thema&#39;s van het Gebruik_.

1. Klik eenmaal in de e-mail-Designer op de knop **[!UICONTROL Themes]** op de rechtertrack. Het standaardthema of het thema van de sjabloon wordt weergegeven. U kunt schakelen tussen de twee kleurvarianten voor dit thema.

   `![](assets/theme-default-hero.png)`

1. Klik op de pijl naast het thema dat momenteel wordt gebruikt. De lijst met beschikbare aangepaste thema&#39;s en Adobe-thema&#39;s wordt weergegeven.

   `![](assets/theme-hero-change.png)`

1. Klik op **[!UICONTROL Custom themes]** en selecteer het thema dat u hebt gemaakt.

   `![](assets/theme-select-custom.png)`

1. Klik buiten de vervolgkeuzelijst. Het nieuwe, aangepaste thema past automatisch de stijlen toe op alle e-mailcomponenten. U kunt schakelen tussen de twee kleurvarianten.

1. Wanneer een component is geselecteerd, kunt u de stijl ervan nog steeds ontgrendelen met behulp van het toegewezen pictogram.

   `![](assets/theme-unlock-style.png)`

U kunt op elk gewenst moment naar een ander thema gaan. De e-mailinhoud blijft ongewijzigd, maar de stijlen worden bijgewerkt met het nieuwe thema.

<!--
>[!NOTE]
> - Themes apply styles globally. Ensure your theme is finalized before applying it to multiple emails.
> - Switching themes may override custom styles applied to individual components.

>[!CAUTION]
> - When using fragments, the email's theme will override the fragment's styles. A warning will be displayed in the editor if there is a conflict.

## Example Use Cases {#example-use-cases}

### 1. Creating a New Theme
- A marketer creates a theme with their brand's colors, fonts, and button styles.
- The theme is saved and reused across multiple email campaigns.

### 2. Switching Themes
- A marketer applies a holiday-themed design to an existing email by switching to a pre-designed holiday theme.-->
