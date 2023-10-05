---
description: Transactionele e-mailsjablonen voor verkoop - Marketo Docs - Productdocumentatie
title: E-mailsjablonen voor transactieverkoop
feature: Sales Insight Actions
exl-id: 0178155e-f01c-449f-b510-40adf718e177
source-git-commit: 7c8703059d7d28afbf57f4f285ac972fb9d8fbef
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# E-mailsjablonen voor transactieverkoop {#transactional-sales-email-templates}

Als uw team transactie- of niet-commerciële e-mailberichten verzendt, kunt u een e-mailsjabloon markeren als niet-commercieel, zodat het afmelden kan omzeilen.

## Notities {#things-to-note}

* Niet-commerciële e-mails gaan voorbij aan abonnementen op verkopen en [Afmeldingscontrole Marketo Engage](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/marketo-unsubscribe-check.md){target="_blank"}, but will not bypass [blocked domains](/help/marketo/product-docs/marketo-sales-insight/actions/admin/blocked-domains.md){target="_blank"}.

* Abonnementsberichten worden niet automatisch toegevoegd aan niet-commerciële e-mails, zelfs niet als de [toevoegen, instelling voor afmelden van berichtbeheer](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/auto-append-unsubscribe-message-setting.md){target="_blank"} is enabled. However, the `{{team_unsubscribe}}` [dynamic field](/help/marketo/product-docs/marketo-sales-insight/actions/templates/dynamic-fields.md){target="_blank"} zal uw team nog bevolken unsubscribe bericht.

## Een e-mailsjabloon configureren voor niet-commercieel gebruik {#configure-an-email-template-for-non-commercial-use}

1. Klik in de kop op **Sjablonen**.

   ![](assets/transactional-sales-email-templates-1.png)

1. Zoek en selecteer de sjabloon die u wilt bijwerken.

   ![](assets/transactional-sales-email-templates-2.png)

1. Schakel de niet-commerciële e-mailschakeloptie in onder Sjablooninstellingen.

   ![](assets/transactional-sales-email-templates-3.png)

## Een niet-commerciële e-mail verzenden {#send-a-non-commercial-email}

>[!NOTE]
>
>Wanneer een persoon die zich niet heeft geabonneerd is geselecteerd, worden deze oranje gemarkeerd.

1. Klik in de kop op **Samenstellen**. Zoek en selecteer de gewenste niet-commerciële sjabloon.

   ![](assets/transactional-sales-email-templates-4.png)

1. Gebruikers zien een banner waarop ze een niet-commerciële e-mailsjabloon kunnen selecteren.

   ![](assets/transactional-sales-email-templates-5.png)

1. Klikken **Verzenden**.

   ![](assets/transactional-sales-email-templates-6.png)

Het e-mailbericht wordt ook verzonden als de persoon het abonnement heeft opgezegd.
