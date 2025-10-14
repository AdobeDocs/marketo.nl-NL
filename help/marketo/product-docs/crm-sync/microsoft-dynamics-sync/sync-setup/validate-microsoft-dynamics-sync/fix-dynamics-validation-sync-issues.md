---
unique-page-id: 10095429
description: Problemen met validatie synchroniseren van dynamiek verhelpen - Marketo Docs - productdocumentatie
title: Problemen met validatie synchroniseren van dynamiek verhelpen
exl-id: 1a300249-65b7-49b1-bf50-82236916298f
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '487'
ht-degree: 0%

---

# Problemen met validatie synchroniseren van dynamiek verhelpen {#fix-dynamics-validation-sync-issues}

## Resultaten van gereedschap Sync valideren {#validate-sync-tool-results}

Wanneer u de Dynamica in werking stelt bevestigt Synchronisatie, produceert het een rapport. Als er een ![&#x200B; x &#x200B;](assets/delete.png) naast een stap is, zie de opties hieronder om het probleem te identificeren en te bevestigen. Voer vervolgens de validatiestappen opnieuw uit totdat het resultaat alleen groene vinkjes weergeeft.

![](assets/image2015-9-22-15-3a58-3a12.png)

## URL is geldig {#url-is-valid}

Als u een ![&#x200B; x &#x200B;](assets/delete.png) hier hebt, verifieer dat URL geldig is. Vind het hier in de Middelen van de Ontwikkelaar en bekijk de Dienst van de Organisatie. De URL kan om een aantal redenen ongeldig zijn.

1. Meld u aan bij Dynamics. Klik het pictogram van Montages en selecteer **Geavanceerde Montages**.

   ![](assets/one.png)

1. Klik Montages en selecteer **Aanpassingen**.

   ![](assets/two.png)

1. Klik {de Middelen van de Ontwikkelaar 0} **.**

   ![](assets/three.png)

1. De URL van de Dienst van de Organisatie kan onder de Eindpunten van de Dienst worden gevonden.

   ![](assets/four.png)

## Gebruikersnaam en wachtwoord zijn geldig {#username-and-password-are-valid}

Als u een ![&#x200B; x &#x200B;](assets/delete.png) hier hebt, verifieer dat uw geloofsbrieven van Microsoft Dynamics geldig zijn. Voor de authentificatie van S2S van het Web API, moet de gebruikersbenaming in Marketo het [&#x200B; e-mailadres &#x200B;](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user) van de Gebruiker van de Toepassing in CRM aanpassen. Voor andere typen moet deze overeenkomen met de gebruikersnaam voor de synchronisatiegebruiker.

## De gebruiker synchroniseren wordt toegewezen aan de Marketo Sync-gebruikersrol {#sync-user-is-assigned-to-the-marketo-sync-user-role}

Als u een ![&#x200B; x &#x200B;](assets/delete.png) hier hebt, zou het één van de drie hieronder kwesties kunnen zijn.

**Optie één - verifieer dat de Rol van de Gebruiker van de Synchronisatie van Marketo in Microsoft Dynamics** wordt gecontroleerd:

1. In Dynamiek, klik het pictogram van Montages en selecteer **Geavanceerde Montages**.

   ![](assets/one.png)

1. Klik **Montages** en selecteer **Veiligheid**.

   ![](assets/six.png)

1. Klik **Gebruikers.**

   ![](assets/image2015-9-24-9-3a47-3a25.png)

1. Klik op de koppeling voor de synchronisatiegebruiker.

   ![](assets/seven.png)

1. Klik **leiden Rollen**.

   ![](assets/eight.png)

1. Controleer of de gebruikersrol Marketo Sync is ingeschakeld. Als niet, controleer het en klik **OK.**

   ![](assets/image2015-9-24-9-3a59-3a21.png)

**Optie Twee - bevestig Toestemming van de Verlening**:

1. Herzie de [&#x200B; Toestemming van de Verlening voor Identiteitskaart van de Cliënt en Registratie van de Toepassing &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md) om app te bevestigen heeft admin toestemming om APIs te roepen.

**Optie Drie - de Gebruiker van de Synchronisatie**:

1. Controleer of de synchronisatiegebruiker is toegevoegd aan Marketo Config.

## Marketo-oplossing is correct geïnstalleerd {#marketo-solution-is-properly-installed}

Als u een ![&#x200B; x &#x200B;](assets/delete.png) hier hebt, ga naar Microsoft Dynamics om te verifiëren de installatie van Marketo daar is. Zie Stap 1 van de Microsoft Dynamics-installatiedocumentatie.

1. In Dynamiek, klik het pictogram van Montages en selecteer **Geavanceerde Montages**.

   ![](assets/one.png)

1. Klik **Montages** en selecteer **Oplossingen.**

   ![](assets/eleven.png)

1. Controleer of de oplossing in de lijst staat.

   ![](assets/twelve.png)

## Alle stappen in de oplossing worden toegelaten {#all-steps-in-the-solution-are-enabled}

Als u een ![&#x200B; x &#x200B;](assets/delete.png) hier hebt, verifieer dat geen van de standaardstappen zijn gedeactiveerd. Alle stappen worden automatisch ingeschakeld bij de installatie, maar kunnen tijdens een aanpassing worden gedeactiveerd.

## De synchronisatiegebruiker wordt toegewezen aan de Marketo-oplossing {#sync-user-is-assigned-to-the-marketo-solution}

Als u een ![&#x200B; x &#x200B;](assets/delete.png) hier hebt, zorg ervoor de gebruiker van de Synchronisatie op de Standaard pagina van Marketo in Microsoft Dynamics wordt toegewezen.

1. In Dynamiek, klik het pictogram van Montages en selecteer **Geavanceerde Montages**.

   ![](assets/one.png)

1. Klik **Montages** en selecteer **Marketo Config**.

   ![](assets/thirteen.png)

1. Controleer of de synchronisatiegebruiker als standaardwaarde is toegewezen.

   ![](assets/fourteen.png)

## Gebruikersnamen en wachtwoord synchroniseren {#sync-user-matches-username-and-password}

Als u een ![&#x200B; x &#x200B;](assets/delete.png) hier hebt, ben zeker om de juiste synchronisatiegebruiker op het gebied van de Gebruiker van Marketo in de Standaard de opstellingsstap van Marketo Config in Microsoft Dynamics toe te wijzen.

>[!MORELIKETHIS]
>
>[&#x200B; bevestigt de Synchronisatie van Microsoft Dynamics &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)
