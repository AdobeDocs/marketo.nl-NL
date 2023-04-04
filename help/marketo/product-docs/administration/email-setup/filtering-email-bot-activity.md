---
description: Filteren van e-mailboxactiviteiten - Marketo-documenten - Productdocumentatie
title: Activiteit e-mailvak filteren
exl-id: 70c97159-72bf-46e5-b29b-247615d0fa80
source-git-commit: 792db38ec0891d4a6de5a8d0bd746bd7bb429edb
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Activiteit e-mailvak filteren {#filtering-email-bot-activity}

Soms kan e-mailactiviteit je e-mail abusievelijk opblazen en op gegevens klikken. Voer de onderstaande stappen uit om dat te verhelpen.

We gebruiken drie verschillende methoden om beide activiteiten te bevestigen:

* Afstemmen met [Interactieve lijst van adverteerders van het Bureau](https://www.iab.com/guidelines/iab-abc-international-spiders-bots-list/){target="_blank"}: De activiteiten die met om het even wat op IAB UA/IP (het adres van de Agent/IP van de Gebruiker) aanpassen zullen als bots worden gemerkt.
* Overeenkomst met nabijheidspatroon: Wanneer meer dan twee activiteiten tegelijkertijd plaatsvinden (in minder dan een seconde), worden ze geïdentificeerd als bots. Kenmerken die in aanmerking worden genomen tijdens de vergelijking zijn:
   * ID lead (moet hetzelfde zijn)
   * E-mailmiddel (moet hetzelfde zijn)
   * Klik op Koppelen of e-mail openen
   * Tijdverschil (zou minder dan één seconde moeten zijn)

Bij klikken op een e-mailkoppeling en e-mail openen worden nieuwe kenmerken gevuld met de onderstaande waarden:

* Activiteiten die als bots worden geïdentificeerd, hebben &quot;Bot Activity&quot; als &quot;True&quot; en &quot;Bot Activity Pattern&quot; als het geïdentificeerde patroon/de geïdentificeerde methode
* Activiteiten die niet als bots worden aangeduid, hebben &quot;Bot Activity&quot; als &quot;False&quot; en &quot;Bot Activity Pattern&quot; als &quot;N.v.t.&quot;
* Activiteiten die zijn uitgevoerd voordat we deze kenmerken hebben geïntroduceerd, hebben &quot;Bot Activity&quot; als &quot; (leeg) en &quot;Bot Activity Pattern&quot; als &quot; &quot; (leeg)

1. Klikken **Beheer**.

   ![](assets/filtering-email-bot-activity-1.png)

1. Klikken **E-mail**.

   ![](assets/filtering-email-bot-activity-2.png)

1. Klik op de knop **Bot-activiteit** tab.

   ![](assets/filtering-email-bot-activity-3.png)

1. Kies **Combineren met IAB-lijst**, **Afstemmen met nabijheidspatroon**, of beide. Kies of beide activiteiten moeten worden geregistreerd _of_ filterbotactiviteit.

   ![](assets/filtering-email-bot-activity-4.png)

>[!NOTE]
>
>Als u Bodyactiviteit filteren kiest, wordt er mogelijk een druppel in het e-mailbericht geopend en wordt op deze knop geklikt omdat de foutactiviteiten worden weggevaagd.

**OPTIONELE STAP**: U schakelt deze functie uit door gewoon de schuifregelaar(s) uit te schakelen. Als u deze optie uitschakelt, worden de gegevens niet opnieuw ingesteld.

>[!TIP]
>
>Gebruik beide activiteitsgegevens in slimme lijsten via Booleaanse waarden (ja/nee) en Activiteit (beide) in de filters &quot;Klikte koppeling in e-mail&quot; en &quot;E-mail openen&quot;, en klik op Koppeling in e-mail en &quot;E-mail openen&quot;.

## IP Lijst van gewezen personen {#ip-blocklist}

Wij hebben een lijst van IP adressen gecompileerd die voor het produceren van miljoenen valse overeenkomsten verantwoordelijk zijn, aangezien zulk engagement die van om het even welke volgende IPs wordt ontvangen automatisch wordt gefilterd uit en niet toegevoegd aan uw Instantie van Marketo Engage. Dit kan leiden tot minder e-mail openen, klikken en andere gerelateerde activiteiten. De onderstaande lijst kan periodiek worden bijgewerkt.

* 209.222.82.126
* 209.222.82.127
* 209.222.82.128
* 209.222.82.129
* 209.222.82.138
* 209.222.82.139
* 209.222.82.140
* 209.222.82.141
* 209.222.82.228
* 209.222.82.229
* 209.222.82.230
* 209.222.82.231
* 209.222.82.232
* 209.222.82.233
* 209.222.82.234
* 209.222.82.235

>[!NOTE]
>
>Wij analyseren en onderzoeken nauwgezet elk IP adres alvorens het aan deze lijst toe te voegen, ervoor zorgen slechts de meest kritieke en schadelijke IPs wordt geblokkeerd.
