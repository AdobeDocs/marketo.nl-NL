---
description: Toestemming voor klant-id en toepassingsregistratie - Marketo-documenten - Productdocumentatie
title: Toestemming verlenen voor client-id en toepassingsregistratie
exl-id: d0c851d7-24a1-4b17-9daa-f0ceed39d040
feature: Microsoft Dynamics
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---

# Toestemming verlenen voor client-id en toepassingsregistratie {#grant-consent-for-client-id-and-app-registration}

## Gedelegeerde gebruikersmachtigingen verlenen voor de synchronisatiegebruiker {#grant-delegated-user-permissions-for-the-sync-user}

1. Gebruik een schoon tekstprogramma (Kladblok voor Vensters, Tekst geeft voor Mac uit) om een Uniform Herkenningsteken van het Middel (URI) voor vergunning tot stand te brengen door de hieronder tekst te kleven en client_id, redirect_uri, en staatswaarden te substitueren.

   ```
   https://login.microsoftonline.com/common/oauth2/authorize?
   client_id='xxxxxx-xxxx-xxxx-xxxx-xxxxxxxx'
   &response_type='code'
   &redirect_uri='https://www.<ourdomain>.com'
   &response_mode='query'
   &state='SOME_UNIQUE_UID'
   client_id value should be the client_id generated in App Registration process
   redirect_uri value should be same as value entered at the time of App registration-> Redirect URIs
   state value can be any ID (e.g.,12345)
   ```

   <table> 
    <colgroup> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>client_id, waarde</strong></td> 
      <td>moet de client_id zijn die is gegenereerd in het registratieproces van de app</td> 
     </tr> 
     <tr> 
      <td><strong>redirect_uri, waarde</strong></td> 
      <td>moet gelijk zijn aan de waarde die is ingevoerd op het moment van de registratie van de app &gt; URI's omleiden</td> 
     </tr> 
     <tr> 
      <td><strong>statuswaarde</strong></td> 
      <td>kan elke id zijn (bijvoorbeeld 12345)</td> 
     </tr> 
    </tbody> 
   </table>

   De uiteindelijke URL moet er ongeveer als volgt uitzien: `https://login.microsoftonline.com/common/oauth2/authorize?client_id=xxxxxx-xxxx-xxxx-xxxx-xxxxxxxx&response_type=code&redirect_uri=https://www.marketo.com&response_mode=query&state=12345`

1. Open de URI die u in een browser hebt gemaakt.

   ![](assets/grant-consent-for-client-id-app-registration-1.png)

1. Meld u aan als Synchronisatiegebruiker waarvoor u machtigingen verleent.

   ![](assets/grant-consent-for-client-id-app-registration-2.png)

   >[!NOTE]
   >
   >Als u reeds aan Azure als Admin op een ander lusje wordt aangemeld, zult u een verschillende browser of wijze Incognito moeten gebruiken om als Gebruiker van de Synchronisatie aan te melden.

1. Klikken **Accepteren**.

   ![](assets/grant-consent-for-client-id-app-registration-3.png)

## Toestemming verlenen voor alle gebruikers {#grant-consent-for-all-users}

Als beheerder, kunt u aan de gedelegeerde toestemmingen van een toepassing namens alle gebruikers in uw huurder ook toestemming geven. Administratieve toestemming verhindert de toestemmingsdialoog voor elke gebruiker in de huurder te verschijnen, en kan in het Azure portaal door gebruikers met de beheerderrol worden gedaan. Leer welke beheerdersrollen kunnen [toestemming hier voor gedelegeerde machtigingen](https://docs.microsoft.com/en-us/azure/active-directory/roles/permissions-reference).

1. Navigeer in uw Azure-portal naar de startpagina van de toepassing.

1. Klik onder Beheren op **API-machtigingen**.

   ![](assets/grant-consent-for-client-id-app-registration-4.png)

1. Klik op de knop **Toelating beheerder** (voor huurder).

   ![](assets/grant-consent-for-client-id-app-registration-5.png)

1. Klikken **Ja** ter bevestiging.

   ![](assets/grant-consent-for-client-id-app-registration-6.png)

