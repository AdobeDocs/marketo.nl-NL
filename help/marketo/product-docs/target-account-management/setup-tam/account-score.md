---
unique-page-id: 11380774
description: Accountscore - Marketo-documenten - productdocumentatie
title: Accountscore
exl-id: 68fb5f41-f715-4a4d-b4da-9db4dc38d67d
feature: Target Account Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '334'
ht-degree: 0%

---

# [!UICONTROL Account Score] {#account-score}

Het noteren van accounts is een essentieel onderdeel van [!UICONTROL Target Account Management] . Het helpt u de mate van betrokkenheid van uw accounts te bepalen.

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
>Als u accountscores wilt berekenen, moet u eerst loodscores maken. Marketo TAM aggregeert automatisch leadscores naar accountscores. Als voorbeeld, zullen wij twee van de bovengenoemde voorbeelden nemen (_Score van de Rente van het Product van de Rekening_ en _Score van de Betrokkenheid van het Web van de Rekening_).
>
>Maak eerst loodscore-velden waarin relevante details van elke lead van een doelaccount worden vastgelegd.
>&#x200B;>Wijs vervolgens die leadscores toe aan hun respectievelijke accountscores:
>&#x200B;>Account Product Interest Score = SUM (Lood Product Interest Score)
>&#x200B;>Account Web Engagement Score = SUM (Lead Web Engagement Score)

>[!NOTE]
>
>Gebruikers kunnen meerdere betrokkenheidsscores voor hun account maken en verschillende persoonlijke scores toewijzen aan verschillende accountscores.

Nadat u de hoofdscore hebt geconfigureerd, voert u de onderstaande stappen uit.

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/account-score-1.png)

1. Klik op **[!UICONTROL Target Account Management]**.

   ![](assets/account-score-2.png)

1. Klik in [!UICONTROL Scoring Fields] op **[!UICONTROL Edit]** .

   ![](assets/account-score-3.png)

   >[!NOTE]
   >
   >U kunt tot **vijf** gebieden kiezen om [!UICONTROL Account Score] te berekenen.

1. Voer de naam [!UICONTROL Account Score] in, klik op de vervolgkeuzelijst **[!UICONTROL Select Person Score]** en selecteer de corresponderende score.

   ![](assets/account-score-4.png)

1. Klik op **[!UICONTROL +Add]** om meer scores toe te voegen.

   ![](assets/account-score-5.png)

1. Voeg alle gewenste scores toe. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/account-score-6.png)
