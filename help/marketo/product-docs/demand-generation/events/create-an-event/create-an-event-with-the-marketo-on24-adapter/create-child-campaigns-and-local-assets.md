---
unique-page-id: 10096675
description: Onderliggende campagnes en lokale middelen maken - Marketo Docs - Productdocumentatie
title: Onderliggende campagnes en lokale elementen maken
exl-id: 272105e1-43d6-455c-a533-aae65e859384
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '678'
ht-degree: 1%

---

# Onderliggende campagnes en lokale elementen maken {#create-child-campaigns-and-local-assets}

Creeer uw kindcampagnes en lokale activa gebruikend de Studio van het Ontwerp.

## Openingspagina en -formulier {#landing-page-and-form}

Om ervoor te zorgen dat mensen correct zijn geregistreerd bij ON24, moeten de volgende velden worden opgenomen in uw Marketo-formulier:

* Voornaam
* Achternaam
* E-mailadres

U kunt ook de volgende velden naar ON24 duwen:

* Bedrijfsnaam
* Beroep

Met de juiste stroomstap toegevoegd aan de registratiecampagne, zullen de mensen aan ON24 worden geduwd en als geregistreerd worden gemerkt. U kunt andere velden aan het formulier toevoegen en de gegevens worden in Marketo vastgelegd als onderdeel van de persoondetails-record.

>[!CAUTION]
>
>Voor een geslaagde integratie moet u een Marketo-formulier gebruiken om uw personen voor de gebeurtenis te registreren, of een niet-Marketo-formulier met de juiste API-integratie om registratiegegevens naar Marketo te verzenden.

## E-mails en URL-tokens {#emails-and-url-tokens}

Maak de uitnodiging, bevestiging, follow-up en dank je e-mails met Marketo.

## E-mailadres en URL-token voor Marketo-bevestiging {#marketo-confirmation-email-and-url-token}

Gebruik Marketo om het bevestigingsbericht voor uw gebeurtenis te verzenden. Wanneer een persoon zich registreert, ontvangt hij of zij een unieke URL om de gebeurtenis in te voeren.

>[!NOTE]
>
>Gebruik de volgende token in uw e-mail om het bevestigingsbericht te vullen met deze unieke URL: `{{member.webinar url}}`. Wanneer u de bevestiging-URL verzendt, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
>
>Stel het type bevestigingsbericht in op **Operationeel** ervoor te zorgen dat personen die zich inschrijven hun bevestigingsinformatie ontvangen, zelfs wanneer zij zich niet hebben geabonneerd.

>[!TIP]
>
>U kunt ON24 configureren voor het verzenden van e-mails voor bevestiging, herinnering of follow-up. Zie de [ON24 Help-site](https://www.on24.com/live-webcast-elite/){target=&quot;_blank&quot;} voor meer informatie.

## Vereisten voor onderliggende campagne registreren {#registration-child-campaign-requirements}

Gebeurtenissen bevatten een of meer onderliggende campagnes die allemaal samenwerken om mensen door de status van het programma te bewegen en u in staat te stellen de prestaties van de gebeurtenis te volgen.

Voorbeelden van kindercampagnes zijn een uitnodigingscampagne, een registratiecampagne en vervolgcampagnes.

>[!CAUTION]
>
>De adapter kan zijn taak alleen uitvoeren als u een registratiecampagne maakt. Deze campagne moet worden geactiveerd door de persoon die een formulier invult en in de eerste stap moet de status van het programma van de persoon worden gewijzigd in **Geregistreerd**. De campagne stuurt vervolgens een bevestigingsbericht. Zie de rest van dit artikel voor meer informatie.

**Registratie/bevestiging (Trigger-campagne)**

* Slimme lijst
* Trigger op basis van **Formulier wordt ingevuld**. Zorg ervoor dat u de landingspagina opneemt waarop het formulier zich bevindt door het te gebruiken **Restrictie toevoegen**, vooral als hetzelfde formulier op meerdere bestemmingspagina&#39;s wordt gebruikt.

>[!CAUTION]
>
>U moet een Marketo-formulier gebruiken om uw personen voor de gebeurtenis te registreren, of een niet-Marketo-formulier met de juiste API-integratie om registratiegegevens naar Marketo te verzenden. Dit is essentieel voor het succes van de integratie van uw gebeurtenispartner.

>[!NOTE]
>
>Als u een Marketo-formulier gebruikt op een landingspagina die geen Marketo is, wordt de trigger **Formulier wordt ingevuld** met de naam van het formulier.

![](assets/image2015-12-22-15-3a20-3a51.png)

**Stroom**

* **Programmastatus wijzigen** - Instellen op webinar -> Geregistreerd.

Deze stroomstap is vereist als de EERSTE STROOMSTAP bij het instellen van uw onderliggende campagne. Wanneer de status van het programma van een persoon verandert in Geregistreerd, plaatst Marketo de registratiegegevens op ON24. Geen andere status zal de persoon over duwen.

* **E-mail verzenden** - Bevestigingse-mail. Deze e-mail instellen op **Operationeel** zodat personen die zich niet hebben ingeschreven deze nog steeds ontvangen.

De **E-mail verzenden** De stroomstap MOET de tweede stap zijn. Het bevestigingsbericht bevat de `{{member.webinar url}}`, die wordt gevuld met informatie die vanuit ON24 naar Marketo wordt teruggestuurd.

![](assets/image2015-12-22-15-3a29-3a50.png)

>[!NOTE]
>
>De volgorde van deze stroomstappen is belangrijk vanwege de volgorde waarin acties worden uitgevoerd in Marketo. De **Programmastatus wijzigen** De stap verzendt de persoon naar ON24 om te registreren en een unieke URL wordt geproduceerd. Nadat dit gebeurt, kunt u het bevestigingsbericht met deze unieke URL verzenden gebruikend `{{member.webinar URL}}` token.
>
>Als de persoon wordt geretourneerd met een registratiefout, wordt de e-mailbevestiging niet ontvangen.

Uw volgende stap is: [De integratie van uw ON24-gebeurtenis testen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md){target=&quot;_blank&quot;}.

>[!MORELIKETHIS]
>
>* [Marketo ON24-adaptergebeurtenissen](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target=&quot;_blank&quot;}
>* [Voorbeeld ON24-gebeurtenisintegratie](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target=&quot;_blank&quot;}
>* [Werken met de status van het Webinar-programma](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md){target=&quot;_blank&quot;}

