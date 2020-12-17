---
unique-page-id: 37356194
description: Een statische lijst exporteren naar Adobe Experience Cloud - Marketo Docs - Productdocumentatie
title: Een statische lijst exporteren naar Adobe Experience Cloud
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '592'
ht-degree: 0%

---


# Een statische lijst exporteren naar Adobe Experience Cloud {#export-a-static-list-to-adobe-experience-cloud}

>[!NOTE]
>
>Een plaatsing HIPAA-klaar van een instantie van Marketo kan deze eigenschap niet gebruiken.

>[!PREREQUISITES]
>
>[Adobe Experience Cloud-publiek delen instellen](http://docs.marketo.com/x/D4GMAg)

## Ondersteunde doeltoepassingen {#supported-destination-applications}

* Adobe Advertising Cloud
* Adobe Analytics (**only** als u een Vergunning van Adobe Audience Manager bezit)
* Adobe Audience Manager
* Adobe Experience Manager
* Adobe Real-Time Customer Data Platform
* Adobe Target

## Hoe te om een Lijst {#how-to-export-a-list} uit te voeren

1. Zoek en selecteer in Marketo de lijst die u wilt exporteren.

   ![](assets/one.png)

1. Klik op de vervolgkeuzelijst **Handelingen weergeven** en selecteer **Verzenden naar Experience Cloud**.

   ![](assets/two-1.png)

1. Klik op de vervolgkeuzelijst **Audience Manager Map** en selecteer de gewenste doelmap in de Experience Cloud.

   ![](assets/three-1.png)

1. Kies of u een nieuw publiek wilt maken of een bestaand publiek wilt overschrijven (in dit voorbeeld maken we een nieuw publiek). Ga de nieuwe publieksnaam in en klik **Send**.

   ![](assets/four.png)

1. Klik **OK**.

   ![](assets/five.png)

   >[!NOTE]
   >
   >Het kan tot 6-8 uur duren voor het publiekslidmaatschap volledig in Adobe bevolkt.

## Notities {#things-to-note}

**Delen naar Adobe Analytics**

Voor klanten die zowel Adobe Audience Manager als Adobe Analytics bezitten, zal deze integratie toelaten om publiek van Marketo aan uw Suites van het Rapport van Adobe Analytics te delen, nochtans zijn er sommige extra configuratiestappen die in Adobe Audience Manager moeten worden genomen om dit toe te laten. Raadpleeg de documentatie bij Adobe Audience Manager voor meer informatie over het instellen van deze instelling: [https://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html](http://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html).

**Trait-gebruik voor Adobe Audience Manager-klanten**

Als u een lijst exporteert in Marketo, worden de volgende wijzigingen weergegeven in uw Adobe Audience Manager-exemplaar:

* Voor alle leads in de geëxporteerde lijst schrijft Marketo een eigenschap met de gehashte e-mails van Leads als een apparaat-id. De naam van het kenmerk komt overeen met de naam van het doelpubliek die u tijdens het exporteren hebt opgegeven.
* Voor alle ECID&#39;s die Marketo heeft weten aan te passen aan de lead in de geëxporteerde lijst, schrijft Marketo een eigenschap met behulp van de ECID-apparaat-id. De naam van het kenmerk komt overeen met de naam van het doelpubliek die u tijdens het exporteren hebt opgegeven.
* Marketo maakt ook een segment in uw Audience Manager-instantie met als enige segmenteringscriterium het ECID-kenmerk. De naam van het segment zal de Naam van het Publiek van de Bestemming aanpassen die u tijdens de uitvoer specificeerde.

## Veelgestelde vragen {#faq}

**Waarom verschilt de lijstgrootte in Marketo van die in Adobe?**

Onder de kap werkt de publieksintegratie door Marketo Munchkin-cookies te synchroniseren met het bijbehorende Adobe ECID-cookie. Marketo kan alleen lidmaatschapsgegevens delen voor leads waarvoor Marketo een ECID heeft gesynchroniseerd. Voor de beste resultaten is het raadzaam om het trackingscript van munchkin.js van Marketo parallel met de trackingcode bezoeker.js van Adobe te laden op alle pagina&#39;s die u voor marketingdoeleinden wilt bijhouden.

**Hoe werkt de cookiesync?**

Wanneer de cookiesync voor uw Abonnement van het Marketo wordt toegelaten, zal Marketo&#39;s munchkin.js proberen om Adobe ECIDs voor de Adobe IMS van de Org te vangen en op te slaan u tijdens de integratieopstelling specificeerde en deze ECIDs aan het overeenkomstige koekjesherkenningsteken van het Marketo aanpas. Hierdoor kunnen de anonieme gebruikersprofielen van Marketo worden verrijkt met Adobe ECID&#39;s.

Een volgende stap is vereist om het anonieme gebruikersprofiel aan een Profiel van de Lood te associëren, dat gebruikend een gewone tekst e-mail wordt geïdentificeerd. Hier wordt precies beschreven hoe dit werkt: [https://docs.marketo.com/display/public/DOCS/Tracking+Anonymous+Activity+and+People](http://docs.marketo.com/display/public/DOCS/Tracking+Anonymous+Activity+and+People).
