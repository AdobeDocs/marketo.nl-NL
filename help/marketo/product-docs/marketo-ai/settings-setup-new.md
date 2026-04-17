---
description: Leer hoe u Marketo AI-machtigingen kunt inschakelen, organisatorische regels kunt configureren en instellingen zoals integratie en meldingen kunt beheren.
title: Instellingen en instellingen
hide: true
hidefromtoc: true
source-git-commit: 967c0accb8ac82a0b27c03de9d577cf48fb034eb
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 1%

---

# Instellingen en instellingen {#settings-setup}

Leer hoe te om toestemmingen toe te laten en het gebied van Montages te gebruiken om verbindingsdetails te bekijken, organisatorische regels te bepalen, en opstellingsintegratie en berichten.

## Machtigingen en rollen {#permission-and-role}

Er is een _Toegang bouwt met AI_ toestemming en a _bouwt met AI gebruiker_ rol, die beheerders grotere controle geeft waarover de gebruikers tot **kunnen toegang hebben bouwt met AI** eigenschap. De toestemming wordt toegewezen op het rolniveau. _bouwt met AI gebruiker_ rol komt met de _Toegang bouwt met AI_ toestemming die door gebrek wordt toegelaten.

>[!IMPORTANT]
>
>De _Toegang bouwt met AI_ toestemming wordt niet toegelaten door gebrek voor alle rollen. Zie de onderstaande tabel voor meer informatie.

<table><thead>
  <tr>
    <th>Functie</th>
    <th>Standaardstatus</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Beheerder</td>
    <td>Ingeschakeld</td>
  </tr>
  <tr>
    <td>Adobe-productbeheerder</td>
    <td>Ingeschakeld</td>
  </tr>
  <tr>
    <td>Gebruiker van marketing</td>
    <td>Uitgeschakeld</td>
  </tr>
  <tr>
    <td>Standaardgebruiker</td>
    <td>Niet beschikbaar</td>
  </tr>
  <tr>
    <td>Samenstellen met AI-gebruiker</td>
    <td>Ingeschakeld</td>
  </tr>
  <tr>
    <td>Aangepaste rollen</td>
    <td>Uitgeschakeld</td>
  </tr>
</tbody>
</table>

### Toegang tot build met AI-machtiging {#access-build-with-ai-permission}

Volg hieronder de stappen om _Toegang toe te laten bouwt met AI_ voor kwalificerende rollen die het niet reeds hebben toegelaten.

1. In uw Mijn Marketo, klik **Admin**, toen **Gebruikers &amp; Rollen**.

   ![](assets/settings-setup-1.png)

1. In het _lusje van Rollen_, selecteer de gewenste rol en klik **geef Rol** uit.

   ![](assets/settings-setup-2.png)

1. De rol neer en controleert _Toegang bouwt met AI_ checkbox en klikt **sparen**.

   ![](assets/settings-setup-3.png)

   >[!NOTE]
   >
   >U kunt deze zelfde stappen gebruiken om de toestemming te verwijderen door **niet** te controleren de _Toegang bouwt met AI_ checkbox.

### Samenstellen met AI-gebruikersrol {#build-with-ai-user-role}

Volgt deze stappen om een specifieke gebruiker aan _toe te wijzen bouwen met AI gebruiker_ rol.

>[!NOTE]
>
>Deze rol **slechts** bevat _Toegang bouwt met AI_ toestemmingen. Als u wilt dat de gebruiker toegang heeft tot meer dan alleen Marketo AI, moet u extra machtigingen toevoegen.

1. In uw Mijn Marketo, klik **Admin**, toen **Gebruikers &amp; Rollen**.

   ![](assets/settings-setup-1.png)

1. Selecteer de gewenste gebruiker en klik **uitgeven Gebruiker**.

   ![](assets/settings-setup-5b.png)

1. In _Rollen en Werkruimten_, selecteer _bouwen met AI gebruiker_ checkbox. Als u meer dan één werkruimte hebt, kunt u specificeren welke degenen toegang in **krijgen +** onderteken drop-down. Klik **sparen** wanneer gedaan.

   ![](assets/settings-setup-6b.png)

### Aangepaste rol {#custom-role}

U hebt ook de optie om een nieuwe rol [&#x200B; tot stand te brengen en zijn toestemmingen aan te passen, die &#x200B;](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role#create-a-role){target="_blank"} toegang bouwen met AI _, samen met om het even wat u wilt, en_ toewijzend die rol [&#x200B; aan specifieke gebruikers.](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user){target="_blank"}

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
