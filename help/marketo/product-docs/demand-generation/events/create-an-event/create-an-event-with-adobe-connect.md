---
unique-page-id: 2949865
description: Een gebeurtenis maken met Adobe Connect - Marketo Docs - Productdocumentatie
title: Een gebeurtenis maken met Adobe Connect
exl-id: 196b1640-9cfd-4485-9bc4-e907d3ac1f16
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '383'
ht-degree: 0%

---

# Een gebeurtenis maken met Adobe Connect {#create-an-event-with-adobe-connect}

Door te synchroniseren met Adobe Connect kunt u uw webinar-registratie en -aanwezigheid in Marketo beheren, zodat de betrokkenheid niet wordt losgekoppeld.

>[!PREREQUISITES]
>
>* [ Verbinding Adobe Connect en Marketo ](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
>* [ creeer een Nieuw Programma van de Gebeurtenis ](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)

Controleer eerst of u een vergadering of seminar in Adobe Connect hebt gemaakt. Als u hulp nodig hebt, controleer de [ Gids van de Gebruiker van Adobe Connect ](https://help.adobe.com/en_US/connect/9.0/using/index.html).

De vergaderingen en seminars die u in Adobe Connect maakt, moeten worden gemaakt in de map die u hebt opgegeven bij het invoeren van uw referenties in Marketo. Nadat u uw vergadering of seminar hebt gemaakt, moet u alle relevante logistieke informatie (zoals het telefoonnummer) noteren die u in het bevestigingsbericht en het ICS-bestand kunt gebruiken.

>[!CAUTION]
>
>Als gebeurtenisgastheer, ben zeker om zich van binnen app aan te sluiten en **niet** via de verbinding die naar aanwezigen wordt verzonden.

>[!NOTE]
>
>Adobe Connect On-Site wordt momenteel niet ondersteund.

1. Selecteer **[!UICONTROL Event Actions]** bij de start van een nieuwe gebeurtenis en vervolgens **[!UICONTROL Event Settings]** .

   ![](assets/image2015-1-30-15-3a34-3a28.png)

   >[!NOTE]
   >
   >Als u **[!UICONTROL Event Settings]** niet ziet in de drop-down, zorg ervoor het kanaal van de gebeurtenis **[!UICONTROL Event with Webinar]** onder &quot;[!UICONTROL Applies to]&quot;geselecteerd heeft.

1. Selecteer onder **[!UICONTROL Event Partner]** de optie **[!UICONTROL Adobe Connect]** .

   ![](assets/event-settings-adobe-connect.png)

1. Selecteer uw **[!UICONTROL Login]** id en selecteer de **[!UICONTROL Event]** .

   ![](assets/event-settings-select-event-adobe-connect.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/event-settings-overview.png)

   Mooi! Uw Adobe Connect-gebeurtenis wordt nu gesynchroniseerd met uw Marketo-gebeurtenis.

   >[!NOTE]
   >
   >De velden die Marketo verzendt, zijn: Voornaam, Achternaam, E-mailadres.

   >[!TIP]
   >
   >Als u de unieke URL van de persoon in een e-mailbericht wilt invoegen, gebruikt u deze token: `{{member.webinar url}}` . Wanneer de e-mail wordt verzonden, lost dit token automatisch de unieke bevestiging-URL van de persoon vanuit Adobe Connect op.
   >
   >Plaats uw bevestigingse-mail aan **Operationeel** om ervoor te zorgen dat de mensen die registreren en kunnen worden afgemeld nog hun bevestigingsinformatie ontvangen.

   Personen die zich aanmelden voor uw webinar, worden via de [!UICONTROL Change Program Status] flowstap naar uw webinar gestuurd wanneer [!UICONTROL New Status] is ingesteld op &quot;Geregistreerd&quot;. Geen andere status zal de persoon over duwen. Zorg er ook voor dat u [!UICONTROL Change Program Status] stap #1 en [!UICONTROL Send Email] stap #2 uitvoert.

   ![](assets/adobe.png)

   >[!CAUTION]
   >
   >Vermijd het gebruik van geneste e-mailprogramma&#39;s voor het verzenden van bevestigingsberichten. Gebruik in plaats hiervan de slimme campagne van het gebeurtenisprogramma, zoals hierboven wordt getoond.

   >[!TIP]
   >
   >Het kan tot 48 uur duren voordat de gegevens in Marketo verschijnen. Als u na het wachten nog steeds niets ziet, selecteert u **[!UICONTROL Refresh from Webinar Provider]** in het menu Gebeurtenishandelingen op het tabblad Overzicht van de gebeurtenis.

   >[!MORELIKETHIS]
   >
   >* [ voeg Adobe Connect als a [!DNL LaunchPoint]  Dienst ](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md) toe
   >* [ geef een Kanaal van de Gebeurtenis ](/help/marketo/product-docs/demand-generation/events/understanding-events/edit-an-event-channel.md) uit
