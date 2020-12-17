---
unique-page-id: 4720710
description: SPF en DKIM instellen voor uw e-maillevering - Marketo Docs - Productdocumentatie
title: SPF en DKIM instellen voor uw e-maillevering
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '454'
ht-degree: 0%

---


# SPF en DKIM instellen voor uw e-mailleveringsmogelijkheden {#set-up-spf-and-dkim-for-your-email-deliverability}

Één snelle methode om uw tarieven van de e-maillevering te verbeteren is **SPF** (het Kader van het Beleid van de Afzender) en **DKIM** (De Sleutels van het Domein identificeerden Post) in uw DNS montages op te nemen. Met deze toevoeging aan uw DNS ingangen, vertelt u ontvangers dat u Marketo hebt gemachtigd om e-mails namens u te verzenden. Zonder deze verandering, heeft uw e-mail een grotere kans om als spam worden gemerkt aangezien e-mail van uw domein werd gericht, maar van een IP adres met een domein van de Marketo wordt verzonden.

>[!CAUTION]
>
>U zult uw netwerkbeheerder nodig hebben om deze verandering in uw DNS verslag aan te brengen.

## SPF {#set-up-spf} instellen

**Als u geen SPF- verslag op uw domein hebt**

Vraag uw netwerkbeheerder om de volgende lijn aan uw DNS ingangen toe te voegen. Vervang [domain] door het hoofddomein van uw website (bijv. &quot;company.com&quot;) en [corpIP] met het IP adres van uw collectieve e-mailserver (bv. &quot;255.255.255.255&quot;). Als u e-mails van meerdere domeinen verzendt via Marketo, moet u deze gegevens aan elk domein toevoegen (op één regel).
[] domainIN TXT v=spf1 mx ip4:[] corpIPinclude:mktomail.com ~all\
Als u een SPF- verslag op uw domein hebt

Als u reeds een SPF verslag in uw DNS ingang hebt, voeg het volgende aan het toe:

include:mktomail.com

## DKIM {#set-up-dkim} instellen

### Wat is DKIM? Waarom wil ik DKIM instellen? {#what-is-dkim-why-do-i-want-to-set-up-dkim}

DKIM is een authentificatieprotocol dat door e-mailontvangers wordt gebruikt om te bepalen als een e-mailbericht werd verzonden door wie het zegt werd verzonden door. DKIM verbetert vaak de leverbaarbaarheid van e-mailberichten aan de Postbus, aangezien een ontvanger er zeker van kan zijn dat het bericht niet vervalst is.

Hoe werkt DKIM?

Nadat u opstelling de openbare sleutel in uw DNS verslag en het verzendende domein in de Admin sectie (A) activeert, zullen wij douaneDKIM het ondertekenen voor uw uitgaande berichten inschakelen, die een gecodeerde digitale handtekening met elke e-mail zullen omvatten wij voor u (B) verzenden. De ontvangers zullen de digitale handtekening kunnen decrypteren door omhoog de &quot;openbare sleutel&quot;in DNS van uw verzendend domein (C) te kijken. Als de sleutel in e-mail met de sleutel in uw DNS verslag beantwoordt, zal de ontvangende postserver waarschijnlijker de e-mailMarketo goedkeuren die namens u wordt verzonden.

![](assets/image2015-1-12-13-3a56-3a55.png)

Hoe stel ik DKIM in?

Raadpleeg [Een aangepaste DKIM-handtekening instellen](set-up-a-custom-dkim-signature.md).

>[!MORELIKETHIS]
>
>* [Meer informatie over SPF en hoe het werkt](http://www.open-spf.org/Introduction/)
>* [Hulpprogramma&#39;s voor e-maillevering van Marketo](https://www.marketo.com/software/email-marketing/email-deliverability/)
>* [Is mijn SPF correct opstelling?](http://www.kitterman.com/spf/validate.html)
>* [Heb ik de juiste syntaxis gebruikt?](http://www.open-spf.org/SPF_Record_Syntax/)

>



