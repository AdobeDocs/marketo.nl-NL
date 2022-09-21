---
unique-page-id: 10096656
description: Een gebeurtenis maken met de Marketo ON24-adapter - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met de Marketo ON24-adapter
exl-id: a240ff72-b12f-4e3a-8e14-94fddb02f944
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 0%

---

# Een gebeurtenis maken met de Marketo ON24-adapter {#create-an-event-with-the-marketo-on-adapter}

U moet bekend zijn met de bouwstenen en de aanbevolen volgorde voor het maken van Events in Marketo. U zou ook werkende kennis van de volgende concepten van Marketo moeten hebben:

* [Marketo-programma&#39;s](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md){target=&quot;_blank&quot;} en gebeurtenissen, en de verschillen tussen deze gebeurtenissen
* [Kanalen](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target=&quot;_blank&quot;}
* [Lokale elementen](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-local-assets-in-a-program.md){target=&quot;_blank&quot;}
* [Kindercampagnes](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md){target=&quot;_blank&quot;} en [Programmastatussen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md){target=&quot;_blank&quot;}

>[!NOTE]
>
>Raadpleeg de [Marketo API-documentatie](https://developers.marketo.com/documentation/rest/){target=&quot;_blank&quot;} voor meer informatie over Marketo API&#39;s.

## Vereisten {#prerequisites}

U hebt het volgende nodig om de Marketo ON24-integratie te kunnen gebruiken:

* **Abonnement op ON24-webcasts** - Als u geen huidig abonnement hebt, neemt u rechtstreeks contact op met ON24. **OPMERKING**: ON24 Hosted Edition is vereist. ON24 Gebeurtenisbeheer is niet vereist.

* **Beheerdersrechten op ON24** - U hebt dit nodig om deze connector te gebruiken en gasten te maken in het ON24-systeem.
* **ON24-verbindingsgegevens** - U moet deze gegevens invoeren in Marketo om de integratie in te schakelen: Gebruikersnaam, Wachtwoord, Client-id en Client-sleutel. Neem contact op met uw ON24-accountmanager of ON24-support als u hulp nodig hebt met uw gegevens.
* **Registratieformulier** - Gebruik een Marketo-formulier of een niet-Marketo-formulier samen met de juiste API om ervoor te zorgen dat registratiegegevens en registratiegegevens worden doorgegeven aan Marketo.
* **Kindercampagne registreren** - Een campagne van het registratiekind in uw Gebeurtenis van Marketo moet behoorlijk worden gecreeerd en worden gevormd voor uw integratie van de Partner van de Gebeurtenis om te werken.

## Processtroom {#process-flow}

Ga als volgt te werk om een gebeurtenis te maken met de Marketo On24-adapter:

1. [Uw webinar-gebeurtenis maken in ON24](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-your-webinar-event-in-on24.md){target=&quot;_blank&quot;}
1. [Gebeurtenisinstellingen configureren en Marketo synchroniseren met uw webinar](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md){target=&quot;_blank&quot;}
1. [Onderliggende campagnes en lokale elementen maken](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-child-campaigns-and-local-assets.md){target=&quot;_blank&quot;}
1. [ON24-gebeurtenisintegratie testen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md){target=&quot;_blank&quot;}
1. [Voorbeeld ON24-gebeurtenisintegratie](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target=&quot;_blank&quot;}
1. [Werken met de status van het Webinar-programma](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md){target=&quot;_blank&quot;}
1. [ON24 Updates voor gebeurtenisregistratie](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md){target=&quot;_blank&quot;}
