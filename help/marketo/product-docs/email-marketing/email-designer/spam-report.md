---
solution: Marketo Engage
product: marketo
title: Spam Assassin
description: TEKST KOMT HIER
level: Beginner, Intermediate
feature: Email Editor
hide: true
hidefromtoc: true
source-git-commit: 0157bc64444151a43bf464158d508e84d75b3427
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# Spam Assassin {#spam-assassin}

Gebruikend SpamAssassin in Marketo Engage, kunt u uw e-mailinhoud testen en de waarschijnlijkheid zien van ISPs/de leveranciers van de Brievenbus die het als spam merken.

SpamAssassin analyseert uw inhoud en wijst een score toe die op diverse criteria wordt gebaseerd. Hoe lager de score, hoe beter. Het is belangrijk om een lage score te behouden, omdat het verzenden van e-mails met een hoge score een negatief effect kan hebben op de algehele prestaties.

## Heb toegang tot het Spam- rapport {#access-the-spam-report}

1. Van het Simuleren scherm, klik het **Spam- rapport** knoop.

SCREENSHOT

1. Er wordt een spamrapport gegenereerd.

SCREENSHOT

1. Controleer de scores en beschrijvingen voor elk item.

>[!IMPORTANT]
>
>Als de totale score hoger is dan 5, kan je e-mail worden geblokkeerd of gemarkeerd als spam bij levering.

1. Als u de score te hoog vindt, bewerkt u de inhoud in de e-mail-Designer en voert u het Spam-rapport opnieuw uit totdat de score naar wens is.

SCREENSHOT

>[!NOTE]
>
>Spam score wordt afgeleid via SpamAssassin, en de regels zijn niet het eigendom van Adobe. Meer details over deze regels kunnen in de [ documentatie SpamAssassin ](https://spamassassin.apache.org/#_blank) worden gevonden. Een volledige lijst van fouten [ kan hier ](https://spamassassin.apache.org/old/tests_3_0_x.html?utm_source=chatgpt.com) worden gezien.
