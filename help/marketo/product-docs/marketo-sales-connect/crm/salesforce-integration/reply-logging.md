---
unique-page-id: 14352480
description: Logboekregistratie voor reacties (SFDC) - Marketo Docs - Productdocumentatie
title: Logboekregistratie voor reacties (SFDC)
exl-id: 11f84157-55b7-42a7-81d0-f5848adbb9f4
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---

# Logboekregistratie voor reacties (SFDC) {#reply-logging-sfdc}

Met Sales Connect kunt u de antwoorden van uw vooruitzichten automatisch laten registreren bij Salesforce. De structuur waarmee u dit kunt doen, is gebaseerd op het bijhouden van onze e-mailantwoorden. Als we het antwoord van een vooruitzicht kunnen volgen, kunnen we dat antwoord aan Salesforce vastleggen.

## Vereisten {#requirements}

* E-mails via API-registratie moeten worden geregistreerd
* Moet [ een antwoord ](/help/marketo/product-docs/marketo-sales-connect/email/common-tracking-questions/how-reply-tracking-works.md) kunnen volgen
* Moet zijn verbonden met [!DNL Salesforce]
* Moet [!DNL Salesforce] [ API vraag ](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) beschikbaar hebben

## Logboekregistratie voor reactie inschakelen {#enable-reply-logging}

1. Als u antwoordregistratie wilt inschakelen, gaat u naar de pagina met [!DNL Salesforce] instellingen. Zodra API het registreren wordt gecontroleerd zult u de optie zien om _Reacties van het Logboek_ te controleren.

   >[!NOTE]
   >
   >Voor het registreren van antwoorden gelden dezelfde regels als voor het registreren van e-mails die worden verzonden. Dit omvat de manier waarop e-mails worden geregistreerd; voor leads en contactpersonen; wanneer er een dubbele record is; als er geen overeenkomende records worden gevonden.

## Type instellen op Reageren in [!DNL Salesforce] {#setting-type-to-reply-in-salesforce}

Het is belangrijk dat u zinvolle gegevens uit uw [!DNL Salesforce] -rapporten ophaalt. Doordat het veld Type kan worden ingevuld als &#39;Reageren&#39;, kunt u die gegevens via uw rapporten ophalen. Werk samen met uw `[!DNL Salesforce] admin` voor deze setup.

1. Ga naar **[!UICONTROL Setup]** > **[!UICONTROL Customize]** > **[!UICONTROL Activities]** > **[!UICONTROL Task Fields]** .
1. Klik op **[!UICONTROL Type]**.
1. Klik onder Picklist voor taaktype op **[!UICONTROL New]** .
1. Typ &quot;Reageren&quot; in het lege vak. Zorg ervoor dat u de letter &#39;R&#39; gebruikt en klik op **[!UICONTROL Save]** .

   >[!NOTE]
   >
   >U hoeft geen standaard te selecteren in de keuzelijst Type. [!DNL Sales Connect] controleert of dit type activiteit beschikbaar is in uw [!DNL Salesforce] -instantie en vult het taakveld op de binnenkomende activiteiten dienovereenkomstig in.
