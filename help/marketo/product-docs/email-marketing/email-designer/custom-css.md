---
solution: Marketo Engage
product: marketo
title: Aangepaste CSS toevoegen aan uw e-mailinhoud
description: Leer hoe u aangepaste CSS rechtstreeks in de e-mailDesigner in Marketo Engage toevoegt aan uw e-mailinhoud.
level: Intermediate
feature: Email Designer
exl-id: c191b44a-47ab-41f8-aa95-9268e359e5db
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '587'
ht-degree: 0%

---

# Aangepaste CSS toevoegen aan uw e-mailinhoud {#custom-css}

Voeg uw eigen aangepaste CSS rechtstreeks toe in de Marketo Engage Email Designer voor geavanceerde, specifieke opmaak.

## Aangepaste CSS definiëren {#define-custom-css}

1. Zorg ervoor dat er inhoud is gedefinieerd in de e-mailtoepassing van Designer door ten minste één component toe te voegen.

1. Selecteer **[!UICONTROL Body]** in het deelvenster **[!UICONTROL Navigation tree]** aan de linkerkant of in het rechterdeelvenster. **[!UICONTROL CSS styles]** wordt rechts weergegeven.

   ![](assets/custom-css-1.png){width="800" zoomable="yes"}

   >[!NOTE]
   >
   >De sectie **[!UICONTROL CSS styles]** is alleen beschikbaar wanneer inhoud aanwezig is in de editor.

1. Klik op **[!UICONTROL + Add custom CSS]** .

   >[!NOTE]
   >
   >De knop **[!UICONTROL Add custom CSS]** is alleen beschikbaar wanneer **[!UICONTROL Body]** is geselecteerd. U kunt echter aangepaste CSS-stijlen toepassen op alle componenten in uw inhoud.

