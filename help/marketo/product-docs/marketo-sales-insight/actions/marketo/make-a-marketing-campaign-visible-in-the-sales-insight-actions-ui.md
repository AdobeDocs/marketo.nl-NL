---
description: Een marketingcampagne zichtbaar maken in de gebruikersinterface Handelingen voor verkoopinzicht - Marketo Docs - Productdocumentatie
title: Een marketingcampagne zichtbaar maken in de gebruikersinterface Handelingen van het verkoopinzicht
exl-id: 223baca3-159e-4f0d-b26f-f4c924a39fc3
feature: Sales Insight Actions
source-git-commit: b037057cb37c830760a5d5bc24591f85ad306ae8
workflow-type: tm+mt
source-wordcount: '300'
ht-degree: 0%

---

# Een marketingcampagne zichtbaar maken in de gebruikersinterface Handelingen van het verkoopinzicht {#make-a-marketing-campaign-visible-in-the-sales-insight-actions-ui}

Campagnes kunnen alleen worden gedeeld als ze zichtbaar worden gemaakt.

Met Handelingen van het Inzicht van de Verkoop, zullen de gebruikers toegang tot nieuwe verkoopapp genoemd toutapp.com hebben. Deze app geeft hen een nieuwe reeks actiemogelijkheden, maar erft ook _toevoegt aan de Campagne van de Marketing_ eigenschap beschikbaar in de kernversie van de Inzichten van de Verkoop. Dit is belangrijk om in mening te houden, omdat afhankelijk van waar u gebruikers tot Add aan de eigenschap van de Campagne van de Marketing (toutapp.com of de het pakketervaring van MSI SFDC) wilt toegang hebben, uw campagnes van Marketo verschillend zullen moeten worden gevormd. Zie de nota in Stap 4 om meer te leren.

1. Selecteer (of maak) de campagne die u wilt delen.

   ![](assets/make-a-marketing-campaign-visible-sia-1.png)

1. Klik de **Slimme Lijst** tabel.

   ![](assets/make-a-marketing-campaign-visible-sia-2.png)

1. Voeg de trigger Campagne is Requested toe.

   ![](assets/make-a-marketing-campaign-visible-sia-3.png)

1. Voor bron, kies &quot;is&quot; **de Dienst API van het Web**.

   ![](assets/make-a-marketing-campaign-visible-sia-4.png)

   >[!NOTE]
   >
   >Als u de marketing campagne aan gebruikers wilt tonen die _toevoegen aan de Campagne van de Marketing_ van toutapp.com (dit omvat ook als u Webtoepassing hebt ingebed in CRM via het voorwerp van de Verkoop van Marketo Outbox), plaats het aan &quot;de Dienst API van het Web.&quot; Als u wilt dat de marketingcampagne wordt weergegeven wanneer een gebruiker de acties in het MSI-deelvenster in Salesforce gebruikt op de lead, contact, accountpagina of de bulkactieknoppen in de lijst met leads en contactpersonen, werkt u deze bij naar &quot;Sales Insight&quot;

1. Klik de **Stroom** tabel.

   ![](assets/make-a-marketing-campaign-visible-sia-5.png)

1. Voeg de actie Interessant moment-stroom toe.

   ![](assets/make-a-marketing-campaign-visible-sia-6.png)

1. Voor Type, uitgezochte **Web**.

   ![](assets/make-a-marketing-campaign-visible-sia-7.png)

1. Schrijf in het vak Beschrijving een bericht naar uw verkoopteam. In dit voorbeeld gebruiken we tokens om het formulier op te geven dat is ingevuld.

   ![](assets/make-a-marketing-campaign-visible-sia-8.png)

1. Klik het **lusje van het 0} Programma {en** activeer **de campagne.**

   ![](assets/make-a-marketing-campaign-visible-sia-9.png)
