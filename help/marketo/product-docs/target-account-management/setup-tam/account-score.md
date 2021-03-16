---
unique-page-id: 11380774
description: Accountscore - Marketo Docs - Productdocumentatie
title: Accountscore
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Accountscore {#account-score}

Het Scoren van de rekening is een essentieel deel van het Beheer van de Rekening van het Doel. Het helpt u de mate van betrokkenheid van uw accounts te bepalen.

## Wat is het Scorebord van de Rekening? {#what-is-account-scoring}

Het is een systematische benadering die wordt ontworpen om verkoop en marketing teams te helpen de bedrijven (met inbegrip van vooruitzichten) identificeren en voorrang geven die het meest waarschijnlijk om een aankoop zullen maken.

In de complexe wereld van B2B-aankoopprocessen is het zeldzaam dat één persoon een aankoopbeslissing neemt. Er zijn vaak verschillende rollen mee gemoeid, elk met zijn eigen behoeften. Bij het maken van een score op basis van accounts wordt hiermee rekening gehouden door de leadscores van meerdere leads samen te voegen en een score op accountniveau te leveren.

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

## Hoe te om de Score van de Rekening {#how-to-configure-account-score} te vormen

>[!NOTE]
>
>Als u accountscores wilt berekenen, moet u eerst loodscores maken. Marketo TAM aggregeert automatisch leadscores naar accountscores. Als voorbeeld, zullen wij twee van de bovengenoemde voorbeelden (_Score van de Rente van het Product van de Rekening_ en _Score van de Betrokkenheid van het Web van de Rekening_) nemen.
>
>Maak eerst loodscore-velden waarin relevante details van elke lead van een doelaccount worden vastgelegd.\
>Wijs vervolgens die leadscores toe aan hun respectievelijke accountscores:\
>Account Product Interest Score = SUM (Lood Product Interest Score)\
>Account Web Engagement Score = SUM (Lead Web Engagement Score)

>[!NOTE]
>
>Gebruikers kunnen meerdere betrokkenheidsscores voor hun account maken en verschillende persoonlijke scores toewijzen aan verschillende accountscores.

Nadat u de hoofdscore hebt geconfigureerd, voert u de onderstaande stappen uit.

1. Klik **Admin**.

   ![](assets/one-1.png)

1. Klik **Doelaccountbeheer**.

   ![](assets/account-score-2.png)

1. Klik in Velden noteren op **Bewerken**.

   ![](assets/account-score-3.png)

   >[!NOTE]
   >
   >U kunt maximaal **vijf** velden kiezen om de accountscore te berekenen.

1. Ga de naam van de Score van de Rekening in, klik **Uitgezochte Score** drop-down en selecteer de overeenkomstige score.

   ![](assets/four.png)

1. Klik **+Add** om meer scores toe te voegen.

   ![](assets/five.png)

1. Voeg alle gewenste scores toe. Klik **Opslaan** wanneer gereed.

   ![](assets/six.png)
