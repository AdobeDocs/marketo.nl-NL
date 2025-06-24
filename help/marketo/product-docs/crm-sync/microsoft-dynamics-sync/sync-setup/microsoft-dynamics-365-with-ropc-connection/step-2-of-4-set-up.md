---
description: Stap 2 van 4 - Opstelling de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel - de Documentatie van Marketo -
title: Stap 2 van 4 - Opstelling de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel
exl-id: 41c05910-d8e3-4fb7-8f68-17ee10294e57
feature: Microsoft Dynamics
source-git-commit: e3f61755dccd9bea1378a429fc428b440fc3ecb4
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 1%

---

# Stap 2 van 4: Opstelling de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel {#step-2-of-4-set-up-the-marketo-solution-ropc}

Laten we beginnen met het maken van een gebruikersaccount.

>[!PREREQUISITES]
>
>[ Stap 1 van 4: Installeer de Oplossing van Marketo met de Verbinding van de Controle van het Wachtwoord van de Eigenaar van het Middel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md){target="_blank"}

## Nieuwe gebruiker maken {#create-a-new-user}

1. Meld u aan bij Dynamiek. Klik op het pictogram Instellingen en selecteer **[!UICONTROL Advanced Settings]** .

   ![](assets/one.png)

1. Klik op **[!UICONTROL Settings]** en selecteer **[!UICONTROL Security]** .

   ![](assets/two.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/three.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/four.png)

1. Klik op **[!UICONTROL Add and License Users]** in het nieuwe venster.

   ![](assets/five.png)

1. Er wordt een nieuw tabblad geopend. Klik op **[!UICONTROL Admin]** boven aan de pagina.

   ![](assets/six.png)

1. Er wordt een ander nieuw tabblad geopend. Klik op **[!UICONTROL Add a user]**.

   ![](assets/seven.png)

   >[!IMPORTANT]
   >
   >De gebruiker van de Synchronisatie zou lees toestemming aan Marketo Config moeten hebben.

1. Voer al uw gegevens in. Klik op **[!UICONTROL Add]** als u klaar bent.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Deze naam moet een specifieke synchronisatiegebruiker zijn en geen bestaande rekening van de gebruiker van CRM. Het hoeft geen echt e-mailadres te zijn.

1. Voer het e-mailbericht in waarin u de nieuwe gebruikersgegevens wilt ontvangen en klik op **[!UICONTROL Send email and close]** .

   ![](assets/nine.png)

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo-versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie [ de Oplossing van Marketo van de Verbetering voor Microsoft Dynamics ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}.

>[!IMPORTANT]
>
>Taal het plaatsen van de Gebruiker van de Synchronisatie [ zou aan Engels ](https://learn.microsoft.com/en-us/power-platform/admin/enable-languages){target="_blank"} moeten worden geplaatst.

1. Ga terug naar de tab **[!UICONTROL Enabled Users]** en vernieuw de lijst met gebruikers.

   ![](assets/ten.png)

1. Houd de muisaanwijzer boven de nieuwe Marketo Sync-gebruiker en schakel een selectievakje in. Klik om het te selecteren.

   ![](assets/eleven.png)

1. Klik op **[!UICONTROL Manage Roles]**.

   ![](assets/twelve.png)

1. Controleer **[!UICONTROL Marketo Sync User]** en klik op **[!UICONTROL OK]** .

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen _niet_ terug naar Marketo worden gesynchroniseerd.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna daar! Alles wat we nog hebben, is om Marketo Solution te informeren over de nieuwe gebruiker die is gemaakt.

1. Ga terug naar het gedeelte Geavanceerde instellingen, klik op het pictogram ![](assets/image2015-5-13-15-3a49-3a19.png) naast Instellingen en selecteer **[!UICONTROL Marketo Config]** .

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als u **[!UICONTROL Marketo Config]** niet ziet in het menu Instellingen. Als dat niet werkt, probeer [ om de Oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md){target="_blank"} opnieuw te publiceren of logout en terug binnen.

1. Klik op **[!UICONTROL Default]**.

   ![](assets/fifteen.png)

1. Klik op de zoekknop in het veld **[!UICONTROL Marketo User]** en selecteer de synchronisatiegebruiker die u hebt gemaakt.

   ![](assets/sixteen.png)

1. Klik op het pictogram ![](assets/image2015-3-13-15-3a10-3a11.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Klik **X** in het hoger-recht om het scherm te sluiten.

   ![](assets/seventeen.png)

1. Klik op het pictogram ![](assets/image2015-5-13-15-3a49-3a19-1.png) naast Instellingen en selecteer **[!UICONTROL Solutions]** .

   ![](assets/eighteen.png)

1. Klik op **[!UICONTROL Publish All Customizations]** .

   ![](assets/nineteen.png)

>[!MORELIKETHIS]
>
>[ Stap 3 van 4: Verbind de Oplossing van Marketo met de Verbinding van de Controle van het Wachtwoord van de Eigenaar van het Middel ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md){target="_blank"}
