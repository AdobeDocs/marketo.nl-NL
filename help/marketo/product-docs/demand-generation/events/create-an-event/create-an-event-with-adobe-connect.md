---
unique-page-id: 2949865
description: Een gebeurtenis maken met Adobe Connect - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met Adobe Connect
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '399'
ht-degree: 0%

---


# Een gebeurtenis maken met Adobe Connect {#create-an-event-with-adobe-connect}

Door te synchroniseren met Adobe Connect kunt u uw webinar-registratie en -aanwezigheid beheren in Marketo, zodat de betrokkenheid niet wordt losgekoppeld.

>[!PREREQUISITES]
>
>* [Adobe Connect en Marketo koppelen](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)


Controleer eerst of u een vergadering of seminar in Adobe Connect hebt gemaakt. Raadpleeg voor hulp de [Adobe Connect User Guide](https://help.adobe.com/en_US/connect/9.0/using/index.html). De vergaderingen en seminars die u in Adobe Connect maakt, moeten worden gemaakt in de map die u hebt opgegeven bij het invoeren van uw referenties in Marketo. Nadat u uw vergadering of seminar hebt gemaakt, moet u alle relevante logistieke informatie (zoals het telefoonnummer) noteren die u in het bevestigingsbericht en het ICS-bestand kunt gebruiken.

>[!NOTE]
>
>Wij **bieden momenteel geen ondersteuning voor Adobe Connect On-Site.**

1. Selecteer **Gebeurtenishandelingen** thuis van een nieuwe gebeurtenis en **Gebeurtenisinstellingen**.

   ![](assets/image2015-1-30-15-3a34-3a28.png)

   >[!NOTE]
   >
   >Als u **Gebeurtenisinstellingen** niet ziet in de vervolgkeuzelijst, controleert u of het kanaal van de gebeurtenis **Gebeurtenis met webinar** is geselecteerd onder &quot;Van toepassing op&quot;.

1. Selecteer **Adobe Connect** onder **Gebeurtenispartner**.

   ![](assets/event-settings-adobe-connect.png)

1. Selecteer uw **Login** ID en selecteer uw **Gebeurtenis**.

   ![](assets/event-settings-select-event-adobe-connect.png)

1. Klik **Opslaan**.

   ![](assets/event-settings-overview.png)

   Mooi! Uw Adobe Connect-gebeurtenis wordt nu gesynchroniseerd met uw Marketo-gebeurtenis.

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres.

   >[!TIP]
   >
   >Als u de unieke URL van de persoon in een e-mailbericht wilt invoegen, gebruikt u deze token: `{{member.webinar url}}`. Wanneer de e-mail wordt verzonden, lost dit token automatisch de unieke bevestiging-URL van de persoon vanuit Adobe Connect op.
   >
   >Stel uw bevestigingsbericht in op **Operationeel** om ervoor te zorgen dat personen die zich registreren en mogelijk niet-geabonneerd zijn, nog steeds hun bevestigingsgegevens ontvangen.

   ![](assets/adobe.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als na het wachten dat lang u nog niets ziet, uitgezocht **verfrist zich van Webinar Leverancier** van het menu van de Acties van de Gebeurtenis in het Summiere lusje van uw gebeurtenis.

   >[!MORELIKETHIS]
   >
   > * [Adobe Connect toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
   > * [Een gebeurteniskanaal bewerken](/help/marketo/product-docs/demand-generation/events/understanding-events/edit-an-event-channel.md)


Personen die zich aanmelden voor uw webinar, worden via de stap Program Status wijzigen naar uw webinar geduwd wanneer de Nieuwe status is ingesteld op &quot;Geregistreerd&quot;. Geen andere status zal de persoon over duwen. Zorg er ook voor dat u in stap 1 van de statusstroom van het programma Wijzigen en stap 2 in de E-mailflow verzendt.
