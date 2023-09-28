---
description: Instelling voor automatisch uit te schrijven berichten toevoegen - Marketo Docs - Productdocumentatie
title: Instelling voor automatisch toevoegen van abonnement op bericht
hide: true
hidefromtoc: true
feature: Marketo Sales Connect
exl-id: 2d4c96b3-6d27-46e9-abb0-2571f3e03611
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 0%

---

# Instelling voor automatisch toevoegen van abonnement op bericht {#auto-append-unsubscribe-message-setting}

Zorg ervoor dat elk verzonden e-mailbericht een afmeldingsbericht bevat, zodat ontvangers de mogelijkheid hebben om zich af te melden. Wanneer het toevoegen van het afmeldingsbericht wordt toegelaten, zal al mededeling uw team van de Verkoop van Marketo een afmeldingsbericht, met inbegrip van e-mail die van de Webtoepassing, Salesforce, de Gmail- stop, en de stop van Vooruitzichten verzendt omvatten.

## Notities {#things-to-note}

* Voor e-mailberichten die vanuit de plug-ins worden verzonden, wordt het abonnement alleen opgezegd wanneer een sjabloon wordt gebruikt.

* Als u het `{{team_unsubscribe}}` dynamisch veld in een e-mailsjabloon en de instelling voor het toevoegen van een bericht voor afmelden is ingeschakeld. Het dynamische veld voor het afmelden van een abonnement vult het afmeldingsbericht in _in plaats van_ je afmeldingsbericht toevoegen.

## Toevoegen via abonnement in-/uitschakelen {#enable-disable-unsubscribe-append}

1. Klik op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/auto-append-unsubscribe-message-setting-1.png)

1. Klik onder Beheerinstellingen op **Abonnementen opzeggen**.

   ![](assets/auto-append-unsubscribe-message-setting-2.png)

1. Verplaats de schuifregelaar op het tabblad Berichten onder Bericht bij opzeggen toevoegen naar de gewenste status.

   ![](assets/auto-append-unsubscribe-message-setting-3.png)

>[!TIP]
>
>Als u het toevoegen onbruikbaar maakt unsubscribe bericht plaatsen, adviseren wij toevoegend een unsubscribe footer aan uw malplaatjes om ervoor te zorgen uw mededeling een opt-out optie heeft. U kunt dit doen door uw eigen douanebericht aan elke malplaatje toe te voegen, of door te gebruiken `{{team_unsubscribe}}` [dynamisch veld](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/dynamic-fields-glossary.md){target="_blank"}.
