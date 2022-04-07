---
unique-page-id: 11382829
description: Marketo Outlook-insteekmodule verwijderd door IT - Marketo Docs - Productdocumentatie
title: Marketo Outlook-insteekmodule verwijderd door IT
exl-id: 678684da-3e99-462f-9950-504df1c1bb1e
source-git-commit: a24b0de6493d4849723099d6164fafb73ef7c926
workflow-type: tm+mt
source-wordcount: '128'
ht-degree: 0%

---

# Marketo Outlook-insteekmodule verwijderd door IT {#marketo-outlook-plugin-uninstall-by-it}

Zo kan de IT-afdeling de Marketo Outlook-insteekmodule extern verwijderen.

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

Zie [Microsoft&#39;s volledige lijst met switches](https://support.microsoft.com/en-us/office/command-line-switches-for-microsoft-office-products-079164cd-4ef5-4178-b235-441737deb3a6) als u verschillende registrerenniveaus of gebruikersinterfaceniveaus zou willen proberen.
