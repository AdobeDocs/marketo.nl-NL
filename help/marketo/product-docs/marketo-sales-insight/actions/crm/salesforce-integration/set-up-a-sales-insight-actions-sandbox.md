---
description: Een Insight Handelingen Handelingen Handelssandbox voor verkoop instellen - Marketo Docs - Productdocumentatie
title: Een handelings-Insight-handelingensandbox instellen
exl-id: 8bc3a8a6-7fbc-4cbe-99a7-21b066ec4f96
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '671'
ht-degree: 0%

---

# Een handelings-Insight-handelingensandbox instellen {#set-up-a-sales-insight-actions-sandbox}

>[!NOTE]
>
>De Acties van Insight van de Verkoop van Marketo is een web-based toepassing die exclusief met Salesforce CRM via het [ pakket van Insight van de Verkoop van Marketo ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"} integreert. Het wordt soms bedoeld als &quot;Verkoop van Marketo,&quot;of eenvoudig &quot;Acties.&quot;

Als u een Marketo-sandbox hebt, kunt u een Actions-instantie inschakelen die met uw sandbox wordt gebruikt voor testdoeleinden.

Wanneer u een Actions-instantie instelt, moet u bepalen of deze wordt geconfigureerd voor gebruik met Salesforce Sandbox of Salesforce-productie. Dit komt doordat Salesforce verschillende eindpunten voor elk gebruikt, en Handelingen de verbinding met Salesforce gebruiken voor het activeren en verifiëren van gebruikers.

Voer de onderstaande stappen uit om een Actions-instantie in te stellen voor gebruik met uw Salesforce Sandbox-instantie.

>[!NOTE]
>
>U kunt meer over leren hoe de gebruikers [ hun plaats van Acties ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-checklist.md){target="_blank"} zullen activeren. U kunt ook leren hoe de gebruikers [ met Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"} voor authentiek zullen verklaren. Bovendien, als u verkiest gebruikers met e-mail en wachtwoord voor authentiek te laten verklaren, kunt u meer over dit in ons [ de montagesartikel van het Beheer van de Login ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"} leren.

## Een verzoek indienen voor een instantie Handelingen die moet worden geleverd aan uw Marketo-sandbox {#request=an-actions-instance}

Handelingen Insight voor verkoop zijn alleen ingeschakeld voor Marketo Sandbox-instanties als daarom wordt gevraagd. Neem contact op met het Adobe-accountteam (uw accountmanager) om een aanvraag in te dienen.

## Account voor handelingen instellen voor Marketo-sandbox {#provision-your-actions-account}

Als Handelingen zijn ingeschakeld voor uw Marketo-sandbox, moet u de onderstaande stappen volgen om uw nieuwe exemplaar te activeren.

1. Meld u aan bij uw Marketo Sandbox-instantie.

1. Navigeer aan **Admin**.

1. Selecteer **Insight van de Verkoop**.

1. Selecteer **Config van Acties**.

   >[!IMPORTANT]
   >
   >Een e-mailadres kan slechts voor één instantie van Acties over zowel Sandbox als de instanties van de Productie worden gebruikt. Als u een beheerder bent die toegang tot veelvoudige instanties over Productie en Sandbox zal vereisen, moet u een verschillend e-mailadres voor elk gebruiken.

1. Selecteer op de inrichtingskaart de gebruiker die u wilt uitnodigen voor uw exemplaar van Sales Insight Actions.

## Activeren uw instantie van Acties {#activate-your-actions-instance}

Uw Actions-exemplaar moet worden geactiveerd met een Salesforce-productieaccount. Nadat het is geactiveerd, kan het worden geschakeld naar een Salesforce Sandbox-account.

1. Zoek de verzonden uitnodiging.

1. Klik **krijgen Begonnen** Verbinding.

1. Activeer met je Salesforce Production-exemplaar.

1. Volg de aanwijzingen om het account in te stellen. Voor een gedetailleerd overzicht, controleer ons [ Gebruiker op het instappen artikel ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}.

## De ActionScript-instantie voorbereiden op compatibiliteit met uw Salesforce Sandbox-instantie {#prepare-your-actions-instance}

Voor handelingen moet u eerst een nieuwe instantie activeren bij een Salesforce-productiegebruiker. Nadat u deze optie hebt geactiveerd, kunt u de volgende stappen uitvoeren om uw exemplaar voor te bereiden op compatibiliteit met de Salesforce-sandbox.

1. Werk login montages aan &quot;Alle Login Methoden,&quot;bij zodat kunt u login met een gebruikersbenaming en een wachtwoord indien nodig. Indien gewenst, kan dit worden teruggezet naar &quot;Alleen Salesforce&quot; nadat alles is geconfigureerd. [ zie hoe te om dit te doen ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

1. Verbinding met Salesforce Production verbreken en verbinding maken met uw Salesforce-sandbox. [ zie hoe te om hier ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"} te verbinden. Selecteer voor stap 3 &quot;Sandbox&quot; in plaats van &quot;Salesforce&quot;. Als u al verbinding hebt, ziet u een optie om de verbinding te verbreken op het tabblad Salesforce-verbindingen en -aanpassingen.

>[!NOTE]
>
>Als u een aangepast domein hebt voor uw Salesforce-instantie, raden we u aan u aan te melden bij uw Salesforce-instantie voordat u verbinding maakt met Salesforce of zich aanmeldt bij Handelingen.

## Aanvragen dat uw Actions-instantie wordt geconverteerd naar compatibiliteit met uw Salesforce-sandbox {#request-your-actions-instance-be-converted}

1. De Steun van Marketo Engage van het contact [ om uw nieuwe instantie van de Acties van Insight van de Verkoop aan te vragen wordt gevormd om compatibel met Sandbox van Salesforce te zijn.](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}

1. Test alles op de juiste wijze door u aan te melden met de knop &quot;Aanmelden met Salesforce&quot; op de pagina toutapp.com/login.

   ![](assets/set-up-a-sales-insight-actions-sandbox-1.png)

   >[!TIP]
   >
   >Als u op dit moment problemen ondervindt, kunt u een verzoek indienen om het wachtwoord opnieuw in te stellen en een wachtwoord gebruiken om weer toegang te krijgen tot uw account.

Uw instantie kan nu worden gebruikt met uw Salesforce Sandbox-instantie. Als u [ Salesforce auto-login ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"} van Salesforce zou willen gebruiken, kunt u terug naar &quot;Salesforce slechts&quot;in uw [ montages van het Login Beheer ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"} schakelen.

>[!NOTE]
>
>* [ verbind Uw Rekening van de Acties van Insight van de Verkoop met Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"}
>* [ Gebruiker van de Acties van Insight van de Verkoop op het instappen van Gids ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}
>* [ Auto Login van Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"}
>* [ Login de Montages van het Beheer ](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}
