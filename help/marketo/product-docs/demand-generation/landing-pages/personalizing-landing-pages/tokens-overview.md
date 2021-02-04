---
unique-page-id: 2950799
description: Overzicht van tokens - Marketo Docs - Productdocumentatie
title: Overzicht van tokens
translation-type: tm+mt
source-git-commit: 2969e6f94f5fd781e2167ae2aa8680bb8d134754
workflow-type: tm+mt
source-wordcount: '300'
ht-degree: 0%

---


# Overzicht van tokens {#tokens-overview}

Een token is een variabele die kan worden gebruikt in de stappen voor slimme campagnestromen, e-mails, landingspagina&#39;s, fragmenten en webcampagnes van Marketo.

## Standaardwaarden {#understanding-default-values} begrijpen

Wanneer u een token gebruikt, wilt u ook een standaardwaarde opgeven. Dit is de tekst die laat zien of een persoon geen waarde heeft voor het veld waarnaar u verwijst.

![](assets/image2014-12-2-13-3a16-3a48.png)

In dit voorbeeld wordt in de e-mail het woord &quot;Groetings, (voornaam)&quot; of &quot;Greetings, aardling&quot; (standaardwaarde) vermeld.

![](assets/two.png)

>[!CAUTION]
>
>Tokens werken niet in de preheader wanneer de e-maileditor van Marketo wordt gebruikt. Als u een token wilt gebruiken in de preheader, moet dit via uw eigen HTML in een e-mailsjabloon gebeuren.

>[!NOTE]
>
>Deze lijst is niet limitatief. Tokens worden ook gecreeerd voor elk douaneveld dat u in Marketo hebt.

## Persontokens {#person-tokens}

* `{{lead.Acquisition Date}}`
* `{{lead.Acquisition Program Name}}`
* `{{lead.Acquisition Program}}`
* `{{lead.Address}}`
* `{{lead.Anonymous IP}}`
* `{{lead.Black Listed}}`
* `{{lead.City}}`
* `{{lead.Country}}`
* `{{lead.Created At}}`
* `{{lead.Date of Birth}}`
* `{{lead.Department}}`
* `{{lead.Do Not Call}}`
* `{{lead.Do Not Call Reason}}`
* `{{lead.Email Address}}`
* `{{lead.Email Invalid}}`
* `{{lead.Email Invalid Cause}}`
* `{{lead.Fax Number}}`
* `{{lead.First Name}}`
* `{{lead.Full Name}}`
* `{{lead.Id}}`
* `{{lead.Inferred City}}`
* `{{lead.Inferred Company}}`
* `{{lead.Inferred Country}}`
* `{{lead.Inferred Metropolitan Area}}`
* `{{lead.Inferred Phone Area Code}}`
* `{{lead.Inferred Postal Code}}`
* `{{lead.Inferred State Region}}`
* `{{lead.Is Customer}}`
* `{{lead.Is Employee}}`
* `{{lead.Is Partner}}`
* `{{lead.Job Title}}`
* `{{lead.Last Name}}`
* `{{lead.Lead Source}}`
* `{{lead.Marketing Suspended}}`
* `{{lead.Middle Name}}`
* `{{lead.Mobile Phone Number}}`
* `{{lead.Original Referrer}}`
* `{{lead.Original Search Engine}}`
* `{{lead.Original Search Phrase}}`
* `{{lead.Original Source Info}}`
* `{{lead.Original Source Type}}`
* `{{lead.Person Notes}}`
* `{{lead.Phone Number}}`
* `{{lead.Registration Source Info}}`
* `{{lead.Registration Source Type}}`
* `{{lead.Salutation}}`
* `{{lead.SFDC Created Date}}`
* `{{lead.SFDC Is Deleted}}`
* `{{lead.SFDC Type}}`
* `{{lead.Unsubscribed}}`
* `{{lead.Unsubscribed Reason}}`
* `{{lead.Updated At}}`
* Velden van aangepaste personen werken ook als u hun weergavenaam gebruikt, bijvoorbeeld `{{lead.Custom Field Name}}`

## Bedrijfstokens {#company-tokens}

* `{{Company.Account Owner Email Address}}`
* `{{Company.Address}}`
* `{{Company.Annual Revenue}}`
* `{{Company.City}}`
* `{{Company.Company Name}}`
* `{{Company.Company Notes}}`
* `{{Company.Country}}`
* `{{Company.Industry}}`
* `{{Company.Main Phone}}`
* `{{Company.Num Employees}}`
* `{{Company.Parent Company Name}}`
* `{{Company.Postal Code}}`
* `{{Company.SFDC Account Num}}`
* `{{Company.SFDC Created Date}}`
* `{{Company.SFDC Type}}`
* `{{Company.SIC Code}}`
* `{{Company.Site}}`
* `{{Company.State}}`
* `{{Company.Website}}`
* De gebieden van het bedrijf van de douane werken ook als u hun vertoningsnaam ex gebruikt. `{{Company.Custom Field Name}}`

## CampagneTokens {#campaign-tokens}

* `{{campaign.name}}`
* `{{campaign.id}}`
* `{{campaign.description}}`

## Systeemtokens {#system-tokens}

>[!NOTE]
>
>Meer informatie over deze tokens vindt u in de verklarende woordenlijst [Systeemtokens](/help/marketo/product-docs/email-marketing/general/using-tokens/system-tokens-glossary.md).

* `{{system.date}}`
* `{{system.time}}`
* `{{system.dateTime}}`
* `{{system.forwardToFriendLink}}`
* `{{system.unsubscribeLink}}`
* `{{system.viewAsWebpageLink}}`

## Tokens {#trigger-tokens} activeren

* `{{trigger.Trigger Name}}`
* `{{trigger.Name}}`
* `{{trigger.Link}}`
* `{{trigger.Subject}}`
* `{{trigger.Category}}`
* `{{trigger.Details}}`
* `{{trigger.Web Page}}`
* `{{trigger.Client IP Address}}`
* `{{trigger.Sent By}}`
* `{{trigger.Received By}}`
* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!NOTE]
>
>Meer informatie over [tokens voor interessante momenten](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/tokens-for-interesting-moments.md) vindt op basis van triggers die in een slimme campagne worden gebruikt.

## Programmatokens {#program-tokens}

* `{{program.Name}}`
* `{{program.Description}}`
* `{{program.id}}`

## Mijn tokens {#my-tokens}

Mijn tokens worden bepaald binnen een programma en met `{{my.` gevolgd door de naam u voor het teken creeerde. Meer informatie over [Mijn tokens in een programma](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md).

## Lidtoken {#member-token}

De Tokens van het lid worden gebruikt om unieke waarden van geïntegreerde de dienstenpartners op te nemen. Lid-tokens worden vaak gebruikt voor unieke URL&#39;s voor webinaire deelnemers. Elke persoon heeft een unieke URL om tot webinar toegang te hebben die kan worden opgenomen gebruikend een `{{member.webinar url}}` teken. De token `{{member.webinar url}}` lost automatisch de unieke bevestiging-URL van de persoon op die door het servicebureau is gegenereerd.

* `{{member.webinar url}}`

>[!CAUTION]
>
>De token `{{member.webinar url}}` wordt alleen gevuld als de slimme campagne die de e-mail verzendt een onderliggend element van het gebeurtenisprogramma is.
