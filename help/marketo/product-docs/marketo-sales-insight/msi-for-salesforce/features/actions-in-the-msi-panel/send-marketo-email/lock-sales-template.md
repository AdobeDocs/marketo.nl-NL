---
unique-page-id: 12981050
description: Verkoopsjabloon vergrendelen - Marketo-documenten - productdocumentatie
title: Verkoopsjabloon vergrendelen
exl-id: 005dde5d-ed60-444b-b7a3-b91be72a0151
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---

# Verkoopsjabloon vergrendelen {#lock-sales-template}

Om de gebruikers van CRM te verhinderen verkoopmalplaatjes uit te geven, kunnen de beheerders de capaciteit toelaten om malplaatjes te sluiten, die dan gebruikers toestaan om malplaatjes individueel van de e-mailredacteur te sluiten.

>[!CAUTION]
>
>Deze functie werkt alleen voor Salesforce en is niet compatibel met Microsoft Dynamics of andere CRM&#39;s. Sjablonen die worden geopend via de plug-ins Outlook of Gmail worden niet vergrendeld omdat de editor niet wordt beheerd door Marketo.

## Sjabloon vergrendelen inschakelen {#enable-lock-template}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar **Beheer** en klik vervolgens op **Verkoopoverzicht**.

   ![](assets/1.png)

1. Onder **Instellingen**, klikt u op **Bewerken**.

   ![](assets/2.png)

1. Controleren **Sjablonen vergrendelen**. Klikken **Opslaan**.

   ![](assets/image2017-10-9-8-3a19-3a45.png)

>[!NOTE]
>
>Dit selectievakje is standaard ingeschakeld en de mogelijkheid sjablonen te vergrendelen is ingeschakeld. Als u de optie uitschakelt, wordt de functie voor vergrendelingssjablonen in de e-maileditor uitgeschakeld.

>[!NOTE]
>
>Als u deze instelling als beheerder wijzigt, wordt **niet** met terugwerkende kracht van invloed zijn op bestaande templates; Dit betekent dat ze niet automatisch worden vergrendeld.

## Sjabloon vergrendelen in de e-maileditor {#lock-template-in-the-email-editor}

1. Selecteer het e-mailbericht dat u wilt vergrendelen en klik op **Concept bewerken**.

   ![](assets/5.png)

1. Klik in de e-maileditor op **E-mailinstellingen**.

   ![](assets/6.png)

1. Controleren **Publiceren naar Marketo Sales Insight** als het nog niet gecontroleerd is. U kunt nu de controle ongedaan maken **CRM-gebruiker toestaan om e-mail te bewerken** om de sjabloon te vergrendelen. Klikken **Opslaan**.

   ![](assets/7.png)

   >[!NOTE]
   >
   >Dit selectievakje is standaard ingeschakeld en CRM-gebruikers mogen e-mailberichten bewerken.
