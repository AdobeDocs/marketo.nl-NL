---
description: Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 2 van 3 - Marketo Docs - Productdocumentatie installeren
title: Marketo voor Microsoft Dynamics 2016/Dynamics 365 op locatie installeren Stap 2 van 3
exl-id: c789b977-7ada-4f5d-8488-e1b58963f7e3
feature: Microsoft Dynamics
source-git-commit: e3f61755dccd9bea1378a429fc428b440fc3ecb4
workflow-type: tm+mt
source-wordcount: '467'
ht-degree: 1%

---

# Stap 2 van 3 Opstelling Marketo for Dynamics (2016 On-Prem/Dynamics 365 On-Premises){#step-of-set-up-for-marketo-on-premises-2016}

Geweldig werk bij het voltooien van de vorige stappen. Laten we hier doorheen gaan.

>[!PREREQUISITES]
>
>[ installeer Marketo voor Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 1 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md){target="_blank"}

## Een nieuwe gebruiker maken {#create-a-new-user}

1. Meld u aan bij Dynamics. Klik op het pictogram Instellingen en selecteer Geavanceerde instellingen.

   ![](assets/step-2-of-3-marketo-on-premises-2016-1.png)

1. Klik op **[!UICONTROL Settings]** en selecteer **[!UICONTROL Security]** .

   ![](assets/step-2-of-3-marketo-on-premises-2016-2.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-3.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-4.png)

1. Klik op **[!UICONTROL Add and License Users]**. Er moet een nieuw tabblad worden geopend.

   ![](assets/step-2-of-3-marketo-on-premises-2016-5.png)

1. Klik op **[!UICONTROL Admin]** boven aan de pagina. Er moet een ander nieuw tabblad worden geopend.

   ![](assets/step-2-of-3-marketo-on-premises-2016-6.png)

1. Klik op **[!UICONTROL Add a user]**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-7.png)

1. Voer al uw gegevens in. Klik op **[!UICONTROL Add]** als u klaar bent.

   ![](assets/step-2-of-3-marketo-on-premises-2016-8.png)

   >[!NOTE]
   >
   >Deze naam moet een specifieke synchronisatiegebruiker zijn en geen bestaande rekening van de gebruiker van CRM. Het hoeft geen echt e-mailadres te zijn.

1. Voer het e-mailbericht in waarin u de nieuwe gebruikersgegevens wilt ontvangen en klik op E-mail verzenden en sluit het.

   ![](assets/step-2-of-3-marketo-on-premises-2016-9.png)

## Een nieuwe clienttoepassing maken {#create-a-new-client-application}

Volg de stappen in [ dit artikel van Microsoft ](https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/development/enabling-oauth-confidential-clients-with-ad-fs#create-an-application-group-in-ad-fs-2016-or-later){target="_blank"} om een nieuwe Toepassing van de Cliënt tot stand te brengen en toestemmingen te verlenen. Noteer de client-id/-geheim van de Dynamic-clienttoepassing.

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om uw Marketo te bevorderen, zie [ Verbetering de Oplossing van Marketo voor Microsoft Dynamics ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}.

>[!IMPORTANT]
>
>Taal het plaatsen van de Gebruiker van de Synchronisatie [ zou aan Engels ](https://learn.microsoft.com/en-us/power-platform/admin/enable-languages){target="_blank"} moeten worden geplaatst.

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Security]** .

   ![](assets/assign1.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/assign2.png)

1. Hier wordt een lijst met gebruikers weergegeven. Selecteer de specifieke gebruiker van de Synchronisatie van Marketo of contacteer uw [ Actieve beheerder van de Federatie van de Folder van de Diensten ](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} (ADFS) om een specifieke gebruiker voor Marketo tot stand te brengen.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Selecteer de synchronisatiegebruiker. Klik op **[!UICONTROL Manage Roles]**.

   ![](assets/assign4.png)

1. Controleer Marketo Sync User en klik op **[!UICONTROL OK]** .

   ![](assets/assign5.png)

   >[!TIP]
   >
   >Als u niet de rol ziet, ga terug naar [ stap 1 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md) en voer de oplossing in.

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen _niet_ terug naar Marketo worden gesynchroniseerd.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna klaar! We hebben slechts een paar laatste stukken configuratie voordat we naar het volgende artikel gaan.

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Marketo Config]** .

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als Marketo Config ontbreekt. Als de kwestie voortduurt, [ publiceer de Oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md){target="_blank"} of probeer het programma openen en terug binnen.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/configure2.png)

1. Klik op het veld **[!UICONTROL Marketo User]** en selecteer de synchronisatiegebruiker.

   ![](assets/configure3.png)

1. Klik op het pictogram Opslaan in de rechterbenedenhoek.

   ![](assets/configure4.png)

1. Klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal verslagen wilt beperken u synchroniseert, [ opstelling een filter van de douanesynchronisatie ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} nu.
* Stel [ in werking bevestigen de Synchronisatie van Microsoft Dynamics ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

>[!MORELIKETHIS]
>
>[ installeer Marketo voor Microsoft Dynamics 2016/Dynamics 365 On-Premises Stap 3 van 3 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-3-of-3-connect.md){target="_blank"}
