---
unique-page-id: 9437340
description: RTP implementeren met Tealium Tag Manager - Marketo Docs - Productdocumentatie
title: RTP implementeren met Tealium Tag Manager
exl-id: 7a099184-625c-46b2-a741-3bcdad0a238e
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---

# RTP implementeren met Tealium Tag Manager {#implementing-rtp-using-tealium-tag-manager}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren.

1. Meld u aan bij uw account voor Tagbeheer voor Tealium.

1. Navigeer naar het tabblad Labels en voeg de aangepaste containertag voor thealium toe, die zich onder het tabblad Misc van de Marketplace bevindt.

1. Typ in het veld Titel de waarde **Marketo RTP** en klik op **Voltooien**.

1. Sla uw wijzigingen op.

   >[!NOTE]
   >
   >De nieuwe container hoeft nog niet te worden gepubliceerd.

1. Nadat het profiel is opgeslagen, klikt u op uw naam/e-mailadres in de rechterbovenhoek van de iQ-console van Tealium.

1. Klik in het menu Beheer op **Sjablonen beheren** onder Accountbeheerder.

1. Selecteren **Aangepaste container voor thealium: Marketo RTP** in de vervolgkeuzelijst om de tagsjabloon te openen.

1. Meld u aan bij uw RTP-account.

1. Ga naar Accountinstellingen.

   >[!NOTE]
   >
   >Ga naar stap 11 als u al een JavaScript-tag hebt ontvangen van Support.

1. Zoek onder Domein het relevante domein en klik op **Label genereren**.

1. Kopieer de RTP JavaScript-tag en plak deze tussen Start tagbibliotheekcode en End-tagbibliotheekcode in de sjabloon Traagheidsprofiel.

   >[!NOTE]
   >
   >**Belangrijke stappen**
   >
   >Verwijder de `<!-- RTP tag -->` en `<!-- End of RTP tag -->` -tags uit de code die u in dit bestand plaatst.
   >
   >Alle `<script type='text/javascript'>` en `</script>` -tags uit de code die u in dit bestand plaatst.

1. **Klik op Profielsjabloon opslaan** en publiceert u uw nieuwe profiel.
