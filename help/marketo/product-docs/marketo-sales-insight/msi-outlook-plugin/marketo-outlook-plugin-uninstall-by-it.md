---
unique-page-id: 11382829
description: Marketo Outlook-insteekmodule verwijderd door IT - Marketo Docs - Productdocumentatie
title: Marketo Outlook-insteekmodule verwijderd door IT
translation-type: tm+mt
source-git-commit: 972cf9769ac751d9abfd5665975703dcd07930f0
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 0%

---


# Marketo Outlook-insteekmodule verwijderd door IT {#marketo-outlook-plugin-uninstall-by-it}

Hier is hoe IT de Insteekmodule Marketo Outlook extern kan verwijderen.

Voer de volgende bevellijn als zoals &quot;Systeem&quot;of een Administratieve gebruikersrekening met de /x schakelaar in werking om te desinstalleren.

`<pre>msiexec.exe /x [File Name] /qn </pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn </pre>`

Voor het oplossen van problemen kunt u registreren toelaten om een dossier van het outputlogboek tot stand te brengen.

`<pre>msiexec.exe /x [File Name] /qn /L*v MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v MarketoAddinUninstall.log</pre>`

Als u een locatie voor de logbestanden wilt opgeven, geeft u het bestandspad op de opdrachtregel op.

`<pre>msiexec.exe /x [File Name] /qn /L*v [File Path]MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**Voorbeeld**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddinUninstall.log</pre>`

>[!CAUTION]
>
>Als u de plug-in extern verwijdert, worden Outlook op de computer van de gebruiker forceerd gesloten.

Gelieve te verwijzen [de volledige lijst van Microsoft van schakelaars](https://support.microsoft.com/en-us/kb/227091) als u verschillende registrerenniveaus of gebruikersinterfaceniveaus zou willen proberen.
