---
description: Push Clone - Marketo Docs - Productdocumentatie
title: Push Clone
hide: true
hidefromtoc: true
source-git-commit: 97015b31c9a20a3052526a39ed26fc9cf0097e82
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 0%

---

# Push Clone {#push-clone}

Met deze functie kunt u segmenten in uw Adobe Experience Platform naar Marketo duwen in de vorm van een statische lijst.

>[!PREREQUISITES]
>
>* [Een API-gebruiker maken](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) in Marketo.
>* Ga vervolgens naar **Beheer** > **Launchpoint**. Zoek de naam van de rol die u net hebt gemaakt en klik op **Details weergeven**. De gegevens kopiëren en opslaan in **Client-id** en **Clientgeheim**, aangezien u het voor deze eigenschap zult nodig hebben.
>* Maak in Marketo een statische lijst of zoek en selecteer een lijst die u al hebt gemaakt. Je hebt de id nodig.


1. Aanmelden bij [Adobe Experience Platform](https://experience.adobe.com/).

   ![](assets/push-an-adobe-experience-platform-segment-1.png)

1. Klik op het rasterpictogram en selecteer **Experience Platform**.

   ![](assets/push-an-adobe-experience-platform-segment-2.png)

1. Klik in de linkernav op **Doelen**.

   ![](assets/push-an-adobe-experience-platform-segment-3.png)

1. Klikken **Catalogus**.

   ![](assets/push-an-adobe-experience-platform-segment-4.png)

1. De tegel Marketo Engage zoeken en klikken **Segmenten activeren**.

   ![](assets/push-an-adobe-experience-platform-segment-5.png)

1. Klikken **Nieuwe bestemming configureren**.

   ![](assets/push-an-adobe-experience-platform-segment-6.png)


1. Selecteer onder Accounttype het keuzerondje Bestaande of Nieuwe account (in dit voorbeeld kiezen we **Bestaande account**). Klik op het pictogram Account selecteren.

   ![](assets/push-an-adobe-experience-platform-segment-7.png)

1. Kies het bestemmingsaccount en klik op **Selecteren**.

   ![](assets/push-an-adobe-experience-platform-segment-8.png)

1. Voer een bestemming in **Naam** en een optionele beschrijving. Klik op de vervolgkeuzelijst Personen maken en kies &quot;Identieke bestaande Marketo-personen en Ontbrekende personen maken in Marketo&quot; _of_ &quot;Alleen voor bestaande Marketo-personen.&quot; In dit voorbeeld kiezen we het eerste.

   ![](assets/push-an-adobe-experience-platform-segment-9.png)

   >[!NOTE]
   >
   >Als u Alleen bestaande Marketo-personen afstemmen kiest, hoeft u alleen de e-mail en/of de ECID toe te wijzen, zodat u de stappen 13 tot en met 16 kunt overslaan.

1. Deze sectie is optioneel. Klikken **Maken** om over te slaan.

   ![](assets/push-an-adobe-experience-platform-segment-10.png)

1. Selecteer het doel dat u hebt gemaakt en klik op **Volgende**.

   ![](assets/push-an-adobe-experience-platform-segment-11.png)

1. Kies het segment dat u naar Marketo wilt verzenden en klik op **Volgende**.

   ![](assets/push-an-adobe-experience-platform-segment-12.png)

1. Klikken **Nieuwe toewijzing toevoegen**.

   ![](assets/push-an-adobe-experience-platform-segment-13.png)

1. Klik op het toewijzingspictogram.

   ![](assets/push-an-adobe-experience-platform-segment-14.png)

1. Voornaam toewijzen door **firstName** en klikken **Selecteren**.

   ![](assets/push-an-adobe-experience-platform-segment-15.png)

1. Wijs de Achternaam en de Naam van het Bedrijf in kaart door te klikken **Nieuwe toewijzing toevoegen** en herhaalt u stap 15 tweemaal, waarbij u **lastName** en vervolgens **companyName**.

   ![](assets/push-an-adobe-experience-platform-segment-16.png)

1. Nu is het tijd om het e-mailadres toe te wijzen. Klikken **Nieuwe toewijzing toevoegen** opnieuw.

   ![](assets/push-an-adobe-experience-platform-segment-17.png)

1. Klik op het toewijzingspictogram.

   ![](assets/push-an-adobe-experience-platform-segment-18.png)

1. Klik op het keuzerondje Identiteitsnaamruimte selecteren en kies  **E-mail** en klik vervolgens op **Selecteren**.

   ![](assets/push-an-adobe-experience-platform-segment-19.png)

1. Nu is het tijd om de bronvelden te kiezen. Klik op het cursorpictogram voor e-mail.

   ![](assets/push-an-adobe-experience-platform-segment-20.png)

1. Klik op het keuzerondje Identiteitsnaamruimte selecteren, zoek en selecteer **E-mail** en klik vervolgens op **Selecteren**.

   ![](assets/push-an-adobe-experience-platform-segment-21.png)

1. Klik op het cursorpictogram in de rij om het bronveld Bedrijfsnaam te kiezen.

   ![](assets/push-an-adobe-experience-platform-segment-22.png)

1. Laat het keuzerondje Kenmerk selecteren ingeschakeld. Zoek naar &quot;bedrijf&quot; en selecteer **companyName** en klik vervolgens op **Selecteren**.

   ![](assets/push-an-adobe-experience-platform-segment-23.png)

1. Wijs de brongebieden voor Achternaam en Voornaam door het curseurpictogram voor elk te klikken en Stap 23 tweemaal te herhalen, kiezen **lastName** en vervolgens **firstName**.

   ![](assets/push-an-adobe-experience-platform-segment-24.png)

1. Klikken **Volgende**.

   ![](assets/push-an-adobe-experience-platform-segment-25.png)

1. Je hebt nu de id van je lijst nodig. Klik op het tabblad in uw browser waarin de statische lijst van Marketo is geopend (of open een nieuw tabblad en selecteer de gewenste statische lijst).

   ![](assets/push-an-adobe-experience-platform-segment-26.png)

1. Markeer en kopieer de lijst-id aan het einde van de URL.

   ![](assets/push-an-adobe-experience-platform-segment-27.png)

1. Plak de id die u zojuist hebt gekopieerd onder Toewijzing-id en klik op **Volgende**.

   ![](assets/push-an-adobe-experience-platform-segment-28.png)

1. Klikken **Voltooien**.

   ![](assets/push-an-adobe-experience-platform-segment-29.png)
