---
unique-page-id: 12981050
description: Verkoopsjabloon vergrendelen - Marketo Docs - Productdocumentatie
title: Verkoopsjabloon vergrendelen
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---


# Verkoopsjabloon vergrendelen {#lock-sales-template}

Om de gebruikers van CRM te verhinderen verkoopmalplaatjes uit te geven, kunnen de beheerders de capaciteit toelaten om malplaatjes te sluiten, die dan gebruikers toestaan om malplaatjes individueel van de e-mailredacteur te sluiten.

>[!CAUTION]
>
>Deze eigenschap werkt slechts voor Salesforce en is niet compatibel met de Dynamica van Microsoft of andere CRMs. De malplaatjes die van Vooruitzichten of Gmail stop-ins worden betreden zullen niet worden gesloten, aangezien de redacteur niet door Marketo wordt gecontroleerd.

## Sjabloon vergrendelen inschakelen {#enable-lock-template}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar **Admin** en klik vervolgens op **Verkoopoverzicht**.

   ![](assets/1.png)

1. Klik onder **Instellingen** op **Bewerken**.

   ![](assets/2.png)

1. Schakel de optie **Sjablonen** vergrendelen in. Klik op **Opslaan**.

   ![](assets/image2017-10-9-8-3a19-3a45.png)

>[!NOTE]
>
>Dit selectievakje is standaard ingeschakeld en de mogelijkheid sjablonen te vergrendelen is ingeschakeld. Als u de optie uitschakelt, wordt de functie voor vergrendelingssjablonen in de e-maileditor uitgeschakeld.

>[!NOTE]
>
>Het wijzigen van deze instelling als beheerder heeft **geen** terugwerkende kracht op bestaande sjablonen; Dit betekent dat ze niet automatisch worden vergrendeld.

## Sjabloon vergrendelen in de e-maileditor {#lock-template-in-the-email-editor}

1. Selecteer het e-mailbericht dat u wilt vergrendelen en klik op Concept **** bewerken.

   ![](assets/5.png)

1. Klik in de e-maileditor op **E-mailinstellingen**.

   ![](assets/6.png)

1. Schakel **Publiceren naar Verkoopoverzicht** als dit nog niet is gecontroleerd. U kunt nu de optie **CRM-gebruiker toestaan om e-mail** te bewerken uitschakelen om de sjabloon te vergrendelen. Klik op **Opslaan**.

   ![](assets/7.png)

   >[!NOTE]
   >
   >Dit selectievakje is standaard ingeschakeld en CRM-gebruikers mogen e-mailberichten bewerken.

