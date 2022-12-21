---
unique-page-id: 1147328
description: Harde en zachte grenzen in e-mail - Marketo Docs - Productdocumentatie
title: Harde en zachte grenzen in e-mail
exl-id: 53298562-76b6-473a-bf9f-2bec682f4d35
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---

# Harde en zachte grenzen in e-mail {#hard-and-soft-bounces-in-email}

Een harde stuit kan het e-mailadres van een persoon ongeldig maken wanneer een mailserver Marketo vertelt dat het e-mailadres van de persoon niet kan worden bezorgd. Een zachte stuit betekent dat er iets fout is gegaan bij het verzenden van de e-mail aan de persoon; dit wordt automatisch opgelost en kan soms dagen duren . Zowel harde als zachte vlekken bestaan uit [meerdere categorieën](https://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838).

## Stuitclassificatie {#bounce-classification}

Er zijn vijf tekenreeksen voor personen in Marketo die te maken hebben met problemen bij het verzenden van e-mail.

1. **E-mail opgeschort** - Ingesteld op Waar wanneer een bepaald type harde stuit voorkomt.
1. **E-mail geschorste oorzaak** - Er kunnen vele redenen zijn. In dit veld wordt geprobeerd de oorzaak uit te leggen.
1. **E-mail opgeschort op** - Wanneer de aanstootgevende stuit, zal Marketo het versturen aan de persoon voor 24 uur van dit timestamp opschorten.
1. **E-mail ongeldig** - Ingesteld op Waar wanneer een bepaald type harde stuit voorkomt.
1. **Ongeldige oorzaak e-mail** - De reden voor de harde stuit.

>[!NOTE]
>
>Nadat een persoon **e-mail opgeschort** status, kan het selectievakje voor geschorste e-mail niet worden gewist. De persoon wordt echter nog steeds 24 uur na de eerste opschorting mailbaar.
>
>Wanneer een persoon is gemarkeerd als **e-mail ongeldig**, kunnen ze alleen handmatig opnieuw worden ingesteld (wat we u alleen aanraden als u weet dat bepaalde e-mailadressen geldig zijn) door het selectievakje Ongeldig e-mailadres uit te schakelen op het tabblad Personinfo van hun record.

>[!PREREQUISITES]
>
>Volg [deze stappen](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md) om een E-mailprestatierapport te maken dat stuitergegevens genereert.

Nadat u uw e-mailprestatierapport hebt gemaakt, moet uw scherm er ongeveer als volgt uitzien:

![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>Spam-filters maken soms harde golven. Deze &quot;vals-positieven&quot; zijn geen aanwijzing van de ware geldigheid van het e-mailadres van de persoon.
