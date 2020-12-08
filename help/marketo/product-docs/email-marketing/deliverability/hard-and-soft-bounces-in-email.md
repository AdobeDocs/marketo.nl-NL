---
unique-page-id: 1147328
description: Harde en zachte grenzen in e-mail - Marketo Docs - Productdocumentatie
title: Harde en zachte grenzen in e-mail
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 0%

---


# Harde en zachte grenzen in e-mail {#hard-and-soft-bounces-in-email}

Een harde stuit kan het e-mailadres van een persoon ongeldig verklaren wanneer een postserver Marketo vertelt dat de e-mail van de persoon niet kan worden geleverd. Een zachte stuit betekent dat er iets fout is gegaan bij het verzenden van de e-mail aan de persoon; dit wordt automatisch opgelost en kan soms dagen duren . Zowel harde als zachte stuiteringen bestaan uit [meerdere categorieën](http://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838).

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

## Stuitclassificatie {#bounce-classification}

Er zijn vijf tekenreeksen in Marketo die verwant zijn aan problemen met het verzenden van e-mail.

1. **E-mail opgeschort** - Ingesteld op Waar wanneer een bepaald type harde stuit voorkomt.
1. **Opgeschorte oorzaak** via e-mail - Er kunnen vele redenen zijn. In dit veld wordt geprobeerd de oorzaak uit te leggen.
1. **E-mail opgeschort om **- Wanneer de beledigende stuit voorkomt, zal Marketo het versturen aan de persoon voor 24 uur van dit timestamp opschorten.
1. **Ongeldig** e-mailadres - Ingesteld op Waar wanneer een bepaald type harde stuit voorkomt.
1. **Ongeldige oorzaak** e-mail - De reden voor de harde stuit.

>[!NOTE]
>
>Nadat een persoon de status **voor geschorste** e-mail heeft bereikt, kan het selectievakje voor geschorste e-mail niet meer worden gewist. De persoon zal echter nog steeds 24 uur na de eerste opschorting mailbaar worden.
>
>Als een persoon is gemarkeerd als een **e-mailadres dat ongeldig** is, kan deze alleen handmatig opnieuw worden ingesteld (wat we u alleen aanraden als u weet dat bepaalde e-mailadressen geldig zijn) door het selectievakje Ongeldig e-mailadres op het tabblad Persongegevens van zijn record uit te schakelen.

>[!NOTE]
>
>**Vereisten**
>
>Voer [de volgende stappen](../../../product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md) uit om een e-mailprestatierapport te maken waarin stuitergegevens worden gegenereerd.

Nadat u uw e-mailprestatierapport hebt gemaakt, moet uw scherm er ongeveer als volgt uitzien: ![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>Spam-filters maken soms harde golven. Deze &quot;vals-positieven&quot; zijn geen aanwijzing van de ware geldigheid van het e-mailadres van de persoon.

