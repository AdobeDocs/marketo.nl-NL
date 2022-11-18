---
description: De ON24-integratie instellen met Marketo - Marketo Docs - Productdocumentatie
title: De ON24-integratie met Marketo instellen
exl-id: 395ffa37-b87d-4eb4-bf9f-72aa96dc819c
source-git-commit: 3e0823976e8b837fcb2fdbbf03f26da48cbd74b7
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# De ON24-integratie met Marketo instellen{#set-up-the-on24-integration-with-marketo}

Hier is hoe te opstelling uw ON24 gebeurtenisintegratie.

## Een alleen-API rol maken {#create-an-api-only-role}

1. Klik in Mijn Marketo op **Beheer**.

   ![](assets/set-up-the-on24-integration-with-marketo-1.png)

1. Klik onder Beveiliging op **Gebruikers en rollen**.

   ![](assets/set-up-the-on24-integration-with-marketo-2.png)

1. Klik op de knop **Rollen** en vervolgens **Nieuwe rol**.

   ![](assets/set-up-the-on24-integration-with-marketo-3.png)

1. Voer een rolnaam in. Open de **API voor toegang** en selecteert u &quot;Read-Write Custom Object&quot; en &quot;Read-Write Person.&quot; Klikken **Maken**.

   ![](assets/set-up-the-on24-integration-with-marketo-4.png)

## Een nieuwe gebruiker maken {#create-a-new-user}

1. Blijf in Gebruikers &amp; Rollen, klik **Gebruikers** en klik op **Nieuwe gebruiker uitnodigen**.

   ![](assets/set-up-the-on24-integration-with-marketo-5.png)

1. Voer de gegevens van de nieuwe gebruiker in en klik op **Volgende**.

   ![](assets/set-up-the-on24-integration-with-marketo-6.png)

1. Selecteer de functie Alleen ON24-API die u zojuist hebt gemaakt. Selecteer **Alleen API** selectievakje. Klikken **Volgende**.

   ![](assets/set-up-the-on24-integration-with-marketo-7.png)

1. Klikken **Verzenden**.

   ![](assets/set-up-the-on24-integration-with-marketo-8.png)

>[!NOTE]
>
>Een uitnodiging is niet vereist voor alleen API-gebruikers.

## ON24-verbinding instellen {#set-up-on24-connection}

1. Blijf in de sectie Admin en klik op **LaunchPoint**.

   ![](assets/set-up-the-on24-integration-with-marketo-9.png)

1. Klikken **Nieuw** dan **Nieuwe service**.

   ![](assets/set-up-the-on24-integration-with-marketo-10.png)

1. Kies een weergavenaam. Klik op de knop **Service** vervolgkeuzelijst en selecteer **Aangepast**. Voer een beschrijving in. Klik op de vervolgkeuzelijst Alleen API-gebruiker en selecteer de gebruiker die u hebt gemaakt [in de bovenstaande stappen](#create-a-new-user). Klikken **Maken**.

   ![](assets/set-up-the-on24-integration-with-marketo-11.png)

1. Zoek de aangepaste LaunchPoint-service die u net hebt gemaakt en klik op Details weergeven.

   ![](assets/set-up-the-on24-integration-with-marketo-12.png)

1. Markeer, klik met de rechtermuisknop, kopieer en sla de client-id op (u hebt deze later nodig). Herhaal deze bewerking voor clientgeheim.

   ![](assets/set-up-the-on24-integration-with-marketo-13.png)

1. In de boom op de linkerzijde, klik de Diensten van het Web.

   ![](assets/set-up-the-on24-integration-with-marketo-14.png)

1. Markeer onder &quot;REST API&quot; de markering, klik met de rechtermuisknop, kopieer en sla het eerste deel van de Identity op (tot de &#39;m&#39; op .com).

   ![](assets/set-up-the-on24-integration-with-marketo-15.png)

1. Navigeer met uw opgeslagen client-id, clientgeheim en identiteit naar uw ON24-account. De overige stappen worden daar uitgevoerd en zijn [hier beschreven](https://on24support.force.com/Support/s/article/Connect-Marketo-ON24-Connect-Data-Integration#Step6){target=&quot;_blank&quot;}.
