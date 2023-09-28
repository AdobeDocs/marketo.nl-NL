---
description: Een sandbox Handelingen voor het toezicht op de verkoop instellen - Marketo Docs - Productdocumentatie
title: Een sandbox Handelingen voor het toezicht op verkopen instellen
exl-id: 58af77ef-93ea-4149-be91-f86cdc8f7476
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '626'
ht-degree: 0%

---

# Een sandbox Handelingen voor het toezicht op verkopen instellen {#set-up-a-sales-insight-actions-sandbox}

>[!NOTE]
>
>Marketo Sales Insight Actions is een webtoepassing die via de [Marketo Sales Insight-pakket](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}. Het wordt soms bedoeld als &quot;Verkoop van Marketo,&quot;of eenvoudig &quot;Acties.&quot;

Als u een Marketo-sandbox hebt, kunt u een Actions-instantie inschakelen die met uw sandbox wordt gebruikt voor testdoeleinden.

Wanneer het opzetten van een instantie van Acties, moet u beslissen of het zal worden gevormd om met de Sandbox van Salesforce of productie Salesforce te werken. Dit komt omdat Salesforce voor elk verschillende eindpunten gebruikt, en de Acties gebruiken de verbinding aan Salesforce om gebruikers te activeren en voor authentiek te verklaren.

Voer de onderstaande stappen uit om een instantie Actions in te stellen voor gebruik met de Salesforce-sandbox-instantie.

>[!NOTE]
>
>U kunt meer weten over de manier waarop gebruikers [hun Actions-licentie activeren](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-checklist.md){target="_blank"}. You can also learn about how users will [authenticate with Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"}. Additionally, if you prefer to have users authenticate with email and password, you can learn more about this in our [Login Management settings article](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

## Een verzoek indienen voor een instantie Handelingen die moet worden geleverd aan uw Marketo-sandbox {#request=an-actions-instance}

Handelingen voor verkoopinzicht zijn alleen ingeschakeld voor instanties van Marketo Sandbox. Neem contact op met het accountteam van de Adobe (uw accountmanager) om een aanvraag in te dienen.

## Account voor handelingen instellen voor Marketo-sandbox {#provision-your-actions-account}

Als Handelingen zijn ingeschakeld voor uw Marketo-sandbox, moet u de onderstaande stappen volgen om uw nieuwe exemplaar te activeren.

1. Meld u aan bij uw Marketo Sandbox-instantie.

1. Navigeren naar **Beheerder**.

1. Selecteren **Verkoopoverzicht**.

1. Selecteren **Handelingen configureren**.

   >[!IMPORTANT]
   >
   >Een e-mailadres kan slechts voor één instantie van Acties over zowel Sandbox als de instanties van de Productie worden gebruikt. Als u een beheerder bent die toegang tot veelvoudige instanties over Productie en Sandbox zal vereisen, moet u een verschillend e-mailadres voor elk gebruiken.

1. Selecteer in de inrichtingskaart de gebruiker die u wilt uitnodigen voor uw exemplaar Handelingen voor het toezicht op de verkoop.

## Activeren uw instantie van Acties {#activate-your-actions-instance}

Uw instantie van Acties zal met een Salesforce productierekening moeten worden geactiveerd. Nadat het wordt geactiveerd, kan het aan een rekening worden geschakeld Salesforce Sandbox.

1. Zoek de verzonden uitnodiging.

1. Klik op de knop **Aan de slag** Koppeling.

1. Activeer met uw Salesforce Production-exemplaar.

1. Volg de aanwijzingen om het account in te stellen. Voor een gedetailleerd overzicht bekijkt u onze [Artikelen voor gebruikers aan boord](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}.

## Bereid uw Instantie van Acties voor om compatibel met uw zandbak van Salesforce te zijn {#prepare-your-actions-instance}

Voor handelingen moet u eerst een nieuwe instantie activeren met een Salesforce-productiegebruiker. Nadat u deze optie hebt geactiveerd, kunt u de volgende stappen uitvoeren om uw exemplaar voor te bereiden op compatibiliteit met Salesforce-sandbox.

1. Werk login montages aan &quot;Alle Login Methoden,&quot;bij zodat kunt u login met een gebruikersbenaming en een wachtwoord indien nodig. Indien aangewezen, kan dit aan &quot;Salesforce slechts&quot;worden geschakeld nadat alles wordt gevormd. [Kijk hier hoe u dit kunt doen](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

1. Haal de verbinding met Salesforce Production los en maak verbinding met uw Salesforce-sandbox. [Kijk hier hoe u verbinding kunt maken](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"}. Selecteer voor stap 3 &quot;Sandbox&quot; in plaats van &quot;Salesforce&quot;. Als u reeds verbonden bent, zou u een optie moeten zien om op het lusje van Verbindingen Salesforce en Aanpassingen los te maken.

>[!NOTE]
>
>Als u een douanedomein voor uw instantie Salesforce hebt, adviseren wij het programma worden geopend aan uw instantie Salesforce alvorens met Salesforce te verbinden of het programma te openen aan Acties.

## Vraag uw Instantie van Acties worden omgezet om compatibel met Uw zandbak van Salesforce te zijn {#request-your-actions-instance-be-converted}

1. Contact [Ondersteuning voor Marketo Engage](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} om uw nieuwe instantie van de Acties van het Inzicht van de Verkoop aan te vragen wordt gevormd om compatibel met Sandbox Salesforce te zijn.

1. Test alles op de juiste wijze door u aan te melden met de knop &quot;Aanmelden met Salesforce&quot; op de pagina toutapp.com/login.

   ![](assets/set-up-a-sales-insight-actions-sandbox-1.png)

   >[!TIP]
   >
   >Als u op dit moment problemen ondervindt, kunt u een verzoek indienen om het wachtwoord opnieuw in te stellen en een wachtwoord gebruiken om weer toegang te krijgen tot uw account.

Uw instantie kan nu worden gebruikt met uw Salesforce Sandbox-instantie. Als u wilt gebruiken [Automatische aanmelding bij Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"} from Salesforce, you can switch back to "Salesforce Only" in your [Login Management settings](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

>[!NOTE]
>
>* [Sluit uw account voor Handelingen in het kader van Handelingen in het kader van Verkoopoverzicht aan op Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"}
>* [Handleiding voor het toezicht op de verkoop](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}
>* [Automatische aanmelding van Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"}
>* [Aanmeldingsbeheerinstellingen](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}
