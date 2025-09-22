---
unique-page-id: 7504923
description: Plaats  [!DNL Google AdWords]  Omzettingen in het Model van de Opbrengst met een Rekening van de Manager - de Documenten van Marketo - de Documentatie van het Product
title: Plaats  [!DNL Google AdWords]  Omzettingen in het Model van Inkomsten met een Rekening van de Manager
exl-id: 8c9f50cf-0a8b-4f9a-a0bd-bb57eeac24cf
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '374'
ht-degree: 1%

---

# Conversies [!DNL Google AdWords] in het inkomstenmodel instellen met een beheerdersaccount {#set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account}

Koppel uw [!DNL Google AdWords] -account aan Marketo om automatisch offline conversiegegevens te uploaden van Marketo naar [!DNL Google AdWords] . Dan, van [!DNL AdWords] UI, zult u gemakkelijk kunnen zien welke kliks in gekwalificeerde lood, kansen en nieuwe klanten (of welke opbrengststadia resulteerden u) wilt volgen nadat u [ douanekolommen ](https://support.google.com/adwords/answer/3073556) in [!DNL AdWords] toevoegt.

Als u veelvoudige [!DNL Google Adwords] rekeningen hebt, kunt u de Rekening van de Manager van de a [[!DNL Google AdWords]  gebruiken ](https://www.google.com/adwords/manager-accounts/) (vroeger gekend als Mijn Centrum van de Cliënt) om hen met Marketo te integreren.

U kunt [!DNL AdWords] offline conversies toewijzen aan een of meer fasen in een omzettingsmodel. Er zijn twee manieren:

* Werkgebied, actie
* [!DNL AdWords] Toewijzing

>[!PREREQUISITES]
>
>[ voeg  [!DNL Google AdWords]  als Dienst van het Lanceerpunt met een Rekening van de Manager toe ](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md)

## Werkgebiedactie gebruiken {#use-stage-action}

Wijs een [!DNL AdWords] -conversie toe onder werkgebiedhandelingen.

1. Selecteer de stap die u wilt toewijzen aan een [!DNL AdWords] -conversie.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Selecteer **[!UICONTROL Stage Actions]** onder de vervolgkeuzelijst **[!UICONTROL Set AdWords Conversion]** .

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Stel een **[!DNL AdWords]conversie** in.

   >[!NOTE]
   >
   >Voor elke onderliggende account kan een andere [!DNL AdWords] -conversie worden geselecteerd.

   ![](assets/image2015-3-27-17-3a16-3a37.png)

   Tip: als u geen conversies van het type [!DNL AdWords] hebt, klikt u op **[!UICONTROL +New Conversion]** .

   ![](assets/image2015-3-27-17-3a18-3a58.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-3-27-17-3a21-3a15.png)

1. Nadat u alle omzettingen van [!DNL AdWords] in inkomstenstadia in kaart hebt gebracht, ga terug naar de summiere pagina. Selecteer **[!UICONTROL Model Actions]** en kies **[!UICONTROL Approve Stages]** .

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## Pro-tip: voeg een nieuwe omzetting toe {#pro-tip-add-a-new-conversion}

Pro tip! Er kan een nieuwe [!DNL AdWords] offline conversie worden gemaakt vanuit Marketo.

>[!CAUTION]
>
>Voor nieuwe omzettingen die zijn gemaakt met Marketo is de instelling &quot;optimalisatie&quot; ingeschakeld. Dit betekent dat biedstrategieën van [!DNL AdWords] zijn toegestaan om uw biedingen voor deze conversies te optimaliseren. U kunt deze instelling wijzigen vanuit uw [!DNL AdWords] -account.

1. Selecteer **[!UICONTROL Stage Actions]** onder de vervolgkeuzelijst **[!UICONTROL Set AdWords Conversion]** .

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Selecteer **[!UICONTROL New Conversion]**.

   ![](assets/image2015-3-27-17-3a23-3a13.png)

1. Ga de Naam van de a **Omzetting** in. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-3-27-17-3a24-3a49.png)

   Uitstekend! Deze nieuwe conversie wordt weergegeven in uw [!DNL AdWords] -account.

## Toewijzing [!DNL AdWords] gebruiken {#use-adwords-mapping}

U kunt al uw modelfasen aan uw [!DNL AdWords] Omzetting in één plaats associëren gebruikend [!DNL AdWords] Toewijzingen.

1. Selecteer **[!UICONTROL Edit AdWords Mappings]**.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. Selecteer de gewenste **[!DNL AdWords]Rekening** en gewenste **[!DNL AdWords]Omzetting** voor elk stadium dat u wilt volgen.

   ![](assets/image2015-3-27-17-3a30-3a15.png)

1. Klik op **[!UICONTROL Save]** als u de stadia hebt toegewezen.

   ![](assets/image2015-3-27-17-3a30-3a48.png)

1. Nadat u alle omzettingen van [!DNL AdWords] in inkomstenstadia in kaart hebt gebracht, ga terug naar de summiere pagina. Selecteer **[!UICONTROL Model Actions]** en kies **[!UICONTROL Approve Stages]** .

   ![](assets/image2015-2-27-12-3a20-3a20.png)

Als u de gegevens van de offline conversie wilt weergeven, moet u zich aanmelden bij uw [!DNL AdWords] -account. Wij adviseren u hun [ eigenschap van de Kolommen van de Douane ](https://support.google.com/adwords/answer/3073556) gebruikt om de kolommen van de omzettelling voor elke off-line omzetting tot stand te brengen u uit Marketo invoert.
