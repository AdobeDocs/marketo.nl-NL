---
description: Leer hoe u Marketo AI-machtigingen kunt inschakelen, organisatorische regels kunt configureren en instellingen zoals integratie en meldingen kunt beheren.
title: Instellingen en instellingen
hide: true
hidefromtoc: true
exl-id: d6f37214-65b9-48c1-bf9f-d64b4eda87b9
source-git-commit: 491c2fc587fdeee1cbb65a8022f91c6f7c9a65be
workflow-type: tm+mt
source-wordcount: '333'
ht-degree: 0%

---

# Instellingen en instellingen {#settings-setup}

Leer hoe te om toestemmingen toe te laten en het gebied van Montages te gebruiken om verbindingsdetails te bekijken, organisatorische regels te bepalen, en opstellingsintegratie en berichten.

## Machtigingen {#permissions}

>[!IMPORTANT]
>
>In de fase van Alpha van Marketo AI, _wordt de toegang toegelaten door gebrek_ voor de volgende rollen: Admin, de Marketing Gebruiker van Admin van het Product van Adobe, StandaardGebruiker. Dus in plaats van het in te schakelen voor rollen die je toegang wilt hebben, moet je het uitschakelen voor rollen die je niet hebt.

### Toegang voor iedereen {#access-for-all}

Als u Marketo AI ingeschakeld wilt voor alle rollen hierboven, hoeft u niets te doen.

### Toegang voor sommigen {#access-for-some}

Als u toegang voor om het even welke rollen wilt verwijderen, volg de hieronder stappen.

1. In uw Mijn Marketo, klik **Admin**, toen **Gebruikers &amp; Rollen**.

   ![](assets/settings-setup-1.png)

1. In het _lusje van Rollen_, selecteer de gewenste rol (of rollen) en klik **geef Rol** uit.

   ![](assets/settings-setup-2.png)

1. De rol neer en _uncheck_ de **Toegang bouwt met AI** checkbox en klikt **sparen**.

   ![](assets/settings-setup-3.png)

### Aangepaste rol {#custom-role}

U hebt ook de optie om een nieuwe rol [&#x200B; tot stand te brengen en zijn toestemmingen aan te passen, die &#x200B;](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role#create-a-role){target="_blank"} toegang bouwen met AI _samen met om het even wat u wilt, en_ toewijzend die rol [&#x200B; aan specifieke gebruikers.](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user){target="_blank"}

<!-- ## Permissions {#permissions}

In order to access Marketo AI, Admins must first enable role permissions. 

1. In your My Marketo, click **Admin**, then **Users & Roles**.

   ![](assets/settings-setup-1.png)

1. In the _Roles_ tab, select the desired role and click **Edit Role**.

   ![](assets/settings-setup-2.png)

1. Scroll down and select the **Access Build with AI** checkbox and click **Save**.

   ![](assets/settings-setup-3.png)

-->

## Instellingen {#settings}

1. In uw Mijn Marketo, klik **bouwen met AI** tegel.

   ![](assets/settings-setup-4.png)

1. Klik op het tandwielpictogram.

   ![](assets/settings-setup-5.png)

### Verbinding {#connection}

Dit tabblad bevat geen bewerkbare velden. U ziet hier accountgegevens zoals uw Munchkin-id en IMS-organisatie.

![](assets/settings-setup-6.png)

### Organisatieregels {#organizational-rules}

Organisatierichtlijnen en restricties definiëren die de Marketo AI volgt bij het maken of wijzigen van Marketo Engage-elementen.

![](assets/settings-setup-7.png){width="800" zoomable="yes"}

>[!NOTE]
>
>Regels gebruiken de opmaak Markering met de voorgrond van YAML. Algemene regels gelden voor alle werkruimten. Workspace-regels overschrijven algemene instellingen.

### Integraties (binnenkort beschikbaar) {#integrations}

Verbindingen met externe services en API&#39;s configureren.

_Dit lusje kan in UI verschijnen, maar het is nog niet beschikbaar voor gebruik. Gelieve te controleren terug voor updates_.

### Meldingen (binnenkort beschikbaar) {#notifications}

Waarschuwingsvoorkeuren en berichtkanalen beheren.

_Dit lusje kan in UI verschijnen, maar het is nog niet beschikbaar voor gebruik. Gelieve te controleren terug voor updates_.
