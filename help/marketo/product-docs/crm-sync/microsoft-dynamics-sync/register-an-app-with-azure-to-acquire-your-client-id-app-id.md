---
unique-page-id: 12983390
description: Registreer een app bij Azure om uw client-id/app-id aan te schaffen - Marketo Docs - Productdocumentatie
title: Registreer een app bij Azure om uw client-id/app-id op te halen
exl-id: 006cd130-a2fc-41ce-b5ee-890ef6167b34
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '311'
ht-degree: 0%

---

# Registreer een app bij Azure om uw client-id/app-id op te halen {#register-an-app-with-azure-to-acquire-your-client-id-app-id}

Azure Active Directory breidt uw directories op locatie uit naar de cloud en biedt ondersteuning voor MS Dynamics 365 CRM met ADFS-verificatie op locatie.

## Een nieuwe app registreren {#registering-a-new-app}

1. [Aanmelden](https://login.microsoftonline.com/){target="_blank"} naar de Microsoft Azure-beheerportal met een account met beheerdersrechten. U kunt het Microsoft Azure-portaal ook openen via het Office 365 Admin Center door de **[!UICONTROL Admin]** item in het linkernavigatievenster en selecteren **[!UICONTROL Azure AD]**.

   >[!CAUTION]
   >
   >U moet een account gebruiken in hetzelfde Office 365-abonnement als de account waarmee u de app wilt registreren.

   >[!NOTE]
   >
   >Als u geen Azure-account hebt, kunt u [aanmelden](https://azure.microsoft.com/en-us/free/){target="_blank"} voor één. Raadpleeg de documentatie bij Microsoft of neem contact op met uw Microsoft-vertegenwoordiger voor meer informatie. Nadat u een Azure-account hebt gemaakt, kunt u een of meer apps registreren aan de hand van de onderstaande procedure.
   >
   >
   >Als u een Azure-account hebt maar uw Office 365-abonnement met Microsoft Dynamics 365 niet beschikbaar is in uw Azure-abonnement, volgt u [deze instructies](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription){target="_blank"} om de twee accounts te koppelen.

1. Zoeken en klikken **[!UICONTROL Azure Active Directory]** in het linkernavigatiegebied.

   ![](assets/two.png)

1. Klik onder Beheren op **[!UICONTROL App registrations]**.

   ![](assets/three.png)

1. Klikken **[!UICONTROL New registration]** boven aan de pagina.

   ![](assets/four.png)

1. Voer een naam voor uw app in, kies het accounttype dat u wilt gebruiken en voer een omleidings-URL in. Klik vervolgens op **[!UICONTROL Register]** onder aan de pagina.

   ![](assets/five.png)

1. U moet nu uw app in de **[!UICONTROL App registrations]** tab.

   ![](assets/six.png)

## Toepassingsmachtigingen configureren {#configuring-app-permissions}

1. Onder de **[!UICONTROL App registrations]** in uw Actieve Folder, klik app u toestemmingen voor wilt vormen.

   ![](assets/seven.png)

1. Klik onder Beheren op **[!UICONTROL API permissions]**.

   ![](assets/eight.png)

1. Klik op de knop **[!UICONTROL Add a permission]** knop.

   ![](assets/nine.png)

1. Kies **[!UICONTROL Dynamics CRM]**.

   ![](assets/ten.png)

1. Controleer de **[!UICONTROL Access Common Data Service as organization users]** en klik vervolgens op **[!UICONTROL Add permissions]**.

   ![](assets/eleven.png)

1. Zodra de toestemmingen met succes zijn toegevoegd, wacht minstens 10 seconden.

   ![](assets/twelve.png)

1. Klik op de knop **[!UICONTROL Grant admin consent]** knop.

   ![](assets/thirteen.png)

1. Klikken **[!UICONTROL Yes]** ter bevestiging.

   ![](assets/fourteen.png)

   En je bent klaar!

   ![](assets/fifteen.png)
