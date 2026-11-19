# Missies beheren

De volgende velden zijn beschikbaar op missieniveau, zodat u verschillende missiebeperkingen kunt configureren op basis van uw zakelijke vereisten.

| Sectie                  | Parameter                                          | Beschrijving                                                                                                                                                                                                                                                        |
| ----------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Algemene informatie** | Opdrachtnummer                                     | Een unieke identifier die automatisch of handmatig aan de missie wordt toegewezen voor tracking- en referentiedoeleinden.                                                                                                                                           |
|                         | Barcode afzender                                   | Barcode gekoppeld aan de afzender of zending, gebruikt voor scannen en snelle identificatie tijdens verwerkings- en bezorgingsactiviteiten.                                                                                                                         |
|                         | ID bovenliggende container                         | Identificeert de bovenliggende container waartoe de missie of zending behoort, waardoor hiërarchische zendingstracking mogelijk wordt.                                                                                                                              |
|                         | Groeperingssleutel                                 | Een waarde die wordt gebruikt om meerdere missies samen te groeperen voor planning, routering of operationele doeleinden.                                                                                                                                           |
|                         | Containertype                                      | Definieert het type container dat voor de zending wordt gebruikt (bijv. doos, pallet, envelop), wat van invloed kan zijn op handling- of transportbeperkingen.                                                                                                      |
|                         | Type statusconfiguratie                            | Specificeert de workflowconfiguratie voor statussen die op de missie wordt toegepast en bepaalt de beschikbare missiestaten en overgangen.                                                                                                                          |
|                         | Configuratietype meldingen                         | Definieert de meldingsregels die aan de missie zijn gekoppeld, zoals waarschuwingen die naar klanten, chauffeurs of operators worden gestuurd tijdens de voortgang van de missie.                                                                                   |
|                         | Geplande bezorger                                  | De geplande resource (chauffeur, technicus of agent) die is toegewezen om de missie uit te voeren.                                                                                                                                                                  |
|                         | Herkomst                                           | De startlocatie van waaruit de missie begint of waar de goederen worden opgehaald.                                                                                                                                                                                  |
|                         | Prioriteit                                         | Geeft het belangrijkheidsniveau van de missie aan, wat invloed kan hebben op de planningsvolgorde en uitvoeringsplanning.                                                                                                                                           |
|                         | Opslagplaats                                       | Specificeert de opslag- of magazijnlocatie die aan de missie is gekoppeld vóór verzending of na afronding.                                                                                                                                                          |
|                         | Vaste bezoekduur                                   | Definieert de verwachte duur die nodig is om de missie op de locatie te voltooien.                                                                                                                                                                                  |
|                         | Sleutels                                           | Referentie-ID's of tags die worden gebruikt voor classificatie-, filter- of integratiedoeleinden.                                                                                                                                                                   |
|                         | Compatibiliteit met de resources                   | Definieert beperkingen die ervoor zorgen dat alleen compatibele resources (op basis van vaardigheden, voertuigtype of configuratie) aan de missie kunnen worden toegewezen.                                                                                         |
|                         | Vereis dat alle vaardigheden compatibel zijn       | Wanneer ingeschakeld, moet de toegewezen resource over alle vereiste vaardigheden beschikken die voor de missie zijn gedefinieerd.                                                                                                                                  |
|                         | Levering moet worden uitgevoerd vóór elke ophaling | Zorgt ervoor dat leveringsactiviteiten worden voltooid vóór ophaaltaken binnen dezelfde missiesequentie.                                                                                                                                                            |
|                         | Eenmalig wachtwoord                                | Een beveiligingsverificatiecode die vereist is om voltooiing van de missie of leveringsbevestiging te valideren.                                                                                                                                                    |
|                         | Herkomstagentschap                                 | Het agentschap of de operationele eenheid die verantwoordelijk is voor het initiëren van de missie.                                                                                                                                                                 |
|                         | Bestemmingsagentschap                              | Het agentschap of de operationele eenheid die verantwoordelijk is voor het ontvangen of voltooien van de missie.                                                                                                                                                    |
|                         | Etappe                                             | Stelt een segment voor van een missie met meerdere fasen of een transportroute.                                                                                                                                                                                     |
|                         | Missiestatus                                       | Toont de huidige status van de missie binnen de operationele workflow (bijv. Gepland, Toegewezen, In uitvoering, Voltooid, Geannuleerd).                                                                                                                            |
| **Ophaalinformatie**    | Ophaling (adres)                                   | Specificeert het primaire adres waar de ophaling zal plaatsvinden.                                                                                                                                                                                                  |
|                         | Ophaling (adresaansluiting)                        | Geeft aanvullende adresgegevens zoals gebouwnaam, appartementnummer, verdieping of toegangs instructies om de ophaallocatie nauwkeurig te helpen vinden.                                                                                                            |
|                         | Ophaalaanduiding                                   | Identificeert de ophaallocatie of de organisatienaam die aan de zending is gekoppeld.                                                                                                                                                                               |
|                         | Ophaling (voornaam)                                | Voornaam van de contactpersoon die beschikbaar is op de ophaallocatie.                                                                                                                                                                                              |
|                         | Ophaling (achternaam)                              | Achternaam van de contactpersoon die verantwoordelijk is voor het coördineren van de ophaling.                                                                                                                                                                      |
|                         | Ophaling (mobiele telefoon)                        | Mobiel telefoonnummer van de contactpersoon voor ophaling, gebruikt voor communicatie tijdens de uitvoering van de missie.                                                                                                                                          |
|                         | Ophaling (vaste telefoon)                          | Vaste telefoonnummer van de ophaallocatie of contactpersoon.                                                                                                                                                                                                        |
|                         | Ophaling (e-mail)                                  | E-mailadres van het ophaalcontact voor het verzenden van meldingen of communicatie met betrekking tot de missie.                                                                                                                                                    |
|                         | Aanvraagdatum ophaling                             | De gevraagde datum en tijd waarop de ophaling moet beginnen.                                                                                                                                                                                                        |
|                         | Einddatum aangevraagde ophaling                    | De laatst acceptabele datum en tijd waarop de ophaling voltooid moet zijn.                                                                                                                                                                                          |
|                         | Ophaalinstructies                                  | Speciale instructies of operationele notities die aan de resource die de ophaling uitvoert worden verstrekt (bijv. toegangsprocedures, hanteringsvereisten, beveiligingsinstructies).                                                                               |
|                         | Scanbare containercode                             | Barcode of scanbare identifier gekoppeld aan de container, waardoor snelle verificatie en tracking tijdens ophaaloperaties mogelijk is.                                                                                                                             |
| **Leveringsinformatie** | Adres                                              | Specificeert het primaire bestemmingsadres waar de levering moet worden voltooid.                                                                                                                                                                                   |
|                         | Levering (adresaansluiting)                        | Geeft aanvullende locatiegegevens zoals appartementnummer, gebouwnaam, verdieping, poortnummer of toegangs instructies om het leveringspunt nauwkeurig te helpen vinden.                                                                                            |
|                         | Aanduiding                                         | Geeft de naam aan van de afleverlocatie, het bedrijf of de organisatie die de zending ontvangt.                                                                                                                                                                     |
|                         | Voornaam                                           | Voornaam van de ontvanger of contactpersoon op de afleverlocatie.                                                                                                                                                                                                   |
|                         | Achternaam                                         | Achternaam van de ontvanger of verantwoordelijke contactpersoon.                                                                                                                                                                                                    |
|                         | Mobiele telefoon                                   | Mobiel telefoonnummer van het leveringscontact, gebruikt voor communicatie tijdens de uitvoering van de levering.                                                                                                                                                   |
|                         | Vaste telefoon                                     | Vaste telefoonnummer gekoppeld aan de afleverlocatie of ontvanger.                                                                                                                                                                                                  |
|                         | E-mail                                             | E-mailadres van de ontvanger dat wordt gebruikt voor meldingen, bevestigingen of leveringsupdates.                                                                                                                                                                  |
|                         | Aanvraagdatum levering                             | De gevraagde datum en tijd waarop de levering moet beginnen of worden uitgevoerd.                                                                                                                                                                                   |
|                         | Einddatum aangevraagde levering                    | De laatst acceptabele datum en tijd waarop de levering voltooid moet zijn.                                                                                                                                                                                          |
|                         | Achteraf betalen                                   | Specificeert het bedrag dat op het moment van levering van de ontvanger moet worden geïnd, indien van toepassing.                                                                                                                                                   |
|                         | Leveringsprijs                                     | Definieert de leveringskosten die aan de missie zijn gekoppeld voor facturatie- of boekhoudkundige doeleinden.                                                                                                                                                      |
|                         | Leveringsinstructies                               | Speciale notities of operationele instructies die aan de leveringsresource worden verstrekt (bijv. toegangsprocedures, gewenste leveringstijd, voorzorgsmaatregelen bij handling).                                                                                  |
|                         | Fallback-levering in PUDO                          | Geeft aan of de zending kan worden omgeleid naar een Pick-Up and Drop-Off (PUDO)-punt als de primaire leveringspoging mislukt of de ontvanger niet beschikbaar is.                                                                                                  |
| **Aangepaste velden**   | Aangepaste velden                                  | De sectie Aangepaste velden stelt gebruikers in staat aanvullende informatie te definiëren en vast te leggen die specifiek is voor zakelijke vereisten en niet wordt gedekt door de standaard missievelden.                                                         |
| **Artikelen**           | Artikelen                                          | De sectie Artikelen bevat gedetailleerde informatie over de items of goederen die aan een missie zijn gekoppeld. Hiermee kunnen gebruikers de kenmerken, hoeveelheid en hanteringsvereisten van de producten die worden opgehaald of geleverd definiëren.           |
| **Openingstijden**      | Openingstijden                                     | De sectie Openingstijden definieert de tijdsperioden waarin een ophaal- of afleverlocatie beschikbaar is voor operationele activiteiten. Hiermee wordt gegarandeerd dat missies alleen binnen de toegestane werktijden van de locatie worden gepland en uitgevoerd. |
| **PUDO-informatie**     | PUDO-id                                            | Een unieke identifier toegewezen aan het Pick-Up and Drop-Off-punt, gebruikt voor tracking en systeemreferentie.                                                                                                                                                    |
|                         | PUDO (adresaansluiting)                            | Geeft aanvullende adresgegevens zoals gebouwinformatie, verdiepingnummer of specifieke toegangs instructies om het PUDO-punt gemakkelijk te helpen vinden.                                                                                                          |
|                         | PUDO-adres                                         | Specificeert het fysieke adres van de Pick-Up and Drop-Off-locatie.                                                                                                                                                                                                 |
|                         | PUDO-voornaam                                      | Voornaam van de verantwoordelijke contactpersoon op de PUDO-locatie.                                                                                                                                                                                                |
|                         | PUDO-achternaam                                    | Achternaam van de contactpersoon die de activiteiten op het PUDO-punt beheert of coördineert.                                                                                                                                                                       |
|                         | PUDO-vaste telefoon                                | Vaste telefoonnummer van de PUDO-locatie voor operationele communicatie.                                                                                                                                                                                            |
|                         | PUDO-mobiele telefoon                              | Mobiel telefoonnummer van de PUDO-contactpersoon voor realtime communicatie tijdens de uitvoering van de missie.                                                                                                                                                    |
|                         | PUDO-e-mail                                        | E-mailadres gekoppeld aan de PUDO-locatie, gebruikt voor meldingen en operationele correspondentie.                                                                                                                                                                 |
|                         | Vaste bezoekduur PUDO                              | Definieert de standaardtijd die nodig is om de activiteiten (ophaling of aflevering) op de PUDO-locatie te voltooien. Deze duur wordt door het planningssysteem gebruikt voor planning en route-optimalisatie.                                                      |
|                         | Ophalen PUDO                                       | Ophalen PUDO verwijst naar de Pick-Up and Drop-Off (PUDO)-locatie die is aangewezen als ophaalpunt voor een missie in plaats van het standaard ophaaladres.                                                                                                         |
|                         | Levering PUDO                                      | Levering PUDO verwijst naar de Pick-Up and Drop-Off (PUDO)-locatie die wordt gebruikt als alternatief of definitief leveringsadres in plaats van het primaire adres van de ontvanger.                                                                               |

