---
unique-page-id: 15695874
description: Verbind  [!DNL BrightTALK]  met Marketo - de Documenten van Marketo - de Documentatie van het Product
title: Verbind  [!DNL BrightTALK]  met Marketo
exl-id: 5c6a12ec-301b-4dec-975c-24ec759ebb37
feature: Administration, Integrations
source-git-commit: b95458ffab422901ef5e674756ae5e413ec542fd
workflow-type: tm+mt
source-wordcount: '285'
ht-degree: 0%

---

# Verbinden [!DNL BrightTALK] met Marketo {#connect-brighttalk-to-marketo}

Leer hoe u het [!DNL BrightTALK] -kanaal koppelt aan uw Marketo-instantie. Hiervoor moet u een beheerder voor beide zijn.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## Stappen in [!DNL BrightTALK] {#steps-in-brighttalk}

1. Login aan [&#x200B; business.brighttalk.com/demandcentral &#x200B;](https://business.brighttalk.com/demandcentral/login){target="_blank"} en klik **[!UICONTROL Connect Now]**.
1. Klik onder [!UICONTROL Advanced Marketo Connector] op **[!UICONTROL Connect]** .
1. U komt naar het aanmeldingsscherm en vraagt om: Client ID, Client Secret, Identity Service URL en Rest Service URL. Meld u aan bij Marketo voor deze informatie.

## Stappen in Marketo {#steps-in-marketo}

>[!NOTE]
>
>U moet nu een [!DNL API Only User Role] en [!DNL API User] instellen om te beperken welke machtigingen [!DNL BrightTALK] in uw Marketo-instantie heeft. Omdat we al artikelen voor die stappen hebben, koppelen we u aan deze stappen.

1. Creeer een [&#x200B; slechtsAPI Rol van de Gebruiker &#x200B;](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target="_blank"}.

1. [&#x200B; creeer een API Gebruiker &#x200B;](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target="_blank"}, gebruikend de [!DNL BrightTALK] API Rol u tijdens Stap 4 creeerde.

1. Ga terug naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/connect-brighttalk-to-marketo-1.png)

1. Klik onder **[!UICONTROL Integration]** op **[!UICONTROL LaunchPoint]** .

   ![](assets/connect-brighttalk-to-marketo-2.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL New]** en selecteer **[!UICONTROL New Service]** .

   ![](assets/connect-brighttalk-to-marketo-3.png)

1. Voer een **[!UICONTROL Display Name]** van uw keuze in. Klik **[!UICONTROL Service]** drop-down en selecteer **[!UICONTROL Custom]** (_niet_ uitgezocht [!DNL BrightTALK]).

   ![](assets/connect-brighttalk-to-marketo-4.png)

   >[!CAUTION]
   >
   >Vergeet niet [!DNL BrightTALK] niet in de vervolgkeuzelijst te selecteren. Dit is een gebied dat we momenteel verwijderen en door dit te selecteren kunnen er belangrijke problemen ontstaan met uw [!DNL Marketo/BrightTALK] -integratie.

1. Voer een [!UICONTROL Description] van uw keuze in. Klik op de vervolgkeuzelijst **[!UICONTROL API Only User]** en selecteer de [!DNL BrightTALK API User] die u tijdens Stap 5 hebt gemaakt. Klik op **[!UICONTROL Create]**.

   ![](assets/connect-brighttalk-to-marketo-5.png)

1. Klik op **[!UICONTROL View Details]** voor de aangepaste service die u zojuist hebt gemaakt.

   ![](assets/connect-brighttalk-to-marketo-6.png)

1. Kopieer (en sla) **[!UICONTROL Client ID]** en **[!UICONTROL Client Secret]** op. Klik op **[!UICONTROL Close]**.

   ![](assets/connect-brighttalk-to-marketo-7.png)

1. Selecteer onder **[!UICONTROL Integration]** de optie **[!UICONTROL Web Services]** .

   ![](assets/connect-brighttalk-to-marketo-8.png)

1. Kopieer (en sla) de **[!UICONTROL Endpoint]** en **[!UICONTROL Identity]** onder **[!UICONTROL Rest API]** op.

   ![](assets/connect-brighttalk-to-marketo-9.png)

## Extra stappen in [!DNL BrightTALK] {#additional-steps-in-brighttalk}

1. Keer terug naar het [!DNL BrightTALK] scherm van de schakelaaropstelling van Stap 3, en ga de geloofsbrieven in u van Stappen 12 en 14 bewaarde.

Nadat de aanmeldingsgegevens zijn geverifieerd, hebt u officieel verbinding gemaakt met Marketo. [!DNL BrightTALK] In de volgende stap moet u bepalen welke gegevensvelden u wilt synchroniseren. Als u hulp met dat nodig hebt, gelieve te contacteren Steun bij [&#x200B; BrightTALK &#x200B;](https://www.brighttalk.com/){target="_blank"}.
