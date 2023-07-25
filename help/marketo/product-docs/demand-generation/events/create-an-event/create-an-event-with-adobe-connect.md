---
unique-page-id: 2949865
description: Een gebeurtenis maken met Adobe Connect - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met Adobe Connect
exl-id: 196b1640-9cfd-4485-9bc4-e907d3ac1f16
feature: Events
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 0%

---

# Een gebeurtenis maken met Adobe Connect {#create-an-event-with-adobe-connect}

Door te synchroniseren met Adobe Connect kunt u uw webinar-registratie en -aanwezigheid in Marketo beheren, zodat de betrokkenheid niet wordt losgekoppeld.

>[!PREREQUISITES]
>
>* [Koppeling Adobe Connect en Marketo](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
>* [Een nieuw gebeurtenisprogramma maken](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)

Controleer eerst of u een vergadering of seminar in Adobe Connect hebt gemaakt. Als u hulp nodig hebt, raadpleegt u de [Adobe Connect-gebruikershandleiding](https://help.adobe.com/en_US/connect/9.0/using/index.html).

De vergaderingen en seminars die u in Adobe Connect maakt, moeten worden gemaakt in de map die u hebt opgegeven bij het invoeren van uw referenties in Marketo. Nadat u uw vergadering of seminar hebt gemaakt, moet u alle relevante logistieke informatie (zoals het telefoonnummer) noteren die u in het bevestigingsbericht en het ICS-bestand kunt gebruiken.

>[!CAUTION]
>
>Als gastheer van de gebeurtenis moet u zich aanmelden vanuit de app en **niet** via de koppeling die naar de deelnemers wordt gestuurd.

>[!NOTE]
>
>Adobe Connect On-Site wordt momenteel niet ondersteund.

1. Selecteer bij een nieuwe gebeurtenis de optie **Gebeurtenishandelingen** en vervolgens **Gebeurtenisinstellingen**.

   ![](assets/image2015-1-30-15-3a34-3a28.png)

   >[!NOTE]
   >
   >Als u het niet ziet **Gebeurtenisinstellingen** in de vervolgkeuzelijst, zorg ervoor dat het kanaal van de gebeurtenis **Gebeurtenis met webinar** geselecteerd onder &quot;Van toepassing op&quot;.

1. Onder **Gebeurtenispartner**, selecteert u **Adobe Connect**.

   ![](assets/event-settings-adobe-connect.png)

1. Selecteer uw **Aanmelden** ID en selecteer uw **Gebeurtenis**.

   ![](assets/event-settings-select-event-adobe-connect.png)

1. Klikken **Opslaan**.

   ![](assets/event-settings-overview.png)

   Mooi! Uw Adobe Connect-gebeurtenis wordt nu gesynchroniseerd met uw Marketo-gebeurtenis.

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres.

   >[!TIP]
   >
   >Als u de unieke URL van de persoon in een e-mailbericht wilt invoegen, gebruikt u deze token: `{{member.webinar url}}`. Wanneer de e-mail wordt verzonden, lost dit token automatisch de unieke bevestiging-URL van de persoon vanuit Adobe Connect op.
   >
   >Stel het bevestigingsbericht in op **Operationeel** om ervoor te zorgen dat personen die zich inschrijven en eventueel worden afgemeld, nog steeds hun bevestigingsinformatie ontvangen.

   Personen die zich aanmelden voor uw webinar, worden via de stap Program Status wijzigen naar uw webinar geduwd wanneer de Nieuwe status is ingesteld op &quot;Geregistreerd&quot;. Geen andere status zal de persoon over duwen. Zorg er ook voor dat u in stap 1 van de statusstroom van het programma Wijzigen en stap 2 in de E-mailflow verzendt.

   ![](assets/adobe.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als u na het wachten nog steeds niets ziet, selecteert u **Vernieuwen vanaf webinar-provider** in het menu Gebeurtenishandelingen op het tabblad Overzicht van uw gebeurtenis.

   >[!MORELIKETHIS]
   >
   >* [Adobe Connect toevoegen als een LaunchPoint-service](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
   >* [Een gebeurteniskanaal bewerken](/help/marketo/product-docs/demand-generation/events/understanding-events/edit-an-event-channel.md)
