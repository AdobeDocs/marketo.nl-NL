---
unique-page-id: 10096677
description: Test uw ON24-gebeurtenisintegratie - Marketo Docs - Productdocumentatie
title: ON24-gebeurtenisintegratie testen
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---


# ON24-gebeurtenisintegratie testen {#test-your-on-event-integration}

Zorg ervoor dat u de integratie van uw gebeurtenis grondig test.

## Aanbevolen testsequentie voordat u de eerste campagne uitvoert {#recommended-test-sequence-before-running-your-first-campaign}

1. Vul het registratieformulier van de gebeurtenis in en gebruik een geldig e-mailadres om het te testen.
1. Bevestig de testnaam die wordt weergegeven met de status **Geregistreerd** in het raster Lidmaatschap van uw Marketo-gebeurtenis.
1. Bevestig de testnaam ook zoals **Geregistreerd** in ON24 toont.
1. Bevestig dat het geldige e-mailadres dat u hebt gebruikt om de testnaam te registreren, een bevestigingsbericht naar de gebeurtenis heeft ontvangen en dat de unieke URL in de e-mail is opgelost.

   >[!NOTE]
   >
   >U moet de `{{member.webinar url}}` token gebruiken in het bevestigingsbericht om de unieke URL weer te geven in het e-mailbericht van elke registrant.

## Na de gebeurtenis {#after-the-event}

Hieronder wordt beschreven hoe gegevens worden bijgewerkt nadat de gebeurtenis heeft plaatsgevonden:

* Marketo haalt de gegevens van deelnemers elke nacht op uit ON24.
* Zodra de gegevens van de aanwezige tussen Marketo en ON24 synchroniseren, werkt Marketo de lidmaatschapsstatus aan Bijgewoond, Bijgewoond op bestelling, of Geen Show bij. Op het tabblad **Overzicht** van de gebeurtenis wordt de status van de gebeurtenis bijgewerkt naar **Gebeurtenis voltooid**.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Voorbeeld ON24-gebeurtenisintegratie](example-on24-event-integration.md)
>* [Inzicht in Marketo ON24-adaptergebeurtenissen](understanding-marketo-on24-adapter-events.md)

>



