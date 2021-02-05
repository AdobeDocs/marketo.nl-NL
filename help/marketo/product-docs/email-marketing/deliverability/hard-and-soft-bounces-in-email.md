---
unique-page-id: 1147328
description: Harde en zachte grenzen in e-mail - Marketo Docs - Productdocumentatie
title: Harde en zachte grenzen in e-mail
translation-type: tm+mt
source-git-commit: 615ddd6ffdb3873baa159d440db7b24f3a07e6b0
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---


# Harde en zachte grenzen in e-mail {#hard-and-soft-bounces-in-email}

Een harde stuit kan het e-mailadres van een persoon ongeldig verklaren wanneer een postserver Marketo vertelt dat de e-mail van de persoon niet kan worden geleverd. Een zachte stuit betekent dat er iets fout is gegaan bij het verzenden van de e-mail aan de persoon; dit wordt automatisch opgelost en kan soms dagen duren . Zowel hard als zachte grenzen bestaan uit [veelvoudige categorieën](https://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838).

## Stuitclassificatie {#bounce-classification}

Er zijn vijf tekenreeksen in Marketo die verwant zijn aan problemen met het verzenden van e-mail.

1. **E-mail opgeschort**  - Ingesteld op Waar wanneer een bepaald type harde stuit voorkomt.
1. **Opgeschorte oorzaak**  via e-mail - Er kunnen vele redenen zijn. In dit veld wordt geprobeerd de oorzaak uit te leggen.
1. **E-mail opgeschort om** - Wanneer de beledigende stuit voorkomt, zal Marketo het versturen naar de persoon gedurende 24 uur na deze tijdstempel opschorten.
1. **Ongeldig**  e-mailadres - Ingesteld op Waar wanneer een bepaald type harde stuit voorkomt.
1. **Ongeldige oorzaak**  e-mail - De reden voor de harde stuit.

>[!NOTE]
>
>Nadat een persoon de status **e-mail is geschorst** heeft bereikt, is er geen manier om het selectievakje voor geschorste e-mail te ontruimen. De persoon zal echter nog steeds 24 uur na de eerste opschorting mailbaar worden.
>
>Wanneer een persoon is gemarkeerd als **e-mail ongeldig**, kunnen deze alleen handmatig opnieuw worden ingesteld (wat we u alleen aanraden als u weet dat bepaalde e-mailadressen geldig zijn) door het vakje &quot;E-mail ongeldig&quot; op het tabblad Person Info van hun record uit te schakelen.

>[!PREREQUISITES]
>
>Voer [deze stappen](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md) uit om een e-mailprestatierapport te maken dat stuitergegevens genereert.

Nadat u uw e-mailprestatierapport hebt gemaakt, moet uw scherm er ongeveer als volgt uitzien:

![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>Spam-filters maken soms harde golven. Deze &quot;vals-positieven&quot; zijn geen aanwijzing van de ware geldigheid van het e-mailadres van de persoon.
