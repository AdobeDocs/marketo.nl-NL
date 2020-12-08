---
unique-page-id: 14746594
description: Een SMTP-server instellen - Marketo Docs - Productdocumentatie
title: Een SMTP-server instellen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---


# Een SMTP-server instellen {#setting-up-an-smtp-server}

## Overzicht {#overview}

**Wat is een server SMTP?**

**** Eenvoudig **** Protocol van de ******** Overdracht van de Post, is dit de server verantwoordelijk voor het verzenden van uw uitgaande post. Wanneer u een e-mailbericht verzendt van uw e-mailclient, gebruikt u dezelfde service om uw e-mailbericht te verzenden.

**Waarom wil ik mijn SMTP-server instellen met Sales Connect?**

Het staat u toe om de reputatie van het domein en de leverbaarheid van uw bedrijf te gebruiken, en niet op anderen te hoeven vertrouwen&quot;. Onze standaardMSC Servers maken deel uit van een gedeelde IP pool, wat het verzenden van een gedeelde reputatie betekent. We raden uw team ten zeerste aan om hun eigen leveringskanaal in te stellen met Sales Connect.

**Hoe verzendt Sales Connect met mijn SMTP-server?**

Voer [deze stappen](http://docs.marketo.com/x/ZgPh)uit.

![](assets/1.png)

`<pre><em>SMTP Server Setup Page in Sales Connect</em><br> </pre>` **Moet ik iets instellen in mijn e-mailclient?**

Wat een leveringskanaal betreft, nee. Nadat u de add-in hebt geïnstalleerd, gebruikt Sales Connect hetzelfde leveringskanaal als u hebt ingesteld voor het verzenden van e-mails.

## De SMTP-referenties ophalen {#getting-the-smtp-credentials}

**Hoe krijg ik mijn geloofsbrieven SMTP?**

Neem contact op met uw IT-team om na te gaan welk leveringskanaal uw bedrijf gebruikt om e-mails te verzenden en hoe u toegang krijgt tot uw SMTP-referenties. Afhankelijk van hoe uw server wordt gevormd, kunt u sommige douanewaarden voor de Naam van de Server SMTP of de Haven van de Server hebben. Neem contact op met uw e-mailprovider als u geen toegewezen IT-team hebt.

**Wat zijn mijn opties als mijn bedrijf Office365 gebruikt?**

Pros

* Eenvoudig in te stellen
* Om het even welke gebruiker met een rekening Office365 zal toegang tot deze server SMTP hebben

Cons

* Throtting kan optreden
* Elke gebruiker moet dit zelf instellen
* Het wijzigen van het O365-wachtwoord van een gebruiker leidt tot een verbroken verbinding

Als u Office365 of Uitwisseling Online gebruikt, kunt u met uw server verbinden SMTP gebruikend een standaardreeks geloofsbrieven. Houd er rekening mee dat Office365 geen service voor het leveren van grote hoeveelheden e-mail is, hoewel dit goed werkt bij het verzenden van eenmalige e-mails. Bij het verzenden van grote e-mailberichten kan Office365 uw e-mails vertragen, wat tot mislukte bezorging kan leiden. Meer over deze controle uit het artikel van Microsoft op [hoe te opstelling SMTP cliëntvoorlegging](http://support.office.com/en-us/article/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-office-365-69f58e99-c550-4274-ad18-c805d654b4c4).
`<blockquote>  <p>“You can only send from one email address unless your device can store login credentials for multiple Office 365 mailboxes. Office 365 imposes a limit of 30 messages sent per minute, and a limit of 10,000 recipients per day.”</p> </blockquote>`\
Als u besluit om Office365 als uw leveringskanaal te gebruiken, zult u deze geloofsbrieven moeten ingaan. De zelfde geloofsbrieven kunnen niet over het team worden gebruikt omdat Office365 e-mail en het wachtwoord van de gebruiker gebruikt om verbinding te maken.

Microsoft en bulksgewijs verzenden

[Klik hier](http://technet.microsoft.com/en-us/library/exchange-online-limits.aspx#RecipientLimits) voor meer informatie over bulkverzending in Office365.
`<blockquote>  <p>“Exchange Online customers who need to send legitimate bulk commercial email (for example, customer newsletters) should use third-party providers that specialize in these services.”</p> </blockquote>`\
**Wat als mijn bedrijf Gmail gebruikt?**

U hoeft geen SMTP-referenties op te halen als uw team Gmail wilt gebruiken als leveringskanaal met Sales Connect. Met Sales Connect kunnen gebruikers via onze OAuth-integratie toegang krijgen tot hun Gmail-leveringskanaal. Gebruikers kunnen dit inschakelen door hun Sales Connect-account te integreren met Gmail.

![](assets/2.png)

**Kan ik de zelfde geloofsbrieven SMTP met mijn volledige team delen?**

Dit hangt van het leveringskanaal af u gebruikt. De diensten zoals Sparkpost staan de geloofsbrieven toe om op domein-gebaseerd te zijn, zodat wordt iedereen die met een specifiek domein verzendt voor authentiek verklaard om door die server te verzenden. Als dit het geval is, dan ja, kunt u de geloofsbrieven met het team delen.

Als u verbinding maakt met Office365, zijn de gegevens gebaseerd op e-mailadressen. Dit betekent dat alleen het e-mailadres waarmee de verbinding tot stand is gebracht, wordt geverifieerd voor het verzenden van e-mails via dat leveringskanaal, zodat de gegevens **niet** mogen worden gedeeld.

![](assets/3.png)

