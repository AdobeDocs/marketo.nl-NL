---
description: Chatbotgedrag - Marketo Docs - Productdocumentatie
title: Chatbotgedrag
feature: Dynamic Chat
exl-id: e91e7981-6617-42fe-8120-a7311a99cdfb
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1680'
ht-degree: 0%

---

# Chatbotgedrag {#chatbot-behavior}

Hieronder volgen verschillende mogelijke scenario&#39;s waarin het verwachte gedrag van Chatbot voor de bezoeker in elke scenario wordt beschreven.

<table>
  <tbody>
    <tr>
      <th>Afkorting</th>
      <th>Details</th>
    </tr>
    <tr>
      <td>D1, D2, D3, enz.</td>
      <td>Vertegenwoordigt veelvoudige dialogen waar D1 dialoog één is</td>
    </tr>
    <tr>
      <td>P1, P2, P3, enz.</td>
      <td>Vertegenwoordigt dialoogprioriteiten waar P1 de hoogste prioriteit is</td>
    </tr>
    <tr>
      <td>WP1, WP2, WP3, enz.</td>
      <td>Vertegenwoordigt veelvoudige Web-pagina's waar WP1 de eerste Web-pagina is</td>
    </tr>
    <tr>
      <td>V1, V2, V3, enz.</td>
      <td>Vertegenwoordigt meerdere bezoekers van webpagina's waarbij V1 één bezoeker is</td>
    </tr>
   </tbody>
</table>

## Scenarios {#scenarios}

