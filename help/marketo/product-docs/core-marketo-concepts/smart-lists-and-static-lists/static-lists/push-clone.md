---
description: Push Clone - Marketo Docs - Productdocumentatie
title: Push Clone
hide: true
hidefromtoc: true
source-git-commit: 8920bc525075923b32e7330da20debb7b8f47b06
workflow-type: tm+mt
source-wordcount: '467'
ht-degree: 0%

---

# Push Clone {#push-clone}

Met deze functie kunt u segmenten in uw Adobe Experience Platform naar Marketo duwen in de vorm van een statische lijst.

>[!PREREQUISITES]
>
>* [Een API-gebruiker maken](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) in Marketo.
>* Ga vervolgens naar **Beheer** > **Launchpoint**. Zoek de naam van de rol die u net hebt gemaakt en klik op **Details weergeven**. De gegevens kopiëren en opslaan in **Client-id** en **Clientgeheim**, aangezien u het voor deze eigenschap zult nodig hebben.


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

Vervolgens moet u kiezen of u alleen bestaande Marketo-personen wilt afstemmen, of bestaande Marketo-personen wilt afstemmen en de vermiste personen in Marketo wilt maken. Hieronder vindt u secties waarin wordt beschreven hoe u beide kunt uitvoeren.

## Bestaande Marketo-personen op één lijn brengen en ontbrekende personen maken in Marketo {#match-existing-marketo-people-create-missing-people}

Na de volgende stappen 1-8 hierboven...

1. Voer een bestemming in **Naam** en een optionele beschrijving. Klik op de vervolgkeuzelijst Personen maken en selecteer **Bestaande Marketo-personen op één lijn brengen en ontbrekende personen maken in Marketo**.

   ![](assets/push-an-adobe-experience-platform-segment-9.png)

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

1. Wijs de Achternaam en de Naam van het Bedrijf in kaart door te klikken **Nieuwe toewijzing toevoegen** opnieuw en herhalend Stap 7 tweemaal, die lastName en toen companyName kiest.

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

MORREAAL

## Alleen bestaande Marketo-personen afstemmen {#match-existing-marketo-people-only}

>[!NOTE]
>
>De identiteiten worden gebruikt om gelijken in Marketo te zoeken. Als een gelijke wordt gevonden, wordt de persoon toegevoegd aan de statische Lijst. Als er geen overeenkomst wordt gevonden, worden deze personen verwijderd (dus niet gemaakt in Marketo).

1. _In Marketo_, maakt u een statische lijst of zoekt en selecteert u een lijst die u al hebt gemaakt. Kopieer de toewijzing-id van het einde van de URL.

PICC

>[!NOTE]
>
>Voor de beste resultaten moet de lijst waarnaar u verwijst in Marketo leeg zijn.

1. Voer in Adobe Experience Platform de id in die u zojuist hebt gekopieerd. Kies uw begindatum. Personen worden voortdurend gesynchroniseerd tot de gekozen einddatum. Voor een onbepaalde synchronisatie laat u de einddatum leeg. Klikken **Volgende** wanneer gereed.

PICC

1. Bevestig uw wijzigingen en klik op **Voltooien**.

PICC
