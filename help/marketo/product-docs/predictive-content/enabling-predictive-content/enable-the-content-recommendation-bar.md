---
unique-page-id: 4720108
description: De balk met aanbevelingen voor inhoud - Marketo Docs - Productdocumentatie inschakelen
title: De balk met aanbevelingen voor inhoud inschakelen
translation-type: tm+mt
source-git-commit: 06e0f5489e6375a97e2fe77834bf45fa41f23ea6
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 0%

---


# De balk Aanbevolen inhoud {#enable-the-content-recommendation-bar} inschakelen

De Content Recommendation Engine maakt gebruik van voorspellende analytische algoritmen en computerleeralgoritmen om relevante inhoud aan elke webbezoeker te leveren. De aanbevolen engine voorspelt welke inhoud het beste per bezoeker zou presteren. De inhoud voor de engine wordt gecontroleerd en beheerd onder de Recommendations-pagina, zodat u uw ROI voor inhoud kunt optimaliseren.

>[!PREREQUISITES]
>
>Voordat u voorspellende inhoud inschakelt, moet u:
>
>* **Voorspelende inhoud voorbereiden**
   >
   >   
   * [Voorspelende inhoud voor ](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md) e-mailprogramma bewerken
   >   * [Predictieve inhoud voor rijke ](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md) media bewerken
   >   * [Voorspelende inhoud voor de balk met aanbevelingen bewerken](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md)
>
>* [Een titel voor preventieve inhoud goedkeuren](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md)


## De balk Aanbevolen inhoud {#enable-and-customize-the-content-recommendation-bar} inschakelen en aanpassen

1. Ga naar **Inhoudsinstellingen**.

   ![](assets/settings-dropdown-hand.png)

1. Klik **Bar**.

   ![](assets/content-settings-bar-hand.png)

1. Om de bar van de Aanbeveling voor een URL toe te laten, klik eenvoudig **On** en dan **sparen**.

   ![](assets/bar-enable.png)

1. Als u een URL wilt aanpassen, selecteert u kleuren, stijlen, opmaak, pijlen voor de aanbevolen balk en pagina&#39;s die u wilt opnemen in of uitsluiten van de balk. Aanpassen aan de branding van uw website. Klik **Opslaan**.

   ![](assets/bar-customize-details-hands.png)

   >[!NOTE]
   >
   >**Weergave-URL opnemen/uitsluiten**
   >
   >* De weergave-URL moet het pad van het domein zijn
   >* Geen https:// of https:// opnemen
   >* Gebruik * voor jokertekens
   * Een puntkomma als scheidingsteken gebruiken
   * Voorbeeld: /contact_us*; *action=logout*
   * Dit veld is hoofdlettergevoelig


## Overwegingen {#recommendation-bar-considerations} voor de aanbevolen balk

* U hebt minstens één inhoudsstuk voor de aanbevelingsbar nodig die aan **op** op de pagina van Recommendations wordt geplaatst voor de motor van de Aanbeveling om te werken. Als er geen inhoud is ingeschakeld en de balk is ingesteld op **Aan**, wordt het effect Pijl rechts onder op de webpagina weergegeven, maar wordt er geen aanbevolen inhoud weergegeven.

* Hoe meer inhoud in de aanbevolen engine wordt uitgevoerd, hoe beter de algoritme kan testen en leren welke inhoud het beste werkt. We raden u aan om te beginnen met 10 tot 20 actieve inhoudsonderdelen en om nieuwe inhoud toe te voegen.
* Het inhoudsstuk u voor aanbeveling toelaat zou de markering van Javascript RTP moeten omvatten. Hierdoor kan de algoritme aanbevolen inhoud bijhouden en optimaliseren.

>[!MORELIKETHIS]
[Voorspelende inhoud voor web-rijke media inschakelen](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
