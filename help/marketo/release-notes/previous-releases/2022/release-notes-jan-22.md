---
description: Opmerkingen bij de release - januari 2022 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - januari 2022
exl-id: babc4e7f-3f11-4883-80c6-58e69c3e1ab4
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '884'
ht-degree: 0%

---

# Opmerkingen bij de release: januari 2022 {#release-notes-jan-22}

De volgende functies zijn opgenomen in de release van 22 januari. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![ worden aangegeven ster ](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalversies_**

De volgende eigenschappen zullen beginnen om op **Januari 21, 2022**, met een gefaseerde uitrol van elke eigenschap over de volgende weken (tenzij anders gespecificeerd) worden vrijgegeven.

## Ervaring van de volgende generatie {#modern-ux}

* **Bijgewerkte Screens in de Ervaring van de Volgende-Generatie**: Wij leveren extra, verfrisste schermen in de volgende-generatieervaring die een bijgewerkt ontwerp en bruikbaarheidsverhogingen aanbieden die via knevelschakelaar toegankelijk zijn:

   * Gegevens over bestemmingspagina-element in [!UICONTROL Design Studio]
   * Gegevens over bestemmingspagina-element in [!UICONTROL Marketing Activities]

## [!DNL Microsoft Dynamics] Integratie {#microsoft-dynamics-integration}

* **die van het Multiselect Type van het Gebied van de Optie over het algemeen Beschikbaar** synchroniseert: Synchroniseer het multiselect type van optionset gebied van [!DNL Microsoft Dynamics] aan hefboomwerking in Slimme Lijsten en Slimme Campagnes voor meer korrelige publiek die richten. Voorbeelden zijn: onderwerpen/producten van belang, voorkeurscommunicatiemiddelen en meer. Deze nieuwe synchronisatie is beschikbaar voor [!DNL Microsoft Dynamics] versie 9.X (inclusief Dynamics 365 Online).

* **Server aan de Authentificatie van de Server voor[!DNL Microsoft Dynamics 365 Online]**: Voor verhoogde veiligheid, zullen wij nu Server aan Server (S2S) als extra wijze van authentificatie voor de de synchronisatiegebruiker van Marketo Engage op Azure Actieve Folder voor niet-interactieve toegang tot [!DNL Microsoft Dynamics 365 Online] steunen. Dit staat u toe om multi-factorauthentificatie aan te wenden, aangezien al authentificatie en sign-ons op OAuth (slechts cliëntidentiteitskaart en cliëntgeheim) zullen worden gebaseerd.

>[!NOTE]
>
>De S2S-modus is gebaseerd op de toepassingsgebruiker in plaats van de licentiegebruiker, die het gebruik van een aanvullende licentie opslaat.

## Beheer {#administration}

* **[Regels van de Bevestiging van de Vorm](/help/marketo/product-docs/administration/settings/global-form-validation-rules.md)**: Handhaaf de gezondheid van uw gegevensbestand met de capaciteit om problematische of ongewenste e-maildomeinen te blokkeren van het voorleggen van de vormen van Marketo Engage. Met het algemene deelvenster Regel voor formuliervalidatie kunnen beheerders een lijst van gewezen personen definiëren of een vooraf gedefinieerde lijst met gratis consumentendomeinen toestaan om formulieren te blokkeren.

* **[het Bestaan Veiligheid van de Kopbal van de Pagina](/help/marketo/product-docs/administration/settings/landing-page-headers.md)**: De beheerders kunnen de Strikte Veiligheid van het Vervoer en X-Kader de kopballen van Opties op hun het landen paginabereedschappen beheren om sterke veiligheidseisen af te dwingen.

**_vrijstellend door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

## AEP Marketo Engage-bestemmingsconnector - Nieuwe leads maken {#aep-marketo-engage-destination-connector}

Marketo Engage-klanten die ook de Adobe Experience Platform (AEP) gebruiken, kunnen hun database maximaliseren met de mogelijkheid om nieuwe persoonrecords van AEP via de AEP-doelconnector naar Marketo Engage te sturen. Wanneer het verzenden van publiekssegmenten van AEP naar Marketo Engage, kunnen de mensen binnen het segment die niet reeds in uw gegevensbestand van Marketo Engage [ bestaan automatisch aan het ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/push-an-adobe-experience-platform-segment-to-a-marketo-static-list.md) worden toegevoegd.

## [!DNL Sales Insight] {#sales-insight}

![ (star) ](assets/yellow-star.png)

**[!DNL Sales Insight]voor [!DNL Salesforce] CRM**

* **Nieuwe Kolom van het Type voor[!UICONTROL Best Bets]**: De verkopers zullen snellere inzichten met een nieuwe kolom krijgen geëtiketteerd &quot;Type&quot;om tussen lood en contacten op de [!UICONTROL Best Bets] pagina te onderscheiden.

* **[!DNL Salesforce]Platform API-update**: als reactie op [!DNL Salesforce] het annuleren van [!DNL Salesforce] Platform API-versies 21.0 tot en met 30.0 is het [!DNL Sales Insight] -pakket bijgewerkt met de nieuwste API&#39;s.

* **Bijgewerkte branding**: Alle [!DNL Sales Insight] pagina&#39;s worden bijgewerkt om met branding van Adobe te richten.

**[!DNL Sales Insight]for[!DNL Microsoft Dynamics]**

* **bijgewerkte Lay-out van de Rekening**: De verkopers kunnen een collectieve mening van de hoogste activiteiten zoals krijgen: e-mailactiviteiten, Webactiviteiten, interessante momenten, en scoreveranderingen voor alle contacten binnen een rekening.

## [!DNL Sales Connect] {#sales-connect}

![ (star) ](assets/yellow-star.png)

* **de Resultaten en de Redenen van de Vraag**: Begrijp en volg de uitgaande inspanningen van uw verkoopteams meer in detail met nieuwe, volledig klantgerichte vraaguitkomst en vraagredenopties. Naast deze nieuwe gebieden, introduceren wij nieuw bestuur om vraagreden en resultaatselectie af te dwingen terwijl de verkopers vraag maken, nieuw bestuur om vraagredenen en resultaten toe te laten of onbruikbaar te maken, en een nieuw de reden van de Vraag en het Uitkomsten van de Vraag [!DNL Salesforce] de douanegebied van de Activiteit van de Vraag voor het registreren van gegevens aan [!DNL Salesforce]. [ klik hier ](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812) om meer te leren.

* **[!DNL Salesforce]Aanpassing van activiteitsdetails**: leg meer verkoopactiviteiten en taakgegevens vast in [!DNL Salesforce] door aan te passen welke informatie wordt toegevoegd aan het [!DNL Salesforce] veld van het taakonderwerp wanneer een verkoopactiviteit aan [!DNL Salesforce] van [!DNL Sales Connect] wordt geregistreerd. [ klik hier ](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819) om meer te leren.

## Aankondigingen {#announcements}

* **Verdringing van Marketo Sky**: In Maart, zal Marketo Sky niet meer beschikbaar zijn aangezien wij onze middelen op het leveren van de volgende-generatiegebruikerservaring concentreren. In een poging om toegang te behouden tot functionaliteit die vandaag de dag exclusief is voor Marketo Sky, introduceren we Asset Expiration en Smart Campaign Priority Override in de mainstream-ervaring in maart. [ klik hier ](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33) om meer te leren.

* **Verdringing van de Eindpunten van de Vorm**: Niet gesteunde programmatic vorm POSTs aan het leadCapture/save2 eindpunt zal door de vormen van Marketo Engage worden verworpen. [ klik hier ](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631) om meer te leren.

* **Login nodigt de Dialoog van de Gebruiker uit**: In Maart, zal de bestaande, facultatieve eigenschap &quot;Login Uitnodigt de Dialoog van de Gebruiker&quot;worden afgekeurd. De eigenschap &quot;[!UICONTROL Login in Invite User Dialog]&quot;functionaliteit wordt met voeten getreden door de Universele eigenschap van identiteitskaart, die voor de aanstaande Integratie van het Systeem van Adobe Identity Management wordt vereist en in Augustus 2021 op alle abonnementen werd toegelaten. Als gevolg van de afgekeurde procedure vereist Marketo Engage dat slechts één gebruiker per e-mailadres in een abonnement wordt gekoppeld.

**de Domeinen van Marketo Engage - [!DNL Sales Insight] Configuratie**: Voor de domeinen van Marketo Engage die geen SSL cert hebben provisioned en https://, zullen de vraag met een SSL handshake fout ontbreken. Daarom zullen deze domeinen worden zonsondergang. Als gevolg hiervan kunnen [!DNL Sales Insight] -gebruikers met een oudere configuratie die naar een van deze domeinen verwijzen, op hun pagina Lead, Contact, Account, Opportunity Panels of Marketo Global fouten in de systeemcallout opsporen. Wij adviseren u uw [ configuratie van Marketo Engage ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md) in [!DNL Salesforce] bijwerkt als u in deze fout loopt. U hoeft alleen Marketo Engage-referenties bij te werken die zijn gemarkeerd in de sectie &quot;[!DNL Marketo Sales Insight] Config&quot;&quot; van het document.

**_Webinar van de Versie van het Product_**

[ Januari 2022 de Versie van Marketo Engage Webinar ](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)
