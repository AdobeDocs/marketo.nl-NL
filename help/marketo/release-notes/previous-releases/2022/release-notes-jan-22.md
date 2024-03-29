---
description: Opmerkingen bij de release - januari 2022 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - januari 2022
exl-id: babc4e7f-3f11-4883-80c6-58e69c3e1ab4
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '889'
ht-degree: 0%

---

# Opmerkingen bij de release: Januari 2022 {#release-notes-jan-22}

De volgende functies zijn opgenomen in de release van 22 januari. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Kenmerken die door een ster worden aangeduid (![ster](assets/yellow-star.png)) worden betaald als extra&#39;s. Neem contact op met uw Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalreleases_**

De volgende functies worden vrijgegeven op **21 januari 2022**, met een gefaseerde uitrol van elk onderdeel gedurende de volgende weken (tenzij anders aangegeven).

## Ervaring van de volgende generatie {#modern-ux}

* **Bijgewerkte schermen in de volgende generatie ervaring**: In de volgende generatie bieden we aanvullende, vernieuwde schermen die een bijgewerkt ontwerp en gebruiksverbeteringen bieden die via schakeloptie toegankelijk zijn:

   * Gegevens over bestemmingspagina&#39;s in Design Studio
   * Landingspagina — Gegevens over bedrijfsmiddelen bij marketingactiviteiten

## Integratie van Microsoft Dynamics {#microsoft-dynamics-integration}

* **Het synchroniseren van het Veldtype van de Optie Multiselect over het algemeen Beschikbaar**: Synchroniseer het multiselect optiesgebiedtype van de Dynamica van Microsoft aan hefboomwerking in Slimme Lijsten en Slimme Campagnes voor meer korrelige doelgroep. Voorbeelden zijn: onderwerpen/producten die van belang zijn, de voorkeur voor communicatiemiddelen en meer. Deze nieuwe synchronisatie is beschikbaar voor Microsoft Dynamics versie 9.X (inclusief Dynamics 365 Online).

* **Server-naar-server verificatie voor Microsoft Dynamics 365 Online**: Voor verhoogde veiligheid, zullen wij nu Server aan Server (S2S) als extra wijze van authentificatie voor de gebruiker van de Marketo Engage synchronisatie op Azure Actieve Folder voor niet-interactieve toegang tot de Dynamica 365 Online van Microsoft steunen. Dit staat u toe om multi-factorauthentificatie aan te wenden, aangezien al authentificatie en sign-ons op OAuth (slechts cliëntidentiteitskaart en cliëntgeheim) zullen worden gebaseerd.

>[!NOTE]
>
>De S2S-modus is gebaseerd op de toepassingsgebruiker in plaats van de licentiegebruiker, die het gebruik van een aanvullende licentie opslaat.

## Beheer {#administration}

* **[Validatieregels voor formulieren](/help/marketo/product-docs/administration/settings/global-form-validation-rules.md)**: Houd de status van uw database in stand met de mogelijkheid om problematische of ongewenste e-maildomeinen te blokkeren van het verzenden van Marketo Engage-formulieren. Met het algemene deelvenster Regel voor formuliervalidatie kunnen beheerders een lijst van gewezen personen definiëren of een vooraf gedefinieerde lijst met gratis consumentendomeinen toestaan om formulieren te blokkeren.

* **[Beveiliging koptekst van bestemmingspagina](/help/marketo/product-docs/administration/settings/landing-page-headers.md)**: De beheerders kunnen de Strikte kopballen van de Veiligheid van het Vervoer en x-Kader van Opties op hun landende paginaledomeinen beheren om sterke veiligheidseisen af te dwingen.

**_Vrijgeven door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

## AEP-Marketo Engage-bestemmingsconnector - Nieuwe netwerkleads maken {#aep-marketo-engage-destination-connector}

Marketo Engage klanten die ook de Adobe Experience Platform (AEP) gebruiken kunnen hun gegevensbestand met de capaciteit maximaliseren om net-nieuwe persoonverslagen in Marketo Engage van AEP via de AEP bestemmingsschakelaar te duwen. Wanneer het verzenden van publiekssegmenten van AEP naar Marketo Engage, mensen binnen het segment die niet reeds in uw gegevensbestand van Marketo Engage bestaan [kan er automatisch aan worden toegevoegd](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/push-an-adobe-experience-platform-segment-to-a-marketo-static-list.md).

