---
unique-page-id: 37356194
description: Een lijst verzenden naar Adobe Experience Cloud - Marketo Docs - Productdocumentatie
title: Een lijst naar Adobe Experience Cloud verzenden
exl-id: 770eefe1-05f9-409d-8e7c-b3f1e6ba8139
source-git-commit: 492f21f090dc2478271172cf7db470e16f202366
workflow-type: tm+mt
source-wordcount: '770'
ht-degree: 0%

---

# Een lijst naar Adobe Experience Cloud verzenden {#send-a-list-to-adobe-experience-cloud}

>[!NOTE]
>
>Een implementatie van een Marketo-instantie die klaar is voor HIPAA, kan deze functie niet gebruiken.

>[!PREREQUISITES]
>
>[Organisatietoewijzing Adobe instellen](/help/marketo/product-docs/adobe-experience-cloud-integrations/set-up-adobe-organization-mapping.md){target=&quot;_blank&quot;}

## Ondersteunde doeltoepassingen {#supported-destination-applications}

* Adobe Advertising Cloud
* Adobe Analytics (**alleen** als u een Adobe Audience Manager-licentie hebt)
* Adobe Audience Manager
* Adobe Experience Manager
* Adobe Real-time Customer Data Platform
* Adobe Target

## Hoe te om een Statische Lijst te verzenden {#how-to-send-a-static-list}

Een statische lijst is dat, statisch. De lijst wordt alleen gewijzigd in Adobe Experience Cloud als u deze handmatig aanbrengt.

1. Zoek in Marketo de lijst die u wilt exporteren. Klik er met de rechtermuisknop op en selecteer **Verzenden naar Experience Cloud**.

   ![](assets/send-a-list-to-adobe-experience-cloud-1.png)

1. Klik op de knop **Map Audience Manager** en selecteer de gewenste doelmap in de Experience Cloud.

   ![](assets/send-a-list-to-adobe-experience-cloud-2.png)

1. Kies of u een nieuw publiek wilt maken of een bestaand publiek wilt overschrijven (in dit voorbeeld maken we een nieuw publiek). Voer de nieuwe publieksnaam in en klik op **Verzenden**.

   ![](assets/send-a-list-to-adobe-experience-cloud-3.png)

1. Klikken **OK**.

   ![](assets/send-a-list-to-adobe-experience-cloud-4.png)

   >[!NOTE]
   >
   >Het kan tot 6-8 uur duren voor het publiekslidmaatschap volledig in Adobe bevolkt.

## Een gesynchroniseerde lijst verzenden {#how-to-send-a-synced-list}

Als u een lijst synchroniseert, betekent dit dat telkens wanneer u een lijst in Marketo bijwerkt, deze lijst automatisch wordt gesynchroniseerd met de gebruikers in Adobe Experience Cloud.

1. Zoek in Marketo de lijst die u wilt exporteren. Klik er met de rechtermuisknop op en selecteer **Verzenden naar Experience Cloud**.

   ![](assets/send-a-list-to-adobe-experience-cloud-5.png)

1. Klik op de knop **Poortbibliotheekmap** en selecteer de gewenste doelmap in de Experience Cloud.

   ![](assets/send-a-list-to-adobe-experience-cloud-6.png)

1. Kies of u een nieuw publiek wilt maken of een bestaand publiek wilt overschrijven (in dit voorbeeld maken we een nieuw publiek). Voer de nieuwe publieksnaam in en controleer de **Zorgen dat het lidmaatschap van het publiek synchroon blijft** en klik op **Verzenden**.

   ![](assets/send-a-list-to-adobe-experience-cloud-7.png)

1. Klikken **OK**.

   ![](assets/send-a-list-to-adobe-experience-cloud-8.png)

## Lijstsynchronisatie stoppen {#how-to-stop-a-list-sync}

U kunt voorkomen dat uw lijst op elk gewenst moment wordt gesynchroniseerd.

