---
unique-page-id: 15695874
description: BrightStor TALK verbinden met Marketo - Marketo Docs - Productdocumentatie
title: BrightStorTALK verbinden met Marketo
exl-id: 5c6a12ec-301b-4dec-975c-24ec759ebb37
source-git-commit: 5f509a7aa27692e54bf129b94c657aff0f645f2b
workflow-type: tm+mt
source-wordcount: '343'
ht-degree: 0%

---

# BrightStorTALK verbinden met Marketo {#connect-brighttalk-to-marketo}

Leer hoe u het BrightStor ARCserve-kanaal koppelt aan uw Marketo-exemplaar. Hiervoor moet u een beheerder voor beide zijn.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Stappen in BrightStorTALK {#steps-in-brighttalk}

1. Aanmelden bij [business.brighttalk.com/demandcentral](https://business.brighttalk.com/demandcentral/login){target=&quot;_blank&quot;} en klik op **Nu verbinding maken**.
1. Klik onder Geavanceerde Marketo-connector op **Verbinden**.
1. U komt naar het aanmeldingsscherm en vraagt om: Client ID, Client Secret, Identity Service URL en Rest Service URL. Meld u aan bij Marketo voor deze informatie.

## Stappen in Marketo {#steps-in-marketo}

>[!NOTE]
>
>Op dit moment moet u een gebruiker met alleen de API en een gebruikersrol instellen om te beperken welke machtigingen BrightTALK in uw Marketo-instantie heeft. Omdat we al artikelen voor die stappen hebben, koppelen we u aan deze stappen.

1. Een [Alleen API-gebruikersrol](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target=&quot;_blank&quot;}.

1. [Een API-gebruiker maken](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target=&quot;_blank&quot;}, met behulp van de BrightStor API-rol die u tijdens stap 4 hebt gemaakt.

1. Ga terug naar het beheergebied.

   ![](assets/connect-brighttalk-to-marketo-1.png)

1. Klik onder Integratie op **LaunchPoint**.

   ![](assets/connect-brighttalk-to-marketo-2.png)

1. Klik op de knop **Nieuw** vervolgkeuzelijst en selecteer **Nieuwe service**.

   ![](assets/connect-brighttalk-to-marketo-3.png)

1. Voer een weergavenaam van uw keuze in. Klik op de vervolgkeuzelijst Service en selecteer **Aangepast** (do _niet_ Selecteer BrightStor).

   ![](assets/connect-brighttalk-to-marketo-4.png)

   >[!CAUTION]
   >
   >Vergeet niet om BrightStor ARCserve Backup niet in de vervolgkeuzelijst te selecteren. Dit is een gebied dat we momenteel verwijderen en door dit te selecteren kunnen er belangrijke problemen ontstaan met de integratie tussen Marketo en BrightStor.

1. Voer een beschrijving van uw keuze in. Klik op de vervolgkeuzelijst Alleen API-gebruiker en selecteer de BrightStor API-gebruiker die u tijdens stap 5 hebt gemaakt. Klikken **Maken**.

   ![](assets/connect-brighttalk-to-marketo-5.png)

1. Klikken **Details weergeven** voor de aangepaste service die u zojuist hebt gemaakt.

   ![](assets/connect-brighttalk-to-marketo-6.png)

1. Kopieer (en sla) de **Client-id** en **Clientgeheim**. Klikken **Sluiten**.

   ![](assets/connect-brighttalk-to-marketo-7.png)

1. Selecteer onder Integratie **Webservices**.

   ![](assets/connect-brighttalk-to-marketo-8.png)

1. Kopieer (en sla) de **Endpoint** en **Identiteit**.

   ![](assets/connect-brighttalk-to-marketo-9.png)

## Extra stappen in BrightStorTALK {#additional-steps-in-brighttalk}

1. Keer terug naar het scherm van de de schakelaaropstelling van BrightTALK van Stap 3, en ga de geloofsbrieven in u van Stappen 12 en 14 bewaarde.

   Nadat de referenties zijn geverifieerd, hebt u BrightStor ARCserve Backup officieel verbonden met Marketo. De volgende stap is te bepalen [welke gegevensvelden u wilt synchroniseren](https://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync){target=&quot;_blank&quot;}.
