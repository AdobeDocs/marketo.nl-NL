---
unique-page-id: 15695874
description: "Verbinding maken [!DNL BrightTALK] naar Marketo - Marketo Docs - Productdocumentatie"
title: "Verbinding maken [!DNL BrightTALK] naar Marketo"
exl-id: 5c6a12ec-301b-4dec-975c-24ec759ebb37
feature: Administration, Integrations
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 1%

---

# Verbinden [!DNL BrightTALK] naar Marketo {#connect-brighttalk-to-marketo}

Leer hoe u verbinding maakt met uw [!DNL BrightTALK] naar uw Marketo-exemplaar. Hiervoor moet u een beheerder voor beide zijn.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Stappen in [!DNL BrightTALK] {#steps-in-brighttalk}

1. Aanmelden bij [business.brighttalk.com/demandcentral](https://business.brighttalk.com/demandcentral/login){target="_blank"} en klik op **[!UICONTROL Connect Now]**.
1. Onder [!UICONTROL Advanced Marketo Connector], klikt u op **[!UICONTROL Connect]**.
1. U komt naar het aanmeldingsscherm en vraagt om: Client ID, Client Secret, Identity Service URL en Rest Service URL. Meld u aan bij Marketo voor deze informatie.

## Stappen in Marketo {#steps-in-marketo}

>[!NOTE]
>
>U moet nu een [!DNL API Only User Role] en [!DNL API User] om te beperken welke machtigingen [!DNL BrightTALK] heeft in je Marketo-exemplaar. Omdat we al artikelen voor die stappen hebben, koppelen we u aan deze stappen.

1. Een [Alleen API-gebruikersrol](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target="_blank"}.

1. [Een API-gebruiker maken](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target="_blank"}, met de [!DNL BrightTALK] API Rol u tijdens Stap 4 creeerde.

1. Ga terug naar de **[!UICONTROL Admin]** gebied.

   ![](assets/connect-brighttalk-to-marketo-1.png)

1. Onder **[!UICONTROL Integration]**, klikt u op **[!UICONTROL LaunchPoint]**.

   ![](assets/connect-brighttalk-to-marketo-2.png)

1. Klik op de knop **[!UICONTROL New]** vervolgkeuzelijst en selecteer **[!UICONTROL New Service]**.

   ![](assets/connect-brighttalk-to-marketo-3.png)

1. Voer een **[!UICONTROL Display Name]** van uw keuze. Klik op de knop **[!UICONTROL Service]** vervolgkeuzelijst en selecteer **[!UICONTROL Custom]** (do _niet_ selecteren [!DNL BrightTALK]).

   ![](assets/connect-brighttalk-to-marketo-4.png)

   >[!CAUTION]
   >
   >Vergeet niet om niet te selecteren [!DNL BrightTALK] in de vervolgkeuzelijst. Het is een gebied dat wij momenteel verwijderen en het selecteren van het zou tot significante kwesties met uw kunnen leiden [!DNL Marketo/BrightTALK] integratie.

1. Voer een [!UICONTROL Description] van uw keuze. Klik op de knop **[!UICONTROL API Only User]** en selecteert u de [!DNL BrightTALK API User] u hebt gemaakt tijdens Stap 5. Klik op **[!UICONTROL Create]**.

   ![](assets/connect-brighttalk-to-marketo-5.png)

1. Klikken **[!UICONTROL View Details]** voor de aangepaste service die u zojuist hebt gemaakt.

   ![](assets/connect-brighttalk-to-marketo-6.png)

1. Kopieer (en sla) de **[!UICONTROL Client ID]** en **[!UICONTROL Client Secret]**. Klik op **[!UICONTROL Close]**.

   ![](assets/connect-brighttalk-to-marketo-7.png)

1. Selecteer onder **[!UICONTROL Integration]** de optie **[!UICONTROL Web Services]**.

   ![](assets/connect-brighttalk-to-marketo-8.png)

1. Onder **[!UICONTROL Rest API]**, kopieert (en slaat) de **[!UICONTROL Endpoint]** en **[!UICONTROL Identity]**.

   ![](assets/connect-brighttalk-to-marketo-9.png)

## Extra stappen in [!DNL BrightTALK] {#additional-steps-in-brighttalk}

1. Terugkeren naar de [!DNL BrightTALK] het opstellingsscherm van de schakelaar van Stap 3, en ga de geloofsbrieven in u van Stappen 12 en 14 bewaarde.

Nadat de geloofsbrieven voor authentiek worden verklaard, hebt u officieel verbonden [!DNL BrightTALK] naar Marketo. De volgende stap is te bepalen [welke gegevensvelden u wilt synchroniseren](https://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync){target="_blank"}.
