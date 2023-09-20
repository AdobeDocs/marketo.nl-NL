---
description: Transactionele e-mailsjablonen voor verkoop - Marketo Docs - Productdocumentatie
title: E-mailsjablonen voor transactieverkoop
hide: true
hidefromtoc: true
feature: Marketo Sales Connect
source-git-commit: d6a3d95ed42d1c08d69014e1aa013e7436bd06c2
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 0%

---

# E-mailsjablonen voor transactieverkoop {#transactional-sales-email-templates}

Als uw team transactie- of niet-commerciële e-mailberichten verzendt, kunt u een e-mailsjabloon markeren als niet-commercieel, zodat het afmelden kan omzeilen.

## Notities {#things-to-note}

* Niet-commerciële e-mails gaan voorbij aan abonnementen op verkopen en [Afmeldingscontrole Marketo Engage](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/marketo-unsubscribe-check.md){target="_blank"}, but will not bypass [blocked domains](/help/marketo/product-docs/marketo-sales-insight/actions/admin/blocked-domains.md){target="_blank"}.

* Abonnementsberichten worden niet automatisch toegevoegd aan niet-commerciële e-mails, zelfs niet als de [toevoegen, instelling voor afmelden van berichtbeheer](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/auto-append-unsubscribe-message-setting.md){target="_blank"} is enabled. However, the `{{team_unsubscribe}}` [dynamic field](/help/marketo/product-docs/marketo-sales-insight/actions/templates/dynamic-fields.md){target="_blank"} zal uw team nog bevolken unsubscribe bericht.

## Een e-mailsjabloon configureren voor niet-commercieel gebruik {#configure-an-email-template-for-non-commercial-use}

1. Klik in de kop op **Sjablonen**.

PICC

1. Zoek naar het malplaatje u wilt bijwerken.

PICC

1. Selecteer de sjabloon.

PICC

1. Schakel de niet-commerciële e-mailschakeloptie in onder Sjablooninstellingen.

PICC

## Een niet-commerciële e-mail verzenden {#send-a-non-commercial-email}

Wanneer een persoon die zich niet heeft geabonneerd is geselecteerd, worden deze oranje gemarkeerd.

1. Selecteer in het samenstellingsvenster de niet-commerciële sjabloon die u wilt zien.

PICC

1. Gebruikers zien een banner die hen laat zien dat zij momenteel een niet-commerciële e-mailsjabloon hebben geselecteerd.

PICC

1. Klikken **Verzenden**.

PICC

Het e-mailbericht wordt ook verzonden als de persoon het abonnement heeft opgezegd.
