---
unique-page-id: 14352600
description: Hoe te opstelling Uw Server van Outlook365 SMTP met Verkoop Connect - Marketo Docs - de Documentatie van het Product
title: Hoe te opstelling Uw Server Outlook365 SMTP met Verkoop Connect
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '252'
ht-degree: 0%

---


# Hoe te opstelling Uw Server Outlook365 SMTP met Verkoop verbindt {#how-to-set-up-your-outlook-smtp-server-with-sales-connect}

>[!NOTE]
>
>Als uw organisatie Vooruitzichten gebruikt en u probeert om een e-mailleveringskanaal met Marketo Sales Connect op te zetten, adviseren wij verbindend met uw server van de Uitwisseling [gebruikend onze eigenschap van de e-mailverbinding](http://docs.marketo.com/x/Z4AOAQ).

Voor het instellen van een aangepaste [SMTP](http://docs.marketo.com/x/zYTS)-server als een alternatief leveringskanaal vereist ToutApp wel dat u enige vorm van verificatie gebruikt voor beveiligingsdoeleinden. U kunt opstelling om het even welke server SMTP op uw [SMTP configuratiepagina](http://toutapp.com/next#settings/email-servers/smtp/configure). Aan opstelling een server van Office365 SMTP, adviseert Microsoft de volgende configuratie:\
**SMTP-server**: smtp.office365.com\
**Serverpoort**: Poort 587 - Beveiligd\
**Verificatiemethode**: Aanmelden (SSL/TLS)\
**Gebruikersnaam of aanmelding**: uw Office365-e-mailadres\
**Wachtwoord**: uw Office365-e-mailwachtwoord\
**Uw domein**: het domein van uw bedrijf

Als u nog kwesties vestiging uw server SMTP hebt, partner met uw Uitwisseling Admin om de juiste geloofsbrieven te verzekeren wordt gebruikt.

>[!NOTE]
>
>Wanneer het verzenden door uw Office365 SMTP, legt Microsoft `limit of 30 messages sent per minute`, en een grens van 10.000 ontvangers per dag op. Daarnaast moet `each member` van uw team dat e-mailberichten via hun Office365 SMTP-server wil verzenden, dit instellen met hun eigen e-mailadres en wachtwoord in hun Sales Connect-instellingen. Het controleren van de doos voor het plaatsen &quot; `Make this deliverability channel to all my team members` `" will not work` voor deze configuratie, in overeenstemming met Microsoft Office365 rekeningsbeleid.

