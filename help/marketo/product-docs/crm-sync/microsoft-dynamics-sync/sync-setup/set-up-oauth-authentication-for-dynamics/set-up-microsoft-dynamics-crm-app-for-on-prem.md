---
description: Microsoft Dynamics CRM-app instellen voor on-prem - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics CRM-app instellen voor On-prem
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 0%

---


# Microsoft Dynamics CRM App instellen voor On-Prem {#set-up-microsoft-dynamics-crm-app-for-on-prem}

De op geheim-gebaseerde opstelling van de identiteitskaart/van de Cliënt in Marketo kan voor op-prem met AD FS (ver. worden gedaan. 2016 of hoger). Voor oudere versies van On-prem, gelieve te reiken aan [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) om de authentificatiemethode te veranderen om slechts op gebruiker te worden gebaseerd - identiteitskaart en Wachtwoord.

## Microsoft Dynamics CRM App {#set-up-microsoft-dynamics-crm-app} instellen

Voer de stappen in [dit Microsoft-artikel](https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/development/enabling-oauth-confidential-clients-with-ad-fs#create-an-application-group-in-ad-fs-2016-or-later) uit.

Wanneer u wordt gedaan, is de volgende stap **ga de Dynamica CRM Gegenereerde identiteitskaart van de Cliënt en Geheim in Marketo** in.

## Voer de door CRM gegenereerde client-id voor Dynamics CRM in en geheim in Marketo {#enter-the-dynamics-crm-generated-client-id-and-secret-into-marketo}

De volgende stappen zijn van toepassing op online en op prem versies.

1. Klik in Marketo op **Admin**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-1.png)

1. Klik **Microsoft Dynamics**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-2.png)

1. Klik **Sync uitschakelen**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-3.png)

1. Klik op **Bewerken** naast referenties.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-4.png)

1. Voer **Client ID** en **Client Secret** in die u eerder hebt opgehaald en druk op **Save**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-5.png)

1. Klik **Synchronisatie-instelling valideren**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-6.png)

1. Klik **Volgende**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-7.png)

1. Alle groene vinkjes worden weergegeven. Klik **Close**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-8.png)

   >[!NOTE]
   >
   >Als u een rode X onder uw groene controletekens ziet, zie [dit artikel](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) voor fixingsopties.

1. Klik **Sync inschakelen**.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-9.png)

En dat is het!
