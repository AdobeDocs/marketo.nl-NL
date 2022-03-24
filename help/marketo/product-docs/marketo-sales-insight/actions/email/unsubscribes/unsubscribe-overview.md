---
description: Abonnementsoverzicht - Marketo Docs - Productdocumentatie
title: Overzicht van abonnement opzeggen
exl-id: 7598efa9-9686-4dd0-840b-f8b6de4ab2be
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 0%

---

# Overzicht van abonnement opzeggen {#unsubscribe-overview}

Het wordt steeds belangrijker voor organisaties om zich aan de wetten van de e-mailprivacy te houden. Om dit te helpen, hebben we een aantal verbeteringen aangebracht in onze ervaring voor afmelden.

* Koppelingen voor abonnementen worden geplaatst op alle e-mails die vanuit Marketo Sales en Salesforce worden verzonden (dit geldt niet voor aangepaste e-mails die vanuit Outlook of Gmail worden verzonden)
* Admins kunnen unsubscribe overseinen voor hun volledig team uitgeven
* Afmeldingsgegevens worden opgeslagen in PDV
* Abonnementen kunnen handmatig worden uitgevoerd: Klik op Koppeling, Salesforce Sync en Bounce
* Nieuwe bestemmingspagina voor afmelding van koppeling

## Abonnement op bestemmingspagina van koppeling opzeggen {#unsubscribe-link-landing-page}

Wanneer iemand op de koppeling voor afmelden klikt, wordt hij of zij doorgestuurd naar een bestemmingspagina waar hij of zij kan selecteren van wie hij of zij afmeldt en waarom.

![](assets/unsubscribe-overview-1.png)

Deze informatie wordt opgeslagen in de weergave met persoonlijke details voor weergave op een later tijdstip.

## Groep afmelden {#unsubscribe-group}

Alle geabonneerde personen op één locatie bekijken en beheren.

![](assets/unsubscribe-overview-2.png)

Gebruik de zoekbalk om geabonneerde personen op te zoeken.

![](assets/unsubscribe-overview-3.png)

Als u een Admin bent, kunt u naar de unsubscribe groep gaan om door Account Unsubscribes te filtreren en alle unsubscribes te zien die in uw personengegevensbestand zijn verzameld.

![](assets/unsubscribe-overview-4.png)

## Historiekaart afmelden {#unsubscribe-history-card}

De kaart van de Geschiedenis Unsubscribe helpt beheerders en de gebruikers contextafhankelijke informatie over hun het afmelden geschiedenis van contacten krijgen. Navigeer daar door naar het lusje van Mensen te gaan en een persoon te selecteren. Het bevindt zich onder aan het tabblad Over in de weergave Details persoon.

>[!NOTE]
>
>Er wordt alleen een abonnement op een historie opgezegd als de persoon _geabonneerd_ op een gegeven moment.

![](assets/unsubscribe-overview-5.png)

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Datum</strong></td> 
   <td><p>Hier wordt de datum weergegeven waarop het abonnement is opgezegd of opnieuw is geabonneerd.</p></td> 
  </tr> 
  <tr> 
   <td><strong>Details</strong></td> 
   <td><p>Opnieuw plaatsen: Een Sales Connect-beheerder heeft het abonnement handmatig uit de contactrecord verwijderd. Het kan ook enkele details weergeven met betrekking tot waarom de contactpersoon niet is geabonneerd.</p><p>Abonnement opzeggen: De contactpersoon is afgemeld.</p></td> 
  </tr> 
  <tr> 
   <td><strong>Bron</strong></td> 
   <td><p>Salesforce Sync: Unsubscribe is vastgelegd via een synchronisatie van Salesforce.</p><p>Handmatig: De gebruiker heeft op de knop Abonnement opzeggen geklikt om te weigeren.</p><p>Klikte koppeling: De ontvanger van een e-mail klikte de unsubscribe verbinding.</p><p>"Naam beheerder": De naam van een beheerder zal tonen wanneer de actie contacten resubscribe moest. Gebruikers weten wie het abonnement heeft verwijderd.</p></td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[Bericht voor opzeggen van koppeling aanpassen](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/customize-unsubscribe-link-message.md)
