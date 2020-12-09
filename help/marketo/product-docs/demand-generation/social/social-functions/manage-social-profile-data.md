---
unique-page-id: 2950578
description: Gegevens van sociaal profiel beheren - Marketo-documenten - Productdocumentatie
title: Gegevens van sociaal profiel beheren
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '396'
ht-degree: 0%

---


# Gegevens van sociaal profiel beheren {#manage-social-profile-data}

Wanneer iemand communiceert met een [sociale app](../../../../product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)Marketo of het sociale netwerk toestemming geeft om een Marketo-formulier vooraf in te vullen met een [sociale-formuliervulling](../../../../product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md), legt Marketo alle gegevens vast die beschikbaar zijn via het sociale profiel. U kunt deze informatie weergeven op de pagina [Details](http://docs.marketo.com/display/DOCS/Using+the+Person+Detail+Page)persoon of deze toevoegen als een kolom in een [aangepaste weergave van een slimme lijst](http://docs.marketo.com/display/DOCS/Create+and+Change+Views+for+Lists+and+Smart+List).

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

In sociale formulieren en sociale toepassingen worden enigszins verschillende sets velden vastgelegd. zie de sectie voor elk hieronder.

>[!NOTE]
>
>**Beschikbaarheid**
>
>Niet alle klanten hebben deze functionaliteit aangeschaft. Neem contact op met je verkoper voor meer informatie.

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
>Met gegevens die door het invullen van een sociaal formulier worden vastgelegd, worden overeenkomstige velden overschreven, tenzij u updates van deze velden op formulierniveau [](../../../../product-docs/administration/field-management/block-updates-to-a-field.md)blokkeert.

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
>Met het invullen van een sociaal formulier wordt het e-mailadres *alleen* vastgelegd als de persoon het in het formulier invoert. Als u het e-mailadres nodig hebt, [maakt u het een verplicht veld in uw formulier](../../../../product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md).

>[!MORELIKETHIS]
>
>Schakel het invullen van [sociale formulieren](../../../../product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md)in om deze gegevens van formulieren vast te leggen.

>[!NOTE]
>
>**Diep duiken**
>
>Meer weten over het werken met formulieren in de diepe [Forms](http://docs.marketo.com/display/docs/forms) ?