### Voeg een missie toe

Missie toevoegen stelt gebruikers in staat een missie te maken door een missietype te selecteren, een configuratie te kiezen en verplichte missie-informatie in te voeren. Het systeem voert validaties uit op basis van het geselecteerde missietype.

1. Ga naar **Missies**\
   \&#xNAN;_Dit is de hoofdmodule waarin alle missies worden aangemaakt en beheerd._

<figure><img src="../../.gitbook/assets/image (422).png" alt=""><figcaption></figcaption></figure>

2. Klik op **Toevoegen** vanuit de **Acties** menu \&#xNAN;_Hiermee wordt het scherm voor het aanmaken van een missie geopend._

<figure><img src="../../.gitbook/assets/image (423).png" alt=""><figcaption></figcaption></figure>

\
3\. Selecteer **Opdrachttype**, **Agentschap** \&#xNAN;_(Ophaling → Levering of Levering → Ophaling op_   &#x20;

&#x20;   _basis van uw vereiste)_ \&#xNAN;_Dit definieert de workflow en verantwoordelijke instantie._

<figure><img src="../../.gitbook/assets/image (424).png" alt=""><figcaption></figcaption></figure>

4. Klik op **Volgende**\
   \&#xNAN;_Brengt u naar de stap voor configuratie-selectie._

