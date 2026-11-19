# Levering bij PUDO

Het PUDO-(Pick-Up Drop-Off) bezorgproces stelt chauffeurs in staat pakketten om te leiden naar lokale afgiftepunten wanneer klanten niet beschikbaar zijn. Deze functie maakt dure herbezorgingsritten overbodig en houdt de achterstand in uw depot beheersbaar. U behaalt hogere succespercentages bij de eerste poging en biedt uw klanten meer flexibiliteit.

#### Aan de slag

Voordat u deze functie gebruikt, moet u ervoor zorgen dat aan de volgende vereisten is voldaan:

* PUDO-netwerkgegevens zijn geconfigureerd in het systeem.
* Het **fallback-bezorging in PUDO** veld is ingeschakeld voor de specifieke missie.
* Substatussen voor mislukte PUDO-afgiftes (bijv. "PUDO vol") zijn gedefinieerd in het **configuratiemenu**.
* Maak een route aan in de backoffice.
* Selecteer het selectievakje voor de route die u wilt delen in de **routetabel**.

<figure><img src="../../.gitbook/assets/image (1045).png" alt=""><figcaption></figcaption></figure>

* Klik op het **acties** knop.

<figure><img src="../../.gitbook/assets/image (1046).png" alt=""><figcaption></figcaption></figure>

* Selecteer **publiceren in de mobiele app**.

<figure><img src="../../.gitbook/assets/image (1047).png" alt=""><figcaption></figcaption></figure>

* Klik op **OK** om de publicatie te bevestigen.

<figure><img src="../../.gitbook/assets/image (1048).png" alt=""><figcaption></figcaption></figure>

#### Functieoverzicht

* **Pagina voor het selecteren van PUDO-punten**: Geeft een lijst weer van vooraf geladen relaislocaties nabij het adres van de klant.

<figure><img src="../../.gitbook/assets/image (1049).png" alt=""><figcaption></figcaption></figure>

* **Schuifregelaar zoekradius**: Hiermee kan de chauffeur de afstand vergroten of verkleinen om meer relaispunten te vinden.

<figure><img src="../../.gitbook/assets/image (1050).png" alt=""><figcaption></figcaption></figure>

* **ID van PUDO-bezorglocatie**: Registreert automatisch het specifieke punt waar de chauffeur het pakket heeft afgeleverd.

<figure><img src="../../.gitbook/assets/image (1051).png" alt=""><figcaption></figcaption></figure>

* **Tabblad missielogboeken**: Volgt elke actie van de eerste bezorgpoging tot de uiteindelijke PUDO-afgifte.

<figure><img src="../../.gitbook/assets/image (1052).png" alt=""><figcaption></figcaption></figure>

#### Hoe te beheren: Mislukte leveringen

**Chauffeur: Een pakket omleiden**

1. Tik op de gedeelde route in de mobiele app.
2. Laad het voertuig en tik op **mijn belading valideren**.

<figure><img src="../../.gitbook/assets/image (1053).png" alt=""><figcaption></figcaption></figure>

3. Tik op **mijn route starten**.
4. Selecteer op de locatie van de klant **niet bezorgen** als de klant afwezig is.

<figure><img src="../../.gitbook/assets/image (1054).png" alt=""><figcaption></figcaption></figure>

5. Selecteer de **klant niet beschikbaar** substatus.
6. Schuif de schuifregelaar om de zoekradius aan te passen indien nodig.
7. Selecteer een **PUDO-punt** uit de lijst.
8. Bevestig de status en ga verder met andere leveringen.
9. Wanneer u klaar bent om af te geven, tik dan op de melding van het relaispunt in de **routedetails**.
10. Selecteer de missie en gebruik de **scanner** om het pakket af te geven.

<figure><img src="../../.gitbook/assets/image (1055).png" alt=""><figcaption></figcaption></figure>

11. Leg de **handtekening** en een **foto** vast om de afgifte te valideren.

**Planner: De afgifte verifiëren**

1. Klik op het **verversknop** in de backoffice om realtime-updates te zien.

<figure><img src="../../.gitbook/assets/image (1056).png" alt=""><figcaption></figcaption></figure>

2. Open de missie in de **editor** om te verifiëren de **ID van PUDO-bezorglocatie**.
3. Controleer het **logtabblad** voor een volledige reeks acties met tijdstempels.

**Probleemoplossing: PUDO-problemen**

Als een PUDO-locatie vol of gesloten is:

1. Markeer de missie als **niet afgeleverd op de PUDO-locatie**.
2. Selecteer de specifieke substatus, zoals **PUDO vol** of **PUDO gesloten**.
3. De missie verschijnt als **onopgelost** voor de planner.
4. Neem de missie op in de volgende **planningscyclus** voor een herbezorgingspoging.

#### Productiviteitstips

* 💡 **Automatische detectie**: Het systeem identificeert automatisch PUDO-locaties binnen een straal van 5 km rond de route.
* 💡 **Vooraf geladen gegevens**: Chauffeurs hoeven niet handmatig te zoeken, omdat de dichtstbijzijnde opties al vooraf zijn geladen voordat ze de app openen.
* 💡 **Realtime synchronisatie**: Informatie wordt direct na bevestiging van de afgifte door de chauffeur gesynchroniseerd met de backoffice.
* ⚠️ **Nauwkeurige substatussen**: Gebruik altijd de juiste substatus voor volle of gesloten PUDO-punten om ervoor te zorgen dat de missie wordt gevolgd voor herbezorging.
