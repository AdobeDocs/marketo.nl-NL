---
unique-page-id: 10095429
description: Problemen met validatie synchroniseren van dynamiek verhelpen - Marketo Docs - productdocumentatie
title: Problemen met validatie synchroniseren van dynamiek verhelpen
exl-id: 1a300249-65b7-49b1-bf50-82236916298f
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---

# Problemen met synchronisatie bij validatie van dynamiek oplossen {#fix-dynamics-validation-sync-issues}

## Resultaten van het gereedschap Sync valideren {#validate-sync-tool-results}

Wanneer u de Dynamica in werking stelt bevestigt Synchronisatie, produceert het dit rapport. Als er naast een stap een ![delete](assets/delete.png) is, zie hieronder om het probleem te identificeren en te bevestigen. Voer vervolgens de validatiestappen opnieuw uit totdat het resultaat alleen maar vinkjes weergeeft.

![](assets/image2015-9-22-15-3a58-3a12.png)

## URL is geldig {#url-is-valid}

Als u ![delete](assets/delete.png) hier hebt, verifieer dat URL geldig is. Vind het hier in de Middelen van de Ontwikkelaar en bekijk de Dienst van de Organisatie. De URL kan om een aantal redenen ongeldig zijn.

1. Meld u aan bij Dynamics. Klik op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klik op Instellingen en selecteer **Aanpassingen**.

   ![](assets/two.png)

1. Klik **Developer Resources**.

   ![](assets/three.png)

1. De URL van de Dienst van de Organisatie kan onder de Eindpunten van de Dienst worden gevonden.

   ![](assets/four.png)

## Gebruikersnaam en wachtwoord zijn geldig {#username-and-password-are-valid}

Als u ![—](assets/delete.png) hier hebt, verifieer dat uw gebruikersbenaming en wachtwoord van de Dynamiek van Microsoft geldig zijn.

## De gebruiker synchroniseren wordt toegewezen aan de Marketo Sync-gebruikersrol {#sync-user-is-assigned-to-the-marketo-sync-user-role}

Als u ![—](assets/delete.png) hier hebt, moet u verifiëren dat de rol van de Gebruiker van de Synchronisatie van Marketo in de Dynamiek van Microsoft wordt gecontroleerd. Zie Stap 2 van de de installatiedocumentatie van de Dynamica van Microsoft.

1. Klik in Dynamiek op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klik **Instellingen** en selecteer **Beveiliging**.

   ![](assets/six.png)

1. Klik **Gebruikers.**

   ![](assets/image2015-9-24-9-3a47-3a25.png)

1. Klik op de koppeling voor de synchronisatiegebruiker.

   ![](assets/seven.png)

1. Klik **Rollen beheren**.

   ![](assets/eight.png)

1. Controleer of de gebruikersrol Marketo Sync is ingeschakeld. Als niet, controleer het en klik **OK.**

   ![](assets/image2015-9-24-9-3a59-3a21.png)

## Marketo-oplossing is op de juiste wijze geïnstalleerd {#marketo-solution-is-properly-installed}

Als u ![—](assets/delete.png) hier hebt, ga naar de Dynamica van Microsoft om te verifiëren de installatie van Marketo daar is. Zie Stap 1 van de de opstellingsdocumentatie van de Dynamica van Microsoft.

1. Klik in Dynamiek op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klik **Instellingen** en selecteer **Oplossingen.**

   ![](assets/eleven.png)

1. Controleer of de oplossing in de lijst staat.

   ![](assets/twelve.png)

## Alle stappen in de oplossing zijn ingeschakeld {#all-steps-in-the-solution-are-enabled}

Als u ![—](assets/delete.png) hier hebt, verifieer dat geen van de standaardstappen zijn gedeactiveerd. Alle stappen worden automatisch ingeschakeld bij de installatie, maar kunnen tijdens een aanpassing worden gedeactiveerd.

## De synchronisatiegebruiker wordt toegewezen aan de Marketo-oplossing {#sync-user-is-assigned-to-the-marketo-solution}

Als u ![—](assets/delete.png) hier hebt, zorg ervoor de gebruiker van de Synchronisatie op de Standaard pagina van Marketo in de Dynamiek van Microsoft wordt toegewezen.

1. Klik in Dynamiek op het pictogram Instellingen en selecteer **Geavanceerde instellingen**.

   ![](assets/one.png)

1. Klik **Instellingen** en selecteer **Marketo Config**.

   ![](assets/thirteen.png)

1. Controleer of de synchronisatiegebruiker als standaardwaarde is toegewezen.

   ![](assets/fourteen.png)

## Gebruikersnamen en wachtwoorden synchroniseren {#sync-user-matches-username-and-password}

Als u een ![—](assets/delete.png) hier hebt, ben zeker om de juiste synchronisatiegebruiker op het gebied van de Gebruiker van Marketo in de Standaard de opstellingsstap van de Configuratie van Marketo in de Dynamiek van Microsoft toe te wijzen.

>[!MORELIKETHIS]
>
>[Synchronisatie van Microsoft-dynamiek valideren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)
