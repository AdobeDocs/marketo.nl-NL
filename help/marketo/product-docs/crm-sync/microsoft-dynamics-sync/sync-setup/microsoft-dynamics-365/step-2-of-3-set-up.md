---
unique-page-id: 3571827
description: Stap 2 van 3 - de Marketo van de opstelling om Gebruiker in Dynamiek te synchroniseren - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - Opstelling Marketo om Gebruiker in Dynamiek te synchroniseren
translation-type: tm+mt
source-git-commit: dc20aede0894a09e6c0bcd3d1580859b5fecb5f1
workflow-type: tm+mt
source-wordcount: '461'
ht-degree: 0%

---


# Stap 2 van 3: Marketo synchroniseren van gebruiker in dynamiek instellen {#step-of-set-up-marketo-sync-user-in-dynamics}

Laten we beginnen met het maken van een gebruikersaccount.

>[!NOTE]
>
>**Vereisten**
>
>[Stap 1 van 3: De Marketo-oplossing installeren (online)](step-1-of-3-install.md)

## Nieuwe gebruiker maken {#create-a-new-user}

1. Meld u aan bij Dynamics. Klik op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klik op** Instellingen** en selecteer **Beveiliging**.

   ![](assets/two.png)

1. Klik op **Gebruikers**.

   ![](assets/three.png)

1. Klik op **Nieuw.**

   ![](assets/four.png)

1. Klik op Gebruikers **** toevoegen en licentie toevoegen in het nieuwe venster.

   ![](assets/five.png)

1. Er wordt een nieuw tabblad geopend. Klik op **Beheerder** boven aan de pagina.

   ![](assets/six.png)

1. Er wordt een ander nieuw tabblad geopend. Klik op **Een gebruiker** toevoegen.

   ![](assets/seven.png)

1. Voer al uw gegevens in. Klik op **Toevoegen** als u klaar bent.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Deze naam moet een specifieke synchronisatiegebruiker zijn en geen bestaande rekening van de gebruiker van CRM. Het hoeft geen echt e-mailadres te zijn.

1. Voer het e-mailbericht in waarin u de nieuwe gebruikersgegevens wilt ontvangen en klik op E-mail **verzenden en sluit** het.

   ![](assets/nine.png)

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de rol Marketo Sync User alleen toe aan Marketo Sync user. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Om Marketo te bevorderen, zie de Oplossing van de Marketo van de [Verbetering voor de Dynamica](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md)van Microsoft.

1. Ga terug naar het Toegelaten lusje van Gebruikers en vernieuw de gebruikerslijst.

   ![](assets/ten.png)

1. Houd de muisaanwijzer boven de nieuwe Marketo Sync-gebruiker en schakel een selectievakje in. Klik om het te selecteren.

   ![](assets/eleven.png)

1. Klik op Rollen **beheren**.

   ![](assets/twelve.png)

1. Schakel **Marketo Sync User** in en klik op **OK**.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >Updates die door de synchronisatiegebruiker in uw CRM worden uitgevoerd, worden **niet** weer gesynchroniseerd met Marketo.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna daar! We hebben alleen nog maar Marketo Solution op de hoogte gebracht van de nieuwe gebruiker die is gemaakt.

1. Ga terug naar de Geavanceerde sectie van Montages, klik het ![](assets/image2015-5-13-15-3a49-3a19.png)pictogram naast Montages, en selecteer **Marketo Config**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >Vernieuw de pagina als u **Marketo Config** niet ziet in het menu Instellingen. Als dat niet werkt, probeer om de Oplossing [van het Marketo opnieuw te](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) [](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) publiceren of logout en terug binnen.

1. Klik op **Standaard**.

   ![](assets/fifteen.png)

1. Klik op de zoekknop in het veld **Marketo-gebruiker** en selecteer de synchronisatiegebruiker die u hebt gemaakt.

   ![](assets/sixteen.png)

1. Klik op het ![](assets/image2015-3-13-15-3a10-3a11.png)pictogram in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Klik op de **X** rechtsboven om het scherm te sluiten.

   ![](assets/seventeen.png)

1. Klik op het ![](assets/image2015-5-13-15-3a49-3a19-1.png)pictogram naast Instellingen en selecteer **Oplossingen**.

   ![](assets/eighteen.png)

1. Klik op de knop **Alle aanpassingen** publiceren.

   ![](assets/nineteen.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

    * Als u het aantal records dat u synchroniseert wilt beperken, moet u [een aangepast synchronisatiefilter instellen] (../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md).
    * Voer het proces [Validate Microsoft Dynamics Sync] (../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) uit. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
    * Login in de Marketo Sync Gebruiker in de Dynamica CRM van Microsoft.

>[!NOTE]
>
>**Verwante artikelen**
>
>
>[Stap 3 van 3: Microsoft Dynamics verbinden met Marketo (online)](step-3-of-3-connect.md)
