---
unique-page-id: 4720710
description: SPF en DKIM instellen voor uw e-maillevering - Marketo Docs - Productdocumentatie
title: SPF en DKIM instellen voor uw e-maillevering
exl-id: a0f88e94-3348-4f48-bbd2-963e2af93dc0
feature: Deliverability
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 0%

---

# SPF en DKIM instellen voor uw e-maillevering {#set-up-spf-and-dkim-for-your-email-deliverability}

Een snelle manier om de verzendkosten voor e-mail te verbeteren, is door de verzendkosten op te nemen **SPF** (Beleidskader voor verzender) en **DKIM** (Domeinsleutels Identificeerde Post) in uw DNS-instellingen. Met deze toevoeging aan uw DNS ingangen, vertelt u ontvangers dat u Marketo hebt gemachtigd om e-mails namens u te verzenden. Zonder deze wijziging heeft uw e-mail een grotere kans om als spam te worden gemerkt aangezien e-mail van uw domein werd gericht, maar van een IP adres met een domein van Marketo wordt verzonden.

>[!CAUTION]
>
>U zult uw netwerkbeheerder nodig hebben om deze verandering in uw DNS verslag aan te brengen.

## SPF instellen {#set-up-spf}

**Als u geen SPF- verslag op uw domein hebt**

Vraag uw netwerkbeheerder om de volgende lijn aan uw DNS ingangen toe te voegen. Vervangen [domein] met het hoofddomein van uw website (bijv. &quot;company.com&quot;) en [corpIP] met het IP-adres van uw e-mailserver (bijvoorbeeld &quot;255.255.255.255&quot;). Als u e-mails verzendt vanuit meerdere domeinen via Marketo, moet u deze gegevens aan elk domein toevoegen (op één regel).

`[domain] IN TXT v=spf1 mx ip4:[corpIP] include:mktomail.com ~all`

**Als u een SPF- verslag op uw domein hebt**

Als u reeds een SPF verslag in uw DNS ingang hebt, voeg het volgende aan het toe:

include:mktomail.com

## DKIM instellen {#set-up-dkim}

**Wat is DKIM? Waarom wil ik DKIM instellen?**

DKIM is een authentificatieprotocol dat door e-mailontvangers wordt gebruikt om te bepalen als een e-mailbericht werd verzonden door wie het zegt werd verzonden door. DKIM verbetert vaak de leverbaarbaarheid van e-mailberichten aan de Postbus, aangezien een ontvanger er zeker van kan zijn dat het bericht niet vervalst is.

**Hoe werkt DKIM?**

Nadat u opstelling de openbare sleutel in uw DNS verslag en het verzendende domein in de Admin sectie (A) activeert, zullen wij douaneDKIM het ondertekenen voor uw uitgaande berichten inschakelen, die een gecodeerde digitale handtekening met elke e-mail zullen omvatten wij voor u (B) verzenden. De ontvangers zullen de digitale handtekening kunnen decrypteren door omhoog de &quot;openbare sleutel&quot;in DNS van uw verzendend domein (C) te kijken. Als de sleutel in de e-mail met de sleutel in uw DNS verslag beantwoordt, zal de ontvangende postserver waarschijnlijker zijn om e-mail te aanvaarden Marketo die namens u wordt verzonden.

![](assets/image2015-1-12-13-3a56-3a55.png)

**Hoe stel ik DKIM in?**

Zie [Een aangepaste DKIM-handtekening instellen](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}.

>[!MORELIKETHIS]
>
>* [Meer informatie over SPF en hoe het werkt](http://www.open-spf.org/Introduction/){target="_blank"}
>* [Is mijn SPF correct opstelling?](https://www.kitterman.com/spf/validate.html){target="_blank"}
>* [Heb ik de juiste syntaxis gebruikt?](http://www.open-spf.org/SPF_Record_Syntax/){target="_blank"}
