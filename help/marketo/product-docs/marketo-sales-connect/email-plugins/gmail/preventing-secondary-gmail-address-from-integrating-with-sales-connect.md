---
unique-page-id: 14352546
description: Voorkomen dat Secundair Gmail-adres wordt geïntegreerd met Sales Connect - Marketo Docs - Productdocumentatie
title: Voorkomen dat Secundair Gmail-adres wordt geïntegreerd met Sales Connect
exl-id: a84fe53b-0ec8-400c-8747-be496c68a8e3
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---

# Voorkomen dat Secundair Gmail-adres wordt geïntegreerd met [!DNL Sales Connect] {#preventing-secondary-gmail-address-from-integrating-with-sales-connect}

## Gebroken Gmail-integratie (waarom verzendt mijn persoonlijke Gmail e-mail) {#broken-gmail-integration-why-is-my-personal-gmail-sending-emails}

De meest voorkomende reden voor een verbroken Gmail-verbinding is een onbedoelde integratie met de persoonlijke account van een gebruiker. Dit kan gebeuren wanneer een gebruiker op &quot;Verbinding maken&quot; klikt of wanneer hij of zij een e-mail probeert te verzenden via zijn of haar persoonlijke account. Dit kan zeer verleidelijk zijn om te doen omdat de optie zal bestaan wanneer het toegang tot van uw Gmail- rekening in de zelfde instantie van [!DNL Chrome] zoals uw werk e-mail.

## Waarom probeert [!DNL Sales Connect] zelfs met mijn persoonlijke Gmail te integreren? {#why-does-sales-connect-even-try-to-integrate-with-my-personal-gmail}

[!DNL Sales Connect] integreert met Gmail door een uitbreiding die in [!DNL Chrome] wordt geïnstalleerd browser. Wanneer de extensie een instantie van Gmail opent, biedt deze een optie om hierin te integreren. Om integratie met uw persoonlijke Gmail- rekening te verhinderen, adviseren wij één van drie dingen...

Aanmelden als een andere [!DNL Chrome] gebruiker (aanbevolen)

Klik [&#x200B; deze verbinding &#x200B;](https://support.google.com/chrome/answer/2364824?hl=en) om te lezen hoe te om een ander [!DNL Chrome] Profiel tot stand te brengen.

**Pros**: Het ondertekenen binnen als een andere gebruiker zal een nieuw geval van [!DNL Chrome] openen. Deze instantie is een gloednieuw venster van [!DNL Chrome] en geen van uw oude extensies bestaat in deze instantie. Het houdt ook cookies bij zodat u zich niet telkens bij uw Gmail hoeft aan te melden.

**Kons**: Moet twee vensters van [!DNL Chrome] open hebben.

Andere browser gebruiken

**Pros:** Gebruikend een andere Internet browser (IE of Firefox) die niet de geïnstalleerde uitbreiding heeft zal dit verhinderen om te gebeuren.

**Kons**: Het gebruiken van veelvoudige browsers kan irriterend zijn.

Een Incognito-venster gebruiken

**Pros:** Een incognitovenster is als het openen van een naakte versie van [!DNL Chrome]. Dit betekent dat er geen extensies zijn geïnstalleerd en dat [!DNL Sales Connect] er niet is om verbinding te maken.

**Kons**: U zult binnen aan Gmail moeten ondertekenen telkens als u uw dag begint, en opnieuw als u toevallig het venster sluit.
