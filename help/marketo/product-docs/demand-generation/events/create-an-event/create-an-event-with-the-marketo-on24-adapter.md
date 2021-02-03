---
unique-page-id: 10096656
description: Creeer een Gebeurtenis met de Adapter van Marketo ON24 - Marketo Docs - de Documentatie van het Product
title: Creeer een Gebeurtenis met de Adapter Marketo ON24
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 0%

---


# Creeer een Gebeurtenis met de Adapter van het Marketo ON24 {#create-an-event-with-the-marketo-on-adapter}

## Voordat u {#before-you-begin} begint

U zou met de bouwstenen en de geadviseerde opeenvolging voor het creëren van Gebeurtenissen in Marketo vertrouwd moeten zijn. U zou ook werkende kennis van de volgende concepten Marketo moeten hebben:

* [Marketo-](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md) programma&#39;s en gebeurtenissen en de verschillen tussen deze
* [Kanalen](/help/marketo/product-docs/administration/tags/create-a-program-channel.md)
* [Lokale elementen](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-local-assets-in-a-program.md)
* [Onderliggende ](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md) campagnes en  [programmastatussen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md)

>[!NOTE]
>
>Raadpleeg de [Marketo API-documentatie](https://developers.marketo.com/documentation/rest/) voor meer informatie over Marketo API&#39;s.

## Vereisten {#prerequisites}

Voor de integratie Marketo ON24 is het volgende vereist:

* **Abonnement op ON24-webcasts**  - Neem rechtstreeks contact op met ON24 als u geen huidig abonnement hebt. **OPMERKING**: ON24 Hosted Edition is vereist. ON24 Gebeurtenisbeheer is niet vereist.

* **Beheerdersrechten voor ON24**  - Dit is nodig om deze connector te gebruiken en gasten te maken in het ON24-systeem.
* **ON24 verbindingsgeloofsbrieven**  - U zult deze informatie in Marketo moeten ingaan om de integratie toe te laten: Gebruikersnaam, Wachtwoord, Client-id en Client-sleutel. Neem contact op met uw ON24-accountmanager of ON24-support als u hulp nodig hebt met uw gegevens.
* **Registratieformulier**  - Gebruik een Marketo-formulier of een niet-Marketo-formulier samen met de juiste API om ervoor te zorgen dat registratiegegevens en informatie over de registrant worden doorgegeven aan Marketo.
* **De kindcampagne**  van de registratie - een campagne van het registratiekind in uw Gebeurtenis Marketo moet behoorlijk voor uw integratie van de Partner van de Gebeurtenis worden gecreeerd en worden gevormd om te werken.

## Processtroom {#process-flow}

Ga als volgt te werk om een gebeurtenis te maken met de adapter Marketo On24:

1. [Voer uw ON24-referenties in Marketo in](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/enter-your-on24-credentials-in-marketo.md)
1. [Uw webinar-gebeurtenis maken in ON24](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-your-webinar-event-in-on24.md)
1. [Gebeurtenisinstellingen configureren en markering synchroniseren met uw webinar](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md)
1. [Onderliggende campagnes en lokale elementen maken](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-child-campaigns-and-local-assets.md)
1. [ON24-gebeurtenisintegratie testen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md)
1. [Voorbeeld ON24-gebeurtenisintegratie](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
1. [Werken met de status van het Webinar-programma](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md)
1. [ON24 Updates voor gebeurtenisregistratie](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md)
