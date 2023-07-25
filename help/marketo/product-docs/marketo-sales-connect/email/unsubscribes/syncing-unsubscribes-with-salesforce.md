---
unique-page-id: 14746188
description: Abonnementen synchroniseren met Salesforce - Marketo Docs - Productdocumentatie
title: Abonnementen synchroniseren met Salesforce
exl-id: 1694d7bf-d2f6-4950-8a3e-c7d89c37b276
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
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

Wanneer u de synchronisatie voor afmelden hebt ingeschakeld (stap 3 hieronder), schakelt u de nachtelijke synchronisatie in. De synchronisatie vindt eenmaal per dag plaats rond 20:00 PST. Het zal bidirectioneel alle unsubscribes in de Verkoop van Marketo met het Opt gebied in Salesforce synchroniseren.

## Synchronisatie van abonnement op Salesforce configureren {#configure-unsubscribe-sync-to-salesforce}

Gebruikers kunnen beslissen of ze hun afmeldingsgegevens willen synchroniseren met het standaardveld Afmelden via e-mail dat Marketo ook kan synchroniseren met, of ze kunnen synchroniseren met het veld Afmelden bij Marketo zodat Afmelden bij verkoop en Afmelden bij marketing kunnen worden gedifferentieerd.

1. Ga naar de [webtoepassing](https://toutapp.com/login), klikt u op het tandwielpictogram en selecteert u **Instellingen**.

   ![](assets/one-1.png)

1. Onder beheerinstellingen selecteert u **Abonnementen opzeggen**.

   ![](assets/two-2.png)

1. Klikken **Synchroniseren met Salesforce** Schakel vervolgens de nachtelijke synchronisatie in.

   ![](assets/three-2.png)

1. Selecteer het veld waarmee u wilt synchroniseren.

   ![](assets/4.png)

   | Veld | Beschrijving |
   |---|---|
   | **Sync to Salesforce Opt Out field** | Hiermee wordt het veld Salesforce Opt Out standaard alleen bijgewerkt. |
   | **Het veld Afmelden bij Marketo synchroniseren** | Als je afschriften van verkoop en marketing wilt scheiden, kies dan deze optie om extra [Het veld Marketo Sales Opt Out.](#msoo) |

## Het veld Weigeren installeren in de paginalayout {#installing-the-opt-out-field-in-the-page-layout}

**E-mail uitschakelen**

Email Opt Out is een standaardveld in Salesforce dat beschikbaar is om te installeren vanaf Salesforce. U moet een Salesforce Admin zijn om het te installeren.

1. Ga naar [Salesforce.com](https://salesforce.com) en meld u aan.

   ![](assets/five-1.png)

1. Klik op uw gebruikersnaam en selecteer **Instellen**.

   ![](assets/six-1.png)

1. Zoek in het vak Snel zoeken naar Contactpersoon of Lead. In dit scenario installeren wij het gebied aan de de paginalay-out van het Contact, maar u zult voor beide persoonverslagen willen installeren.

   ![](assets/seven-1.png)

1. Selecteren **Pagina-indelingen**.

   ![](assets/eight-1.png)

1. Selecteren **Bewerken** naast de pagina-indeling waaraan u het veld wilt toevoegen.

   ![](assets/nine.png)

1. Selecteren **Velden**.

   ![](assets/ten.png)

1. Sleep e-mail Opt-out naar de pagina-indeling.

   ![](assets/11.png)

1. Klikken **Opslaan**.

   ![](assets/twelve.png)

## Marketo-verkoop niet beschikbaar {#marketo-sales-opt-out}

Het veld Marketo Sales Opt Out is een aangepast veld dat beschikbaar is voor gebruikers die Marketo Sales Connect Customizations hebben geïnstalleerd.

Zodra u de Marketo Sales Connect Customizations in Salesforce hebt geïnstalleerd, wordt het veld Marketo Sales Opt Out weergegeven dat voor u beschikbaar is.
