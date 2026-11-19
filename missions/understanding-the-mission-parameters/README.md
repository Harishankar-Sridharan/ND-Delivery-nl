# De missieparameters begrijpen

### De missieparameters begrijpen

Missieparameters zijn de kerngegevens die de kenmerken, doelstellingen en uitvoeringsdetails van elke missie definiëren. Het begrijpen van deze parameters is essentieel om ervoor te zorgen dat missies correct worden geconfigureerd, toegewezen en uitgevoerd in het veld.

Deze parameters bieden zowel operationele als logistieke informatie die wordt gebruikt door

coördinatoren, dispatchers en bezorgers.

#### Missieparameters openen

Vanaf de **Missiepagina**

1. Klik op het **potlood** pictogram naast de missie die u wilt bewerken

<figure><img src="../../.gitbook/assets/image (421).png" alt=""><figcaption></figcaption></figure>

#### Beschrijving van missieparameters

### Tabblad Missieparameters <a href="#tabblad-missieparameters" id="tabblad-missieparameters"></a>

### Missie

| Sectie     | Parameter                                    | Beschrijving                                                                                              |
| ---------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Missie** | Barcode                                      | Automatisch gegenereerd door Nomadia Delivery om de missie uniek te identificeren.                        |
|            | Agentschap (verplicht)                       | Verplicht veld dat het agentschap specificeert dat verantwoordelijk is voor de afhandeling van de missie. |
|            | Onderaannemer                                | Externe bezorgdienst toegewezen om de missie te voltooien.                                                |
|            | Barcode afzender                             | Optionele barcode aangeleverd door de opdrachtnemer.                                                      |
|            | ID bovenliggende container                   | Identificeert de hoofdcontainer of groep waartoe de missie behoort.                                       |
|            | Groeperingssleutel                           | Groepeert missies die aan dezelfde klant zijn gekoppeld voor eenvoudiger afhandeling.                     |
|            | Containertype                                | Type gebruikte container (doos, pallet, krat, enz.).                                                      |
|            | Herkomst                                     | Oorspronkelijke verzendlocatie van de levering.                                                           |
|            | Geplande bezorger                            | Naam van de toegewezen bezorger.                                                                          |
|            | Prioriteit                                   | Geeft urgentie aan (hoog, gemiddeld, laag).                                                               |
|            | Type statusconfiguratie                      | Definieert de workflow die op de missie wordt toegepast.                                                  |
|            | Enkel type wachtwoord                        | Beveiligingscode (PIN/OTP) gebruikt voor verificatie.                                                     |
|            | Missiestatus                                 | Huidige missiestatus (bijv. Wachtend, Geleverd).                                                          |
|            | Substatus                                    | Gedetailleerde status binnen de hoofdstatus.                                                              |
|            | Reden                                        | Reden voor de huidige substatus.                                                                          |
|            | Opdrachttype                                 | Levering, afhaling, gekoppelde afhaling & levering, bezoek, dropshipping.                                 |
|            | Voorlopige datum                             | Voorlopige missiedatum.                                                                                   |
|            | Scan datum hoofdepot                         | Datum/tijd waarop gescand bij het depot.                                                                  |
|            | Opslagplaats                                 | Locatie binnen het depot waar het item is opgeslagen.                                                     |
|            | Vaste bezoekduur                             | Geschatte tijd (in minuten) om de missie te voltooien.                                                    |
|            | Compatibiliteit met middelen                 | Geeft compatibiliteit met toegewezen middelen aan.                                                        |
|            | Vereis dat alle vaardigheden compatibel zijn | Zorgt ervoor dat het middel aan alle vereiste vaardigheden voldoet.                                       |
|            | Levering vóór afhaling                       | Dwingt de volgorde levering vóór afhaling af.                                                             |
|            | Sleutels                                     | Geeft aan of sleutels/toegangscodes vereist zijn.                                                         |
|            | Positie                                      | Volgorde van de missie in de route.                                                                       |

