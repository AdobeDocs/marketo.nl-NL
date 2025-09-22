---
description: Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce - Marketo Docs - de Documentatie van het Product
title: Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce
exl-id: cfe71388-282b-45e5-a817-45a951f613bc
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '461'
ht-degree: 0%

---

# Redenen van de Vraag van het logboek en de Resultaten van de Vraag van Salesforce {#log-call-reasons-and-call-outcomes-to-salesforce}

Als u vraagresultaten en vraagredenen aan Salesforce voor het melden of zicht doeleinden wilt registreren, kunt u een gebied van de douaneactiviteit voor elk tot stand brengen. Elk veld moet een specifieke API-naam gebruiken (in Salesforce bekend als &quot;veldnaam&quot;).

* De Naam van het Gebied van Resultaten van de vraag: mktosales_call_result
* De Naam van het Gebied van de Redenen van de vraag: mktosales_call_reason

Als u deze velden wilt gebruiken, moet u het veld eerst maken als een veld voor aangepaste activiteit. Als u deze zichtbaar wilt maken voor gebruikers, moet u deze toevoegen aan de pagina-indeling van het taakobject.

## Salesforce Classic {#salesforce-classic}

### Aangepast activiteitsveld maken in Salesforce Classic  {#create-custom-activity-field-in-salesforce-classic}

1. In Salesforce, klik **Opstelling**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-1.png)

1. Typ &quot;Activiteiten&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-2.png)

1. Klik {de Gebieden van de Douane van de Activiteit 0} **.**

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-3.png)

1. Klik **Nieuw**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-4.png)

1. Selecteer het gegevenstype &quot;Tekst&quot;en klik **daarna**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-5.png)

1. Geef het aangepaste veld de veldnaam zoals hierboven gedefinieerd. De veldlengte mag niet langer zijn dan 255 tekens. Het Etiket van het gebied zal het gebied zichtbaar aan uw verkoopteam zijn en kan worden aangepast om aan de behoeften van uw team te voldoen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-6.png)

1. De overige instellingen zijn optioneel. Zodra u de configuratie hebt voltooid, klik **daarna**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-7.png)

1. Selecteer de gewenste gebied-vlakke veiligheidsmontages voor dit gebied en klik **daarna** (het beeld hieronder is slechts een voorbeeld).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-8.png)

   >[!NOTE]
   >
   >Zorg ervoor dat het aangepaste veld zichtbaar is voor het profiel dat de gebruikers van Verkoopacties gebruiken, samen met alle andere acties die u wilt weergeven.

1. Selecteer welke paginalay-outs u het gebied wilt dat aan wordt toegevoegd en **klikt sparen** (naar keuze, kunt u **klikken sparen &amp; Nieuw** en het proces voor het gebied van de Reden van de Vraag herhalen).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-9.png)

### Aangepast activiteitenveld toevoegen aan taakpaginalay-out in Salesforce Classic {#add-custom-activity-field-to-task-page-layout-in-salesforce-classic}

>[!NOTE]
>
>U hoeft deze stappen alleen uit te voeren als u in Stap 9 hierboven de gewenste paginalay-out niet hebt geselecteerd.

1. In Salesforce, klik **Opstelling**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-10.png)

1. Typ &quot;Taak&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-11.png)

1. Klik **Lay-outs van de Pagina van de Taak**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-12.png)

1. Klik **uitgeven** naast de lay-out van de taakpagina u dit gebied aan wilt toevoegen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-13.png)

1. Sleep het veld naar het gewenste gedeelte van de taakpaginalay-out.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-14.png)

1. Klik **sparen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-15.png)

## Salesforce Lightning {#salesforce-lightning}

### Veld voor aangepaste activiteit maken in Salesforce Lightning {#create-custom-activity-field-in-salesforce-lightning}

1. In Salesforce, klik op het tandwielpictogram op het hoogste recht en selecteer **Opstelling**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-16.png)

1. Klik **Manager van Objecten**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-17.png)

1. Typ &quot;Activiteit&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-18.png)

1. Klik het **etiket van de Activiteit**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-19.png)

1. Klik **Gebieden &amp; Verhoudingen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-20.png)

1. Klik **Nieuw**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-21.png)

### Aangepast activiteitenveld toevoegen aan taakpaginalayout in Salesforce Lightning {#add-custom-activity-field-to-task-page-layout-in-salesforce-lightning}

1. In Salesforce, klik op het tandwielpictogram op het hoogste recht en selecteer **Opstelling**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-22.png)

1. Klik **Manager van Objecten**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-23.png)

1. Typ &quot;Taak&quot; in het vak Snel zoeken.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-24.png)

1. Klik het **etiket van de Taak**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-25.png)

1. Klik **Lay-outs van de Pagina**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-26.png)

1. Klik op de taakpaginalay-out waaraan u dit veld wilt toevoegen.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-27.png)

1. Sleep het veld naar het gewenste gedeelte van de taakpaginalay-out.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-28.png)

1. Klik **sparen**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-29.png)

>[!MORELIKETHIS]
>
>* [ Resultaten van de Vraag ](/help/marketo/product-docs/marketo-sales-insight/actions/phone/call-outcomes.md)
>* [ Redenen van de Vraag ](/help/marketo/product-docs/marketo-sales-insight/actions/phone/call-reasons.md)
