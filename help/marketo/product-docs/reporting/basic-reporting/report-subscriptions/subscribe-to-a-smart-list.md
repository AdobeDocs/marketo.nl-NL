---
unique-page-id: 7505310
description: Abonneren op een slimme lijst - Marketo Docs - Productdocumentatie
title: Abonneren op een slimme lijst
exl-id: 4ea1664b-8178-41ae-a184-a8ebe090ef96
feature: Reporting
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '400'
ht-degree: 0%

---

# Abonneren op een slimme lijst {#subscribe-to-a-smart-list}

Abonneren op slimme lijsten is een goede manier om mensen bij te houden, met rapporten die rechtstreeks naar uw Postvak IN worden verzonden.

U kunt een abonnement op een slimme lijst maken op twee verschillende plaatsen:

* [!UICONTROL Marketing Activities]
* [!UICONTROL Database]

Abonnementen gebruiken de volledige lijst met personen op het moment dat het abonnement wordt uitgevoerd.

Abonnementen worden live weergegeven op de locatie in de slimme lijst, in [!UICONTROL Marketing Activities] of [!UICONTROL Database] .

U kunt meerdere abonnementen maken van dezelfde slimme lijst.

Abonnementen zijn specifiek voor de werkruimte. Deze lijst met abonnementen bevindt zich bijvoorbeeld in een andere werkruimte dan de abonnementen die in de rest van dit artikel worden weergegeven:

![](assets/one.png)

>[!NOTE]
>
>U kunt per Marketo-instantie maximaal 100.000 abonnementen en maximaal 100.000 personen per abonnement gebruiken. Als de slimme lijst meer dan 100.000 namen bevat, voert Marketo het abonnement voor de eerste 100.000 uit.

## Een abonnement voor een slimme lijst maken {#create-a-smart-list-subscription}

1. Ga naar **[!UICONTROL Database]** of **[!UICONTROL Marketing Activities]** .

   ![](assets/db.png)

1. Selecteer de slimme lijst waarvoor u een abonnement wilt maken. Klik op **[!UICONTROL List Actions]** en selecteer **[!UICONTROL New Smart List Subscription]** .

   ![](assets/three.png)

1. Geef uw abonnement een **[!UICONTROL Name]** en selecteer of voer de e-mailadressen van de **[!UICONTROL Recipients]** in.

   ![](assets/image2015-9-14-13-3a18-3a38.png)

1. Klik op de lijst **[!UICONTROL Frequency]** en selecteer een frequentie.

   ![](assets/image2015-9-14-13-3a21-3a21.png)

1. Stel de **[!UICONTROL End Delivery]** datum in. U kunt **[!UICONTROL Never]** of een kalenderdatum selecteren.

   ![](assets/image2015-9-14-13-3a23-3a37.png)

1. Klik op **[!UICONTROL Format]** en kies in de lijst.

   ![](assets/image2015-9-14-13-3a25-3a25.png)

1. Klik op **[!UICONTROL Create]**.

   ![](assets/image2015-9-11-15-3a58-3a4.png)

1. Uw nieuwe abonnement op de slimme lijst wordt boven aan de lijst weergegeven op het tabblad Abonnementen. Klik op **[!UICONTROL Send]** als u nu wilt verzenden en niet wilt wachten tot de geplande e-maillevering.

   ![](assets/eight.png)

1. We raden u aan het selectievakje **[!UICONTROL Active]** uit te schakelen om een abonnement op een slimme lijst te deactiveren als er niemand op is geabonneerd.

   ![](assets/nine.png)

   Dat was makkelijk, niet?

## E-mailbericht {#email-message}

Ontvangers ontvangen een e-mail met de mogelijkheid om het rapport te downloaden en een koppeling rechtstreeks naar de lijst in het Marketo-exemplaar. De downloadkoppeling verloopt over vier dagen.

>[!NOTE]
>
>Als het [ Veilige plaatsen van de Abonnement Admin ](/help/marketo/product-docs/reporting/basic-reporting/report-subscriptions/secure-the-subscription-admin-setting.md) aan **[!UICONTROL Yes]** wordt geplaatst, slechts zullen de mensen met toegang tot de instantie van Marketo het rapport kunnen downloaden.

![](assets/image2015-4-17-15-3a46-3a47.png)

Als een rapport 0 personen bevat, ontvangen ontvangers nog steeds een e-mail. In de e-mail staat echter alleen dat er geen personen zijn om te rapporteren.

![](assets/image2015-4-17-16-3a11-3a8.png)

>[!NOTE]
>
>Wanneer u een slim lijstfilter wijzigt u een abonnement op hebt gebaseerd, werkt het het rapport eveneens bij.

De e-mail bevat ook aanvullende informatie over de filters die zijn gebruikt om de lijst te maken.

## Een abonnement verwijderen {#delete-a-subscription}

Als u een abonnement wilt verwijderen, selecteert u het op het tabblad Abonnementen en klikt u op **[!UICONTROL Delete Subscription]** .

![](assets/twelve.png)

>[!MORELIKETHIS]
>
>* [ geef een Slim Abonnement van de Lijst ](/help/marketo/product-docs/reporting/basic-reporting/report-subscriptions/edit-a-smart-list-subscription.md) uit
>* [ Beveilig het Plaatsen van Admin van het Abonnement ](/help/marketo/product-docs/reporting/basic-reporting/report-subscriptions/secure-the-subscription-admin-setting.md)
