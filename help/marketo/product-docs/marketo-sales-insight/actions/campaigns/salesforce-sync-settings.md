---
description: Salesforce Sync Settings - Marketo Docs - Productdocumentatie
title: Salesforce-instellingen synchroniseren
exl-id: fa13ced2-6184-485f-a0ef-813ccab4f0fe
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 1%

---

# [!DNL Salesforce] Instellingen synchroniseren {#salesforce-sync-settings}

## E-mailactiviteit aanmelden bij [!DNL Salesforce] via API {#logging-email-activity-to-salesforce-via-api}

Voor deze functionaliteit moet u zich op de Enterprise/Unlimited Edition van [!DNL Salesforce] bevinden, of op de Professional-editie als u Integratie via de Web Services API hebt aangeschaft.

>[!PREREQUISITES]
>
>[!DNL Salesforce] en [!DNL Sales Insight Actions] moeten zijn verbonden.

1. Klik in [!DNL Sales Insight Actions] op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/salesforce-sync-settings-1.png)

1. Klik onder [!UICONTROL Admin Settings] (of &quot;[!UICONTROL My Account]&quot; als u geen beheerder bent) op **[!UICONTROL Salesforce]** .

   ![](assets/salesforce-sync-settings-2.png)

1. Klik op de tab **[!UICONTROL Sync Settings]** .

   ![](assets/salesforce-sync-settings-3.png)

1. Klik op de pijl naast [!UICONTROL Log Email Activity] t/m [!DNL Salesforce] .

   ![](assets/salesforce-sync-settings-4.png)

1. Klik op de tab **[!UICONTROL Salesforce API]** . Op deze kaart kunt u uw voorkeur voor het registreren van informatie aan [!DNL Salesforce] plaatsen. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/salesforce-sync-settings-5.png)

## E-mailactiviteit aanmelden bij [!DNL Salesforce] via e-mail naar [!DNL Salesforce] (BCC) {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

Zodra u &quot;[!UICONTROL Email to Salesforce (BCC)]&quot;activeert, zult u een BCC van uw verkoop e-mails ontvangen en uw e-mails zullen als activiteiten op kansen, lood en contacten worden geregistreerd.

>[!PREREQUISITES]
>
>[!DNL Salesforce] en [!DNL Sales Insight Actions] moeten zijn verbonden.

**om uw e-mails in [!DNL Salesforce] via E-mail (BCC) te registreren**

1. Klik in Marketo Sales op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/salesforce-sync-settings-6.png)

1. Klik onder [!UICONTROL Admin Settings] (of &quot;[!UICONTROL My Account]&quot; als u geen beheerder bent) op **[!UICONTROL Salesforce]** .

   ![](assets/salesforce-sync-settings-7.png)

1. Klik op de tab **[!UICONTROL Sync Settings]** .

   ![](assets/salesforce-sync-settings-8.png)

1. Klik op de tab **[!UICONTROL Email to Salesforce (BCC)]** en klik op **[!UICONTROL Activate]** .

   ![](assets/salesforce-sync-settings-9.png)

Als uw e-mailadres om een of andere reden niet wordt aangemeld, voert u de volgende stappen uit om de functie BCC in uw [!DNL Salesforce] -account te activeren:[!DNL Salesforce]

1. Meld u aan bij uw [!DNL Salesforce] -instantie.
1. Zoek de gebruikersnaam in de rechterbovenhoek en selecteer de vervolgkeuzelijst.
1. Selecteer **[!UICONTROL My Settings]**.
1. Selecteer **[!UICONTROL Email]**.
1. Selecteer **[!UICONTROL My Email to Salesforce]**.
1. Op deze pagina, zult u een gebied geëtiketteerd &quot;[!UICONTROL Email to Salesforce Address]&quot; zien. Als er niets naast het is bevolkt, scrol neer aan &quot;[!UICONTROL My Acceptable Email Addresses].&quot;
1. Voer het e-mailadres of de e-mailadressen in die u voor BCC wilt gebruiken.
1. Klik op **[!UICONTROL Save Changes]**.

**kan Mijn e-mail aan [!DNL Salesforce] in Mijn Montages niet vinden**

