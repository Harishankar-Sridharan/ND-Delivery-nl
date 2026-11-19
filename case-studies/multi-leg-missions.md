# Missies met meerdere etappes

**Nomadia Delivery** maakt gebruik van missies met meerdere trajecten om pakketten te volgen over meerdere hubs en agentschappen, van afhaling in de eerste mijl tot levering in de laatste mijl. Deze functie biedt end-to-end zichtbaarheid voor complexe supply chain-operaties door een missie langs elk contactpunt te volgen. U krijgt een volledige, traceerbare keten van bewaring voor elk pakket in uw netwerk.

#### Aan de slag

Om deze functie te gebruiken, moet u ervoor zorgen dat u een gebruikersaccount hebt met rechten voor uw specifieke agentschap.

* Toegang tot de **Nomadia Delivery** backoffice.
* Gebruikersaccount toegewezen aan een **Oorsprongsagentschap**.
* Geconfigureerde routeringsinfrastructuur voor geautomatiseerde zone-toewijzing.
* Log in op **Nomadia Delivery** als gebruiker van het **Oorsprongsagentschap**.

<figure><img src="../.gitbook/assets/image (1057).png" alt=""><figcaption></figcaption></figure>

#### Functieoverzicht

* **Agentschap**: Toont de huidige locatie van de missie en bepaalt de zichtbaarheid voor de gebruiker.
* **Oorsprongsagentschap**: Markeert de hub waar de afhaling in de eerste mijl begint.
* **Bestemmingsagentschap**: Markeert de laatste hub van waaruit de klant het pakket ontvangt.
* **Etappe**: Geeft de huidige fase aan: Verzameling, Distributie of Levering.

<figure><img src="../.gitbook/assets/image (1058).png" alt=""><figcaption></figcaption></figure>

#### Handleiding: Een missie met meerdere trajecten aanmaken

1. Klik op de **missie** tabblad.

<figure><img src="../.gitbook/assets/image (1059).png" alt=""><figcaption></figcaption></figure>

2. Selecteer **Toevoegen** vanuit de **Acties** menu.
3. Selecteer **Cross-Docking** als missietype, kies het vereiste agentschap en klik op **Volgende**.

<figure><img src="../.gitbook/assets/image (1060).png" alt=""><figcaption></figcaption></figure>



4. Selecteer de **Oorsprongsagentschap** en de **Bestemmingsagentschap**.
5. Stel de **Etappe** in op **Verzameling**.
6. Voer de details van de afhaal- en leveringslocatie in.
7. Klik op **Toevoegen** om de missie op te slaan.

<figure><img src="../.gitbook/assets/image (1061).png" alt=""><figcaption></figcaption></figure>

#### Handleiding: Missietrajecten en zichtbaarheid bijwerken (API /updateMultiLegStatusInformation)

1. Gebruik het **Bijwerkingspunt voor statusinformatie van meerdere trajecten** eindpunt om tussen trajecten te schakelen.
2. Stel de **Etappe** in op **Distributie** wanneer het item klaar is voor transport in de middenmijl.

<figure><img src="../.gitbook/assets/image (1062).png" alt=""><figcaption></figcaption></figure>

3. Navigeer naar de **Configuratie** module om de zichtbaarheid voor gebruikers te beheren.
4. Selecteer **Bewerken** voor een specifieke gebruiker op de **Gebruikers beheren** pagina.
5. Open de **Regels en rechten** tabblad.

<figure><img src="../.gitbook/assets/image (1063).png" alt=""><figcaption></figcaption></figure>

6. Activeer de **Beheer missies in transit** rechts.
7. Klik op **Opslaan** om de gebruiker missies te laten zien die hun hub hebben verlaten.

<figure><img src="../.gitbook/assets/image (1064).png" alt=""><figcaption></figcaption></figure>

8. De missies in transit worden nu weergegeven in de **Missies** tabblad.

<figure><img src="../.gitbook/assets/image (1065).png" alt=""><figcaption></figcaption></figure>

9. Werk de **Etappe** in op **Levering** bij wanneer de missie aankomt bij de laatste hub.
10. Stel de **Status** in op **Ontvangen** voor de gebruiker van het bestemmingsagentschap.

<figure><img src="../.gitbook/assets/image (1066).png" alt=""><figcaption></figcaption></figure>

#### Handleiding: Missiegeschiedenis controleren

1. Open een missie in het **Editor**.
2. Selecteer de **Logboeken** tabblad om elke statuswijziging en agentschapsovergang te bekijken.

<figure><img src="../.gitbook/assets/image (1067).png" alt=""><figcaption></figcaption></figure>

#### Productiviteitstips

* 💡 **Geautomatiseerde toewijzing**: Routeringsinfrastructuur vult automatisch agenten en subzones in zodra u de missie aanmaakt.
* 💡 **Flexibele invoer**: Maak missies rechtstreeks aan in de status distributie of levering als onderaannemers de eerste afhaling hebben afgehandeld.
* ⚠️ **Verlies van zichtbaarheid**: Missies verdwijnen normaal gesproken uit het oorsprongsoverzicht zodra ze de hub verlaten, tenzij specifieke rechten zijn ingeschakeld.
