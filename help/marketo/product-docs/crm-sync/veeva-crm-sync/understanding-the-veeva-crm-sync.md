---
description: Begrijpen van de  [!DNL Veeva]  Synchronisatie van CRM - de Documenten van Marketo - de Documentatie van het Product
title: Begrijpen van de  [!DNL Veeva]  Synchronisatie van CRM
exl-id: 99ade106-7f32-40e8-8b9a-2b1d0e769b9c
feature: Veeva CRM
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# De [!DNL Veeva] CRM Sync begrijpen {#understanding-the-veeva-crm-sync}

In een paar eenvoudige stappen is het eenvoudig om een synchronisatie uit te voeren tussen Adobe Marketo Engage en de [!DNL Veeva] CRM.

## Hoe de Synchronisatie werkt {#how-the-sync-works}

Marketo Engage synchroniseert met [!DNL Veeva] CRM de hele dag, elke dag. Elke synchronisatie neemt enige tijd in beslag, pauzeert 5 minuten en start opnieuw.

>[!NOTE]
>
>De allereerste synchronisatie kan uren of zelfs dagen duren omdat Marketo Engage de volledige database kopieert vanuit [!DNL Veeva] . Daarna neemt elke synchronisatie doorgaans minuten (soms seconden) in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

![](assets/understanding-the-veeva-sync-1.png)

De synchronisatie tussen [!DNL Veeva] en Marketo Engage is bidirectioneel alleen voor contactvelden in het account-object Person. In deze gevallen geldt dat wanneer u wijzigingen aanbrengt in [!DNL Veeva] of Marketo Engage, de updates worden weerspiegeld in beide systemen. Alle andere syncs zijn van [!DNL Veeva] aan slechts Marketo Engage. Klik op de onderstaande koppelingen voor meer informatie.

## Wat is gesynchroniseerd tussen Marketo Engage en [!DNL Veeva] {#what-is-synced-between-marketo-engage-and-veeva}

* [&#x200B; Rekeningen van de Persoon &#x200B;](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/person-account-sync-faq.md){target="_blank"}
* Gebruikers
* [&#x200B; Vraag en de Zeer belangrijke Voorwerpen van de Vraag &#x200B;](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
* [&#x200B; de Voorwerpen van de Douane &#x200B;](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target="_blank"}

## Informatie over dingen {#things-to-know}

* De [&#x200B; geloofsbrieven u in Marketo Engage voor  [!DNL Veeva]](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} ingaat worden gebruikt om gegevens over te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

* [!DNL Veeva] CRM is gebaseerd op force.com en de rijke ervaring die Marketo Engage met het platform heeft, wordt in deze synchronisatie overgeërfd.

* De Veeva CRM toont: Lead, Contact, Accounts, Business Accounts, Opportunity, Campaign en Activity. Ze worden echter niet ondersteund tijdens de synchronisatie met Marketo Engage.
