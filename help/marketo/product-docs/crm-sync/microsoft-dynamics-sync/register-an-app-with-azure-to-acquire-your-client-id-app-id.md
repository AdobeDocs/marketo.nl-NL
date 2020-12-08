---
unique-page-id: 12983390
description: Registreer een app bij Azure om uw client-id/app-id aan te schaffen - Marketo Docs - Productdocumentatie
title: Registreer een app bij Azure om uw client-id/app-id op te halen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '346'
ht-degree: 0%

---


# Registreer een app bij Azure om uw client-id/app-id op te halen {#register-an-app-with-azure-to-acquire-your-client-id-app-id}

Azure Active Directory breidt uw directories op locatie uit naar de cloud en biedt ondersteuning voor MS Dynamics 365 CRM met ADFS-verificatie op locatie.

## Een nieuwe app registreren {#registering-a-new-app}

1. [Meld u aan bij](http://manage.windowsazure.com/) de Microsoft Azure-beheerportal met een account met beheerdersrechten. U kunt tot het portaal van Microsoft Azure ook toegang hebben door Office 365 Admin Center door het **Admin** punt in de linkernavigatieruit uit te breiden en **Azure AD** te selecteren.

   >[!CAUTION]
   >
   >U moet een account gebruiken in hetzelfde Office 365-abonnement als de account waarmee u de app wilt registreren.

   >[!NOTE]
   >
   >Als u geen Azure-account hebt, kunt u zich [aanmelden](https://azure.microsoft.com/en-us/free/) voor een account. Raadpleeg de documentatie van Microsoft of neem contact op met uw vertegenwoordiger van Microsoft voor meer informatie. Nadat u een Azure-account hebt gemaakt, kunt u een of meer apps registreren aan de hand van de onderstaande procedure.
   >
   >
   >Als u een Azure-account hebt maar uw Office 365-abonnement op Microsoft Dynamics 365 niet beschikbaar is in uw Azure-abonnement, volgt u [deze instructies](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription) om de twee accounts te koppelen.

1. Zoek en klik op **Azure Active Directory** in het linkernavigatievenster.

   ![](assets/two.png)

1. Klik onder Beheer op **Toepassingsregistraties**.

   ![](assets/three.png)

1. Klik op **Nieuwe registratie **boven aan de pagina.

   ![](assets/four.png)

1. Voer een naam voor uw app in, kies het accounttype dat u wilt gebruiken en voer een omleidings-URL in. Klik vervolgens onder aan de pagina op **Registreren** .

   ![](assets/five.png)

1. De app wordt nu weergegeven op het tabblad **App-registraties** .

   ![](assets/six.png)

## Toepassingsmachtigingen configureren {#configuring-app-permissions}

1. Klik onder het tabblad **App-registraties** in uw Active Directory op de toepassing waarvoor u machtigingen wilt configureren.

   ![](assets/seven.png)

1. Klik onder Beheren op **API-machtigingen**.

   ![](assets/eight.png)

1. Klik op de knop **Een machtiging** toevoegen.

   ![](assets/nine.png)

1. Kies **Dynamics CRM**.

   ![](assets/ten.png)

1. Schakel het vak **Toegang tot algemene gegevensservice als organisatiegebruiker***s** in en klik op Machtigingen **toevoegen.**

   ![](assets/eleven.png)

1. Zodra de toestemmingen met succes zijn toegevoegd, wacht minstens 10 seconden.

   ![](assets/twelve.png)

1. Klik op de knop **Toekenning** beheerder verlenen.

   ![](assets/thirteen.png)

1. Klik op **Ja** om te bevestigen.

   ![](assets/fourteen.png)

   En je bent klaar!

   ![](assets/fifteen.png)