<figure><img src="../../.gitbook/assets/image (425).png" alt=""><figcaption></figcaption></figure>

5.  Selecteer een **Missieconfiguratie**:

    * Standaardconfiguratie
    * Eventuele aangepaste configuratie die eerder is gemaakt\
      \&#xNAN;_Configuraties helpen het gedrag van de missie automatisch in te vullen of te sturen._

    <figure><img src="../../.gitbook/assets/image (426).png" alt=""><figcaption></figcaption></figure>
6. Enter **verplichte missiedetails** op basis van missietype \&#xNAN;_Velden variëren afhankelijk van of het Ophaling of Levering is._

<figure><img src="../../.gitbook/assets/image (427).png" alt=""><figcaption></figcaption></figure>

7. Klik op **Toevoegen** of **Toevoegen en afdrukken** \&#xNAN;_Toevoegen → Slaat de missie op_ \&#xNAN;_Toevoegen en afdrukken → Slaat de missiedetails op en drukt ze af_

<figure><img src="../../.gitbook/assets/image (428).png" alt=""><figcaption></figcaption></figure>

### Missiewizard: een begeleid stap-voor-stap proces

De missie-aanmaakwizard in Nomadia Delivery biedt een gebruiksvriendelijk, stapsgewijs proces om moeiteloos missies aan te maken en toe te voegen. Van het invoeren van basisgegevens van de missie tot het specificeren van openingstijden van de klant, vereenvoudigt de wizard de missie-instelling en zorgt hij tegelijkertijd voor nauwkeurigheid en efficiëntie gedurende het hele proces.

