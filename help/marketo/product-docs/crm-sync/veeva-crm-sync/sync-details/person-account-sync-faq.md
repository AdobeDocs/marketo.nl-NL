---
description: Veelgestelde vragen over synchronisatie van persoonlijke accounts - Marketo-documenten - Productdocumentatie
title: Veelgestelde vragen over synchronisatie van persoonlijke account
exl-id: b77bb44f-94d0-40b2-9955-9636421ac468
feature: Veeva CRM
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '472'
ht-degree: 0%

---

# Veelgestelde vragen over synchronisatie van persoonlijke account {#person-account-sync-faq}

Marketo Engage synchroniseert de gehele database met [!DNL Veeva] voor het type persoonlijke account van records. Na de synchronisatie wacht het 5 minuten, dan synchroniseert opnieuw, de hele dag, elke dag.

Persoonlijke accounts kunnen in [!DNL Veeva] worden ingesteld om aan de behoeften van uw organisatie te voldoen.

>[!NOTE]
>
>We synchroniseren alleen &#39;Professional&#39;-rijaccounts als Personaccounts.

**wat een persoonrekening is?**

Een persoonaccount lijkt sterk op het rekeningobject in [!DNL Veeva] CRM. Een persoonlijke account heeft echter toegang tot zowel accountvelden als contactvelden.

**wat gebeurt wanneer een persoonrekening aan Marketo wordt gesynchroniseerd?**

Een persoonaccount wordt als bedrijf en als persoon gesynchroniseerd met Marketo.

>[!NOTE]
>
>De aangepaste velden voor een persoonaccount worden naar zowel bedrijf als persoon in Marketo gekopieerd.

**hoe ik bedrijfsrekeningen en persoonrekeningen onderscheiden?**

Gebruik het filter &quot;Is Person&quot;Rekening in uw Slimme Lijst om persoonrekeningen van standaardbedrijfsrekeningen te scheiden.

**Welk e-mailgebied zou ik voor persoonrekeningen moeten gebruiken?**

Er zijn twee e-mailvelden voor een persoonaccount. Gebruik het veld E-mailadres in uw formulieren (niet het persoonlijke e-mailadres) om ervoor te zorgen dat Marketo de-duplicatie en andere e-mailverwerking correct werkt.

## Richting synchroniseren {#sync-direction}

De synchronisatie van contactgerelateerde velden van de Personaccount is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in [!DNL Veeva] CRM of Marketo, worden uw updates weerspiegeld in beide systemen. De velden op de account worden slechts in één richting gesynchroniseerd, van [!DNL Veeva] CRM tot Marketo.

**wat als de veranderingen in beide systemen aan de gebieden van het Contact op de Rekening van de Persoon tezelfdertijd worden aangebracht?**

We zouden aardig zijn en [!DNL Veeva] CRM laten winnen. Dit soort botsing van gegevens treedt echter zelden op.

**zijn lood of het type van Contact van verslagen die met [!DNL Veeva] CRM worden gesynchroniseerd?**

[!DNL Veeva] CRM heeft alleen echt betrekking op persoonlijke-accountobjecten en heeft ook Business Accounts. De traditionele CRM-typen Lead, Contacts en Opportunity worden niet echt gebruikt in traditionele [!DNL Veeva] CRM-systemen. Deze worden mogelijk gemaakt in [!DNL Veeva] CRM, maar worden niet officieel ondersteund via deze connector.

**kan ik een persoon in een contact in Marketo omzetten?**

Nee, omdat Lead en Contact geen ondersteunde typen zijn voor synchronisatie met [!DNL Veeva] CRM. Omzetten wordt daarom niet ondersteund.

**kan ik manueel een synchronisatie van een contact dwingen?**

Nee, omdat Contactpersoon geen onafhankelijk type record is, wordt het synchroniseren van een persoon naar [!DNL Veeva] niet ondersteund.

**doet elke enige standaardgebiedssynchronisatie aan Marketo?**

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw Marketo Sync-gebruiker toegang heeft.

**zal Marketo de [!DNL Veeva] bevestigingsregels respecteren?**

Ja, als er een conflict is, zullen wij het resultaat in het Logboek van de Activiteit van de lood registreren.

>[!MORELIKETHIS]
>
>* [ Gebrek  [!DNL Veeva]  het Toewijzing van het Gebied ](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/default-veeva-field-mapping.md){target="_blank"}
>* [ synchroniserend Vraag en de Zeer belangrijke Berichten van de Vraag ](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