<table>
  <tr>
      <th>Scenario</th>
      <th>Chatbotgedrag verwacht</th>
      <th>Handeling Backend</th>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoeken WP1</p>
      </td>
      <td>
        <p>D1 wordt omgezet in V1</p>
      </td>
      <td>Het aantal triggers voor D1 wordt met 1 verhoogd</td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoeken WP1</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 wordt omgezet in V1</p>
        <p>Na vernieuwen wordt D1 opnieuw opgelost</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Na vernieuwen worden geen wijzigingen aangebracht in D1-trigger of -betrokkenheidstelling</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 maar heeft niet gereageerd</p>
      </td>
      <td>D1 wordt omgezet in V1</td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Geen wijziging van het aantal D1-contracten</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 en verstrekt de eerste reactie</p>
      </td>
      <td>D1 wordt omgezet in V1</td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Het aantal contracten voor D1 wordt met 1 verhoogd</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 en verstrekt de eerste reactie</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 wordt omgezet in V1</p>
        <p>Na vernieuwen wordt D1 voortgezet</p>
      </td>
      <td>
        <p>Het aantal triggers en het aantal contracten voor D1 wordt met 1 verhoogd</p>
        <p>Na vernieuwen worden er geen aantallen gewijzigd</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1, neemt contact op met de chatbot en voltooit D1</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 wordt omgezet in V1</p>
        <p>Na vernieuwen wordt er geen dialoogvenster of volgende dialoogvenster opgelost voor V1</p>
      </td>
      <td>
        <p>Het aantal triggers, het aantal contracten en het voltooide aantal voor D1 worden met 1 verhoogd</p>
        <p>Na vernieuwen wordt geen dialoogvenster of volgende dialoogvenster opgelost</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 gericht voor WP1 slechts, WP2</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 maar heeft niet gereageerd</p>
        <p>V1 bezoeken WP2</p>
      </td>
      <td>
        <p>Het paginabezoek WP1, D1 zal aan V1 worden opgelost</p>
        <p>Pagina bezoek WP2, D1 zal aan V2 worden opgelost</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>In WP2, geen verandering in D1 trekkertelling</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 gericht voor WP1 slechts, WP2</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 en ingeschakeld</p>
        <p>V1 bezoeken WP2</p>
      </td>
      <td>
        <p>Het paginabezoek WP1, D1 zal aan V1 worden opgelost</p>
        <p>Paginabezoek WP2, D1 wordt omgezet naar V1</p>
      </td>
      <td>
        <p>Het aantal triggers en het aantal contracten voor D1 wordt met 1 verhoogd</p>
        <p>In WP2, geen verandering in om het even welk aantal</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>D2 alleen gericht op WP2</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 en verstrekt de eerste reactie</p>
        <p>V1 bezoeken WP2</p>
      </td>
      <td>
        <p>D1 zal op WP1 worden opgelost</p>
        <p>D1 zal V1 op WP2 blijven</p>
      </td>
      <td>
        <p>Het aantal triggers en het aantal contracten voor D1 wordt met 1 verhoogd</p>
        <p>Geen wijziging van het aantal triggers of afspraken voor D2</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>D2 alleen gericht op WP2</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 maar heeft niet gereageerd</p>
        <p>V1 bezoeken WP2</p>
      </td>
      <td>D1 zal op WP1 <br/> worden opgelost
      D2 zal op WP2 worden opgelost</td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Het aantal triggers voor D2 wordt met 1 verhoogd</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>D2 alleen gericht op WP2</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 en voltooit D1</p>
        <p>V1 bezoeken WP2</p>
      </td>
      <td>D1 zal op WP1 worden opgelost en op post-voltooiing <br/> D2 zal op WP2 worden opgelost</td>
      <td>
        <p>Het aantal triggers, het aantal contracten en het voltooide aantal voor D1 worden met 1 verhoogd</p>
        <p>Het aantal triggers voor D2 wordt met 1 verhoogd</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>D2 alleen gericht op WP2</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 en voltooit D1</p>
        <p>V1 bezoeken WP2</p>
        <p>V1 klikt op D2 levert de eerste reactie</p>
      </td>
      <td>D1 zal op WP1 worden opgelost en op post-voltooiing <br/> D2 zal op WP2 worden opgelost</td>
      <td>
        <p>Het aantal triggers, het aantal contracten en het voltooide aantal voor D1 worden met 1 verhoogd</p>
        <p>Het aantal triggers en contracten voor D2 wordt met 1 verhoogd</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 maar heeft niet gereageerd</p>
        <p>D1 is niet gepubliceerd</p>
      </td>
      <td>D1 wordt omgezet in V1</td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Geen wijziging van het aantal D1-afspraken</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 maar heeft niet gereageerd</p>
        <p>D1 is niet gepubliceerd</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 zal voor de eerste keer aan V1 worden opgelost</p>
        <p>Na vernieuwen wordt er geen dialoogvenster opgelost</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Geen wijziging van het aantal D1-afspraken</p>
        <p>Na vernieuwen worden geen wijzigingen aangebracht in de D1-trigger of -betrokkenheidstelling</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 met D1</p>
        <p>D1 is niet gepubliceerd</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 wordt omgezet in V1</p>
        <p>Na vernieuwen wordt D1 voortgezet</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>D1-aantal taken wordt met 1 verhoogd</p>
        <p>Na vernieuwen, aangezien D1 wordt voortgezet zonder verdere wijziging voor het activeren of tellen van betrokkenheid</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 maar heeft niet gereageerd</p>
        <p>D1 wordt gepubliceerd met nieuwe veranderingen</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 zal voor de eerste keer aan V1 worden opgelost</p>
        <p>Na vernieuwen wordt het dialoogvenster met nieuwe wijzigingen opgelost</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Na verfrissen zich, als D1 met nieuwe veranderingen maar geen verdere verandering om telling teweeg te brengen</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die slechts voor WP1 wordt gericht</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 verstrekt de eerste reactie</p>
        <p>D1 wordt gepubliceerd met nieuwe veranderingen</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 zal voor de eerste keer aan V1 worden opgelost</p>
        <p>Na vernieuwen wordt het dialoogvenster met oude wijzigingen voortgezet</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Het aantal contracten voor D1 wordt met 1 verhoogd</p>
        <p>Na verfrissen zich, aangezien oude D1 zal verschijnen zodat geen verandering om telling teweeg te brengen</p>
      </td>
    </tr>
    <tr>
     <td>
        <p>D1 gericht voor WP1 met 1 prioriteit</p>
        <p>D2 gericht op WP1 met 2 prioriteit</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 maar heeft niet gereageerd</p>
        <p>D1 is niet gepubliceerd</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 zal voor de eerste keer aan V1 worden opgelost</p>
        <p>Na vernieuwen wordt D2 omgezet in V1</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Na verfrissen, zal het trekkeraantal voor D2 met 1 worden verhoogd</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 gericht voor WP1 met 1 prioriteit</p>
        <p>D2 gericht op WP1 met 2 prioriteit</p>
        <p>V1 bezoekt WP1 voor het eerst</p>
        <p>V1 klikt op D1 en voltooit D1</p>
        <p>V1 verfrist WP1 en zie D2 <br/> V1 klikt op D2 en voltooit D2</p>
        <p>Marketer heeft wijzigingen aangebracht in D1 en opnieuw gepubliceerd</p>
        <p>V1 vernieuwt WP1</p>
      </td>
      <td>
        <p>D1 zal voor de eerste keer aan V1 worden opgelost</p>
        <p>Na vernieuwen wordt D2 omgezet in V1</p>
        <p>Na het invullen van D1 en D2, ongeacht welke wijzigingen of opnieuw gepubliceerde D1, wordt D2 niet opnieuw weergegeven in V1</p>
      </td>
      <td>
        <p>Het aantal triggers, het aantal contracten en het voltooide aantal voor D1 worden met 1 verhoogd</p>
        <p>Vernieuwen nadat D2 is voltooid, geen actie te ondernemen</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 die voor WP1 met "Tijd op Plaats"trekker van 30 seconden wordt gericht</p>
        <p>V1 bezoeken WP1</p>
      </td>
      <td>
        <p>D1 zal worden opgelost maar zal niet aan V1 in werking worden gesteld</p>
        <p>Na 30 seconden wordt D1 getoond/geactiveerd tot V1</p>
      </td>
      <td>Het aantal triggers voor D1 wordt slechts met 1 verhoogd nadat meer dan 30 seconden is doorgebracht op de webpagina</td>
    </tr>
    <tr>
      <td>
        <p>D1 gericht voor WP1, WP2 met "Tijd op pagina"trekker van 30 seconden</p>
        <p>V1 bezoeken WP1, WP2</p>
      </td>
      <td>
        <p>D1 zal worden opgelost maar zal niet aan V1 in werking worden gesteld</p>
        <p>Na 30 seconden wordt D1 getoond/geactiveerd tot V1</p>
      </td>
      <td>Het aantal triggers voor D1 wordt slechts met 1 verhoogd nadat meer dan 30 seconden is doorgebracht op de webpagina</td>
    </tr>
    <tr>
      <td>
        <p>D1 gericht voor WP1 met "scrollpercentage"trekker van 50</p>
        <p>V1 bezoeken WP1</p>
      </td>
      <td>
        <p>D1 zal worden opgelost maar zal niet aan V1 in werking worden gesteld</p>
        <p>Na 50% schuiven wordt D1 weergegeven/geactiveerd voor V1</p>
      </td>
      <td>Het aantal triggers voor D1 wordt pas met 1 verhoogd wanneer 50% wordt geschoven</td>
    </tr>
    <tr>
      <td>
        <p>D1 die voor WP1 met 1 prioriteit en gebeurtenis "Tijd op pagina"trekker van 30 seconden wordt gericht</p>
        <p>D2 gericht voor WP1 met 2 prioriteit en gebeurtenis "paginascrollpercentage"van 50</p>
        <p>V1 bezoeken WP1, na 10 seconden V1 bezoeken WP2, V1 bezoeken WP1</p>
      </td>
      <td>
        <p>Op WP1, zal D1 worden opgelost maar zal niet aan V1 in werking worden gesteld</p>
        <p>Op WP2 zal D2 worden opgelost maar niet aan V1 in werking gesteld</p>
        <p>Op WP1, zal D1 worden opgelost en na 20 seconden zal D1 aan V1 worden teweeggebracht</p>
      </td>
      <td>Het aantal triggers voor D1 wordt slechts na 30 seconden met 1 verhoogd</td>
    </tr>
    <tr>
      <td>
        <p>D1 die voor WP1 met "Tijd op Plaats"trekker van 1 minuut wordt gericht</p>
        <p>V1 bezoeken WP1 voor 1 minuut en getoond D1 maar niet</p>
        <p>V1 sluit WP1 en komt terug naar WP1 2 dagen later</p>
      </td>
      <td>
        <p>D1 zal automatisch aan V1 tonen aangezien zij reeds aan de trekkercriteria tijdens de vorige zitting hebben voldaan</p>
        <p>Dezelfde logica wordt toegepast op "Tijd op pagina" en "Schuifpercentage pagina"</p>
      </td>
      <td>
        <p>Het aantal triggers voor D1 wordt met 1 verhoogd</p>
        <p>Na terugkeer, geen actie te ondernemen</p>
      </td>
    </tr>
  </tbody>
</table>

## Resolutie van lead in realtime {#real-time-lead-resolution}

Tijdens een gesprek met een anonieme lead en een e-mailid is opgegeven, lossen we op of er een bekende lead-record met die e-mailid bestaat en gebruiken we die record voor personalisatie in real-time. Als wij veelvoudige verslagen vinden, voegen wij hen in real time samen. Dit gedrag wordt geïmplementeerd voor zowel Dialoogvensters als Conversationele stromen.
