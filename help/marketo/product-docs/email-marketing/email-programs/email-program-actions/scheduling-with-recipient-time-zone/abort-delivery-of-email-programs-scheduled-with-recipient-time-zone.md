---
unique-page-id: 13795727
description: Aflevering van e-mailprogramma's die zijn gepland met de tijdzone voor ontvangers - Marketo Docs - Productdocumentatie
title: Aflevering van e-mailprogramma's afbreken die zijn gepland met de tijdzone van de ontvanger
exl-id: e69afa4a-32fb-4791-a9b6-683d64d610d6
feature: Email Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---

# Aflevering van e-mailprogramma&#39;s afbreken die zijn gepland met de tijdzone van de ontvanger {#abort-delivery-of-email-programs-scheduled-with-recipient-time-zone}

In noodgevallen kunt u de levering afbreken van een e-mailprogramma dat al is gestart met het uitvoeren van de tijdzone voor ontvangers ingeschakeld.

Aangezien e-mailprogramma&#39;s die zijn gepland met de tijdzone van de ontvanger maximaal 24 uur kunnen duren, wordt elke volgende verzending na dat punt geannuleerd wanneer de levering van het programma wordt afgebroken.

1. Selecteer het e-mailprogramma dat u wilt annuleren en klik op **Aflevering afbreken** onder de goedkeuringstegel in het bedieningspaneel.

   ![](assets/ptz-abortdelivery.png)

1. Bevestig dat u de levering wilt annuleren door op **Afbreken**.

   ![](assets/image2018-2-23-11-3a20-3a27.png)

1. Na annulering wordt **Resultaten** Het raster van uw e-mailprogramma ziet er ongeveer zo uit als hieronder. Alle volgende verzendingen worden geannuleerd en worden weergegeven als &quot;Verzonden via e-mail&quot; in het dialoogvenster **Type activiteit** kolom.

   ![](assets/image2018-2-23-11-3a22-3a11.png)

   >[!NOTE]
   >
   >Geannuleerde e-mails worden **niet** tonen als een zachte stuit *tot* het tijdstip waarop zij oorspronkelijk in hun respectieve tijdzones moesten worden geleverd. Tot dat moment worden ze nog steeds weergegeven als &quot;E-mail verzenden&quot;.

1. Vanuit het raster kunt u op een e-mail klikken om de activiteitengegevens weer te geven. Voor geannuleerde verzendingen ziet het pop-upvenster Details er als volgt uit:

   ![](assets/image2018-2-23-11-3a30-3a46.png)

>[!MORELIKETHIS]
>
>* [Tijdzone van ontvanger](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [E-mailprogramma&#39;s met tijdzone voor ontvangers plannen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
