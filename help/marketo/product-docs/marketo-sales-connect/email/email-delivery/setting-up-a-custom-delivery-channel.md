---
unique-page-id: 14746470
description: Aangepast leveringskanaal instellen - Marketo-documenten - Productdocumentatie
title: Een aangepast leveringskanaal instellen
exl-id: a31f7bfd-a4ee-4948-9bdc-b49d47054d40
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '397'
ht-degree: 0%

---

# Een aangepast leveringskanaal instellen {#setting-up-a-custom-delivery-channel}

Met Marketo Sales Connect kunt u integreren met een aangepaste SMTP-server voor de levering van uw e-mails. Dit is een goede optie voor degenen die geen grote e-mails uit hun Gmail of de leveringskanaal van de Uitwisseling willen verzenden.

De gebruikers kunnen opstelling een douaneSMTP server voor hun eigen individueel gebruik, of de Admins kunnen opstelling een Team SMTP dat over alle Verkoop Connect gebruikers in uw geval moet worden gedeeld.

>[!NOTE]
>
>* Naast het opzetten van uw server SMTP, uw [e-mailidentiteit moet worden geverifieerd](/help/marketo/product-docs/marketo-sales-connect/getting-started/email-settings/verify-your-email.md) voordat je e-mails kunt verzenden.
>* Wij adviseren werkend met uw team van IT of SMTP serververkoper om de juiste servergeloofsbrieven voor uw server te krijgen SMTP.
>* U kunt niet uw server van Gmail en van de Uitwisseling verbinden gebruikend de SMTP servergeloofsbrieven. Gebruik onze E-mailverbindingsservice om deze providers te integreren.

## Aangepaste SMTP {#custom-smtp}

1. Aanmelden bij de [webtoepassing](https://toutapp.com/login)klikt u op het tandwielpictogram rechtsboven en kiest u **Instellingen**.

   ![](assets/setting-up-a-custom-delivery-channel-1.png)

1. Klik onder Mijn account op **E-mailinstellingen**.

   ![](assets/setting-up-a-custom-delivery-channel-2.png)

1. Klikken **Aangepast leveringskanaal**.

   ![](assets/setting-up-a-custom-delivery-channel-3.png)

1. Ga uw geloofsbrieven van de Server SMTP in en klik **Verbinden**.

   ![](assets/setting-up-a-custom-delivery-channel-4.png)

   >[!NOTE]
   >
   >Als dit uw enige leveringskanaal is, wordt het automatisch toegewezen aan al uw e-mailidentiteiten, en u wordt hier gedaan. Als dit niet uw enige leveringskanaal is, gelieve te blijven aan Stap 5.

1. Zorg dat u zich nog steeds in e-mailinstellingen bevindt en klik op **Adres en handtekening**.

   ![](assets/setting-up-a-custom-delivery-channel-5.png)

1. Zoek de e-mailidentiteit waarvoor u een leveringskanaal wilt kiezen en klik op **Leveringskanaal kiezen**.

   ![](assets/setting-up-a-custom-delivery-channel-6.png)

1. Klik op de afleveringskaart op **Bewerken**.

   ![](assets/setting-up-a-custom-delivery-channel-7.png)

1. Klik op de vervolgkeuzelijst Kanaal en kies het aangepaste leveringskanaal dat u zojuist hebt toegevoegd. Klikken **Opslaan**.

   ![](assets/setting-up-a-custom-delivery-channel-8.png)

   >[!NOTE]
   >
   >Als uw teambeheerder omhoog de Server van het Team SMTP plaatst, zal het automatisch slechts op uw standaard e-mailidentiteit van toepassing zijn, en beschikbaar als optie voor uw andere e-mailidentiteiten.

## Team SMTP-server {#team-smtp-server}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Aanmelden bij de [webtoepassing](https://toutapp.com/login)klikt u op het tandwielpictogram rechtsboven en kiest u **Instellingen**.

   ![](assets/setting-up-a-custom-delivery-channel-9.png)

1. Klik onder Beheerinstellingen op **Algemeen**.

   ![](assets/setting-up-a-custom-delivery-channel-10.png)

1. Klikken **Teamleveringskanaal**.

   ![](assets/setting-up-a-custom-delivery-channel-11.png)

1. Ga uw geloofsbrieven van de Server SMTP in en klik **Verbinden**.

   ![](assets/setting-up-a-custom-delivery-channel-12.png)

   >[!NOTE]
   >
   >De server van Team SMTP zal het standaardleveringskanaal van de standaard e-mailidentiteit voor alle teamleden zijn. Bovendien is deze beschikbaar als optie voor het leveringskanaal voor alle andere e-mailidentiteiten.

   >[!MORELIKETHIS]
   >
   >* [E-mailverbinding voor Gmail-gebruikers](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
   >
   >* [E-mailverbinding voor Outlook-gebruikers](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
