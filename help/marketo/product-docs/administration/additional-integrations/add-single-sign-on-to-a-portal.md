---
unique-page-id: 2360356
description: Eén aanmelding toevoegen aan een portal - Marketo Docs - Productdocumentatie
title: Eén aanmelding toevoegen aan een portal
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 0%

---


# Eén aanmelding toevoegen aan een portal {#add-single-sign-on-to-a-portal}

Als u een directoryservice hebt die gebruikers verifieert, kunt u SSO (Single Sign-On) in Marketo toestaan. Wij steunen deze eigenschap gebruikend de Taal van de Prijsverhoging van de Veiligheid (SAML) versie 2.0 en hoger.

Marketo werkt als SAML Service Provider (SP) en is afhankelijk van een externe identiteitsprovider (IdP) om gebruikers te verifiëren.

Zodra SSO wordt toegelaten, kan IdP de geloofsbrieven van een gebruiker bevestigen. Wanneer een gebruiker de software van het Marketo wenst te gebruiken, verzendt IdP dan een ondertekend bericht van SAML naar Marketo, handelend als SP. Dit bericht vouwt aan Marketo dat de gebruiker wordt gemachtigd om de software van Marketo te gebruiken.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!NOTE]
>
>Bent u een Microsoft Azure-gebruiker? Bekijk hun [integratiezelfstudie](https://azure.microsoft.com/en-us/documentation/articles/active-directory-saas-marketo-tutorial/).

## Hoe te om het Verzoek {#how-to-send-the-request} te verzenden

* Verzend het verzoek SSO, dat een reactie van SAML is, naar `https://login.marketo.com/saml/assertion/<your-munchkin-id>`
* Als Publiek URL van SP. [https://saml.marketo.com/sp](https://saml.marketo.com/sp) gebruiken
* Als u het SPNameQualifier attribuut gebruikt, plaats het element NameID voor Onderwerp aan [https://saml.marketo.com/sp](https://saml.marketo.com/sp)
* Als u veelvoudige abonnementen van de Marketo aan de zelfde leverancier SSO federaliseert, kunt u unieke URL van SP voor elke Marketo gebruiken sub met het formaat `https://saml.marketo.com/sp/<munchkin_id>`

>[!NOTE]
>
>Marketo ondersteunt alleen Identiteitsprovider-gestarte (ook wel IdP-gestarte genoemd), waarin de gebruiker eerst de aanmeldingspagina IDP start, verifieert en vervolgens naar Mijn Marketo navigeert.

## Aanvullende notities {#additional-notes}

* **Synchronisatietijd**  - Voor een nieuwe gebruiker is er ongeveer een vertraging van 10 minuten voordat een eerste SSO-aanvraag wordt verwerkt.
* **Gebruikersinrichting**  - Gebruikers worden handmatig geleverd door Marketo.
* **Autorisatie**  - Gebruikersmachtigingen blijven behouden in Marketo.
* **OAuth-ondersteuning**  - Marketo biedt momenteel geen ondersteuning voor OAuth.

>[!NOTE]
>
>Voordat u begint, moet u het certificaat van identiteitsprovider in de indeling X.509 en de extensie .crt, .der of .cer hebben.

## SAML-instellingen {#update-saml-settings} bijwerken

SSO is standaard uitgeschakeld. Volg deze stappen om SAML toe te laten en het te vormen.

1. Ga naar **Admin** en klik **Single Sign-On**.

   ![](assets/image2014-9-24-14-3a36-3a50.png)

   >[!NOTE]
   >
   >Als u **Single Sign-On** onder **Admin** niet ziet, contacteer [[Marketo Support]](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Klik onder de sectie **SAML Settings** op **Edit**.

   ![](assets/image2014-9-24-14-3a37-3a3.png)

1. Wijzig **SAML Single Sign-On** in **Enabled**.

   ![](assets/image2014-9-24-14-3a37-3a17.png)

1. Voer uw **Uitgever-id**, **Entiteit-id** in, selecteer **Gebruikersnaam-locatie** en klik vervolgens op **Bladeren**.

   ![](assets/image2014-9-24-14-3a37-3a32.png)

1. Selecteer uw **Identiteitsprovidercertificaat**-bestand.

   ![](assets/image2014-9-24-14-3a38-3a8.png)

1. Klik **Opslaan**.

   ![](assets/image2014-9-24-14-3a38-3a22.png)

## Omleidingsinstellingen voor pagina-omleiding bijwerken {#update-redirect-page-settings}

1. Klik onder de sectie **Pagina&#39;s omleiden** op **Bewerken**.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >Klanten die gebruikmaken van een universele id in combinatie met een SSO, moeten de aanmeldings-URL van de Identiteitsprovider invoeren in het veld **Aanmeldings-URL**.

1. Voer een **aanmeldings-URL** in. Dit is de URL waarnaar de gebruiker moet worden geleid wanneer deze zich afmeldt bij Marketo.

   ![](assets/eight.png)

1. Voer een **Fout-URL** in. Dit is de URL waarnaar de gebruiker moet worden geleid voor het geval dat het aanmelden bij Marketo mislukt. Klik **Opslaan**.

   ![](assets/nine.png)

   >[!NOTE]
   >
   >Beide pagina&#39;s moeten openbaar zijn.