***

### Pakket

| Sectie     | Parameter    | Beschrijving                                                 |
| ---------- | ------------ | ------------------------------------------------------------ |
| **Pakket** | Producttype  | Categorie van het product (bijv. elektronica, boodschappen). |
|            | Lengte       | Pakketlengte.                                                |
|            | Breedte      | Pakketbreedte.                                               |
|            | Hoogte       | Pakkethoogte.                                                |
|            | Gewicht      | Pakketgewicht.                                               |
|            | Volume       | Pakketvolume.                                                |
|            | Pakketwaarde | Aangegeven geldwaarde.                                       |
|            | Opmerking    | Interne notities voor de missie.                             |

***

### Afhaling

| Sectie       | Parameter                          | Beschrijving                                             |
| ------------ | ---------------------------------- | -------------------------------------------------------- |
| **Afhaling** | Adres (verplicht)                  | Afhaaladres (niet-bewerkbaar na routering).              |
|              | Contactgegevens                    | Functie, naam, telefoonnummer en e-mail van de afzender. |
|              | Opgehaald door                     | Persoon/agent die de afhaling heeft uitgevoerd.          |
|              | Aanvraagdatum afhaling / einddatum | Gevraagd tijdvenster voor afhaling.                      |
|              | Scanbare containercode             | Barcode voor identificatie van de container.             |
|              | Afhaalinstructies / opmerking      | Speciale instructies voor afhaling.                      |

***

### Levering

| Sectie       | Parameter                          | Beschrijving                                              |
| ------------ | ---------------------------------- | --------------------------------------------------------- |
| **Levering** | Adres (verplicht)                  | Afleveradres (niet-bewerkbaar na routering).              |
|              | Contactgegevens                    | Functie, naam, telefoonnummer en e-mail van de ontvanger. |
|              | Geleverd door                      | Persoon/agent die de levering heeft voltooid.             |
|              | Aanvraagdatum levering / einddatum | Gevraagd tijdvenster voor levering.                       |
|              | Onder rembours                     | Te innen bedrag.                                          |
|              | Leveringsprijs                     | Leveringskosten voor facturering.                         |
|              | Leveringsinstructies / opmerking   | Speciale leveringsinstructies.                            |

***

### Artikelen

| Sectie        | Parameter     | Beschrijving                               |
| ------------- | ------------- | ------------------------------------------ |
| **Artikelen** | Soort artikel | Gedefinieerd itemtype.                     |
|               | Gepland       | Geplande hoeveelheid (0 = niet gekoppeld). |
|               | Gereed        | Werkelijk voltooide hoeveelheid.           |

***

### Openingstijden

| Sectie             | Parameter     | Beschrijving                                           |
| ------------------ | ------------- | ------------------------------------------------------ |
| **Openingstijden** | Openingsslots | Toegestane tijdvensters voor uitvoering van de missie. |

***

### Foto's

| Sectie     | Parameter | Beschrijving                                    |
| ---------- | --------- | ----------------------------------------------- |
| **Foto's** | Foto's    | Afbeeldingen gemaakt tijdens afhaling/levering. |

***

### Handtekeningen

| Sectie             | Parameter      | Beschrijving                                         |
| ------------------ | -------------- | ---------------------------------------------------- |
| **Handtekeningen** | Handtekeningen | Handtekeningen van opdrachtnemer, bezorger en klant. |

***

### Documenten

| Sectie         | Parameter  | Beschrijving                                                     |
| -------------- | ---------- | ---------------------------------------------------------------- |
| **Documenten** | Documenten | Bestanden gekoppeld uit de Nomadia-bibliotheek of clouddiensten. |

***

### Logboeken

| Sectie        | Parameter            | Beschrijving                                             |
| ------------- | -------------------- | -------------------------------------------------------- |
| **Logboeken** | Missiegebeurtenissen | Tijdlijn van alle missiegebeurtenissen met tijdstempels. |

\
​
