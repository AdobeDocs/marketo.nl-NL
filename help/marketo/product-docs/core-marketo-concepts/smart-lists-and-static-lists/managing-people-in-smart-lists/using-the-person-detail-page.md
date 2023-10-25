---
unique-page-id: 2953415
description: De persoonlijke detailpagina gebruiken - Marketo Docs - Productdocumentatie
title: De detailpagina voor personen gebruiken
exl-id: 8476ed02-6d94-4aa5-91f6-55c81a87f745
feature: Smart Lists
source-git-commit: 208ba59e3a5cb8e613e887b4c89e51cec4b3f897
workflow-type: tm+mt
source-wordcount: '550'
ht-degree: 13%

---

# De detailpagina voor personen gebruiken {#using-the-person-detail-page}

De pagina met persoonlijke details bevat alle informatie die Marketo over een persoon weet. U kunt gegevens rechtstreeks vanaf deze pagina bewerken.

## Aan Personen met detailpagina {#getting-to-person-detail-page}

Er zijn veel manieren om specifieke mensen te openen. Enkele voorbeelden zijn:

* Van de **Database**, kunt u zoeken in Snel zoeken
* Alle **Slimme lijst** of lijst
* **Leden** tabblad van een programma
* **Campagneleden weergeven** in een slimme campagne
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
>U kunt ook informatie over opportunity zien [ingevoegd via API](https://developers.marketo.com/rest-api/lead-database/opportunities/) voor instanties die niet zijn gesynchroniseerd met een CRM.

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
| Bron persoon | Status | Telefoon | Marketo Social Facebook Display Name | Marketo Social Facebook ID |
| Marketo Social Facebook Foto-URL | Marketo Social Facebook Profile URL | Marketo Social Facebook Reach | Inschrijvingen verwezen naar Marketo Social Facebook | Bezoeken verwezen naar Marketo Social Facebook |
| Marketo Social Gender | Inschrijving als laatste verwijzing voor Marketo Social | Bezoek van laatst vermelde Marketo Social | Marketo Social LinkedIn Display Name | Marketo Social LinkedIn ID |
| Marketo Social LinkedIn Foto-URL | Marketo Social LinkedIn Profile URL | Marketo Social LinkedIn Reach | Inschrijvingen verwezen naar Marketo Social LinkedIn | Bezoeken verwezen naar Marketo Social LinkedIn |
| Marketo Social Syndication ID | Marketo Social Total Vermeld inschrijvingen | Marketo Sociale Totaal Aangewezen bezoeken | Weergavenaam sociale Twitter van Marketo | Marketo ID sociale Twitter |
| Marketo Sociale Twitter Foto-URL | Marketo URL profiel voor sociale Twitter | Marketo Social Twitter Reach | Sociale Twitter van Marketo — Inschrijvingen | Bezoeken van de sociale Twitter van Marketo |
| Tussenvoegsel | Mobiel | Aantal werknemers | Telefoonnummer | Postcode |
| Prioriteit | Relatieve score | Functie | Aanhef | SIC-code |
| Vestiging | Staat | Niet geabonneerd | Reden voor niet geabonneerd | Bijgewerkt op |
| Urgentie | Website |  |  |  |

>[!NOTE]
>
>Sommige velden zijn _niet_ bewerkbaar:
>
>* Activiteitenlogboek
>* Bedrijfsgegevens
>* Mogelijkheden voor SFDC-contactpersonen
>* Bepaalde Marketo-specifieke velden, zoals Aanmaakdatum en Oorspronkelijk brontype.
>
>Meer informatie over [Door het systeem beheerde velden](/help/marketo/product-docs/administration/field-management/understanding-system-managed-fields.md){target="_blank"}.

>[!MORELIKETHIS]
>
>[Een aangepast tabblad maken voor de detailpagina voor personen](/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md){target="_blank"}
