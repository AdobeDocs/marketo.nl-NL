---
unique-page-id: 2950578
description: Gegevens van sociaal profiel beheren - Marketo-documenten - productdocumentatie
title: Gegevens van sociaal profiel beheren
exl-id: 9b20c6fc-5c80-4665-9c93-1bb6e53a29ae
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '304'
ht-degree: 5%

---

# Gegevens van sociaal profiel beheren {#manage-social-profile-data}

Wanneer iemand met een Marketo communiceert [sociale app](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)of geeft hun sociale netwerk toestemming om een Marketo-formulier vooraf in te vullen met [sociale formulieren invullen](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md), legt Marketo alle gegevens vast die beschikbaar zijn via het sociale profiel. U kunt deze informatie weergeven op het tabblad [Persoonsgegevens, pagina](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md), of voeg het als kolom in een [aangepaste weergave van een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/create-and-change-views-for-lists-and-smart-list.md).

In sociale formulieren en sociale toepassingen worden enigszins verschillende sets velden vastgelegd. zie de sectie voor elk hieronder.

>[!AVAILABILITY]
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

## Vastgelegd via sociale app {#captured-via-social-app}

Afhankelijk van de privacy-instellingen van het netwerk en de gebruiker worden een of meer van deze velden opgehaald:

>[!NOTE]
>
>De aanvullende informatie van sociale netwerken wordt ongeveer vijf minuten na toestemming van de persoon op de pagina Details persoon weergegeven.

## Uit Twitter: {#from-twitter}

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
>Door het sociale formulier vastgelegde gegevens overschrijven overeenkomende velden, tenzij u [blokupdates van deze velden op formulierniveau](/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md).

## Uit Twitter: {#from-twitter-1}

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
>Met sociale formulieren wordt het e-mailadres vastgelegd _alleen_ indien de persoon het formulier invult. Als u het e-mailadres nodig hebt, moet u [van het formulier een vereist veld maken in uw formulier](/help/marketo/product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md).

>[!MORELIKETHIS]
>
>Schakel [sociale formulieren invullen](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md).
