---
unique-page-id: 11380774
description: Accountscore - Marketo-documenten - productdocumentatie
title: Accountscore
exl-id: 68fb5f41-f715-4a4d-b4da-9db4dc38d67d
feature: Target Account Management
source-git-commit: e49860ae611f2f77789bb491aeccbee46a911a2c
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---

# Accountscore {#account-score}

Het Scoren van de rekening is een essentieel deel van het Beheer van de Rekening van het Doel. Het helpt u de mate van betrokkenheid van uw accounts te bepalen.

## Wat is het Scorebord van de Rekening? {#what-is-account-scoring}

Het is een systematische benadering die wordt ontworpen om verkoop en marketing teams te helpen de bedrijven (met inbegrip van vooruitzichten) identificeren en voorrang geven die het meest waarschijnlijk om een aankoop zullen maken.

In de complexe wereld van B2B-aankoopprocessen is het zeldzaam dat één individu een aankoopbeslissing neemt. Het gaat vaak om verschillende rollen, elk met eigen behoeften. Bij het maken van een score op basis van accounts wordt hiermee rekening gehouden door de leadscores van meerdere leads samen te voegen en een score op accountniveau te leveren.

## Algemene voorbeelden {#common-examples}

<table> 
 <tbody>
  <tr>
   <td><strong>Score voor accountbetrokkenheid</strong></td> 
   <td>Diepte van betrokkenheid op basis van gedragsactiviteiten die via verschillende kanalen (bijvoorbeeld e-mail, web en advertenties) van personen in specifieke doelaccounts worden bijgehouden.</td>
  </tr>
  <tr>
   <td><strong>Interescore voor product van account</strong></td>
   <td>Personen van doelaccounts die belangstelling tonen voor de inhoud van een specifiek product (bijvoorbeeld het downloaden van een witboek).</td> 
  </tr>
  <tr>
   <td><strong>Score voor online betrokkenheid van account</strong></td>
   <td>Personen van doelaccounts die webkanaal bezoeken. Dezelfde score kan worden gemaakt om de betrokkenheid van kanalen via e-mail, advertenties of andere kanalen te meten.</td> 
  </tr>
 </tbody>
</table>

## Accountscore configureren {#how-to-configure-account-score}

>[!NOTE]
>
>Als u accountscores wilt berekenen, moet u eerst loodscores maken. Marketo TAM aggregeert automatisch leadscores naar accountscores. Als voorbeeld nemen we twee van de bovenstaande voorbeelden (_Interescore voor product van account_ en _Score voor online betrokkenheid van account_).
>
>Maak eerst loodscore-velden waarin relevante details van elke lead van een doelaccount worden vastgelegd.\
>Wijs vervolgens die leadscores toe aan hun respectievelijke accountscores:\
>Account Product Interest Score = SUM (Lood Product Interest Score)\
>Account Web Engagement Score = SUM (Lead Web Engagement Score)

>[!NOTE]
>
>Gebruikers kunnen meerdere betrokkenheidsscores voor hun account maken en verschillende persoonlijke scores toewijzen aan verschillende accountscores.

Nadat u de hoofdscore hebt geconfigureerd, voert u de onderstaande stappen uit.

1. Klikken **Beheerder**.

   ![](assets/account-score-1.png)

1. Klikken **Doelaccountbeheer**.

   ![](assets/account-score-2.png)

1. Klik in Velden noteren op **Bewerken**.

   ![](assets/account-score-3.png)

   >[!NOTE]
   >
   >U kunt maximaal **vijf** velden voor het berekenen van de accountscore.

1. Voer de naam van de accountscore in en klik op de knop **Persoonsscore selecteren** en selecteer de corresponderende score.

   ![](assets/account-score-4.png)

1. Klikken **+Toevoegen** voor meer scores.

   ![](assets/account-score-5.png)

1. Voeg alle gewenste scores toe. Klikken **Opslaan** wanneer gereed.

   ![](assets/account-score-6.png)
