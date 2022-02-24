---
unique-page-id: 10095429
description: Problemen met validatie synchroniseren van dynamiek verhelpen - Marketo Docs - productdocumentatie
title: Problemen met validatie synchroniseren van dynamiek verhelpen
exl-id: 1a300249-65b7-49b1-bf50-82236916298f
source-git-commit: 8d401eeba46dc1b21983ea03c8ecd823046a5479
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Problemen met validatie synchroniseren van dynamiek verhelpen {#fix-dynamics-validation-sync-issues}

## Resultaten van gereedschap Sync valideren {#validate-sync-tool-results}

Wanneer u de Dynamica in werking stelt bevestigt Synchronisatie, produceert het een rapport. Als er een ![x](assets/delete.png) naast een stap raadpleegt u de onderstaande opties om het probleem te identificeren en op te lossen. Voer vervolgens de validatiestappen opnieuw uit totdat het resultaat alleen groene vinkjes weergeeft.

![](assets/image2015-9-22-15-3a58-3a12.png)

## URL is geldig {#url-is-valid}

Als u een ![x](assets/delete.png) Controleer hier of de URL geldig is. Vind het hier in de Middelen van de Ontwikkelaar en bekijk de Dienst van de Organisatie. De URL kan om een aantal redenen ongeldig zijn.

1. Meld u aan bij Dynamics. Klik op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klik op Instellingen en selecteer **Aanpassingen**.

   ![](assets/two.png)

1. Klikken **Bronnen voor ontwikkelaars**.

   ![](assets/three.png)

1. De URL van de Dienst van de Organisatie kan onder de Eindpunten van de Dienst worden gevonden.

   ![](assets/four.png)

## Gebruikersnaam en wachtwoord zijn geldig {#username-and-password-are-valid}

Als u een ![x](assets/delete.png) Controleer hier of uw gebruikersnaam en wachtwoord voor Microsoft Dynamics geldig zijn.

## De gebruiker synchroniseren wordt toegewezen aan de Marketo Sync-gebruikersrol {#sync-user-is-assigned-to-the-marketo-sync-user-role}

Als u een ![x](assets/delete.png) het zou hier een van de drie onderstaande kwesties kunnen zijn .

**Optie één - controleer of de gebruikersrol van Marketo Sync is ingeschakeld in Microsoft Dynamics**:

1. Klik in Dynamics op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klikken **Instellingen** en selecteert u **Beveiliging**.

   ![](assets/six.png)

1. Klikken **Gebruikers.**

   ![](assets/image2015-9-24-9-3a47-3a25.png)

1. Klik op de koppeling voor de synchronisatiegebruiker.

   ![](assets/seven.png)

1. Klikken **Rollen beheren**.

   ![](assets/eight.png)

1. Controleer of de gebruikersrol Marketo Sync is ingeschakeld. Zo niet, controleer het en klik op **OK.**

   ![](assets/image2015-9-24-9-3a59-3a21.png)

**Optie twee - Toestemming voor subsidie bevestigen**:

1. Controleer de [Toestemming verlenen voor client-id en toepassingsregistratie](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md) om te bevestigen dat de app beheerderstoestemming heeft om API&#39;s aan te roepen.

**Optie drie - Gebruiker synchroniseren**:

1. Controleer of de synchronisatiegebruiker is toegevoegd aan Marketo Config.

## Marketo-oplossing is correct geïnstalleerd {#marketo-solution-is-properly-installed}

Als u een ![x](assets/delete.png) Ga hier naar Microsoft Dynamics om te controleren of de installatie van Marketo er is. Zie Stap 1 van de de opstellingsdocumentatie van de Dynamica van Microsoft.

1. Klik in Dynamics op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klikken **Instellingen** en selecteert u **Oplossingen.**

   ![](assets/eleven.png)

1. Controleer of de oplossing in de lijst staat.

   ![](assets/twelve.png)

## Alle stappen in de oplossing worden toegelaten {#all-steps-in-the-solution-are-enabled}

Als u een ![x](assets/delete.png) Controleer hier of geen van de standaardstappen is gedeactiveerd. Alle stappen worden automatisch ingeschakeld bij de installatie, maar kunnen tijdens een aanpassing worden gedeactiveerd.

## De synchronisatiegebruiker wordt toegewezen aan de Marketo-oplossing {#sync-user-is-assigned-to-the-marketo-solution}

Als u een ![x](assets/delete.png) Controleer hier of de synchronisatiegebruiker is toegewezen aan de standaardpagina Marketo in Microsoft Dynamics.

1. Klik in Dynamics op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klikken **Instellingen** en selecteert u **Marketo Config**.

   ![](assets/thirteen.png)

1. Controleer of de synchronisatiegebruiker als standaardwaarde is toegewezen.

   ![](assets/fourteen.png)

## Gebruikersnamen en wachtwoord synchroniseren {#sync-user-matches-username-and-password}

Als u een ![x](assets/delete.png) hier, ben zeker om de juiste synchronisatiegebruiker op het gebied van de Gebruiker van Marketo in Marketo toe te wijzen Config Standaard opstellingsstap in de Dynamica van Microsoft.

>[!MORELIKETHIS]
>
>[Microsoft Dynamics Sync valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)
