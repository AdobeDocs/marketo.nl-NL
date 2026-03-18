---
unique-page-id: 14352484
description: Hulp bij het herstellen van de fout We kunnen uw aanvraag niet verifiëren wanneer u verbinding maakt met Sales Connect op Salesforce. Problemen met verificatie oplossen.
title: '"We konden uw aanvraag niet verifiëren" bij verbinding met Salesforce oplossen'
exl-id: ddd49064-f584-4490-8d45-29cf61ed3ebe
feature: Marketo Sales Connect
source-git-commit: 15427eacd2fc42a02f6a4c59d9102bacba02e57b
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 3%

---

# &quot;We konden uw verzoek niet verifiëren&quot; herstellen bij verbinding met [!DNL Salesforce] {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Als u het foutbericht &quot;Uw verzoek kan niet worden geverifieerd&quot; ontvangt wanneer u probeert een verbinding tot stand te brengen tussen [!DNL Sales Connect] en [!DNL Salesforce] , is het mogelijk dat de toegang tot de API van [!DNL Salesforce] wordt beperkt. Neem contact op met uw [!DNL Salesforce] -beheerder om te controleren of de volgende functies aanwezig zijn.

## API inschakelen in gebruikersmachtigingen {#enable-api-in-user-permissions}

1. Een [!DNL Salesforce] Admin-aanmelding bij SFDC laten uitvoeren.
1. Selecteer **[!UICONTROL Setup]**.
1. Selecteer **[!UICONTROL Manage Users]**.
1. Selecteer **[!UICONTROL Profiles]**.
1. Zoek het profiel onder de ToutApp-gebruikers en klik op **[!UICONTROL Edit]** .
1. Schuif omlaag naar **[!UICONTROL Administrative Permissions]** en controleer of **[!UICONTROL API Enabled]** is ingeschakeld.

## Controleren of [!DNL Salesforce] blokkeert [!DNL Sales Connect] van verbinding {#check-if-salesforce-is-blocking-sales-connect-from-connecting}

1. U moet zich bij [!DNL Salesforce] Admin aanmelden bij SFDC.
1. Selecteer **[!UICONTROL Setup]**.
1. Selecteer **[!UICONTROL Manage Apps]**.
1. Selecteer **[!UICONTROL Connected Apps OAuth Usage]**.
1. Zorg ervoor dat [!DNL Sales Connect] &quot;[!UICONTROL Block]&quot;naast het toont. Als &quot;[!UICONTROL Unblock]&quot; wordt weergegeven, klikt u op de knop om de toegang van [!DNL Sales Connect] tot [!DNL Salesforce] te ontgrendelen.
