---
description: Transactionele e-mailsjablonen voor verkoop - Marketo Docs - Productdocumentatie
title: E-mailsjablonen voor transactieverkoop
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 0%

---

# E-mailsjablonen voor transactieverkoop {#transactional-sales-email-templates}

Als uw team transactie- of niet-commerciële e-mailberichten verzendt, kunt u een e-mailsjabloon markeren als niet-commercieel, zodat het afmelden kan omzeilen.

## Notities {#things-to-note}

* De niet-commerciële e-mail zal verkoop wegvallen unsubscribes en [&#x200B; Marketo Engage unsubscribe controle &#x200B;](/help/marketo/product-docs/marketo-sales-connect/email/unsubscribes/marketo-unsubscribe-check.md){target="_blank"}, maar zal [&#x200B; geblokkeerde domeinen &#x200B;](/help/marketo/product-docs/marketo-sales-connect/admin/blocked-domains.md){target="_blank"} niet omzeilen.

* Unsubscribe berichten zullen niet automatisch aan niet-commerciële e-mails worden toegevoegd, zelfs als [&#x200B; toevoegt unsubscribe bericht admin die &#x200B;](/help/marketo/product-docs/marketo-sales-connect/email/unsubscribes/auto-append-unsubscribe-message-setting.md){target="_blank"} plaatst wordt toegelaten. Nochtans, zal het `{{team_unsubscribe}}` [&#x200B; dynamische gebied &#x200B;](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/dynamic-fields-glossary.md){target="_blank"} nog uw team bevolken unsubscribe bericht.

## Een e-mailsjabloon configureren voor niet-commercieel gebruik {#configure-an-email-template-for-non-commercial-use}

1. In de kopbal, klik **Malplaatjes**.

   ![](assets/transactional-sales-email-templates-1.png)

1. Zoek en selecteer de sjabloon die u wilt bijwerken.

   ![](assets/transactional-sales-email-templates-2.png)

1. Schakel de niet-commerciële e-mailschakeloptie in onder Sjablooninstellingen.

   ![](assets/transactional-sales-email-templates-3.png)

## Een niet-commerciële e-mail verzenden {#send-a-non-commercial-email}

>[!NOTE]
>
>Wanneer een persoon die zich niet heeft geabonneerd is geselecteerd, worden deze oranje gemarkeerd.

1. In de kopbal, stelt de klik **samen**. Zoek en selecteer de gewenste niet-commerciële sjabloon.

   ![](assets/transactional-sales-email-templates-4.png)

1. Gebruikers zien een banner waarop ze een niet-commerciële e-mailsjabloon kunnen selecteren.

   ![](assets/transactional-sales-email-templates-5.png)

1. Klik **verzenden**.

   ![](assets/transactional-sales-email-templates-6.png)

Het e-mailbericht wordt ook verzonden als de persoon het abonnement heeft opgezegd.
