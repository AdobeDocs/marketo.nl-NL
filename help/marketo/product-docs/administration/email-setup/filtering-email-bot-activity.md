---
description: Filteren van e-mailboxactiviteiten - Marketo-documenten - Productdocumentatie
title: Activiteit e-mailvak filteren
exl-id: 70c97159-72bf-46e5-b29b-247615d0fa80
source-git-commit: 2ef4b0b2a541c8b6a67bd654fda45956601661bd
workflow-type: tm+mt
source-wordcount: '317'
ht-degree: 0%

---

# Activiteit e-mailvak filteren {#filtering-email-bot-activity}

Soms kan e-mailactiviteit je e-mail abusievelijk opblazen en op gegevens klikken. Voer de onderstaande stappen uit om dat te verhelpen.

We gebruiken drie verschillende methoden om beide activiteiten te bevestigen:

* Afstemmen met [Interactive Adverting Bureau bot list](https://www.iab.com/guidelines/iab-abc-international-spiders-bots-list/){target=&quot;_blank&quot;}: De activiteiten die met om het even wat op IAB UA/IP (het adres van de Agent/IP van de Gebruiker) aanpassen zullen als bots worden gemerkt.
* Overeenkomst met verborgen verbinding UA/IPs: We voegen een verborgen koppeling toe aan alle e-mails en leggen UA/IP-klikken vast die van hen komen. De activiteiten die met deze UA/IPs aanpassen zullen als bots worden gemerkt.
* Overeenkomst met nabijheidspatroon: Wanneer meer dan twee activiteiten tezelfdertijd (onder twee seconden) plaatsvinden, worden zij geïdentificeerd als bots.

Bij klikken op e-mailkoppelingen en e-mailopenen worden nieuwe kenmerken gevuld met de volgende waarden:

* Activiteiten die als bots worden geïdentificeerd, hebben &quot;Bot Activity&quot; als &quot;True&quot; en &quot;Bot Activity Pattern&quot; als het geïdentificeerde patroon/de geïdentificeerde methode
* Activiteiten die niet als bots worden aangeduid, hebben &quot;Bot Activity&quot; als &quot;False&quot; en &quot;Bot Activity Pattern&quot; als &quot;N.v.t.&quot;
* Activiteiten die zijn uitgevoerd voordat we deze kenmerken hebben geïntroduceerd, hebben &quot;Bot Activity&quot; als &quot; (leeg) en &quot;Bot Activity Pattern&quot; als &quot; &quot; (leeg)

1. Klikken **Beheer**.

   ![](assets/filtering-email-bot-activity-1.png)

1. Klikken **E-mail**.

   ![](assets/filtering-email-bot-activity-2.png)

1. Klik op de knop **Bot-activiteit** tab.

   ![](assets/filtering-email-bot-activity-3.png)

1. Klik op de knop **Beide activiteitsidentificatie inschakelen** te activeren schuifregelaar.

   ![](assets/filtering-email-bot-activity-4.png)

>[!NOTE]
>
>U kunt afzonderlijk kiezen of u beide activiteiten wilt laten registreren. Als u dit niet doet, wordt mogelijk een druppel in het e-mailbericht geopend en worden de onjuiste nummers uitgefilterd.

**OPTIONELE STAP**: U schakelt de functie uit door gewoon de schuifregelaar uit te schakelen. Als u deze optie uitschakelt, worden de gegevens wel **niet** opnieuw instellen.

>[!TIP]
>
>Gebruik beide activiteitsgegevens in slimme lijsten via Booleaanse waarden (ja/nee) en Activiteit (beide) in de filters &quot;Klikte koppeling in e-mail&quot; en &quot;E-mail openen&quot;, en klik op Koppeling in e-mail en &quot;E-mail openen&quot;.
