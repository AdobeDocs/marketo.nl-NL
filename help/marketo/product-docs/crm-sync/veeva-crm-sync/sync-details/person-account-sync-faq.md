---
description: Veelgestelde vragen over synchronisatie van persoonlijke accounts - Marketo-documenten - Productdocumentatie
title: Veelgestelde vragen over synchronisatie van persoonlijke account
exl-id: b77bb44f-94d0-40b2-9955-9636421ac468
feature: Veeva CRM
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 0%

---

# Veelgestelde vragen over synchronisatie van persoonlijke account {#person-account-sync-faq}

Marketo Engage synchroniseert uw volledige database met Veeva voor het type persoonlijke account van records. Na de synchronisatie wacht het 5 minuten, dan synchroniseert opnieuw, de hele dag, elke dag.

Persoonlijke accounts kunnen in Veeva worden ingesteld om aan de behoeften van uw organisatie te voldoen.

>[!NOTE]
>
>We synchroniseren alleen &#39;Professional&#39;-rijaccounts als Personaccounts.

**Wat is een persoonaccount?**

Een persoonaccount lijkt sterk op het rekeningobject in Veeva CRM. Een persoonlijke account heeft echter toegang tot zowel accountvelden als contactvelden.

**Wat gebeurt er als een persoonaccount wordt gesynchroniseerd met Marketo?**

Een persoonaccount wordt als bedrijf en als persoon gesynchroniseerd met Marketo.

>[!NOTE]
>
>De aangepaste velden voor een persoonaccount worden naar zowel bedrijf als persoon in Marketo gekopieerd.

**Hoe maak ik onderscheid tussen zakelijke accounts en persoonlijke accounts?**

Gebruik het filter &quot;Is Person&quot;Rekening in uw Slimme Lijst om persoonrekeningen van standaardbedrijfsrekeningen te scheiden.

**Welk e-mailveld moet ik gebruiken voor persoonaccounts?**

Er zijn twee e-mailvelden voor een persoonaccount. Gebruik het veld E-mailadres in uw formulieren (niet het persoonlijke e-mailadres) om ervoor te zorgen dat Marketo de-duplicatie en andere e-mailverwerking correct werkt.

## Richting synchroniseren {#sync-direction}

De synchronisatie van contactgerelateerde velden van de Personaccount is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in Veeva CRM of Marketo, worden uw updates weerspiegeld in beide systemen. De velden op de account worden slechts in één richting gesynchroniseerd, van Veeva CRM tot Marketo.

**Wat gebeurt er als er tegelijkertijd wijzigingen worden aangebracht in de contactvelden van beide systemen op de persoonlijke account?**

We zouden aardig zijn en Veeva CRM laten winnen. Dit soort botsing van gegevens treedt echter zelden op.

**Zijn de Lood of het type van Contact van verslagen gesynchroniseerd met Veeva CRM?**

Veeva CRM heeft alleen echt iets met Person Account-objecten en heeft ook Business Accounts. De traditionele CRM-typen Lood, Contacten en Opportunity worden niet echt gebruikt in traditionele Veeva CRM-systemen. Deze kunnen in Veeva CRM worden gecreeerd, maar zij worden officieel gesteund gebruikend deze schakelaar.

**Kan ik een persoon omzetten in een contactpersoon in Marketo?**

Nee, omdat Lead en Contact geen ondersteunde typen zijn voor synchronisatie met Veeva CRM. Omzetten wordt daarom niet ondersteund.

**Kan ik een synchronisatie van een contact manueel dwingen?**

Nee, omdat Contact geen onafhankelijk type record is, wordt het synchroniseren van een persoon naar Veeva niet ondersteund.

**Synchroniseert elke standaard veld met Marketo?**

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw Marketo Sync-gebruiker toegang heeft.

**Zal Marketo de Veva-validatieregels naleven?**

Ja, als er een conflict is, zullen wij het resultaat in het Logboek van de Activiteit van de lood registreren.

>[!MORELIKETHIS]
>
>* [Standaardveldtoewijzing](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/default-veeva-field-mapping.md){target="_blank"}
>* [Het synchroniseren van Vraag en Vraag Zeer belangrijke Berichten](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