Volg deze stappen om een missie te maken met de wizard

1. Open het delivery managementsysteem en ga vervolgens naar het tabblad ‘**Missies**’

<figure><img src="../../.gitbook/assets/image (429).png" alt=""><figcaption></figcaption></figure>

2. Klik op de ‘**Acties**’-knop en kies ‘**Toevoegen**’ om de missie-aanmaakwizard te starten

<figure><img src="../../.gitbook/assets/image (430).png" alt=""><figcaption></figcaption></figure>

3. Selecteer het type **missie** en **agentschap**

<figure><img src="../../.gitbook/assets/image (431).png" alt=""><figcaption></figcaption></figure>

4. Details van het ophaaladres:

* **Voor ophaalmissies**: Voer de details van het ophaaladres in, zoals **adresregel, stad, staat/provincie, postcode**, en eventuele aanvullende instructies of herkenningspunten om een nauwkeurige identificatie te garanderen.
* **Voor leveringsmissies**: Het agentschapsadres wordt standaard gebruikt.

<figure><img src="../../.gitbook/assets/image (432).png" alt=""><figcaption></figcaption></figure>

5. Details van het leveringsadres:

* **Voor leveringsmissies**: Voer de **gegevens van het leveringsadres**. Het verstrekken van duidelijke en nauwkeurige informatie zorgt voor succesvolle en tijdige leveringen.
* **Voor ophaalmissies**: Het agentschapsadres wordt standaard gebruikt.

