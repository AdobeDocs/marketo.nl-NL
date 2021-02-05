---
unique-page-id: 2950578
description: Gegevens van sociaal profiel beheren - Marketo-documenten - Productdocumentatie
title: Gegevens van sociaal profiel beheren
translation-type: tm+mt
source-git-commit: 074701d1a5f75fe592ac7f44cce6fb3571e94710
workflow-type: tm+mt
source-wordcount: '304'
ht-degree: 0%

---


# Gegevens sociaal profiel beheren {#manage-social-profile-data}

Wanneer iemand met een Marketo [sociale app](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md) in wisselwerking staat, of hun sociale netwerk machtigt om een Marketo-formulier vooraf in te vullen met [sociale notatie](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md), legt Marketo alle gegevens vast die beschikbaar zijn vanuit hun sociale profiel. U kunt deze informatie op [Persoonsdetails pagina](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) bekijken, of het toevoegen als kolom in een [douanemening van een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/create-and-change-views-for-lists-and-smart-list.md).

In sociale formulieren en sociale toepassingen worden enigszins verschillende sets velden vastgelegd. zie de sectie voor elk hieronder.

>[!AVAILABILITY]
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

## Vastgelegd via Sociale app {#captured-via-social-app}

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

## Van Facebook: {#from-facebook}

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
>Door het invullen van een sociaal formulier vastgelegde gegevens overschrijven overeenkomende velden, tenzij u [updates van deze velden op formulierniveau blokkeert](/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md).

## Van Twitter: {#from-twitter-1}

* Voornaam (geparseerd van weergavenaam)
* Achternaam (geparseerd van weergavenaam)
* E-mail

## Van Facebook: {#from-facebook-1}

* Voornaam
* Achternaam
* E-mail
* Geboortedatum
* Functie
* Bedrijf

>[!NOTE]
>
>Met het invullen van een sociaal formulier wordt het e-mailadres _alleen_ vastgelegd als de persoon het in het formulier invoert. Als u het e-mailadres nodig hebt, moet u het [als vereist veld in uw formulier ](/help/marketo/product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md) instellen.

>[!MORELIKETHIS]
>
>Schakel [Vulling van sociaal formulier](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md) in om deze informatie uit formulieren vast te leggen.