## Verkoopoverzicht {#sales-insight}

![(ster)](assets/yellow-star.png)

**Verkoopoverzicht voor Salesforce CRM**

* **Nieuwe tekstkolom voor beste testmodellen**: Verkopers krijgen sneller inzicht in een nieuwe kolom met de naam &quot;Type&quot;, zodat ze onderscheid kunnen maken tussen leads en contactpersonen op de pagina Best Bets.

* **Update voor Salesforce Platform-API**: Als reactie op het afschaffen van Salesforce Platform API versies 21.0 tot en met 30.0 is het Sales Insight-pakket bijgewerkt met de nieuwste API&#39;s.

* **Bijgewerkte branding**: Alle pagina&#39;s van het Inzicht van de Verkoop worden bijgewerkt om zich aan de branding van Adobe te richten.

**Verkoopoverzicht voor Microsoft Dynamics**

* **Bijgewerkte accountlay-out**: Verkopers kunnen een collectieve weergave krijgen van de belangrijkste activiteiten, zoals: e-mailactiviteiten, webactiviteiten, interessante momenten en scorewijzigingen voor alle contactpersonen in een account.

## Verkoop Connect {#sales-connect}

![(ster)](assets/yellow-star.png)

* **Resultaten en redenen van de vraag**: Begrijp en volg de uitgaande inspanningen van uw verkoopteams meer in detail met nieuwe, volledig klantgerichte vraaguitkomst en vraagredenopties. Naast deze nieuwe gebieden, introduceren wij nieuw bestuur om vraagreden en resultaatselectie af te dwingen terwijl de verkopers vraag maken, nieuw bestuur om vraagredenen en uitkomsten toe te laten of onbruikbaar te maken, en een nieuw de douanegebied van de Reden van de Vraag en van de Actie van Salesforce van het Uitkomen van de Vraag voor het registreren van gegevens aan Salesforce. [Klik hier](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812) voor meer informatie.

* **Aanpassing Salesforce Activity Detail**: Vang meer verkoopactiviteit en taakgegevens in Salesforce door aan te passen welke informatie aan het de taakonderwerpgebied van Salesforce wordt toegevoegd wanneer een verkoopactiviteit aan Salesforce van de Verkoop Connect wordt geregistreerd. [Klik hier](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819) voor meer informatie.

## Aankondigingen {#announcements}

* **Marketo Sky Deprectie**: In maart is Marketo Sky niet meer beschikbaar omdat we onze bronnen richten op het bieden van de gebruikerservaring van de volgende generatie. In een poging om toegang te behouden tot functionaliteit die exclusief is voor Marketo Sky vandaag, brengen we Asset Expiration en Smart Campaign Priority Override in maart in de mainstream-ervaring. [Klik hier](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33) voor meer informatie.

* **Vervalsing van eindpunten van formulier**: Niet-ondersteunde POST&#39;s van programmatische formulieren naar het eindpunt leadCapture/save2 worden door Marketo Engage-formulieren afgewezen. [Klik hier](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631) voor meer informatie.

**Marketo Engage Domeinen - Configuratie van het Inzicht van de Verkoop**: Voor Marketo Engage domeinen die geen SSL cert hebben provisioned en https://, zullen de vraag met een SSL handshake fout ontbreken. Daarom zullen deze domeinen worden zonsondergang. Dientengevolge, zouden de gebruikers van het Inzicht van de Verkoop met een oudere configuratie die aan om het even welk van deze domeinen richten in de fouten van de systeemcallout op hun Lood, Contact, Rekening, de Panelen van de Opportunity, of Globale pagina van Marketo kunnen lopen. We raden u aan uw [Marketo Engage-configuratie](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md) in Salesforce als deze fout optreedt. U hoeft alleen de gegevens voor Marketo Engage bij te werken die zijn gemarkeerd in de sectie &quot;Marketo Sales Insight Config&quot; van het document.

**_Webinar productrelease_**

[Januari 2022 de Versie Webinar van de Marketo Engage](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)
