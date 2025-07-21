---
unique-page-id: 13795727
description: Aflevering van e-mailprogramma's die zijn gepland met de tijdzone voor ontvangers - Marketo Docs - Productdocumentatie
title: Aflevering van e-mailprogramma's afbreken die met de tijdzone van de ontvanger zijn gepland
exl-id: e69afa4a-32fb-4791-a9b6-683d64d610d6
feature: Email Programs
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---

# Aflevering van e-mailprogramma&#39;s afbreken die met de tijdzone van de ontvanger zijn gepland {#abort-delivery-of-email-programs-scheduled-with-recipient-time-zone}

In noodgevallen kunt u de levering afbreken van een e-mailprogramma dat al is gestart met het uitvoeren van de tijdzone voor ontvangers ingeschakeld.

Aangezien e-mailprogramma&#39;s die zijn gepland met de tijdzone van de ontvanger maximaal 24 uur kunnen duren, wordt elke volgende verzending na dat punt geannuleerd wanneer de levering van het programma wordt afgebroken.

1. Selecteer het e-mailprogramma dat u wilt annuleren en klik op **[!UICONTROL Abort Delivery]** onder de tegel [!UICONTROL Approval] in het deelvenster Beheer.

   ![](assets/ptz-abortdelivery.png)

1. Bevestig dat u de levering wilt annuleren door op **[!UICONTROL Abort]** te klikken.

   ![](assets/image2018-2-23-11-3a20-3a27.png)

1. Na annulering ziet het raster **[!UICONTROL Results]** van uw e-mailprogramma er ongeveer zo uit als hieronder. Alle volgende verzendingen worden geannuleerd en worden in de kolom **[!UICONTROL Activity Type]** weergegeven als &quot;Verzonden via e-mail&quot;.

   ![](assets/image2018-2-23-11-3a22-3a11.png)

   >[!NOTE]
   >
   >Geannuleerde e-mails zullen **niet** verschijnen als zachte stuit *tot* de tijd zij oorspronkelijk gepland waren om in hun respectieve tijdstreken te worden geleverd. Tot dat moment worden ze nog steeds weergegeven als &quot;E-mail verzenden&quot;.

1. Vanuit het raster kunt u op een e-mail klikken om de activiteitengegevens weer te geven. Voor geannuleerde verzendingen ziet het pop-upvenster Details er als volgt uit:

   ![](assets/image2018-2-23-11-3a30-3a46.png)

>[!MORELIKETHIS]
>
>* [ Begrijpend Ontvankelijke Tijdzone van de Tijd ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [ E-mailprogramma&#39;s van het Programma met de Ontvankelijke Streek van de Tijd ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
