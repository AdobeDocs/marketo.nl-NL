---
solution: Marketo Engage
product: marketo
title: E-mailspamrapport
description: Leer hoe u SpamAssassin kunt gebruiken om uw e-mailinhoud te testen en de kans te zien dat deze als spam wordt gemarkeerd.
level: Beginner, Intermediate
feature: Email Designer
exl-id: 6954850e-2b1a-4bf5-b918-1c54d6926b7e
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---

# E-mailspamrapport {#email-spam-report}

Gebruikend SpamAssassin in Marketo Engage, kunt u uw e-mailinhoud testen en de waarschijnlijkheid zien van ISPs/de leveranciers van de Brievenbus die het als spam merken.

SpamAssassin analyseert uw inhoud en wijst een score toe die op diverse criteria wordt gebaseerd. Hoe lager de score, hoe beter. Het is belangrijk om een lage score te behouden, omdat het verzenden van e-mails met een hoge score een negatief effect kan hebben op de algehele prestaties.

## Heb toegang tot het spamrapport {#access-the-spam-report}

1. In uw e-mail, klik **Simuleer Inhoud**.

   ![](assets/email-spam-report-1.png){width="600" zoomable="yes"}

   >[!NOTE]
   >
   >Als u nog geen testprofiel hebt toegevoegd, moet u dat meteen na Stap 1 doen.

1. Klik het **Spam- rapport** knoop.

   ![](assets/email-spam-report-2.png)

1. Er wordt een spamrapport gegenereerd.

   ![](assets/email-spam-report-3.png){width="600" zoomable="yes"}

1. Controleer de scores en beschrijvingen voor elk item.

   >[!IMPORTANT]
   >
   >Als de totale score hoger is dan 5, kan uw e-mail door de ontvanger worden geblokkeerd, of als spam bij levering worden gemerkt.

1. Als u de score als te hoog beschouwt, geef uw inhoud in E-mail Designer uit die op de bevindingen van het rapport wordt gebaseerd en stel dan het **Spam- rapport** opnieuw in werking.

   ![](assets/email-spam-report-4.png){width="800" zoomable="yes"}

Wanneer de score naar je smaak is, kan deze worden verzonden.

![](assets/email-spam-report-5.png){width="800" zoomable="yes"}

>[!NOTE]
>
>De score van spam wordt afgeleid via SpamAssassin, en **de regels zijn niet bezeten door Adobe**. Meer details over deze regels kunnen in de [&#x200B; documentatie SpamAssassin &#x200B;](https://spamassassin.apache.org/#_blank){target="_blank"} worden gevonden. Een volledige lijst van fouten [&#x200B; kan hier &#x200B;](https://spamassassin.apache.org/old/tests_3_0_x.html){target="_blank"} worden gezien.
