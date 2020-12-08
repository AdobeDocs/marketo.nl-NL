---
unique-page-id: 9437340
description: Implementatie van RTP met behulp van Tagbeheer voor thealium - Marketo Docs - Productdocumentatie
title: RTP implementeren met Tealium Tag Manager
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
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
1. Klik in het menu Beheer op **Sjablonen** beheren onder Accountbeheer.
1. Aangepaste **container voor thealium selecteren: Marketo RTP** van de drop-down lijst om het malplaatje van de Markering te openen.
1. Meld u aan bij uw RTP-account.
1. Ga naar Accountinstellingen.

   >[!NOTE]
   >
   >Ga naar stap 11 als u al een JavaScript-tag hebt ontvangen van Support.

1. Zoek onder Domein het relevante domein en klik op Tag **** genereren.
1. Kopieer de RTP JavaScript-tag en plak deze tussen Start tagbibliotheekcode en End-tagbibliotheekcode in de sjabloon Traagheidsprofiel.

   >[!NOTE]
   >
   >**Belangrijke stappen**
   >
   >Verwijder de `<!-- RTP tag -->` tags en `<!-- End of RTP tag -->` tags uit de code die u in dit bestand plaatst.
   >
   >Verwijder alle `<script type='text/javascript'>` en `</script>` -tags uit de code die u in dit bestand plaatst.

1. **Klik op Profielsjabloon** opslaan en publiceer uw nieuwe profiel.

