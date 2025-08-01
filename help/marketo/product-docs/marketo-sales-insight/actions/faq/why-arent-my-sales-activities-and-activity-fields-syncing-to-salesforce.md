---
description: Waarom synchroniseren mijn verkoopactiviteiten en activiteitenvelden niet met Salesforce? - Marketo Docs - Productdocumentatie
title: Waarom synchroniseren mijn verkoopactiviteiten en activiteitenvelden niet met Salesforce?
exl-id: 5da855f2-18c6-456a-9e5d-ef4499596b3c
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 0%

---

# Waarom synchroniseren mijn verkoopactiviteiten en activiteitenvelden niet met Salesforce? {#why-arent-my-sales-activities-and-activity-fields-syncing-to-salesforce}

**ik zie geen e-mail of vraagactiviteiten die aan Salesforce worden gesynchroniseerd.**

* Zorg ervoor dat je bent verbonden met Salesforce. Elke gebruiker moet een verbinding hebben om zijn e-mail en vraag aan Salesforce te registreren.
* Zorg ervoor u [ de Montages van de Synchronisatie van Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"} hebt gevormd.
* Bij e-mails wordt een recordzoekopdracht uitgevoerd op basis van de Salesforce-id als primair opzoekings- en e-mailadres. U kunt bevestigen dat een persoonverslag een identiteitskaart van Salesforce en e-mailadres verbonden aan hen in [ het Web app van Acties ](https://toutapp.com/next#command_center){target="_blank"} heeft.
* De vraag zal een verslagraadpleging doen die op identiteitskaart van Salesforce slechts wordt gebaseerd. Als geen identiteitskaart van Salesforce op het persoonverslag in Acties bestaat, zal de vraag niet registreren. U kunt bevestigen dat een persoonverslag een identiteitskaart van Salesforce verbonden aan hen in [ het Web app van Acties ](https://toutapp.com/next#command_center){target="_blank"} heeft.

**ik zie geen activiteitengebieden in de update van Salesforce.**

Als u geen e-mail [ gebieden van de activiteitenattributen ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} update in Salesforce ziet, zou het aan beperkingen op de Toegankelijkheid van het Gebied van uw team kunnen zijn. De beveiliging op veldniveau van Salesforce biedt Salesforce Admins de mogelijkheid om beperkingen in te stellen ten aanzien van de informatie die gebruikers kunnen bekijken en bewerken. Als gebruikers van Handelingen geen toegang hebben tot de weergave en het bewerken van deze velden, worden deze velden niet bijgewerkt via de activiteitensync van Handelingen.

* Het werk met uw Salesforce Admin om deze veiligheidsmontages te verzekeren bemoeit zich niet met [ de gebieden van de Activiteit van Salesforce van Acties ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}.
* Als u een Salesforce Admin bent, kunt u uw Toegankelijkheid van het Gebied onder de Controles tabel van de Veiligheid zien. De belangrijkste objecten waarmee acties zullen communiceren, zijn: Leads, Contacten, Rekeningen, Kansen, en Taak/Activiteiten.

>[!NOTE]
>
>Velden die zijn gekoppeld aan de objecten Lead, Contact, Account en Opportunity worden geïnstalleerd met het Insight-pakket Verkoop. De gebieden verbonden aan het [ taak/het verslagtype van de Activiteit zullen ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} door Salesforce Admin moeten worden gecreeerd.
