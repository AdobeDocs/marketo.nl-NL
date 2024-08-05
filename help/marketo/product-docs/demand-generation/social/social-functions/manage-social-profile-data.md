---
unique-page-id: 2950578
description: Gegevens van sociaal profiel beheren - Marketo-documenten - productdocumentatie
title: Gegevens van sociaal profiel beheren
exl-id: 9b20c6fc-5c80-4665-9c93-1bb6e53a29ae
feature: Social
source-git-commit: 6c3f803104c550227aec25376778147ff92aaab9
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 4%

---

# Gegevens van sociaal profiel beheren {#manage-social-profile-data}

Wanneer iemand met a Marketo [ sociale app ](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md) in wisselwerking staat, of hun sociaal netwerk machtigt om een vorm van Marketo met [ sociale vormvulling ](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md) vooraf in te vullen, vangt Marketo alle gegevens beschikbaar van hun sociaal profiel. U kunt deze informatie over de [ pagina van de Details van de Persoon ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) bekijken, of het toevoegen als kolom in a [ douanemening van een slimme lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/create-and-change-views-for-lists-and-smart-list.md).

>[!IMPORTANT]
>
>Op 31 juli 2024 begonnen we met het afschaffen van deze functie. Er kunnen geen nieuwe elementen meer worden gemaakt. Bestaande activa blijven werken tot 31 januari 2025. [ leer meer ](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977) {target="_blank"}

In sociale formulieren en sociale toepassingen worden enigszins verschillende sets velden vastgelegd. Zie de sectie voor elke velden hieronder.

>[!AVAILABILITY]
>
>Niet alle gebruikers van het Marketo Engage hebben deze functionaliteit aangeschaft. Neem contact op met het accountteam van de Adobe (uw accountmanager) voor meer informatie.

## Vastgelegd via sociale app {#captured-via-social-app}

Afhankelijk van de privacy-instellingen van het netwerk en de gebruiker worden een of meer van deze velden opgehaald:

>[!NOTE]
>
>De aanvullende informatie van sociale netwerken wordt ongeveer vijf minuten na toestemming van de persoon op de pagina Details persoon weergegeven.

## Van Twitter: {#from-twitter}

* Voornaam (geparseerd van weergavenaam)
* Achternaam (geparseerd van weergavenaam)
* URL van profielfoto
* URL van profielpagina
* Sociaal bereik (aantal volgers)

>[!NOTE]
>
>Sociale apps halen het e-mailadres van de persoon niet op.

## Uit Facebook: {#from-facebook}

* Voornaam
* Achternaam
* Profiel-URL
* URL van profielfoto
* Geslacht
* Sociaal bereik (aantal vrienden)

### Vastgelegd via Vulling van sociaal formulier {#captured-via-social-form-fill}

Afhankelijk van de privacy-instellingen van het netwerk en de gebruiker worden een of meer van deze velden opgehaald:

>[!CAUTION]
>
>Gegevens die door sociale vormvulling worden gevangen overschrijft passende gebieden tenzij u [ blokupdates aan die gebieden op het vormniveau ](/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md) blokkeert.

## Van Twitter: {#from-twitter-1}

* Voornaam (geparseerd van weergavenaam)
* Achternaam (geparseerd van weergavenaam)
* E-mail

## Uit Facebook: {#from-facebook-1}

* Voornaam
* Achternaam
* E-mail
* Geboortedatum
* Beroep
* Bedrijf

>[!NOTE]
>
>De sociale vormvulling vangt het e-mailadres _slechts_ als de persoon het in de vorm ingaat. Als u het e-mailadres nodig hebt, zou u het [ een vereist gebied in uw vorm ](/help/marketo/product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md) moeten maken.

>[!MORELIKETHIS]
>
>Om deze informatie van vormen te vangen, laat [ sociale vormvulling ](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md) toe.
