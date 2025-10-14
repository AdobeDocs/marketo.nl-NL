---
description: Logboekregistratie voor antwoorden - Marketo Docs - Productdocumentatie
title: Logboekregistratie beantwoorden
hide: true
hidefromtoc: true
exl-id: a89e8212-83cb-4987-abc9-76c5fd74c152
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# Logboekregistratie beantwoorden {#reply-logging}

Met Handelingen van Insight voor verkoopdoeleinden kunt u de antwoorden van je vooruitzichten automatisch laten registreren op [!DNL Salesforce] . De structuur waarmee u dit kunt doen, is gebaseerd op het bijhouden van onze e-mailantwoorden. Als we het antwoord van een vooruitzicht kunnen volgen, kunnen we dat antwoord op [!DNL Salesforce] registreren.

## Vereisten {#requirements}

* E-mails via API-registratie moeten worden geregistreerd
* Moet [&#x200B; een antwoord &#x200B;](/help/marketo/product-docs/marketo-sales-insight/actions/send-a-sales-email/email-tracking-overview.md#how-reply-tracking-works) kunnen volgen
* Moet zijn verbonden met [!DNL Salesforce]
* Moet [!DNL Salesforce] [&#x200B; API vraag &#x200B;](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) beschikbaar hebben

## Logboekregistratie voor reactie inschakelen {#enable-reply-logging}

1. Als u antwoordregistratie wilt inschakelen, gaat u naar de pagina met [!DNL Salesforce] instellingen. Zodra API het registreren wordt gecontroleerd zult u de optie zien om _Reacties van het Logboek_ te controleren.

   >[!NOTE]
   >
   >Voor het registreren van antwoorden gelden dezelfde regels als voor het registreren van e-mails die worden verzonden. Dit omvat de manier waarop e-mails worden geregistreerd; voor leads en contactpersonen; wanneer er een dubbele record is; als er geen overeenkomende records worden gevonden.

## Type instellen op Reageren in [!DNL Salesforce] {#setting-type-to-reply-in-salesforce}

Het is belangrijk dat u zinvolle gegevens uit uw [!DNL Salesforce] -rapporten ophaalt. Doordat het veld Type kan worden ingevuld als &#39;Reageren&#39;, kunt u die gegevens via uw rapporten ophalen. Werk samen met uw `[!DNL Salesforce] admin` voor deze setup.

1. Ga naar **[!UICONTROL Setup]** > **[!UICONTROL Customize]** > **[!UICONTROL Activities]** > **[!UICONTROL Task Fields]** .
1. Klik op **[!UICONTROL Type]**.
1. Klik onder [!UICONTROL Task Type Picklist Values] op **[!UICONTROL New]** .
1. Typ &quot;Reageren&quot; in het lege vak. Zorg ervoor dat u de letter &#39;R&#39; gebruikt en klik op **[!UICONTROL Save]** .

   >[!NOTE]
   >
   >U hoeft geen standaard te selecteren in de keuzelijst Type. [!DNL Sales Insight Actions] controleert of dit type activiteit beschikbaar is in uw [!DNL Salesforce] -instantie en vult het taakveld op de binnenkomende activiteiten dienovereenkomstig in.
