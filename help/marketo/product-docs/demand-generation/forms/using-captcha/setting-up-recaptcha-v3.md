---
description: reCAPTCHA v3 - Marketo Docs - Productdocumentatie instellen
title: reCAPTCHA v3 instellen
hide: true
hidefromtoc: true
exl-id: 235a2688-59a8-4827-a929-a07f3ae06988
source-git-commit: cc66f4ff2e3e0e6ddfabab91215e3ad31f3b9226
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 0%

---

# reCAPTCHA v3 instellen {#setting-up-recaptcha-v3}

ReCAPTCHA v3 is een frictioneloze ervaring die formulierverzendingen scoort op basis van hoe verdacht ze zijn zonder tekst, afbeeldingen of knopuitdagingen te gebruiken. [Meer informatie](https://developers.google.com/search/blog/2018/10/introducing-recaptcha-v3-new-way-to){target=&quot;_blank&quot;}.

## Uw datacenter- en Munchkin-id ophalen {#retrieve-your-data-center-and-munchkin-id}

Voor Stap 6 in de Aanvankelijke reCAPTCHA v3 opstellingssectie hieronder, zult u het Centrum van Gegevens van uw Marketo Engage abonnement en Munchkin identiteitskaart nodig hebben. Zo vind je ze.

1. Klik in Marketo op **Beheer**.

   ![](assets/setting-up-recaptcha-v3-1.png)

1. Klikken **Mijn account**.

   ![](assets/setting-up-recaptcha-v3-2.png)

1. Schuif omlaag naar Ondersteuningsinformatie.

   ![](assets/setting-up-recaptcha-v3-3.png)

## Oorspronkelijke reCAPTCHA v3-instelling {#initial-recaptcha-v3-setup}

De volgende stappen worden uitgevoerd buiten Marketo.

1. Ga naar [https://www.google.com/recaptcha/about/](https://www.google.com/recaptcha/about/){target=&quot;_blank&quot;} en klik op v3-Admin Console.

1. Meld u aan bij of meld u aan bij een Google-account.

1. Klik op de knop Maken (+) om een nieuwe toets te maken.

1. Maak een label om de sleutel aan te duiden die moet worden gebruikt voor Marketo Engage.

1. Tekst kiezen **reCAPTCHA v3**. Marketo Engage biedt momenteel geen ondersteuning voor reCAPTCHA v2.

1. Voeg elk domein toe het Marketo Engage abonnement gebruikt. Domeinen die hier niet zijn ingesteld, retourneren fouten op formulieren waarvoor reCAPTCHA is ingeschakeld. Vergeet niet de woorden &#39;datacenter&#39; en &#39;munchkinID&#39; te vervangen door de woorden [gegevens in uw abonnement](#retrieve-your-data-center-and-munchkin-id).

   * app-datacenter.marketo.com
   * munchkinID.mktoweb.com
   * elk domein en alias van de landingspagina dat in het abonnement is geconfigureerd

   >[!NOTE]
   >
   >Als het datacenter van uw account bijvoorbeeld &quot;sjst&quot; is, is het domein dat u voegt op lijst van gewenste personen `app-sjst.marketo.com`. Als uw Munchkin-id 123-ABC-789 is, is het domein dat u voegt op lijst van gewenste personen `123-ABC-789.mktoweb.com`.

1. Stel een eigenaar in en voeg een e-mailadres toe waar waarschuwingen over deze service moeten worden ontvangen.

1. Accepteer de Servicevoorwaarden van reCAPTCHA.

1. Klikken **Verzenden**.

   >[!NOTE]
   >
   >Houd de plaatssleutel en geheime sleutel handig voor de configuratie van Marketo Engage.

## CAPTCHA instellen in Marketo Engage {#setting-up-captcha-in-marketo-engage}

1. Klik in Marketo op **Beheer**.

   ![](assets/setting-up-recaptcha-v3-4.png)

1. Selecteren **CAPTCHA** in de boom.

   ![](assets/setting-up-recaptcha-v3-5.png)

1. Klikken **Bewerken** op CAPTCHA-instellingen.

   ![](assets/setting-up-recaptcha-v3-6.png)

1. Klik op de vervolgkeuzelijst CAPTCHA en kies reCAPTCHA v3.

   ![](assets/setting-up-recaptcha-v3-7.png)

1. Voeg de Geheime sleutel en Sitesleutel in. Klikken **Opslaan** wanneer gereed.

   ![](assets/setting-up-recaptcha-v3-8.png)
