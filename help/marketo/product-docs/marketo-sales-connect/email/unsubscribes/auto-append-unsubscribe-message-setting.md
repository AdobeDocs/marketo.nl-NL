---
description: Instelling voor automatisch uit te schrijven berichten toevoegen - Marketo Docs - Productdocumentatie
title: Instelling voor automatisch toevoegen van abonnement op bericht
feature: Marketo Sales Connect
exl-id: 8aa75123-f6b5-4dfe-8fa7-f764620c04e8
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 0%

---

# Instelling voor automatisch toevoegen van abonnement op bericht {#auto-append-unsubscribe-message-setting}

Zorg ervoor dat elk verzonden e-mailbericht een afmeldingsbericht bevat, zodat ontvangers de mogelijkheid hebben om zich af te melden. Wanneer het toevoegen van het afmeldingsbericht wordt toegelaten, zal al mededeling uw team van de Verkoop van Marketo een afmeldingsbericht, met inbegrip van e-mail die van de Webtoepassing, Salesforce, de Gmail- stop, en de stop van Vooruitzichten verzendt omvatten.

## Notities {#things-to-note}

* Voor e-mailberichten die vanuit de plug-ins worden verzonden, wordt het abonnement alleen opgezegd wanneer een sjabloon wordt gebruikt.

* Als u het `{{team_unsubscribe}}` dynamische gebied in een e-mailmalplaatje gebruikt en unsubscribe bericht toevoegt wordt het plaatsen toegelaten, zal het team unsubscribe dynamische gebied uw unsubscribe bericht _in plaats van_ het toevoegen van uw unsubscribe bericht bevolken.

## Toevoegen via abonnement in-/uitschakelen {#enable-disable-unsubscribe-append}

1. Klik het tandwielpictogram en selecteer **Montages**.

   ![](assets/auto-append-unsubscribe-message-setting-1.png)

1. Onder Montages Admin, klik **Unsubscribes**.

   ![](assets/auto-append-unsubscribe-message-setting-2.png)

1. Verplaats de schuifregelaar op het tabblad Berichten onder Bericht bij opzeggen toevoegen naar de gewenste status.

   ![](assets/auto-append-unsubscribe-message-setting-3.png)

>[!TIP]
>
>Als u het toevoegen onbruikbaar maakt unsubscribe bericht plaatsen, adviseren wij toevoegend een unsubscribe footer aan uw malplaatjes om ervoor te zorgen uw mededeling een opt-out optie heeft. U kunt dit doen door uw eigen douanebericht aan elk malplaatje toe te voegen, of door het `{{team_unsubscribe}}` [ dynamische gebied ](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/dynamic-fields-glossary.md){target="_blank"} te gebruiken.
