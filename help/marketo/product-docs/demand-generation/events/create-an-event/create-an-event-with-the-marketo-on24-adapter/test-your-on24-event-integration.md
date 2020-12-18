---
unique-page-id: 10096677
description: Test uw ON24-gebeurtenisintegratie - Marketo Docs - Productdocumentatie
title: ON24-gebeurtenisintegratie testen
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 0%

---


# Test uw ON24-gebeurtenisintegratie {#test-your-on-event-integration}

Zorg ervoor dat u de integratie van uw gebeurtenis grondig test.

## Aanbevolen testreeks voor het uitvoeren van de eerste campagne {#recommended-test-sequence-before-running-your-first-campaign}

1. Vul het registratieformulier van de gebeurtenis in en gebruik een geldig e-mailadres om het te testen.
1. Bevestig de testnaam die wordt weergegeven met de status **Geregistreerd** in het Membership-raster van uw Marketo-gebeurtenis.
1. Bevestig de testnaam ook als **Geregistreerd** in ON24 toont.
1. Bevestig dat het geldige e-mailadres dat u hebt gebruikt om de testnaam te registreren, een bevestigingsbericht naar de gebeurtenis heeft ontvangen en dat de unieke URL in de e-mail is opgelost.

   >[!NOTE]
   >
   >U moet de token `{{member.webinar url}}` in uw bevestigingsbericht gebruiken om de unieke URL weer te geven in de e-mail van elke registrant.

## Na de gebeurtenis {#after-the-event}

Hieronder wordt beschreven hoe gegevens worden bijgewerkt nadat de gebeurtenis heeft plaatsgevonden:

* Marketo haalt de gegevens van deelnemers elke nacht op uit ON24.
* Zodra de gegevens van de aanwezige tussen Marketo en ON24 synchroniseren, werkt Marketo de lidmaatschapsstatus aan Bijgewoond, Bijgewoond op bestelling, of Geen Show bij. Op het **Summiere** lusje van de gebeurtenis, wordt de gebeurtenisstatus bijgewerkt aan **Gebeurtenis Complete**.

>[!MORELIKETHIS]
>
>* [Voorbeeld ON24-gebeurtenisintegratie](example-on24-event-integration.md)
>* [Inzicht in Marketo ON24-adaptergebeurtenissen](understanding-marketo-on24-adapter-events.md)

>



