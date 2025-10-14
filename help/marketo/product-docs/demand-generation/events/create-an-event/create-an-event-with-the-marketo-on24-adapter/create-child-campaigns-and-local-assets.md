---
unique-page-id: 10096675
description: Onderliggende campagnes en lokale Assets maken - Marketo Docs - Productdocumentatie
title: Onderliggende campagnes en lokale Assets maken
exl-id: 272105e1-43d6-455c-a533-aae65e859384
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '650'
ht-degree: 1%

---

# Onderliggende campagnes en lokale Assets maken {#create-child-campaigns-and-local-assets}

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
>Gebruik de volgende token in uw e-mail: `{{member.webinar url}}` om het bevestigingsbericht te vullen met deze unieke URL. Wanneer u de bevestiging-URL verzendt, wordt deze token automatisch omgezet in de unieke bevestiging-URL van de persoon.
>
>Plaats het type van uw bevestigingse-mail aan **Operationeel** om ervoor te zorgen dat de mensen die hun bevestigingsinformatie registreren ontvangen, zelfs als zij unsubscribed zijn.

>[!TIP]
>
>U kunt ON24 configureren voor het verzenden van e-mails voor bevestiging, herinnering of follow-up. Zie de [&#x200B; ON24 Plaats van de Hulp &#x200B;](https://support.on24.com/hc/en-us/categories/26127314569115-Webcast-Elite){target="_blank"} voor meer informatie.

## Vereisten voor onderliggende campagne registreren {#registration-child-campaign-requirements}

Gebeurtenissen bevatten een of meer onderliggende campagnes die allemaal samenwerken om mensen door de status van het programma te bewegen en u in staat te stellen de prestaties van de gebeurtenis te volgen.

Voorbeelden van kindercampagnes zijn een uitnodigingscampagne, een registratiecampagne en follow-upcampagnes.

>[!CAUTION]
>
>De adapter kan zijn taak alleen uitvoeren als u een registratiecampagne maakt. Deze campagne moet door de persoon worden teweeggebracht die een vorm invult, en de eerste stap moet de het programmastatus van de persoon in **Geregistreerd** veranderen. De campagne stuurt vervolgens een bevestigingsbericht. Zie de rest van dit artikel voor meer informatie.

**Registratie/Bevestiging (de Campagne van de Trekker)**

* Slimme lijst
* De trekker die op **wordt gebaseerd vult Vorm** uit. Ben zeker om de het landen pagina te omvatten die de vorm op door **te gebruiken Add Beperking** leeft, vooral als de zelfde vorm op veelvoudige het landen pagina&#39;s wordt gebruikt.

>[!CAUTION]
>
>U moet een Marketo-formulier gebruiken om uw personen voor de gebeurtenis te registreren, of een niet-Marketo-formulier met de juiste API-integratie om registratiegegevens naar Marketo te verzenden. Dit is essentieel voor het succes van de integratie van uw gebeurtenispartner.

>[!NOTE]
>
>Als u een Marketo-formulier gebruikt op een landingspagina die geen Marketo is, is de trigger **[!UICONTROL Fills out Form]** met de [!UICONTROL Form Name] .

![](assets/image2015-12-22-15-3a20-3a51.png)

**Stroom**

* **[!UICONTROL Change Program Status]** - Instellen op webinar -> Geregistreerd.

Deze stroomstap is vereist als de EERSTE STROOMSTAP bij het instellen van uw onderliggende campagne. Wanneer de status van het programma van een persoon verandert in Geregistreerd, plaatst Marketo de registratiegegevens op ON24. Geen andere status zal de persoon over duwen.

* **[!UICONTROL Send Email]** - Bevestigingse-mail. Plaats deze e-mail aan **Operationeel** zodat unsubscribed mensen die nog het hebben geregistreerd ontvangen.

De **[!UICONTROL Send Email]** -stap MOET de tweede stap zijn. Het bevestigingsbericht bevat de `{{member.webinar url}}` , die wordt gevuld met informatie die vanuit ON24 naar Marketo wordt verzonden.

![](assets/image2015-12-22-15-3a29-3a50.png)

>[!NOTE]
>
>De volgorde van deze stroomstappen is belangrijk vanwege de volgorde waarin acties worden uitgevoerd in Marketo. De stap **[!UICONTROL Change Program Status]** verzendt de persoon naar ON24 om te registreren en een unieke URL wordt geproduceerd. Hierna kunt u het bevestigingsbericht met deze unieke URL verzenden met de token `{{member.webinar URL}}` .
>
>Als de persoon wordt geretourneerd met een registratiefout, wordt de e-mailbevestiging niet ontvangen.

Uw volgende stap moet [&#x200B; Uw ON24 gebeurtenisintegratie &#x200B;](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md){target="_blank"} testen.

>[!MORELIKETHIS]
>
>* [&#x200B; Begrip Marketo ON24 adaptergebeurtenissen &#x200B;](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
>* [&#x200B; Voorbeeld ON24 de Integratie van de Gebeurtenis &#x200B;](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target="_blank"}
>* [&#x200B; Begrijpend de Statussen van het Programma Webinar &#x200B;](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md){target="_blank"}
