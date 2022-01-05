---
description: Stap 2 van 3 - Opstelling de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel - Marketo Docs - de Documentatie van het Product
title: Stap 2 van 3 - Opstelling de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel
source-git-commit: 17cacaa56a437a568bd0d2cc23020f3f880eaf52
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 0%

---

# Stap 2 van 3: Stel de Marketo-oplossing in met de Wachtwoordbeheerverbinding van de Eigenaar van het Middel {#step-2-of-3-set-up-the-marketo-solution-ropc}

Laten we beginnen met het maken van een gebruikersaccount.

>[!PREREQUISITES]
>
>[Stap 1 van 4: De Marketo-oplossing installeren met de wachtwoordcontroleverbinding van de eigenaar van het resource](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md)

## Nieuwe gebruiker maken {#create-a-new-user}

1. Meld u aan bij Dynamics. Klik op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klikken **Instellingen** en selecteert u **Beveiliging**.

   ![](assets/two.png)

1. Klikken **Gebruikers**.

   ![](assets/three.png)

1. Klikken **Nieuw.**

   ![](assets/four.png)

1. Klikken **Gebruikers toevoegen en licentie geven** in het nieuwe venster.

   ![](assets/five.png)

1. Er wordt een nieuw tabblad geopend. Klikken **Beheer** boven aan de pagina.

   ![](assets/six.png)

1. Er wordt een ander nieuw tabblad geopend. Klikken **Een gebruiker toevoegen**.

   ![](assets/seven.png)

1. Voer al uw gegevens in. Als u klaar bent, klikt u op **Toevoegen**.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >Deze naam moet een specifieke synchronisatiegebruiker zijn en geen bestaande rekening van de gebruiker van CRM. Het hoeft geen echt e-mailadres te zijn.

1. Voer het e-mailbericht in waarin u de nieuwe gebruikersgegevens wilt ontvangen en klik op **E-mail verzenden en sluiten**.

   ![](assets/nine.png)

## Gebruikersrol synchroniseren toewijzen {#assign-sync-user-role}

Wijs de Marketo Sync User rol alleen toe aan de Marketo sync-gebruiker. U hoeft het niet aan andere gebruikers toe te wijzen.

>[!NOTE]
>
>Dit geldt voor Marketo versie 4.0.0.14 en hoger. Voor eerdere versies moeten alle gebruikers de gebruikersrol synchroniseren hebben. Ga voor een upgrade van Marketo naar [Upgrade Marketo Solution for Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
>
>De taalinstelling van de synchronisatiegebruiker [moet worden ingesteld op Engels](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us).

1. Ga terug naar het Toegelaten lusje van Gebruikers en vernieuw de gebruikerslijst.

   ![](assets/ten.png)

1. Houd de muisaanwijzer boven de nieuwe Marketo Sync-gebruiker en schakel een selectievakje in. Klik om het te selecteren.

   ![](assets/eleven.png)

1. Klikken **Rollen beheren**.

   ![](assets/twelve.png)

1. Controleren **Marketo Sync-gebruiker** en klik op **OK**.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >Alle updates die door de synchronisatiegebruiker in uw CRM worden aangebracht, worden **niet** worden gesynchroniseerd naar Marketo.

## Marketo-oplossing configureren {#configure-marketo-solution}

Bijna daar! Alles wat we nog hebben, is om Marketo Solution te informeren over de nieuwe gebruiker die is gemaakt.

1. Ga terug naar het gedeelte Geavanceerde instellingen en klik op de knop ![](assets/image2015-5-13-15-3a49-3a19.png) pictogram naast Instellingen en selecteer **Marketo Config**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >Als u het niet ziet **Marketo Config** vernieuwt de pagina in het menu Instellingen. Als dat niet werkt, probeert u [De Marketo-oplossing publiceren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md) opnieuw of logout and back in.

1. Klikken **Standaard**.

   ![](assets/fifteen.png)

1. Klik op de knop Zoeken op de knop **Marketo-gebruiker** en selecteer de synchronisatiegebruiker u creeerde.

   ![](assets/sixteen.png)

1. Klik op de knop ![](assets/image2015-3-13-15-3a10-3a11.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Klik op de knop **X** in de rechterbovenhoek om het scherm te sluiten.

   ![](assets/seventeen.png)

1. Klik op de knop ![](assets/image2015-5-13-15-3a49-3a19-1.png) pictogram naast Instellingen en selecteer **Oplossingen**.

   ![](assets/eighteen.png)

1. Klik op de knop **Alle aanpassingen publiceren** knop.

   ![](assets/nineteen.png)

## Voordat u verdergaat met stap 3 {#before-proceeding-to-step}

* Als u het aantal records dat u synchroniseert wilt beperken, [een aangepast synchronisatiefilter instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) nu.
* Voer de [Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) proces. Hierbij wordt gecontroleerd of de eerste instellingen correct zijn uitgevoerd.
* Meld u aan bij Marketo Sync User in Microsoft Dynamics CRM.

   >[!MORELIKETHIS]
   >
   >[Stap 3 van 4: Verbind de Oplossing van Marketo met de Verbinding van het Wachtwoord van de Eigenaar van het Middel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md)
