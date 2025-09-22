---
unique-page-id: 4720108
description: De balk met aanbevelingen voor inhoud inschakelen - Marketo Docs - Productdocumentatie
title: De balk met aanbevelingen voor inhoud inschakelen
exl-id: f2244db1-51a9-4e26-9bf7-b2c79df25552
feature: Predictive Content
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '314'
ht-degree: 0%

---

# De balk met aanbevelingen voor inhoud inschakelen {#enable-the-content-recommendation-bar}

De Content Recommendation Engine maakt gebruik van voorspellende analytische algoritmen en technieken voor het leren van machines om relevante inhoud aan elke webbezoeker te leveren. De aanbevolen engine voorspelt welke inhoud het beste per bezoeker zou presteren. De inhoud voor de engine wordt gecontroleerd en beheerd onder de pagina Aanbevelingen, zodat u uw ROI voor inhoud kunt optimaliseren.

>[!PREREQUISITES]
>
>Voordat u voorspellende inhoud inschakelt, moet u:
>
>* **bereidt uw Predictieve Inhoud** voor
>
>   * [ geef Voorspelende Inhoud voor E-mail ](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md) uit of
>   * [ geef Voorspelende Inhoud voor Rijke Media ](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md) uit of
>   * [ geef Voorspelende Inhoud voor de Bar van de Aanbeveling uit ](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md)
>
>* [ keur een Titel voor Voorspelende Inhoud ](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md) goed

## De balk met aanbevelingen voor inhoud inschakelen en aanpassen {#enable-and-customize-the-content-recommendation-bar}

1. Ga naar **[!UICONTROL Content Settings]** .

   ![](assets/settings-dropdown-hand.png)

1. Klik op **[!UICONTROL Bar]**.

   ![](assets/content-settings-bar-hand.png)

1. Als u de balk met aanbevelingen wilt inschakelen voor een URL, klikt u gewoon op **[!UICONTROL On]** en vervolgens op **[!UICONTROL Save]** .

   ![](assets/bar-enable.png)

1. Als u een URL wilt aanpassen, selecteert u kleuren, stijlen, opmaak, pijlen voor de aanbevolen balk en pagina&#39;s die u wilt opnemen in of uitsluiten van de balk. Aanpassen aan de branding van uw website. Klik op **[!UICONTROL Save]**.

   ![](assets/bar-customize-details-hands.png)

   >[!NOTE]
   >
   >**omvat/sluit Vertoning URL** uit
   >
   >* De weergave-URL moet het pad van het domein zijn
   >* Geen https:// of https:// opnemen
   >* &#42; gebruiken voor jokertekens
   >* Een puntkomma als scheidingsteken gebruiken
   >* Voorbeeld: /contact_us &#42;; &#42; action=logout &#42;
   >* Dit veld is hoofdlettergevoelig

## Overwegingen bij de aanbevolen balk {#recommendation-bar-considerations}

* De aanbevolen balk moet ten minste één stuk inhoud bevatten dat op de pagina Aanbevelingen is ingesteld op **[!UICONTROL On]** , anders werkt de engine Aanbeveling niet. Als geen inhoud is ingeschakeld en de balk is ingesteld op **[!UICONTROL On]** , wordt het effect Pijl rechts onder op de webpagina weergegeven, maar wordt geen aanbevolen inhoud weergegeven.

* Hoe meer inhoud in de aanbevolen engine wordt uitgevoerd, hoe beter de algoritme kan testen en leren welke inhoud het beste werkt. We raden u aan om te beginnen met 10 tot 20 actieve inhoudsonderdelen en om nieuwe inhoud toe te voegen.
* Het inhoudsstuk u voor aanbeveling toelaat zou de markering van Javascript RTP moeten omvatten. Hierdoor kan de algoritme aanbevolen inhoud bijhouden en optimaliseren.

>[!MORELIKETHIS]
>
>[ laat Voorspelende Inhoud voor Web Rich Media ](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md) toe