Als u Mijn e-mail naar [!DNL Salesforce] niet ziet onder uw instellingen, is het mogelijk dat uw beheerder deze niet heeft ingeschakeld. Dit kan gebeuren als uw team nieuw is voor [!DNL Salesforce] of als uw team het BCC-adres dat [!DNL Salesforce] verschaft, nooit heeft gebruikt.

>[!NOTE]
>
>U hebt beheerdersrechten nodig om dit in te stellen.

1. Klik op **[!UICONTROL Setup]**.
1. Klik op **[!UICONTROL Email Administration]**.
1. Klik op **[!UICONTROL Email to Salesforce]**.
1. Klik op **[!UICONTROL Edit]**.
1. Schakel het selectievakje naast Actief in.
1. Klik op **[!UICONTROL Save]**.

## [!DNL Sales Insight Actions] Taken/herinneringen synchroniseren naar [!DNL Salesforce] Taken {#sync-sales-insight-actions-tasks-reminders-to-salesforce-tasks}

1. Klik in [!DNL Sales Insight Actions] op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/salesforce-sync-settings-10.png)

1. Klik onder [!UICONTROL Admin Settings] (of &quot;[!UICONTROL My Account]&quot; als u geen beheerder bent) op **[!UICONTROL Salesforce]** .

   ![](assets/salesforce-sync-settings-11.png)

1. Klik op de tab **[!UICONTROL Sync Settings]** .

   ![](assets/salesforce-sync-settings-12.png)

1. Klik op de pijl naast Marketo Sales Tasks/Reminders synchroniseren met [!DNL Salesforce] Tasks.

   ![](assets/salesforce-sync-settings-13.png)

1. Kies de gewenste optie (Synchroniseren met [!DNL Salesforce] taken is standaard ingeschakeld).

   ![](assets/salesforce-sync-settings-14.png)

## [!DNL Sales Insight Actions] Taken synchroniseren met [!DNL Salesforce] voor het eerst {#syncing-sales-insight-ations-tasks-with-salesforce-for-the-first-time}

Wanneer u de synchronisatie tussen [!DNL Sales Insight Actions] - en [!DNL Salesforce] -taken voor het eerst inschakelt, importeren wij uw [!DNL Salesforce] -taken. Er worden geen huidige taken overschreven die u hebt in [!DNL Sales Insight Actions] naar [!DNL Salesforce] . Om rommelige en duplicaattaken te voorkomen, zijn de enige taken die worden gesynchroniseerd van [!DNL Sales Insight Actions] in [!DNL Salesforce] , taken die worden gemaakt nadat u [!DNL Sales Insight Actions] hebt gesynchroniseerd met SFDC.

Dit is wat er gebeurt wanneer u [!DNL Sales Insight Actions] - en SFDC-taken synchroniseert:

Zodra u op Opslaan klikt voor het synchroniseren van taken, wordt er gesynchroniseerd. Dit zal aanvankelijk enige tijd duren.

Herinneringen die in de afgelopen 24 uur zijn bijgewerkt of gemaakt, worden van SFDC naar [!DNL Sales Insight Actions] opgehaald. De synchronisatie is gebaseerd op de vervaldatum en al die taken zullen op het achterste eind worden gesynchroniseerd, maar in het Centrum van het Bevel, zult u slechts taken zien die vandaag en morgen verschuldigd zijn.

Als Synchronisatie eerder is ingeschakeld en u verwijdert alle taken in SFDC, worden alle taken die in de afgelopen 15 dagen zijn verwijderd, verwijderd uit Command Center.

Taken worden voortdurend gesynchroniseerd tussen [!DNL Sales Insight Actions] en SFDC zolang de synchronisatie is ingeschakeld.

Na de eerste synchronisatie worden alle taken die u maakt, bewerkt, voltooit of verwijdert in [!DNL Sales Insight Actions] , gesynchroniseerd met de takenlijst in [!DNL Salesforce] . En alles wat in [!DNL Salesforce] is gemaakt, bewerkt, voltooid of verwijderd, werkt uw takenlijst bij in [!DNL Sales Insight Actions] .

Als u deze synchronisatie wilt inschakelen, schakelt u gewoon het synchronisatievak in de [!UICONTROL Settings] -pagina in de webtoepassing in.
