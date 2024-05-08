---
unique-page-id: 12976798
description: LinkedIn-leadgen. Forms - Marketo Docs - Productdocumentatie instellen
title: LinkedIn-leadgen. Forms instellen
exl-id: 554a546c-adeb-4132-830d-ff15ba5cf9a1
feature: Social
source-git-commit: 94ca714d038863ad801551960c66086ea47e6b10
workflow-type: tm+mt
source-wordcount: '511'
ht-degree: 0%

---

# LinkedIn-leadgen. Forms instellen {#set-up-linkedin-lead-gen-forms}

Gebruik LinkedIn Lead Gen Forms om advertentiecampagnes in LinkedIn uit te voeren en leads te genereren voor Marketo.

>[!IMPORTANT]
>
>LinkedIn voert een upgrade uit van de marketing-API&#39;s die worden gebruikt door de integratie van Marketo Engage LinkedIn. Deze wijzigingen vereisen opnieuw verificatie van alle LinkedIn LaunchPoint-services in uw **Beheerder** > **LaunchPoint** tussen 7 juni en 15 december 2024 om onderbreking van de service te voorkomen. Zie voor meer informatie de [Veelgestelde vragen over migratie](https://nation.marketo.com/t5/employee-blogs/linkedin-re-authentication-required/ba-p/347794){target="_blank"}.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!NOTE]
>
>Een lead van LinkedIn komt niet in Marketo Engage als deze overeenkomt met een bestaand persoonrecord in Marketo dat is gekoppeld aan een bedrijfsrecord dat is gemaakt met behulp van Company API&#39;s en het Marketo-abonnement geen verbinding heeft met een CRM.

1. Ga naar Marketo **Beheerder**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. Ga naar **LaunchPoint**, klikt u op **Nieuw** en selecteert u **Nieuwe service**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. Voer een **Weergavenaam** voor uw dienst, selecteer **Gen.-linkedIn** van de drop-down dienst, en klik **Volgende**.

   ![](assets/linkedin-lead-gen.png)

1. Marketo opent een nieuw tabblad in dezelfde browser voor [linkedin.com](https://www.linkedin.com). Meld u aan bij LinkedIn met het account dat u voor de integratie wilt gebruiken.

   >[!NOTE]
   >
   >De LinkedIn-account heeft toegang nodig tot alle LinkedIn Business Accounts waarvoor u gesponsorde campagnes maakt.

   ![](assets/linkedin-login.png)

1. Ga terug naar Marketo nadat u zich hebt aangemeld bij LinkedIn en klik op **Autoriseren**.

   ![](assets/linkedin-lead-gen-authorize.png)

1. Klik op **Toestaan** om de installatie van de Marketo-app in LinkedIn te accepteren.

   ![](assets/linkedin-marketo-allow.png)

1. Je ziet dat je nu geautoriseerd bent. Klikken **Volgende**.

   ![](assets/image2017-9-28-7-3a55-3a14.png)

   >[!CAUTION]
   >
   >De dienst verloopt automatisch één jaar na vergunning. Om toegang te herstellen klikt u gewoon op **Opnieuw goedkeuren**. U moet mogelijk uw LinkedIn-wachtwoord opnieuw invoeren, afhankelijk van uw browserinstellingen.

1. Selecteer de account(s) waarvan u wilt dat LinkedIn Lead Gen uit Marketo komt en klik op **Volgende**.

   >[!TIP]
   >
   >Als u de zakelijke accounts die u verwacht niet ziet, controleert u of voor de LinkedIn-account van de gebruiker die wordt geautoriseerd, leid-gen-formulierbeheermachtigingen zijn ingesteld voor de zakelijke account in LinkedIn.

   ![](assets/linkedin-pages-to-capture.png)

1. Als u standaard LinkedIn- naar Marketo-veldtoewijzingen wilt accepteren, klikt u gewoon op **Maken**. Als u de standaardveldtoewijzing wilt wijzigen, een veldtoewijzing wilt verwijderen of een nieuwe veldtoewijzing wilt toevoegen, kunt u dit per veld doen via de onderstaande modus.

   >[!CAUTION]
   >
   >Marketo ondersteunt het toewijzen van twee LinkedIn-velden aan één Marketo-veld. **maar alleen wanneer** de twee LinkedIn-velden bevinden zich niet op hetzelfde formulier. Als u twee velden van hetzelfde LinkedIn-formulier toewijst aan één Marketo-veld, kunnen mensen uw Marketo-database niet invoeren.

   ![](assets/linkedin-lead-gen-mapping.png)

   >[!NOTE]
   >
   >Alleen LinkedIn-velden die al zijn opgeslagen naar een [formuliersjabloon](https://www.linkedin.com/help/lms/answer/79634) in LinkedIn Campaign Manager wordt weergegeven als LinkedIn-velden die kunnen worden toegewezen aan Marketo-velden.

   ![](assets/linkedin-installed-services.png)

Echt waar! Mensen die LinkedIn-leadgen-formulieren indienen zullen naar Marketo gaan vliegen terwijl u succesvolle campagnes voert aan de zijde van LinkedIn.

>[!NOTE]
>
>U kunt slechts één LinkedIn-gebruikersaccount autoriseren. Als u meerdere zakelijke accounts hebt die u aan Marketo wilt koppelen, moet u ervoor zorgen dat de LinkedIn-account van de gebruiker die wordt geautoriseerd, leid-gen-formulierbeheermachtigingen heeft voor de Business Account in LinkedIn.

>[!MORELIKETHIS]
>
>[LinkedIn Lead Gen Form Filters and Triggers gebruiken in een slimme campagne](/help/marketo/product-docs/demand-generation/social/social-functions/use-linkedin-lead-gen-form-filters-and-triggers-in-a-smart-campaign.md)
