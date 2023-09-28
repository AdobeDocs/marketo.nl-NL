---
description: Waarom synchroniseren mijn verkoopactiviteiten en activiteitsvelden niet met Salesforce? - Marketo Docs - Productdocumentatie
title: Waarom synchroniseren mijn verkoopactiviteiten en activiteitsvelden niet met Salesforce?
exl-id: 0836876d-1b89-4464-a841-81320a6e45fd
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---

# Waarom synchroniseren mijn verkoopactiviteiten en activiteitsvelden niet met Salesforce? {#why-arent-my-sales-activities-and-activity-fields-syncing-to-salesforce}

**Ik zie geen e-mail- of telefoonactiviteiten gesynchroniseerd met Salesforce.**

* Zorg ervoor dat je verbonden bent met Salesforce. Elke gebruiker zal een verbinding moeten hebben om zijn e-mail en vraag aan Salesforce te registreren.
* Zorg ervoor u hebt gevormd [Instellingen voor Salesforce Sync](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"}.
* De e-mail zal een verslagraadpleging doen die op identiteitskaart Salesforce als primaire raadpleging en e-mailadres als secundair wordt gebaseerd. U kunt bevestigen dat aan een persoonrecord een Salesforce-id en e-mailadres zijn gekoppeld in het dialoogvenster [Handelingen, webapp](https://toutapp.com/next#command_center){target="_blank"}.
* De vraag zal een verslagraadpleging doen die op identiteitskaart van Salesforce slechts wordt gebaseerd. Als geen identiteitskaart van Salesforce op het persoonverslag in Acties bestaat, zal de vraag niet registreren. U kunt bevestigen dat aan een persoonrecord een Salesforce-id is gekoppeld in het dialoogvenster [Handelingen, webapp](https://toutapp.com/next#command_center){target="_blank"}.

**Ik zie geen activiteitsvelden in Salesforce-update.**

Als u geen e-mail ziet [activiteitskenmerkvelden](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} in Salesforce bijwerken, kan dit te wijten zijn aan beperkingen op de toegankelijkheid van velden van uw team. De veiligheid van het Niveau van het Gebied van Salesforce geeft Salesforce Admins de capaciteit om beperkingen te plaatsen rond welke informatie zichtbaar en editable door gebruikers is. Als gebruikers van Handelingen geen toegang hebben tot de weergave en het bewerken van deze velden, worden deze velden niet bijgewerkt via de activiteitensync van Handelingen.

* Werk samen met uw Salesforce-beheerder om ervoor te zorgen dat deze beveiligingsinstellingen geen invloed hebben op [Handelingen Salesforce-activiteitenvelden](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}.
* Als u een Admin Salesforce bent, kunt u uw Toegankelijkheid van het Gebied onder de Controles tabel van de Veiligheid zien. De belangrijkste objecten waarmee acties zullen communiceren, zijn: Leads, Contacten, Rekeningen, Kansen, en Taak/Activiteiten.

>[!NOTE]
>
>De gebieden verbonden aan de Lood, het Contact, de Rekening, en voorwerpen van de Opportunity zullen met het pakket van Salesforce van het Inzicht van de Verkoop worden geïnstalleerd. Aan de [Type taak-/activiteitenrecord moet worden gemaakt](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} door een Salesforce Admin.