1. Voer uw CSS-code in in het speciale tekstgebied dat wordt weergegeven. Zorg ervoor de douane CSS [&#x200B; geldig is en volgt de juiste syntaxis &#x200B;](#use-valid-css). Klik **sparen** wanneer gedaan.

   ![](assets/custom-css-2.png)

   >[!NOTE]
   >
   >U kunt geen douane CSS aan uw inhoud toevoegen wanneer het gebruiken van a [&#x200B; malplaatje met gesloten inhoud &#x200B;](/help/marketo/product-docs/email-marketing/email-designer/content-locking.md). Het knoplabel verandert in **[!UICONTROL View custom CSS]** en elke weergegeven aangepaste CSS is alleen-lezen.

1. Zorg ervoor dat de CSS van toepassing is op uw inhoud. Als het niet, controleer de [&#x200B; sectie van het Oplossen van problemen &#x200B;](#troubleshooting).

   ![](assets/custom-css-3.png)

   >[!NOTE]
   >
   >Als u alle inhoud verwijdert, verdwijnt de sectie en wordt de eerder gedefinieerde aangepaste CSS niet meer toegepast. Voeg inhoud weer toe om de sectie **[!UICONTROL CSS styles]** opnieuw weer te geven. De aangepaste CSS wordt opnieuw toegepast.

## Geldige CSS gebruiken {#using-valid-css}

U kunt elke geldige CSS-tekenreeks invoeren in het tekstgebied **[!UICONTROL Add custom CSS]** . CSS met de juiste opmaak wordt direct toegepast op de inhoud.

>[!CAUTION]
>
>U bent verantwoordelijk voor de beveiliging van uw aangepaste CSS. Zorg ervoor dat uw CSS geen kwetsbaarheden of conflicten met de bestaande inhoud introduceert.
>
>Gebruik geen CSS die de lay-out of functionaliteit van de inhoud onbedoeld kan onderbreken.

+++ Voorbeelden van geldige CSS

Hieronder staan voorbeelden van geldige CSS.

```css
.acr-component[data-component-id="form"] {
  display: flex;
  justify-content: center;
  background: none;
}

.acr-Form {
  width: 100%;
  padding: 20px 100px;
  border-spacing: 0px 8px;
  box-sizing: border-box;
  margin: 0;
}

.acr-Form .spectrum-FieldLabel {
  width: 20%;
}

.acr-Form.spectrum-Form--labelsAbove .spectrum-FieldLabel,
.acr-Form [data-form-item="checkbox"] .spectrum-FieldLabel {
  width: auto;
}

.acr-Form .spectrum-Textfield {
  width: 100%;
}

#acr-form-error,
#acr-form-confirmation {
  width: 100%;
  padding: var(--spectrum-global-dimension-static-size-500);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  gap: var(--spectrum-global-dimension-static-size-200);
}

.spectrum-Form-item.is-required .spectrum-FieldLabel:after{
  content: '*';
  font-size: 1.25rem;
  margin-left: 5px;
  position: absolute;
}

/* Error field placeholder */
.spectrum-HelpText {
  display: none !important;
}

.spectrum-HelpText.is-invalid,
.is-invalid ~ .spectrum-HelpText {
  display: flex !important;
}
```

```css
@media only screen and (min-width: 600px) {
  .acr-paragraph-1 {
    width: 100% !important;
  }
}
```

+++

+++ Voorbeelden van ongeldige CSS

Als ongeldige CSS wordt ingevoerd, wordt een foutbericht weergegeven dat aangeeft dat de CSS niet kan worden opgeslagen. Hieronder staan voorbeelden van ongeldige CSS.

Het gebruik van `<style>` -tags wordt niet geaccepteerd:

```html
<style type="text/css">
  .acr-Form {
    width: 100%;
    padding: 20px 100px;
    border-spacing: 0px 8px;
    box-sizing: border-box;
    margin: 0;
  }
</style>
```

Ongeldige syntaxis, zoals ontbrekende accolades, wordt niet geaccepteerd:

```css
body {
  background: red;
```

+++

## Technische uitvoering {#implementation}

Uw aangepaste CSS wordt aan het einde van de sectie `<head>` toegevoegd als onderdeel van een `<style>` -tag met het kenmerk `data-name="global-custom"` , zoals in het onderstaande voorbeeld. Op deze manier weet u zeker dat de aangepaste stijlen globaal op de inhoud worden toegepast.

+++ Zie voorbeeld

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="content-version" content="3.3.31">
    <meta name="x-apple-disable-message-reformatting">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <style data-name="default" type="text/css">
      td { padding: 0; }
      th { font-weight: normal; }
    </style>
    <style data-name="grid" type="text/css">
      .acr-grid-table { width: 100%; }
    </style>
    <style data-name="acr-theme" type="text/css" data-theme="default" data-variant="0">
      body { margin: 0; font-family: Arial; }
    </style>
    <style data-name="media-default-max-width-500px" type="text/css">
      @media screen and (max-width: 500px) {
        body { width: 100% !important; }
      }
    </style>
    <style data-name="global-custom" type="text/css">
      /* Add you custom CSS here */
    </style>
  </head>
  <body>
    <!-- Minimal content -->
  </body>
</html>
```

+++

De aangepaste CSS wordt niet geïnterpreteerd of gevalideerd door het deelvenster Designer e-mailen **[!UICONTROL Settings]** . Deze is volledig onafhankelijk en kan alleen worden gewijzigd via de optie **[!UICONTROL Add Custom CSS]** .

### Guardrails - Geïmporteerde inhoud {#guardrails}

Houd rekening met het volgende als u aangepaste CSS wilt gebruiken met inhoud die is geïmporteerd in de e-mailtoepassing Designer:

* Als [&#x200B; het invoeren van externe HTML &#x200B;](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#import-html) inhoud met inbegrip van CSS, tenzij u die inhoud omzet, zal het in **[!UICONTROL Compatibility mode]** zijn, waar de **[!UICONTROL CSS styles]** sectie niet beschikbaar is.

* Als bij het importeren van inhoud die is gemaakt met de E-mail-Designer CSS is opgenomen die is toegepast via de optie **[!UICONTROL Add custom CSS]** , is de eerder toegepaste CSS zichtbaar en bewerkbaar met dezelfde optie.

## Problemen oplossen {#troubleshooting}

Als uw aangepaste CSS niet wordt toegepast, probeert u de onderstaande suggesties.

* Zorg ervoor dat uw CSS geldig is en geen syntaxisfouten bevat (zoals ontbrekende accolades, onjuiste eigenschapsnamen). [&#x200B; leer hoe &#x200B;](#use-valid-css)

* Zorg ervoor dat uw CSS wordt toegevoegd aan de tag `<style>` met het kenmerk `data-name="global-custom"` .

* Controleer of het kenmerk `global-custom` set to `data-disabled` is ingesteld voor de stijltag `true` . In dat geval wordt de aangepaste CSS niet toegepast.

+++ Bijvoorbeeld:

  ```html
  <style data-name="global-custom" type="text/css" data-disabled="true"> body: { color: red; } </style>
  ```

+++

* Zorg ervoor dat uw CSS niet wordt overschreven door andere CSS-regels.

   * Gebruik de browsergereedschappen voor ontwikkelaars om de inhoud te controleren en te controleren of uw CSS zich richt op de juiste kiezers.

   * Voeg `!important` aan uw declaraties toe om ervoor te zorgen dat deze voorrang krijgen.

+++ Bijvoorbeeld:

     ```css
     .acr-Form {
       background: red !important;
     }
     ```

+++

>[!NOTE]
>
>Marketo Engage Support is niet ingesteld als hulp bij het oplossen van problemen met aangepaste CSS. Raadpleeg een webontwikkelaar voor hulp bij CSS.
