---
unique-page-id: 1147328
description: Harde en zachte grenzen in e-mail - Marketo Docs - Productdocumentatie
title: Harde en zachte grenzen in e-mail
exl-id: 53298562-76b6-473a-bf9f-2bec682f4d35
feature: Deliverability
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 0%

---

# Harde en zachte grenzen in e-mail {#hard-and-soft-bounces-in-email}

Een harde stuit kan het e-mailadres van een persoon ongeldig maken wanneer een mailserver Marketo vertelt dat het e-mailadres van de persoon niet kan worden bezorgd. Een zachte stuit betekent dat er iets fout is gegaan bij het verzenden van de e-mail aan de persoon; dit wordt automatisch opgelost en kan soms dagen in beslag nemen. Zowel bestaan de harde als zachte grenzen uit [&#x200B; veelvoudige categorieën &#x200B;](https://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838).

## Stuitclassificatie {#bounce-classification}

Er zijn vijf tekenreeksen voor personen in Marketo die te maken hebben met problemen bij het verzenden van e-mail.

1. **E-mail opgeschort** - Reeks aan Waar wanneer een bepaald type harde stuit voorkomt.
1. **E-mail Opgeschorte Oorzaak** - Er kunnen vele redenen zijn. In dit veld wordt geprobeerd de oorzaak uit te leggen.
1. **E-mail die bij** wordt opgeschort - wanneer de beledigende stuit voorkomt, zal Marketo het versturen aan de persoon 24 uren van dit timestamp opschorten.
1. **Ongeldige E-mail** - Reeks aan Waar wanneer een bepaald type van harde stuit voorkomt.
1. **E-mail Ongeldige Oorzaak** - de reden voor de harde stuit.

>[!NOTE]
>
>Nadat een persoon **geschorste e-mail** status bereikt, is er geen manier om e-mail geschorste checkbox te ontruimen. De persoon wordt echter nog steeds 24 uur na de eerste opschorting mailbaar.
>
>Wanneer een persoon als **ongeldige e-mail** duidelijk is, kunnen zij slechts manueel worden teruggesteld (die wij u adviseren slechts doen als u voor bepaalde hun e-mail geldig bent) door de &quot;E-mail ongeldige&quot;doos in het lusje van Info van de Persoon van hun verslag uit te schakelen.

>[!PREREQUISITES]
>
>Volg [&#x200B; deze stappen &#x200B;](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md) om een Rapport van E-mailPrestaties te creëren, dat stuitgegevens zal produceren.

Nadat u uw e-mailprestatierapport hebt gemaakt, moet uw scherm er ongeveer als volgt uitzien:

![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>Spam-filters maken soms harde golven. Deze &quot;vals-positieven&quot; zijn geen aanwijzing van de ware geldigheid van het e-mailadres van de persoon.
