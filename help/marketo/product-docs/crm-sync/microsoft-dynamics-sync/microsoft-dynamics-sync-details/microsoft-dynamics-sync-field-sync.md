---
unique-page-id: 3571838
description: Microsoft Dynamics Sync -Field Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Field Sync
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '364'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Veldsynchronisatie {#microsoft-dynamics-sync-field-sync}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

Synchronisatie tussen Marketo en Dynamics is bijzonder krachtig. Hier zijn de details.

## Hoe worden de velddetails synchroon gehouden tussen de twee systemen? {#how-are-field-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel voor lood en contactentiteiten. Als u veranderingen in een lood of een contact in Dynamiek of een persoon in Marketo aanbrengt, zullen uw updates in beide systemen worden weerspiegeld.

Voor account, gebruiker, opportunity, team en aangepaste entiteiten is de synchronisatie in één richting: Dynamiek naar Marketo. Als u wijzigingen aanbrengt in deze entiteiten in Dynamiek, worden uw updates weerspiegeld in Marketo.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo voor mensen (lood) winnen en de Dynamiek voor contacten zal winnen. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is. Bij one-way sync-entiteiten wint Dynamics altijd.

## Kan ik een veld in Dynamiek creëren gebruikend Marketo? {#can-i-create-a-field-in-dynamics-using-marketo}

Nee, dit wordt momenteel niet ondersteund.

## Ik creëerde een veld in Dynamics. Kan ik het synchroniseren met Marketo? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

Ja, u kunt het veld [](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) synchroniseren zolang de synchronisatiegebruiker er toegang toe heeft in Dynamics.

Welke velden worden gesynchroniseerd met Marketo?

U kunt velden [selecteren die u tijdens de installatie wilt synchroniseren](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) .

## Wat als ik een douanegebied moet toevoegen nadat de Marketo en de Dynamica worden gesynchroniseerd? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

U kunt velden op elk gewenst moment toevoegen en verwachten dat de gegevens worden vernieuwd van Dynamiek naar Marketo. Zie Snelle synchronisatie [gebruiken met de Dynamica van Microsoft voor een Nieuw Geheime](microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) van de Douane voor details.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Snelle synchronisatie gebruiken met Microsoft Dynamics voor een nieuw aangepast veld](microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md)

>



