---
description: De ON24-integratie instellen met Marketo - Marketo Docs - Productdocumentatie
title: De ON24-integratie met Marketo instellen
exl-id: 395ffa37-b87d-4eb4-bf9f-72aa96dc819c
feature: Events
source-git-commit: e3f61755dccd9bea1378a429fc428b440fc3ecb4
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---

# De ON24-integratie met Marketo instellen{#set-up-the-on24-integration-with-marketo}

Hier is hoe te opstelling uw ON24 gebeurtenisintegratie.

## Een alleen-API rol maken {#create-an-api-only-role}

1. Van Mijn Marketo, klik **Admin**.

   ![](assets/set-up-the-on24-integration-with-marketo-1.png)

1. Onder Veiligheid, klik **Gebruikers &amp; Rollen**.

   ![](assets/set-up-the-on24-integration-with-marketo-2.png)

1. Klik het **lusje van Rollen** en dan **Nieuwe Rol**.

   ![](assets/set-up-the-on24-integration-with-marketo-3.png)

1. Voer een rolnaam in. Open het **API van de Toegang** menu en selecteer &quot;Gelezen-Schrijf het Voorwerp van de Douane&quot;en &quot;Gelezen-Schrijf Persoon.&quot; Klik **creëren**.

   ![](assets/set-up-the-on24-integration-with-marketo-4.png)

## Een nieuwe gebruiker maken {#create-a-new-user}

1. Nog in Gebruikers &amp; Rollen, klik het **Gebruikers** lusje en klik **nodigt Nieuwe Gebruiker** uit.

   ![](assets/set-up-the-on24-integration-with-marketo-5.png)

1. Ga de informatie van de nieuwe gebruiker in en klik **daarna**.

   ![](assets/set-up-the-on24-integration-with-marketo-6.png)

1. Selecteer de functie Alleen ON24-API die u zojuist hebt gemaakt. Selecteer **slechts API** checkbox. Klik **daarna**.

   ![](assets/set-up-the-on24-integration-with-marketo-7.png)

1. Klik **verzenden**.

   ![](assets/set-up-the-on24-integration-with-marketo-8.png)

>[!NOTE]
>
>Een uitnodiging is niet vereist voor alleen API-gebruikers.

## ON24-verbinding instellen {#set-up-on24-connection}

1. Nog in de Admin sectie, klik **LaunchPoint**.

   ![](assets/set-up-the-on24-integration-with-marketo-9.png)

1. Klik **Nieuw** toen **Nieuwe Dienst**.

   ![](assets/set-up-the-on24-integration-with-marketo-10.png)

1. Kies een weergavenaam. Klik de **drop-down Dienst** en selecteer **Douane**. Voer een beschrijving in. Klik de slechts drop-down Gebruiker van API en selecteer de gebruiker u [ in de stappen hierboven ](#create-a-new-user) creeerde. Klik **creëren**.

   ![](assets/set-up-the-on24-integration-with-marketo-11.png)

1. Zoek de aangepaste LaunchPoint-service die u net hebt gemaakt en klik op Details weergeven.

   ![](assets/set-up-the-on24-integration-with-marketo-12.png)

1. Markeer, klik met de rechtermuisknop, kopieer en sla de client-id op (u hebt deze later nodig). Herhaal deze bewerking voor clientgeheim.

   ![](assets/set-up-the-on24-integration-with-marketo-13.png)

1. In de boom op de linkerzijde, klik de Diensten van het Web.

   ![](assets/set-up-the-on24-integration-with-marketo-14.png)

1. Markeer onder &quot;REST API&quot; de markering, klik met de rechtermuisknop, kopieer en sla het eerste deel van de Identity op (tot de &#39;m&#39; op .com).

   ![](assets/set-up-the-on24-integration-with-marketo-15.png)

1. Navigeer met uw opgeslagen client-id, clientgeheim en identiteit naar uw ON24-account. De rest stappen worden daar uitgevoerd, en kunnen in de [ documentatie ON24 ](https://support.on24.com/hc/en-us/articles/21420762650523-Data-Integration-Setup-Instructions-When-Using-Marketo-Registration-Option-1){target="_blank"} worden gevonden.
