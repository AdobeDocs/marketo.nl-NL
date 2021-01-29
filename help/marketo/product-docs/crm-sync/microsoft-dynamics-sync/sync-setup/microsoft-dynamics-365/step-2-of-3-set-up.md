---
unique-page-id: 3571827
description: Stap 2 van 3 - de Marketo van de opstelling om Gebruiker in Dynamiek te synchroniseren - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - Opstelling Marketo om Gebruiker in Dynamiek te synchroniseren
translation-type: tm+mt
source-git-commit: 309f299275bfe75e8af0150be0a5ffdf28a54cf8
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 0%

---


# Stap 2 van 3: Markering instellen om gebruiker te synchroniseren in dynamiek {#step-of-set-up-marketo-sync-user-in-dynamics}

Laten we beginnen met het maken van een gebruikersaccount.

>[!PREREQUISITES]
>
>[Stap 1 van 3: De Marketo-oplossing installeren (online)](step-1-of-3-install.md)

## Nieuwe gebruiker {#create-a-new-user} maken

1. Meld u aan bij Dynamics. Klik op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klik op** Instellingen** en selecteer **Beveiliging**.

   ![](assets/two.png)

1. Klik **Users**.

   ![](assets/three.png)

1. Klik **Nieuw.**

   ![](assets/four.png)

1. Klik **Gebruikers toevoegen en Licentie toevoegen** in het nieuwe venster.

   ![](assets/five.png)

1. Er wordt een nieuw tabblad geopend. Klik **Admin** bij de bovenkant van de pagina.

   ![](assets/six.png)

1. Er wordt een ander nieuw tabblad geopend. Klik **Een gebruiker toevoegen**.

   ![](assets/seven.png)

1. Voer al uw gegevens in. Als u klaar bent, klikt u op **Toevoegen**.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Deze naam moet een specifieke synchronisatiegebruiker zijn en geen bestaande rekening van de gebruiker van CRM. Het hoeft geen echt e-mailadres te zijn.

1. Voer het e-mailbericht in waarin u de nieuwe gebruikersgegevens wilt ontvangen en klik op **E-mail verzenden en sluiten**.

   ![](assets/nine.png)

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de rol Marketo Sync User alleen toe aan Marketo Sync user. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie [Oplossing van de Marketo van de Verbetering voor de Dynamica van Microsoft](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/upgrade-the-marketo-solution-for-microsoft-dynamics.md).

1. Ga terug naar het Toegelaten lusje van Gebruikers en vernieuw de gebruikerslijst.

   ![](assets/ten.png)

1. Houd de muisaanwijzer boven de nieuwe Marketo Sync-gebruiker en schakel een selectievakje in. Klik om het te selecteren.

   ![](assets/eleven.png)

1. Klik **Rollen beheren**.

   ![](assets/twelve.png)

1. Schakel **Marketo Sync User** in en klik **OK**.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >Om het even welke updates die in uw CRM door de Gebruiker van de Synchronisatie worden gemaakt zullen **not** worden gesynchroniseerd terug naar Marketo.

## Marketo-oplossing {#configure-marketo-solution} configureren

Bijna daar! We hebben alleen nog maar Marketo Solution op de hoogte gebracht van de nieuwe gebruiker die is gemaakt.

1. Ga terug naar de Geavanceerde sectie van Montages, klik ![](assets/image2015-5-13-15-3a49-3a19.png)pictogram naast Montages, en selecteer **Marketo Config**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >Als u **Marketo Config** in het menu van Montages niet ziet, vernieuw de pagina. Als dat niet werkt, probeer om [de Oplossing van de Marketo ](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) [](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) opnieuw te publiceren of logout en terug binnen.

1. Klik **Standaard**.

   ![](assets/fifteen.png)

1. Klik op de zoekknop in het veld **Marketo User** en selecteer de synchronisatiegebruiker die u hebt gemaakt.

   ![](assets/sixteen.png)

1. Klik op het pictogram ![](assets/image2015-3-13-15-3a10-3a11.png)in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Klik op **X** in de rechterbovenhoek om het scherm te sluiten.

   ![](assets/seventeen.png)

1. Klik op het pictogram ![](assets/image2015-5-13-15-3a49-3a19-1.png)naast Instellingen en selecteer **Oplossingen**.

   ![](assets/eighteen.png)

1. Klik op de knop **Alle aanpassingen publiceren**.

   ![](assets/nineteen.png)

## Voordat u doorgaat naar stap 3 {#before-proceeding-to-step}

    * Als u het aantal records dat u synchroniseert wilt beperken, moet u [een aangepast synchronisatiefilter instellen] (../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md).
    * Voer het proces [Validate Microsoft Dynamics Sync] (../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) uit. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
    * Login in de Marketo Sync Gebruiker in de Dynamica CRM van Microsoft.

>[!NOTE]
>
>**Verwante artikelen**
>
>
>[Stap 3 van 3: Microsoft Dynamics verbinden met Marketo (online)](step-3-of-3-connect.md)
