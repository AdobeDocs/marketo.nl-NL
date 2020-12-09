---
unique-page-id: 10096675
description: Onderliggende campagnes en lokale middelen maken - Marketo Docs - Productdocumentatie
title: Onderliggende campagnes en lokale elementen maken
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '673'
ht-degree: 0%

---


# Onderliggende campagnes en lokale elementen maken {#create-child-campaigns-and-local-assets}

Creeer uw kindcampagnes en lokale activa gebruikend de Studio van het Ontwerp.

## Openingspagina en -formulier {#landing-page-and-form}

Om ervoor te zorgen dat mensen correct bij ON24 worden geregistreerd, moeten de volgende gebieden in uw vorm van het Marketo worden omvat:

* Voornaam
* Achternaam
* E-mailadres

U kunt ook de volgende velden naar ON24 duwen:

* Bedrijfsnaam
* Functie

Met de juiste stroomstap toegevoegd aan de registratiecampagne, zullen de mensen aan ON24 worden geduwd en als geregistreerd worden gemerkt. U kunt andere velden aan het formulier toevoegen en de gegevens worden in Marketo vastgelegd als onderdeel van de persoondetails-record.

>[!CAUTION]
>
>Voor een geslaagde integratie moet u een Marketo-formulier gebruiken om uw personen voor de gebeurtenis te registreren, of een niet-Marketo-formulier met de juiste API-integratie om registratiegegevens naar Marketo te verzenden.

## E-mails en URL-tokens {#emails-and-url-tokens}

Maak de uitnodiging, bevestiging, follow-up en dank u voor e-mails met Marketo.

## E-mail- en URL-token voor markeringsbevestiging {#marketo-confirmation-email-and-url-token}

Gebruik Marketo om het bevestigingsbericht voor uw gebeurtenis te verzenden. Wanneer een persoon zich registreert, ontvangt hij of zij een unieke URL om de gebeurtenis in te voeren.

>[!NOTE]
>
>**Herinnering**
>
>Gebruik de volgende token in uw e-mail om het bevestigingsbericht te vullen met deze unieke URL: `{{member.webinar url}}`. Wanneer u de bevestiging-URL verzendt, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
>
>Stel het type bevestigingsbericht in op **Operationeel** om ervoor te zorgen dat personen die zich registreren hun bevestigingsgegevens ontvangen, zelfs als ze niet zijn geabonneerd.

>[!TIP]
>
>U kunt ON24 configureren voor het verzenden van e-mails voor bevestiging, herinnering of follow-up. Raadpleeg de [ON24 Help-site](http://webcastelitehelp.on24.com) voor meer informatie.

## Vereisten voor onderliggende campagne registreren {#registration-child-campaign-requirements}

Gebeurtenissen bevatten een of meer onderliggende campagnes die allemaal samenwerken om mensen door de status van het programma te bewegen en u in staat te stellen de prestaties van de gebeurtenis te volgen.

Voorbeelden van kindercampagnes zijn een uitnodigingscampagne, een registratiecampagne en vervolgcampagnes.

>[!CAUTION]
>
>De adapter kan zijn taak alleen uitvoeren als u een registratiecampagne maakt. Deze campagne moet worden geactiveerd door de persoon die een formulier invult en in de eerste stap moet de status van het programma van de persoon worden gewijzigd in **Geregistreerd**. De campagne stuurt vervolgens een bevestigingsbericht. Zie de rest van dit artikel voor meer informatie.

**Registratie/bevestiging (Trigger-campagne)**

* Slimme lijst
* Trigger op basis van formulier **** invult. Zorg ervoor dat u de openingspagina opneemt waarop het formulier zich bevindt door Restrictie **** toevoegen te gebruiken, vooral als hetzelfde formulier op meerdere bestemmingspagina&#39;s wordt gebruikt.

>[!CAUTION]
>
>U moet een Marketo-formulier gebruiken om uw personen voor de gebeurtenis te registreren, of een niet-Marketo-formulier met de juiste API-integratie om registratiegegevens naar Marketo te verzenden. Dit is essentieel voor het succes van de integratie van uw gebeurtenispartner.

>[!NOTE]
>
>Als u een Marketo-formulier gebruikt op een landingspagina die geen Marketo is, wordt de trigger Formulier **** invullen met de naam van het formulier.

![](assets/image2015-12-22-15-3a20-3a51.png)

**Stroom**

* **Program Status** wijzigen - Instellen op Webinar -> Geregistreerd.

Deze stroomstap is vereist als de EERSTE STROOMSTAP bij het instellen van uw onderliggende campagne. Wanneer de de programmastatus van een persoon in Geregistreerd verandert, drukt Marketo de registratieinformatie aan ON24. Geen andere status zal de persoon over duwen.

* **E-mail** verzenden - Bevestiging e-mail. Stel deze e-mail in op **Operationeel** zodat niet-geabonneerde personen die zich hebben geregistreerd deze nog ontvangen.

De stap E-mail **** verzenden MOET de tweede stap zijn. Het bevestigingsbericht bevat het bericht `{{member.webinar url}}`, dat wordt gevuld met informatie die vanuit ON24 naar Marketo wordt teruggestuurd.

![](assets/image2015-12-22-15-3a29-3a50.png)

>[!NOTE]
>
>De volgorde van deze stroomstappen is belangrijk vanwege de volgorde waarin handelingen worden uitgevoerd in Marketo. De stap Status **van programma** wijzigen verzendt de persoon naar ON24 om te registreren en er wordt een unieke URL gegenereerd. Hierna kunt u het bevestigingsbericht met deze unieke URL verzenden met de `{{member.webinar URL}}` token.
>
>Als de persoon wordt geretourneerd met een registratiefout, wordt de e-mailbevestiging niet ontvangen.

Uw volgende stap bestaat uit het [testen van de integratie](test-your-on24-event-integration.md)van uw ON24-gebeurtenis.

>[!MORELIKETHIS]
>
>* [Inzicht in Marketo ON24-adaptergebeurtenissen](understanding-marketo-on24-adapter-events.md)
>* [Voorbeeld ON24-gebeurtenisintegratie](example-on24-event-integration.md)
>* [Werken met de status van het Webinar-programma](understanding-webinar-program-statuses.md)
>* [ON24-gebeurtenisintegratie testen](test-your-on24-event-integration.md)

>



