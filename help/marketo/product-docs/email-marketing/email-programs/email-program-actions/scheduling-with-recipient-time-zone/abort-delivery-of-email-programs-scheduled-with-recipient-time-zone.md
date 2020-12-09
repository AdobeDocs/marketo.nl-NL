---
unique-page-id: 13795727
description: Afbreken van de levering van e-mailprogramma's die zijn gepland met de tijdzone van de ontvanger - Marketo Docs - Productdocumentatie
title: Aflevering van e-mailprogramma's afbreken die zijn gepland met de tijdzone van de ontvanger
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---


# Aflevering van e-mailprogramma&#39;s afbreken die zijn gepland met de tijdzone van de ontvanger {#abort-delivery-of-email-programs-scheduled-with-recipient-time-zone}

In noodgevallen kunt u de levering afbreken van een e-mailprogramma dat al is gestart met het uitvoeren van de tijdzone voor ontvangers ingeschakeld.

Aangezien e-mailprogramma&#39;s die zijn gepland met de tijdzone van de ontvanger maximaal 24 uur kunnen duren, wordt elke volgende verzending na dat punt geannuleerd wanneer de levering van het programma wordt afgebroken.

1. Selecteer het e-mailprogramma dat u wilt annuleren en klik vervolgens op **Aflevering** afbreken onder de titel Goedkeuring in het configuratiescherm.

   ![](assets/ptz-abortdelivery.png)

1. Bevestig dat u de levering wilt annuleren door op **Afbreken** te klikken.

   ![](assets/image2018-2-23-11-3a20-3a27.png)

1. Na annulering ziet het raster **Resultaten** van uw e-mailprogramma er ongeveer zo uit als hieronder. Alle volgende verzendingen worden geannuleerd en worden weergegeven als &quot;Verzonden via e-mail&quot; in de kolom **Type** activiteit.

   ![](assets/image2018-2-23-11-3a22-3a11.png)

   >[!NOTE]
   >
   >Geannuleerde e-mails worden **pas** als een zachte stuit weergegeven *wanneer* de levering volgens de planning in de respectievelijke tijdzones moet plaatsvinden. Tot dat moment worden ze nog steeds weergegeven als &quot;E-mail verzenden&quot;.

1. Vanuit het raster kunt u op een e-mail klikken om de activiteitengegevens weer te geven. Voor geannuleerde verzendingen ziet het pop-upvenster Details er als volgt uit:

   ![](assets/image2018-2-23-11-3a30-3a46.png)

>[!MORELIKETHIS]
>
>* [Tijdzone van ontvanger](understanding-recipient-time-zone.md)
>* [E-mailprogramma&#39;s met tijdzone voor ontvangers plannen](schedule-email-programs-with-recipient-time-zone.md)

>



