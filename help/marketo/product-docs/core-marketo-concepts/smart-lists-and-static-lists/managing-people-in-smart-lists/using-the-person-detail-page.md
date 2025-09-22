---
unique-page-id: 2953415
description: De persoonlijke detailpagina gebruiken - Marketo Docs - Productdocumentatie
title: De detailpagina voor personen gebruiken
exl-id: 8476ed02-6d94-4aa5-91f6-55c81a87f745
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '525'
ht-degree: 14%

---

# De detailpagina voor personen gebruiken {#using-the-person-detail-page}

De pagina met persoonlijke details bevat alle informatie die Marketo over een persoon weet. U kunt gegevens rechtstreeks vanaf deze pagina bewerken.

## Aan Personen met detailpagina {#getting-to-person-detail-page}

Er zijn veel manieren om specifieke mensen te openen. Enkele voorbeelden zijn:

* Van het **Gegevensbestand**, kunt u in de Snelle Vondst zoeken
* Om het even welke **Slimme Lijst** of lijst
* **Leden** lusje van een programma
* **de Leden van de Campagne van de Mening** in een Slimme Campagne
* Sommige **rapporten**
  <br> 

1. Dubbelklik op een willekeurige persoon of klik op de id aan de linkerkant.

   ![](assets/one-1.png)

1. Hiermee wordt het detailscherm van de persoon geopend.

   ![](assets/two-5.png)

## Paginaorganisatie - Salesforce {#page-organization-salesforce}

Persoonsgegevens worden gecategoriseerd in de volgende tabbladen:

| Tab | Beschrijving |
|---|---|
| Info | Contactgegevens en aangepaste velden voor een persoon. |
| Bedrijfsgegevens | Informatie en adres van het bedrijf van de persoon. |
| Opportunity-info | Opportunity-informatie gesynchroniseerd vanuit Salesforce. |
| SFDC Lead Field | Ingebouwde Salesforce-velden. |
| Aangepast SFDC-veld | Aangepaste Salesforce-velden. |
| Activiteitenlogboek | Alle activiteiten met betrekking tot de persoon. |

## Paginaorganisatie - Microsoft Dynamics {#page-organization-microsoft-dynamics}

| Tab | Beschrijving |
|---|---|
| Info | Contactgegevens en aangepaste velden voor een persoon. |
| Bedrijfsgegevens | Informatie en adres van het bedrijf van de persoon. |
| Opportunity-info | Opportunity-informatie gesynchroniseerd vanuit Microsoft. |
| Aangepaste Microsoft-velden | Aangepaste Microsoft-velden. |
| Microsoft Lead Field | Ingebouwde Microsoft-velden. |
| Activiteitenlogboek | Alle activiteiten met betrekking tot de persoon. |

>[!NOTE]
>
>U kunt de info van de Kans [ ook zien die via API ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities) voor instanties wordt opgenomen die niet met CRM worden gesynchroniseerd.

## Een veld bewerken {#editing-a-field}

Veel velden kunnen worden bewerkt. Als u de gegevens van een persoon wilt bijwerken, typt u een nieuwe waarde en klikt u buiten het veld dat u wilt opslaan.

![](assets/image2015-2-27-11-3a14-3a2.png)

## Marketo-standaardvelden voorafgaand aan CRM-synchronisatie {#marketo-default-fields-prior-to-crm-sync}

|   |  |  |  |  |
|---|---|---|---|---|
| Adres | Jaaromzet | Anoniem IP-adres | Factuuradres | Factuurstad |
| Factuurland | Factuurpostcode | Factuurstaat | Stad | Bedrijfsnaam |
| Land | Gemaakt op | Geboortedatum | Afdeling | Niet bellen |
| Geen oorzaak aanroepen | Reden voor niet bellen | E-mailadres | E-mail ongeldig | Ongeldige oorzaak e-mail |
| Externe bedrijfs-id | Id externe verkoper | Faxnummer | Voornaam | Volledige naam |
| Marktsegment | Overgenomen stad | Afgeleid bedrijf | Afgeleid land | Overgenomen metropolitaans gebied |
| Gebiedscode afgeleide telefoon | Postcode | Gebied van de betrokken staat | Is anoniem | Is klant |
| Is partner | Beroep | Achternaam | Classificatie | Score |
| Person Source | Status | Telefoon | Marketo Social-weergavenaam [!DNL Facebook] | Marketo Social [!DNL Facebook] ID |
| Marketo Social-URL [!DNL Facebook] | Marketo Social [!DNL Facebook] Profile URL | Marketo Social [!DNL Facebook] Reach | Marketo Social [!DNL Facebook] (Aangewezen inschrijvingen) | Sociale bezoeken van Marketo [!DNL Facebook] |
| Marketo Social Gender | Inschrijving als laatste verwijzing voor Marketo Social | Bezoek van laatst vermelde Marketo Social | Marketo Social-weergavenaam [!DNL LinkedIn] | Marketo Social [!DNL LinkedIn] ID |
| Marketo Social-URL [!DNL LinkedIn] | Marketo Social [!DNL LinkedIn] Profile URL | Marketo Social [!DNL LinkedIn] Reach | Marketo Social [!DNL LinkedIn] (Aangewezen inschrijvingen) | Sociale bezoeken van Marketo [!DNL LinkedIn] |
| Marketo Social Syndication ID | Marketo Social Total Vermeld inschrijvingen | Marketo Sociale Totaal Aangewezen bezoeken | Marketo Social-weergavenaam [!DNL Twitter] | Marketo Social [!DNL Twitter] ID |
| Marketo Social-URL [!DNL Twitter] | Marketo Social [!DNL Twitter] Profile URL | Marketo Social [!DNL Twitter] Reach | Marketo Social [!DNL Twitter] (Aangewezen inschrijvingen) | Sociale bezoeken van Marketo [!DNL Twitter] |
| Tussenvoegsel | Mobiel | Aantal werknemers | Telefoonnummer | Postcode |
| Prioriteit | Relatieve score | Functie | Aanhef | SIC-code |
| Vestiging | Staat | Niet geabonneerd | Reden voor niet geabonneerd | Bijgewerkt op |
| Urgentie | Website |  |  |  |

>[!NOTE]
>
>Sommige gebieden zijn _niet_ editable:
>
>* Activiteitenlogboek
>* Bedrijfsgegevens
>* Mogelijkheden voor SFDC-contactpersonen
>* Bepaalde Marketo-specifieke velden, zoals Aanmaakdatum en Oorspronkelijk Source-type.
>
>Leer meer over [ Systeem Beheerde Gebieden ](/help/marketo/product-docs/administration/field-management/understanding-system-managed-fields.md){target="_blank"}.

>[!MORELIKETHIS]
>
>[ Creërend een Lusje van de Douane voor de Pagina van het Detail van de Persoon ](/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md){target="_blank"}