1. Zoek in Marketo naar de lijst die u niet meer wilt synchroniseren en klik met de rechtermuisknop. Klikken **Lijstsynchronisatie stoppen**.

   ![](assets/send-a-list-to-adobe-experience-cloud-9.png)

1. Selecteer de doelgroep of doelgroepen die u niet meer wilt synchroniseren en klik op **Stoppen**.

   ![](assets/send-a-list-to-adobe-experience-cloud-10.png)

1. Klikken **Stoppen** ter bevestiging.

   ![](assets/send-a-list-to-adobe-experience-cloud-11.png)

## Notities {#things-to-note}

**Delen naar Adobe Analytics**

Voor klanten die zowel Adobe Audience Manager als Adobe Analytics bezitten, zal deze integratie toelaten om publiek van Marketo aan uw Suites van het Rapport van Adobe Analytics te delen, nochtans zijn er sommige extra configuratiestappen die in Adobe Audience Manager moeten worden genomen om dit toe te laten. Raadpleeg de documentatie bij Adobe Audience Manager voor meer informatie over het instellen van deze instelling: [https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html](https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html).

**Trait-gebruik voor Adobe Audience Manager-klanten**

Als u een lijst exporteert in Marketo, worden de volgende wijzigingen weergegeven in uw Adobe Audience Manager-exemplaar:

* Voor alle leads in de geëxporteerde lijst schrijft Marketo een kenmerk met de gehashte e-mails van Leads als een apparaat-id. De naam van het kenmerk komt overeen met de naam van het doelpubliek die u tijdens het exporteren hebt opgegeven.
* Voor alle ECID&#39;s die Marketo heeft kunnen aanpassen aan de lead in de geëxporteerde lijst, schrijft Marketo een kenmerk met de ECID-apparaat-id. De naam van het kenmerk komt overeen met de naam van het doelpubliek die u tijdens het exporteren hebt opgegeven.
* Marketo zal ook een segment in uw Instantie van de Audience Manager tot stand brengen gebruikend het bezit ECID als enige segmenteringscriterium. De naam van het segment zal de Naam van het Publiek van de Bestemming aanpassen die u tijdens de uitvoer specificeerde.

## Veelgestelde vragen {#faq}

**Waarom is de lijstgrootte in Marketo anders dan die in Adobe?**

Onder de motorkap werkt de publieksintegratie door Marketo Munchkin-cookies te synchroniseren met het bijbehorende Adobe ECID-cookie. Marketo kan alleen lidmaatschapsgegevens delen voor leads waarvoor Marketo een ECID heeft gesynchroniseerd. Voor het beste mogelijke resultaat is het raadzaam om het trackingscript Marketo munchkin.js te laden in combinatie met de trackingcode Adobe bezoekor.js op alle pagina&#39;s die u voor marketingdoeleinden wilt bijhouden.

**Hoe werkt de cookiesync?**

Wanneer de cookiesync voor uw Abonnement van Marketo wordt toegelaten, zal Marketo munchkin.js proberen om Adobe ECIDs voor de orde van de Org van de IMS van Adobe te vangen en op te slaan u tijdens de integratieopstelling specificeerde en deze ECIDs aan het overeenkomstige koekjesherkenningsteken van Marketo aan te passen. Hierdoor kunnen anonieme gebruikersprofielen van Marketo worden verrijkt met Adobe-ECID&#39;s.

Een volgende stap is vereist om het anonieme gebruikersprofiel aan een Profiel van de Lood te associëren, dat gebruikend een gewone tekst e-mail wordt geïdentificeerd. Precies hoe dit werkt [hier beschreven](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md).

**Welke informatie wordt gedeeld?**

Deze integratie deelt alleen de lijst met lidmaatschapsinformatie van Marketo naar Adobe (bijvoorbeeld de kennis dat Lead X lid is van Lijst Y). Via deze integratie worden geen extra loodkenmerken aan Adobe gedeeld.
