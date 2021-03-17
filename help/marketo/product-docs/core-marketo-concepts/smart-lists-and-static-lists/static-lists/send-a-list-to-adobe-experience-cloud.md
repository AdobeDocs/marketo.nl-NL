---
unique-page-id: 37356194
description: Een lijst verzenden naar Adobe Experience Cloud - Marketo Docs - Productdocumentatie
title: Een lijst naar Adobe Experience Cloud verzenden
translation-type: tm+mt
source-git-commit: 96d6cc030ecd9d1da844fe27e1c6f62bbd181d62
workflow-type: tm+mt
source-wordcount: '787'
ht-degree: 0%

---


# Een lijst verzenden naar Adobe Experience Cloud {#send-a-list-to-adobe-experience-cloud}

>[!NOTE]
>
>Een plaatsing HIPAA-klaar van een instantie van Marketo kan deze eigenschap niet gebruiken.

>[!PREREQUISITES]
>
>[Adobe Experience Cloud-publiek delen instellen](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/set-up-adobe-experience-cloud-audience-sharing.md)

## Ondersteunde doeltoepassingen {#supported-destination-applications}

* Adobe Advertising Cloud
* Adobe Analytics (**only** als u een Vergunning van Adobe Audience Manager bezit)
* Adobe Audience Manager
* Adobe Experience Manager
* Adobe Real-Time Customer Data Platform
* Adobe Target

## Hoe te om een Statische Lijst {#how-to-send-a-static-list} te verzenden

Een statische lijst is dat, statisch. De lijst wordt alleen gewijzigd in Adobe Experience Cloud als u deze handmatig aanbrengt.

1. Zoek en selecteer in Marketo de lijst die u wilt exporteren.

   ![](assets/send-a-list-to-adobe-experience-cloud-1.png)

1. Klik op de vervolgkeuzelijst **Handelingen weergeven** en selecteer **Verzenden naar Experience Cloud**.

   ![](assets/send-a-list-to-adobe-experience-cloud-2.png)

1. Klik op de vervolgkeuzelijst **Audience Manager Map** en selecteer de gewenste doelmap in de Experience Cloud.

   ![](assets/send-a-list-to-adobe-experience-cloud-3.png)

1. Kies of u een nieuw publiek wilt maken of een bestaand publiek wilt overschrijven (in dit voorbeeld maken we een nieuw publiek). Ga de nieuwe publieksnaam in en klik **Send**.

   ![](assets/send-a-list-to-adobe-experience-cloud-4.png)

1. Klik **OK**.

   ![](assets/send-a-list-to-adobe-experience-cloud-5.png)

   >[!NOTE]
   >
   >Het kan tot 6-8 uur duren voor het publiekslidmaatschap volledig in Adobe bevolkt.

## Hoe te om een Gesynchroniseerde Lijst {#how-to-send-a-synced-list} te verzenden

Als u een lijst synchroniseert, betekent dat telkens wanneer u een lijst bijwerkt in Marketo, dat deze wijziging automatisch wordt doorgevoerd in de doelgroep in Adobe Experience Cloud.

1. Zoek en selecteer in Marketo de lijst die u wilt synchroniseren.

   ![](assets/send-a-list-to-adobe-experience-cloud-6.png)

1. Klik op de vervolgkeuzelijst **Handelingen weergeven** en selecteer **Verzenden naar Experience Cloud**.

   ![](assets/send-a-list-to-adobe-experience-cloud-7.png)

1. Klik op de vervolgkeuzelijst **Audience Library Folder** en selecteer de gewenste doelmap in de Experience Cloud.

   ![](assets/send-a-list-to-adobe-experience-cloud-8.png)

1. Kies of u een nieuw publiek wilt maken of een bestaand publiek wilt overschrijven (in dit voorbeeld maken we een nieuw publiek). Ga de nieuwe publieksnaam in, controleer **Houd het Lidmaatschap van het Publiek in Synchronisatie** doos, en klik **Send**.

   ![](assets/send-a-list-to-adobe-experience-cloud-9.png)

1. Klik **OK**.

   ![](assets/send-a-list-to-adobe-experience-cloud-10.png)

## Hoe te om een Synchronisatie van de Lijst {#how-to-stop-a-list-sync} tegen te houden

U kunt voorkomen dat uw lijst op elk gewenst moment wordt gesynchroniseerd.

1. Zoek en selecteer in Marketo de lijst die u niet meer wilt synchroniseren.

   ![](assets/send-a-list-to-adobe-experience-cloud-11.png)

1. Klik op de vervolgkeuzelijst **Handelingen weergeven** en selecteer **Lijstsynchronisatie stoppen**.

   ![](assets/send-a-list-to-adobe-experience-cloud-12.png)

1. Selecteer de doelgroep(en) die u niet meer wilt synchroniseren en klik op **Stoppen**.

   ![](assets/send-a-list-to-adobe-experience-cloud-13.png)

1. Klik **Stop** om te bevestigen.

   ![](assets/send-a-list-to-adobe-experience-cloud-14.png)

## Notities {#things-to-note}

**Delen naar Adobe Analytics**

Voor klanten die zowel Adobe Audience Manager als Adobe Analytics bezitten, zal deze integratie toelaten om publiek van Marketo aan uw Suites van het Rapport van Adobe Analytics te delen, nochtans zijn er sommige extra configuratiestappen die in Adobe Audience Manager moeten worden genomen om dit toe te laten. Raadpleeg de documentatie bij Adobe Audience Manager voor meer informatie over het instellen van deze instelling: [https://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html](https://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html).

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

Een volgende stap is vereist om het anonieme gebruikersprofiel aan een Profiel van de Lood te associëren, dat gebruikend een gewone tekst e-mail wordt geïdentificeerd. Precies hoe dit werkt is [hier beschreven](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md).

**Welke informatie wordt gedeeld?**

Deze integratie deelt slechts lijstlidmaatschapsinformatie van Marketo aan Adobe (bijvoorbeeld, de kennis dat Lood X een lid van Lijst Y is). Via deze integratie worden geen extra loodkenmerken aan Adobe gedeeld.
