---
unique-page-id: 14746188
description: Abonnementen synchroniseren met Salesforce - Marketo Docs - Productdocumentatie
title: Abonnementen synchroniseren met Salesforce
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 0%

---


# Abonnementen synchroniseren met Salesforce {#syncing-unsubscribes-with-salesforce}

## Vereisten voor Afmelden voor synchronisatie met Salesforce {#requirements-for-unsubscribes-to-sync-to-salesforce}

* Synchronisatie voor afmelden moet zijn ingeschakeld (voor nachtelijke synchronisatie)
* Het veld Uitschakelen moet in Salesforce zijn geïnstalleerd
* De persoonlijke records in Sales Connect moeten een Salesforce-id hebben

**Abonnement op push opzeggen**

Wanneer een abonnement wordt opgehaald in Sales Connect, wordt dit in real-time naar Salesforce verzonden en worden de velden voor Weigeren bijgewerkt waarmee u hebt geselecteerd voor synchronisatie. Als u de Salesforce-synchronisatie hebt uitgeschakeld, wordt het abonnement nog steeds doorgestuurd naar de e-mailoptie.

**Synchronisatie opzeggen**

Wanneer u de synchronisatie voor afmelden hebt ingeschakeld (stap 3 hieronder), schakelt u de nachtelijke synchronisatie in. De synchronisatie vindt eenmaal per dag plaats rond 20:00 PST. Het zal bidirectioneel alle unsubscribes in MSE/ToutApp met het Opt gebied in Salesforce synchroniseren.

## Synchronisatie van abonnement op Salesforce {#configure-unsubscribe-sync-to-salesforce} configureren

Gebruikers kunnen beslissen of ze hun afmeldingsgegevens willen synchroniseren met het standaardveld Afmelden via e-mail dat Marketo ook kan synchroniseren met, of ze kunnen synchroniseren met het veld Afmelden bij markt, zodat Afmelden bij verkoop en Afmelden bij marketing kunnen worden gedifferentieerd.

1. Ga naar [webtoepassing](https://toutapp.com/login), klik op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/one-1.png)

1. Selecteer **Abonnementen** onder Beheerinstellingen.

   ![](assets/two-2.png)

1. Klik **Synchroniseren met Salesforce** en schakel vervolgens de nachtelijke synchronisatie in.

   ![](assets/three-2.png)

1. Selecteer het veld waarmee u wilt synchroniseren.

   ![](assets/4.png)

   | Veld | Beschrijving |
   |---|---|
   | **Sync to Salesforce Opt Out field** | Hiermee wordt het veld Salesforce Opt Out standaard alleen bijgewerkt. |
   | **Sync to Marketo Sales Opt Out field** | Als u verkoop en Marketing wilt scheiden unsubscribes, verkies deze optie om extra [van de Verkoop van de Marketo uit gebied bij te werken.](#msoo) |

## Het veld Weigeren installeren in de paginalayout {#installing-the-opt-out-field-in-the-page-layout}

**E-mail uitschakelen**

Email Opt Out is een standaardveld in Salesforce dat beschikbaar is om te installeren vanaf Salesforce. U moet een Salesforce Admin zijn om het te installeren.

1. Ga naar [Salesforce.com](https://salesforce.com) en meld u aan.

   ![](assets/five-1.png)

1. Klik uw gebruikersbenaming en selecteer **Opstelling**.

   ![](assets/six-1.png)

1. Zoek in het vak Snel zoeken naar Contactpersoon of Lead. In dit scenario installeren wij het gebied aan de de paginalay-out van het Contact, maar u zult voor beide persoonverslagen willen installeren.

   ![](assets/seven-1.png)

1. Selecteer **Pagina-indelingen**.

   ![](assets/eight-1.png)

1. Selecteer **Bewerken** naast de paginalay-out waaraan u het veld wilt toevoegen.

   ![](assets/nine.png)

1. Selecteer **Velden**.

   ![](assets/ten.png)

1. Sleep e-mail Opt-out naar de pagina-indeling.

   ![](assets/11.png)

1. Klik **Opslaan**.

   ![](assets/twelve.png)

## Marketo Sales Opt-out {#marketo-sales-opt-out}

Het veld Aftellen bij verkoop bij voorkeur uit is een aangepast veld dat beschikbaar is voor gebruikers die de Aanpassingen voor afzetten bij verkoop hebben geïnstalleerd.

Zodra u met succes de Aanpassingen van de Verkoop van de Marketo in Salesforce hebt geïnstalleerd, zult u het van de Verkoop van de Marketo van de Verkoop beschikbare gebied zien.
