---
description: Een sandbox Handelingen voor het toezicht op de verkoop instellen - Marketo Docs - Productdocumentatie
title: Een sandbox Handelingen voor het toezicht op verkopen instellen
exl-id: 8bc3a8a6-7fbc-4cbe-99a7-21b066ec4f96
source-git-commit: 1f228323c18204149630a7cb77d6ae0a88b425e3
workflow-type: tm+mt
source-wordcount: '671'
ht-degree: 0%

---

# Een sandbox Handelingen voor het toezicht op verkopen instellen {#set-up-a-sales-insight-actions-sandbox}

>[!NOTE]
>
>De Acties van het Inzicht van de Verkoop van Marketo is een web-based toepassing die exclusief met Salesforce CRM via het [ pakket van het Inzicht van de Verkoop van Marketo ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"} integreert. Het wordt soms bedoeld als &quot;Verkoop van Marketo,&quot;of eenvoudig &quot;Acties.&quot;

Als u een Marketo-sandbox hebt, kunt u een Actions-instantie inschakelen die met uw sandbox wordt gebruikt voor testdoeleinden.

Wanneer het opzetten van een instantie van Acties, moet u beslissen of het zal worden gevormd om met de Sandbox van Salesforce of productie Salesforce te werken. Dit komt omdat Salesforce voor elk verschillende eindpunten gebruikt, en de Acties gebruiken de verbinding aan Salesforce om gebruikers te activeren en voor authentiek te verklaren.

Voer de onderstaande stappen uit om een instantie Actions in te stellen voor gebruik met de Salesforce-sandbox-instantie.

>[!NOTE]
>
>U kunt meer over leren hoe de gebruikers [ hun plaats van Acties ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-checklist.md){target="_blank"} zullen activeren. U kunt ook leren hoe de gebruikers [ met Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"} voor authentiek zullen verklaren. Bovendien, als u verkiest gebruikers met e-mail en wachtwoord voor authentiek te laten verklaren, kunt u meer over dit in ons [ de montagesartikel van het Beheer van de Login ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"} leren.

## Een verzoek indienen voor een instantie Handelingen die moet worden geleverd aan uw Marketo-sandbox {#request=an-actions-instance}

Handelingen voor verkoopinzicht zijn alleen ingeschakeld voor instanties van Marketo Sandbox. Neem contact op met het accountteam van de Adobe (uw accountmanager) om een aanvraag in te dienen.

## Account voor handelingen instellen voor Marketo-sandbox {#provision-your-actions-account}

Als Handelingen zijn ingeschakeld voor uw Marketo-sandbox, moet u de onderstaande stappen volgen om uw nieuwe exemplaar te activeren.

1. Meld u aan bij uw Marketo Sandbox-instantie.

1. Navigeer aan **Admin**.

1. Selecteer **Inzicht van de Verkoop**.

1. Selecteer **Config van Acties**.

   >[!IMPORTANT]
   >
   >Een e-mailadres kan slechts voor één instantie van Acties over zowel Sandbox als de instanties van de Productie worden gebruikt. Als u een beheerder bent die toegang tot veelvoudige instanties over Productie en Sandbox zal vereisen, moet u een verschillend e-mailadres voor elk gebruiken.

1. Selecteer in de inrichtingskaart de gebruiker die u wilt uitnodigen voor uw exemplaar Handelingen voor het toezicht op de verkoop.

## Activeren uw instantie van Acties {#activate-your-actions-instance}

Uw instantie van Acties zal met een Salesforce productierekening moeten worden geactiveerd. Nadat het wordt geactiveerd, kan het aan een rekening worden geschakeld Salesforce Sandbox.

1. Zoek de verzonden uitnodiging.

1. Klik **krijgen Begonnen** Verbinding.

1. Activeer met uw Salesforce Production-exemplaar.

1. Volg de aanwijzingen om het account in te stellen. Voor een gedetailleerd overzicht, controleer ons [ Gebruiker op het instappen artikel ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}.

## Bereid uw Instantie van Acties voor om compatibel met uw zandbak van Salesforce te zijn {#prepare-your-actions-instance}

Voor handelingen moet u eerst een nieuwe instantie activeren met een Salesforce-productiegebruiker. Nadat u deze optie hebt geactiveerd, kunt u de volgende stappen uitvoeren om uw exemplaar voor te bereiden op compatibiliteit met Salesforce-sandbox.

1. Werk login montages aan &quot;Alle Login Methoden,&quot;bij zodat kunt u login met een gebruikersbenaming en een wachtwoord indien nodig. Indien aangewezen, kan dit aan &quot;Salesforce slechts&quot;worden geschakeld nadat alles wordt gevormd. [ zie hoe te om dit te doen ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

1. Haal de verbinding met Salesforce Production los en maak verbinding met uw Salesforce-sandbox. [ zie hoe te om hier ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"} te verbinden. Selecteer voor stap 3 &quot;Sandbox&quot; in plaats van &quot;Salesforce&quot;. Als u reeds verbonden bent, zou u een optie moeten zien om op het lusje van Verbindingen Salesforce en Aanpassingen los te maken.

>[!NOTE]
>
>Als u een douanedomein voor uw instantie Salesforce hebt, adviseren wij het programma worden geopend aan uw instantie Salesforce alvorens met Salesforce te verbinden of het programma te openen aan Acties.

## Vraag uw Instantie van Acties worden omgezet om compatibel met Uw zandbak van Salesforce te zijn {#request-your-actions-instance-be-converted}

1. De Steun van het Marketo Engage van het contact [&#128279;](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}  om uw nieuwe instantie van de Acties van het Inzicht van de Verkoop te verzoeken wordt gevormd om compatibel met Sandbox te zijn Salesforce.

1. Test alles op de juiste wijze door u aan te melden met de knop &quot;Aanmelden met Salesforce&quot; op de pagina toutapp.com/login.

   ![](assets/set-up-a-sales-insight-actions-sandbox-1.png)

   >[!TIP]
   >
   >Als u op dit moment problemen ondervindt, kunt u een verzoek indienen om het wachtwoord opnieuw in te stellen en een wachtwoord gebruiken om weer toegang te krijgen tot uw account.

Uw instantie kan nu worden gebruikt met uw Salesforce Sandbox-instantie. Als u [ Salesforce auto-login ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"} van Salesforce zou willen gebruiken, kunt u terug naar &quot;Salesforce slechts&quot;in uw [ montages van het Login Beheer ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"} schakelen.

>[!NOTE]
>
>* [ verbind Uw Rekening van de Acties van het Inzicht van de Verkoop met Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"}
>* [ Gebruiker van de Acties van het Inzicht van de Verkoop op het instappen van Gids ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}
>* [ Auto Login van Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"}
>* [ Login de Montages van het Beheer ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}
