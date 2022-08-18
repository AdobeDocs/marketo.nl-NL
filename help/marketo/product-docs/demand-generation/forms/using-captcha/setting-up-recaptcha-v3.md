---
description: reCAPTCHA v3 - Marketo Docs - Productdocumentatie instellen
title: reCAPTCHA v3 instellen
hide: true
hidefromtoc: true
exl-id: 235a2688-59a8-4827-a929-a07f3ae06988
source-git-commit: 24942664d613fa2851bad7a0dd3862027deacf37
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# reCAPTCHA v3 instellen {#setting-up-recaptcha-v3}

Intro-tekst

## Oorspronkelijke reCAPTCHA v3-instelling {#initial-recaptcha-v3-setup}

Tekst: Beschrijf v3 - de volgende stappen worden uitgevoerd buiten Marketo Engage.

1. Ga naar [https://www.google.com/recaptcha/about/](https://www.google.com/recaptcha/about/){target=&quot;_blank&quot;} en klik op v3-Admin Console.

1. Meld u aan bij of meld u aan bij een Google-account.

1. Klik op de knop Maken (+) om een nieuwe toets te maken.

1. Maak een label om de sleutel aan te duiden die moet worden gebruikt voor Marketo Engage.

1. Tekst kiezen **reCAPTCHA v3**. Marketo Engage biedt momenteel geen ondersteuning voor reCAPTCHA v2.

1. Voeg elk domein toe het Marketo Engage abonnement gebruikt. Domeinen die hier niet zijn ingesteld, retourneren fouten op formulieren waarvoor reCAPTCHA is ingeschakeld.

   * 123-ABC-456.mktoweb.com
   * app-pod.marketo.com
   * elk domein en alias van de landingspagina dat in het abonnement is geconfigureerd

1. Stel een eigenaar in en voeg een e-mailadres toe waar waarschuwingen over deze service moeten worden ontvangen.

1. Accepteer de Servicevoorwaarden van reCAPTCHA.

1. Klikken **Verzenden**.

>[!NOTE]
>
>Houd de plaatssleutel en geheime sleutel handig voor de configuratie van Marketo Engage.

## CAPTCHA instellen in Marketo Engage {#setting-up-captcha-in-marketo-engage}

1. Klik in Marketo op **Beheer**.

   ![](assets/setting-up-recaptcha-v3-1.png)

1. Selecteren **CAPTCHA** in de boom.

   ![](assets/setting-up-recaptcha-v3-2.png)

1. Klikken **Bewerken** op CAPTCHA-instellingen.

   ![](assets/setting-up-recaptcha-v3-3.png)

1. Klik op de vervolgkeuzelijst CAPTCHA en kies reCAPTCHA v3.

   ![](assets/setting-up-recaptcha-v3-4.png)

1. Voeg de Geheime sleutel en Sitesleutel in. Klikken **Opslaan** wanneer gereed.

   ![](assets/setting-up-recaptcha-v3-5.png)
