---
unique-page-id: 15695874
description: BrightStor EnterpriseTALK verbinden met Marketo - Marketo Docs - Productdocumentatie
title: BrightStorTALK verbinden met Marketo
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---


# BrightStorTALK verbinden met Marketo {#connect-brighttalk-to-marketo}

Leer hoe u het BrightStor ARCserve-kanaal koppelt aan uw Marketo-instantie. Hiervoor moet u een beheerder voor beide zijn.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Stappen in BrightStor {#steps-in-brighttalk}

1. Meld u aan bij [business.brighttalk.com/demandcentral](https://business.brighttalk.com/demandcentral/login) en klik op **Nu verbinden**.
1. Klik onder Geavanceerde markeringsverbinding op **Verbinden**.
1. U komt naar het aanmeldingsscherm en vraagt om: Client ID, Client Secret, Identity Service URL en Rest Service URL. Meld u aan bij Marketo om deze gegevens op te halen.

## Stappen in Marketo {#steps-in-marketo}

>[!NOTE]
>
>Op dit moment moet u een gebruikers- en API-gebruikersrol (alleen API) instellen om te beperken welke machtigingen BrightTALK in uw Marketo-instantie heeft. Omdat we al artikelen voor die stappen hebben, koppelen we u aan deze stappen.

1. Maak een [Alleen API-gebruikersrol](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md).
1. [Maak een API-gebruiker](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) met behulp van de BrightStor API Role die u tijdens stap 4 hebt gemaakt.
1. Ga terug naar het beheergebied.

   ![](assets/one.png)

1. Klik onder Integratie op **LaunchPoint**.

   ![](assets/two.png)

1. Klik op de vervolgkeuzelijst **Nieuw** en selecteer **Nieuwe service**.

   ![](assets/three.png)

1. Voer een weergavenaam van uw keuze in. Klik op de vervolgkeuzelijst Service en selecteer **Custom** (doe _not_ select BrightTALK).

   ![](assets/four.png)

   >[!CAUTION]
   >
   >Vergeet niet om BrightStor ARCserve Backup niet in de vervolgkeuzelijst te selecteren. Dit is een gebied dat we momenteel verwijderen en door dit te selecteren kunnen er belangrijke problemen ontstaan met de integratie tussen Marketo en BrightStor.

1. Voer een beschrijving van uw keuze in. Klik op de vervolgkeuzelijst Alleen API-gebruiker en selecteer de BrightStor API-gebruiker die u tijdens stap 5 hebt gemaakt. Klik **Maken**.

   ![](assets/five.png)

1. Klik **Details van de Mening** voor de douaneservice u enkel creeerde.

   ![](assets/six.png)

1. Kopieer (en sla) **Clientid** en **Clientgeheim** op. Klik **Close**.

   ![](assets/eight-1.png)

1. Selecteer **Webservices** onder Integratie.

   ![](assets/nine-1.png)

1. Kopieer (en sla) onder Rest API **Endpoint** en **Identity** op.

   ![](assets/ten.png)

## Extra stappen in BrightStor {#additional-steps-in-brighttalk}

1. Keer terug naar het scherm van de de schakelaaropstelling van BrightTALK van Stap 3, en ga de geloofsbrieven in u van Stappen 12 en 14 bewaarde.

   Nadat de referenties zijn geverifieerd, hebt u BrightStor ARCserve Backup officieel verbonden met Marketo. De volgende stap is [te bepalen welke gegevensgebieden u ](https://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync) wilt synchroniseren.
