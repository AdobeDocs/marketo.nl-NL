---
unique-page-id: 12983390
description: Registreer een app bij Azure om uw client-id/app-id aan te schaffen - Marketo Docs - Productdocumentatie
title: Registreer een app bij Azure om uw client-id/app-id op te halen
exl-id: 006cd130-a2fc-41ce-b5ee-890ef6167b34
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---

# Registreer een app bij Azure om uw client-id/app-id {#register-an-app-with-azure-to-acquire-your-client-id-app-id} te verkrijgen

Azure Active Directory breidt uw directories op locatie uit naar de cloud en biedt ondersteuning voor MS Dynamics 365 CRM met ADFS-verificatie op locatie.

## Een nieuwe app {#registering-a-new-app} registreren

1. [Meld u ](https://manage.windowsazure.com/) aan bij de Microsoft Azure-beheerportal met een account met beheerdersrechten. U kunt tot het portaal van Microsoft Azure ook toegang hebben door Office 365 Admin Center door **Admin** punt in de linkernavigatieruit uit te breiden en **Azure AD** te selecteren.

   >[!CAUTION]
   >
   >U moet een account gebruiken in hetzelfde Office 365-abonnement als de account waarmee u de app wilt registreren.

   >[!NOTE]
   >
   >Als u geen Azure-account hebt, kunt u [zich ](https://azure.microsoft.com/en-us/free/) voor één account aanmelden. Raadpleeg de documentatie van Microsoft of neem contact op met uw vertegenwoordiger van Microsoft voor meer informatie. Nadat u een Azure-account hebt gemaakt, kunt u een of meer apps registreren aan de hand van de onderstaande procedure.
   >
   >
   >Als u een Azure-account hebt maar uw Office 365-abonnement met Microsoft Dynamics 365 niet beschikbaar is in uw Azure-abonnement, volgt u [deze instructies](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription) om de twee accounts te koppelen.

1. Zoek en klik **Azure Active Directory** in het linkernavigatievenster.

   ![](assets/two.png)

1. Klik onder Beheren op **Toepassingsregistraties**.

   ![](assets/three.png)

1. Klik **Nieuwe registratie** bij de bovenkant van de pagina.

   ![](assets/four.png)

1. Voer een naam voor uw app in, kies het accounttype dat u wilt gebruiken en voer een omleidings-URL in. Klik vervolgens op **Registreren** onder aan de pagina.

   ![](assets/five.png)

1. De toepassing wordt nu weergegeven op het tabblad **Toepassingsregistraties**.

   ![](assets/six.png)

## Toepassingsmachtigingen {#configuring-app-permissions} configureren

1. Klik onder **App-registraties** tabblad in uw Active Directory op de toepassing waarvoor u machtigingen wilt configureren.

   ![](assets/seven.png)

1. Klik onder Beheren op **API-machtigingen**.

   ![](assets/eight.png)

1. Klik op de knop **Een machtiging toevoegen**.

   ![](assets/nine.png)

1. Kies **Dynamische CRM**.

   ![](assets/ten.png)

1. Schakel het selectievakje **Algemene gegevensservice openen als organisatiegebruiker***s** in en klik op **Machtigingen toevoegen.**

   ![](assets/eleven.png)

1. Zodra de toestemmingen met succes zijn toegevoegd, wacht minstens 10 seconden.

   ![](assets/twelve.png)

1. Klik op de knop **Goedkeuring van beheerder toewijzen**.

   ![](assets/thirteen.png)

1. Klik **Ja** om te bevestigen.

   ![](assets/fourteen.png)

   En je bent klaar!

   ![](assets/fifteen.png)
