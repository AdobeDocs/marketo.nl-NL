---
unique-page-id: 14746470
description: Aangepast leveringskanaal instellen - Marketo-documenten - Productdocumentatie
title: Een aangepast leveringskanaal instellen
exl-id: a31f7bfd-a4ee-4948-9bdc-b49d47054d40
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 0%

---

# Een aangepast leveringskanaal instellen {#setting-up-a-custom-delivery-channel}

Met [!DNL Marketo Sales Connect] kunt u integreren met een aangepaste SMTP-server voor de levering van uw e-mails. Dit is een goede optie voor diegenen die geen grote e-mailberichten uit hun Gmail of [!DNL Exchange] leveringskanaal willen verzenden.

De gebruikers kunnen opstelling een douaneSMTP server voor hun eigen individueel gebruik, of Admins kunnen opstelling een Team SMTP dat over alle [!DNL Sales Connect] gebruikers in uw instantie moet worden gedeeld.

>[!NOTE]
>
>* Naast vestiging uw server SMTP, moet uw [ e-mailidentiteit worden geverifieerd ](/help/marketo/product-docs/marketo-sales-connect/getting-started/email-settings/verify-your-email.md) alvorens u e-mails kunt verzenden.
>* Wij adviseren werkend met uw team van IT of SMTP serververkoper om de juiste servergeloofsbrieven voor uw server te krijgen SMTP.
>* U kunt uw Gmail en [!DNL Exchange] server niet verbinden gebruikend de SMTP servergeloofsbrieven. Gebruik onze E-mailverbindingsservice om deze providers te integreren.

## Aangepaste SMTP {#custom-smtp}

1. Login aan de [ Webtoepassing ](https://toutapp.com/login), klik het tandwielpictogram op het hoogste recht en kies **[!UICONTROL Settings]**.

   ![](assets/setting-up-a-custom-delivery-channel-1.png)

1. Klik onder [!UICONTROL My Account] op **[!UICONTROL Email Settings]** .

   ![](assets/setting-up-a-custom-delivery-channel-2.png)

1. Klik op **[!UICONTROL Custom Delivery Channel]**.

   ![](assets/setting-up-a-custom-delivery-channel-3.png)

1. Voer uw [!UICONTROL SMTP Server] -gegevens in en klik op **[!UICONTROL Connect]** .

   ![](assets/setting-up-a-custom-delivery-channel-4.png)

   >[!NOTE]
   >
   >Als dit uw enige leveringskanaal is, wordt het automatisch toegewezen aan al uw e-mailidentiteiten, en u wordt hier gedaan. Als dit niet uw enige leveringskanaal is, gelieve te blijven aan Stap 5.

1. Klik terwijl u zich nog in [!UICONTROL Email Settings] bevindt op **[!UICONTROL Address and Signature]** .

   ![](assets/setting-up-a-custom-delivery-channel-5.png)

1. Zoek de e-mailidentiteit waarvoor u een leveringskanaal wilt kiezen en klik op **[!UICONTROL Choose Delivery Channel]** .

   ![](assets/setting-up-a-custom-delivery-channel-6.png)

1. Klik in de [!UICONTROL Deliverability] -kaart op **[!UICONTROL Edit]** .

   ![](assets/setting-up-a-custom-delivery-channel-7.png)

1. Klik op de vervolgkeuzelijst [!UICONTROL Channel] en kies het aangepaste leveringskanaal dat u zojuist hebt toegevoegd. Klik op **[!UICONTROL Save]**.

   ![](assets/setting-up-a-custom-delivery-channel-8.png)

   >[!NOTE]
   >
   >Als uw teambeheerder omhoog de Server van het Team SMTP plaatst, zal het automatisch slechts op uw standaard e-mailidentiteit van toepassing zijn, en beschikbaar als optie voor uw andere e-mailidentiteiten.

## Team SMTP-server {#team-smtp-server}

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Login aan de [ Webtoepassing ](https://toutapp.com/login), klik het tandwielpictogram op het hoogste recht en kies **[!UICONTROL Settings]**.

   ![](assets/setting-up-a-custom-delivery-channel-9.png)

1. Klik onder [!UICONTROL Admin Settings] op **[!UICONTROL General]** .

   ![](assets/setting-up-a-custom-delivery-channel-10.png)

1. Klik op **[!UICONTROL Team Delivery Channel]**.

   ![](assets/setting-up-a-custom-delivery-channel-11.png)

1. Voer uw [!UICONTROL SMTP Server] -gegevens in en klik op **[!UICONTROL Connect]** .

   ![](assets/setting-up-a-custom-delivery-channel-12.png)

   >[!NOTE]
   >
   >De server van Team SMTP zal het standaardleveringskanaal van de standaard e-mailidentiteit voor alle teamleden zijn. Bovendien is deze beschikbaar als optie voor het leveringskanaal voor alle andere e-mailidentiteiten.

   >[!MORELIKETHIS]
   >
   >* [ E-mailVerbinding voor de Gebruikers van Gmail ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
   >
   >* [ E-mailVerbinding voor  [!DNL Outlook]  Gebruikers ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
