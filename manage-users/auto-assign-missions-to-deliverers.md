# Missies automatisch toewijzen aan bezorgers

De functie voor automatische toewijzing in Nomadia Delivery vereenvoudigt de dispatching door missies automatisch toe te wijzen aan de juiste bezorgers en voertuigen op basis van vooraf gedefinieerde ruimtelijke of postale zones. Dit vermindert de handmatige inspanning, minimaliseert de administratieve werklast en verbetert de efficiëntie, met name bij operaties met een hoog volume.

Voorvereiste: om automatische missie-toewijzingen te gebruiken, moet u vooraf een postcodezone of een ruimtelijke zone hebben geconfigureerd. Raadpleeg voor stapsgewijze begeleiding de handleiding Zonecreatie via automatische sectorisatie.

Volg onderstaande stappen om zones te koppelen aan gebruikers en voertuigen:

1. Open de Nomadia Delivery-applicatie en ga naar het **Tabblad Configuratie.**
2. Selecteer in de vervolgkeuzelijst **Gebruikers beheren**.

**Opmerking**: Zones kunnen alleen worden gekoppeld aan gebruikers die mobiele toegang hebben.

3. Klik op het **Potlood** pictogram naast de gewenste mobiele gebruiker.

<figure><img src="../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

4. Gebruikers met mobiele toegang zien een extra tabblad voor het configureren van zonerechten. Klik **Agentschappen** en **zones** om zone-toewijzingen in te stellen.
5. Verplaats de beschikbare zones van de gekoppelde agentschappen naar het rechterpaneel om ze aan de gebruiker toe te wijzen.

<figure><img src="../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

6. Nadat u de zone-instellingen hebt aangepast, klikt u op **Opslaan** om de wijzigingen te bevestigen.

<figure><img src="../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

Als de gebruiker aan een voertuig is gekoppeld, worden alle zone-instellingen automatisch met dat voertuig gesynchroniseerd.

<figure><img src="../.gitbook/assets/image (184).png" alt=""><figcaption></figcaption></figure>

Nomadia Delivery maakt het ook mogelijk om gebruikers en voertuigen in uitzonderlijke gevallen aan verschillende zones toe te wijzen, zoals bij ziekteverlof of plotselinge onbeschikbaarheid. In dergelijke scenario’s verschijnt een synchronisatiefout in de sectie Algemeen van het voertuig.

<figure><img src="../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>

Zodra gebruikers en voertuigen correct zijn gesynchroniseerd met hun zone-instellingen, worden missies automatisch toegewezen op basis van ruimtelijke afstemming. Als de ophaal- of afleverlocatie van een missie binnen een geconfigureerde zone valt, wordt automatisch de bijbehorende gebruiker of het voertuig dat aan die zone is gekoppeld toegewezen, en wordt het veld Geplande bezorger bijgewerkt.

<figure><img src="../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>

Als meerdere gebruikers dezelfde zone delen, wijst het systeem de missie toe aan de eerste gebruiker.

<figure><img src="../.gitbook/assets/image (187).png" alt=""><figcaption></figcaption></figure>

Tijdens optimalisatie heeft de planner drie opties:

* Gebruik alleen de automatisch toegewezen geplande bezorger.
* Sta toe dat alle compatibele voertuigen in aanmerking worden genomen voor optimalisatie.
* Negeer de automatisch toegewezen bezorgers.

<figure><img src="../.gitbook/assets/image (188).png" alt=""><figcaption></figcaption></figure>