<figure><img src="../../.gitbook/assets/image (433).png" alt=""><figcaption></figcaption></figure>

\
6\. **Pakketinformatie (optioneel)**: In deze stap geeft u details over de pakketten, zoals **afmetingen, gewicht, inhoud**, en eventuele speciale vereisten voor handling. Het aanleveren van nauwkeurige pakketinformatie helpt een correcte behandeling te garanderen en de integriteit van de levering te behouden.

<figure><img src="../../.gitbook/assets/image (436).png" alt=""><figcaption></figcaption></figure>

\
7\. **Definitie van openingstijden van de klant (optioneel)**: Geef de openingstijden van de klant op om leveringen binnen geschikte tijdvakken te plannen. Dit zorgt ervoor dat de levertijden aansluiten bij de beschikbaarheid van de klant, waardoor de kans op gemiste leveringen of weigeringen afneemt.

<figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure>

8. **Missie toevoegen aan het Delivery Management System**: Nadat u alle vereiste informatie hebt ingevoerd, klikt u op de ‘**Toevoegen**’-knop om de missie op te slaan in het delivery managementsysteem. De missie is succesvol aangemaakt. Deze wizard stroomlijnt het proces door gebruikers stap voor stap te begeleiden en ervoor te zorgen dat alle vereiste informatie nauwkeurig wordt ingevoerd.

<figure><img src="../../.gitbook/assets/image (438).png" alt=""><figcaption></figcaption></figure>

9. De missie is succesvol aangemaakt. Deze wizard stroomlijnt het proces door gebruikers stap voor stap te begeleiden en ervoor te zorgen dat alle vereiste informatie nauwkeurig wordt ingevoerd

<figure><img src="../../.gitbook/assets/image (439).png" alt=""><figcaption></figcaption></figure>

### De velden van het importmissiebestand toewijzen

#### De adresvelden toewijzen

Vanaf de **Missiepagina**

1. Klik op **Acties**.
2. Selecteer **Importeren** uit het vervolgkeuzemenu.
3. Klik op **Bladeren (Excel).**
4. Selecteer de **Adres** van de locatie-indicatoren

<figure><img src="../../.gitbook/assets/image (440).png" alt=""><figcaption></figcaption></figure>

5. Klik op **Valideren**

<figure><img src="../../.gitbook/assets/image (441).png" alt=""><figcaption></figcaption></figure>

6. De adresvelden worden succesvol toegewezen

<figure><img src="../../.gitbook/assets/image (442).png" alt=""><figcaption></figcaption></figure>

### De missies inkleuren

Vanaf de **Missiepagina**

1. Klik op **Acties**.
2. Selecteer **Inkleuren** uit het vervolgkeuzemenu.

<figure><img src="../../.gitbook/assets/image (443).png" alt=""><figcaption></figcaption></figure>

3. Selecteer de juiste voorwaarde uit de suggesties.
4. Kies het **Kleur**
5. Klik op **Opslaan**

<figure><img src="../../.gitbook/assets/image (444).png" alt=""><figcaption></figcaption></figure>

6. De geselecteerde kleur wordt succesvol toegepast.

<br>

<br>
