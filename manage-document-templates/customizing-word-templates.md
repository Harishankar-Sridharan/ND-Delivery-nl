# Word-sjablonen aanpassen

Deze gids biedt stap-voor-stap instructies voor het aanpassen van uw Word-sjabloon dat wordt gebruikt in de PDF-exportfunctie, zodat u leveringsgerelateerde documenten kunt downloaden, zoals routebladen, laadbladen, eCMR, missierapporten, stickervellen en bezoekrapporten.

Volg deze stappen om documentsjablonen te beheren:

1. Open de Nomadia Delivery-applicatie en ga naar het **Configuratie** tabblad.
2. Selecteer in het vervolgkeuzemenu **Documentsjablonen.**

<figure><img src="../.gitbook/assets/image (671).png" alt=""><figcaption></figcaption></figure>

De pagina toont alle standaardsjablonen die Nomadia Delivery gebruikt om PDF’s te genereren, waaronder routebladen, laadbladen, eCMR, missierapporten, stickervellen en bezoekrapporten.

<figure><img src="../.gitbook/assets/image (672).png" alt=""><figcaption></figcaption></figure>

Standaardsjablonen in Nomadia Delivery zijn standaard ingeschakeld en kunnen niet worden uitgeschakeld, gewijzigd of verwijderd. Als u echter een sjabloon wilt aanpassen, kunt u het bestaande sjabloon downloaden en de nodige wijzigingen aanbrengen om aan uw behoeften te voldoen.

Volg deze stappen om een bestaand sjabloon te downloaden:

1. Selecteer de **sjabloon(s)** die u wilt downloaden.

<figure><img src="../.gitbook/assets/image (673).png" alt=""><figcaption></figcaption></figure>

2. Open de **Acties** menu en kies **Downloaden**.

<figure><img src="../.gitbook/assets/image (674).png" alt=""><figcaption></figcaption></figure>

3. Er wordt een ZIP-bestand gegenereerd met alle geselecteerde sjablonen.

<figure><img src="../.gitbook/assets/image (675).png" alt=""><figcaption></figcaption></figure>

Volg deze stappen om een bestaand sjabloon te wijzigen:

1. Open het gedownloade sjabloon in Microsoft Word.

<figure><img src="../.gitbook/assets/image (676).png" alt=""><figcaption></figcaption></figure>

2. Raadpleeg het bijgevoegde document FieldsMaster\_DocumentTemplate, waarin alle beschikbare velden staan die binnen het sjabloon kunnen worden gebruikt.
3. Pas het sjabloon aan uw wensen aan door indien nodig velden toe te voegen of te verwijderen uit het veldendocument. Zorg er bij het toevoegen van velden voor dat ze als samengevoegde velden worden ingevoegd en niet als platte tekst, om problemen tijdens het genereren van de PDF te voorkomen. Samengevoegde velden (bijv. «${ (contractor.name)!}») worden wanneer ze zijn geselecteerd gemarkeerd met een grijze achtergrond, terwijl platte tekstvelden dat niet worden.

| Platte tekst          | Samengevoegd veld       |
| --------------------- | ----------------------- |
| ${(contractor.name)!} | «${(contractor.name)!}» |

Volg deze stappen om platte tekst om te zetten in een samenvoegveld:

1. Kopieer de platte tekst van het veld, bijvoorbeeld: ${(contractor.name)!}.
2. Ga naar **Invoegen → Snelle onderdelen → Veld.**

<figure><img src="../.gitbook/assets/image (677).png" alt=""><figcaption></figcaption></figure>

3. Selecteer in de vervolgkeuzelijst Categorieën **Mailmerge**, kies vervolgens **Samenvoegveld** onder Veldnamen
4. Plak de **veldnaam** die u hebt gekopieerd in het tekstvak Veldnaam en klik op **OK**.
5. De platte tekst wordt nu omgezet in een samenvoegveld en ziet eruit als: «${(contractor.name)!}»

<figure><img src="../.gitbook/assets/image (678).png" alt=""><figcaption></figcaption></figure>

"Volg deze stappen om een nieuw sjabloon te activeren."

1. Zodra het nieuwe sjabloon klaar is, gaat u naar de sectie Documentsjablonen om het te uploaden.
2. Ga naar de module Configuratie en selecteer **Documentsjablonen** in het menu.
3. Klik op de **Acties** menu en kies **Importeren**.

<figure><img src="../.gitbook/assets/image (679).png" alt=""><figcaption></figcaption></figure>

4. Blader op uw computer en selecteer het **sjabloon** dat u zojuist hebt gemaakt.

<figure><img src="../.gitbook/assets/image (680).png" alt=""><figcaption></figcaption></figure>

5. Werk indien nodig de identificatie of bestandsnaam bij.

<figure><img src="../.gitbook/assets/image (681).png" alt=""><figcaption></figcaption></figure>

6. Kies het **sjabloontype** in het vervolgkeuzemenu (bijv. Vrachtbrieksjabloon).

<figure><img src="../.gitbook/assets/image (682).png" alt=""><figcaption></figcaption></figure>

7. Selecteer de **agentschap** of agentschappen waar het sjabloon beschikbaar moet zijn (bijv. Louisiana).

<figure><img src="../.gitbook/assets/image (684).png" alt=""><figcaption></figcaption></figure>

8. Klik op **Opslaan** om het sjabloon te uploaden.

<figure><img src="../.gitbook/assets/image (685).png" alt=""><figcaption></figcaption></figure>

Het nieuw geüploade sjabloon verschijnt nu in de sjablonentabel.

Nieuwe sjablonen zijn standaard uitgeschakeld. Om het sjabloon in te schakelen:

9. Selecteer het geüploade sjabloon en klik op de **Acties** menu.
10. Kiezen **In-/uitschakelen** om het sjabloon te activeren.

<figure><img src="../.gitbook/assets/image (686).png" alt=""><figcaption></figcaption></figure>

11. Een melding bevestigt dat het sjabloon succesvol is bijgewerkt, en in de kolom Ingeschakeld staat Ja.

<figure><img src="../.gitbook/assets/image (687).png" alt=""><figcaption></figcaption></figure>

Volg deze stappen om een PDF te genereren met behulp van het nieuw ingeschakelde sjabloon:

1. Navigeer naar de **Missies** tabblad en selecteer een route die naar de mobiele bezorger is gepubliceerd.

<figure><img src="../.gitbook/assets/image (688).png" alt=""><figcaption></figcaption></figure>

2. Klik op de **Acties** menu en kies **Vrachtbrief**.

<figure><img src="../.gitbook/assets/image (689).png" alt=""><figcaption></figcaption></figure>

3. Klik op de knop Downloaden om de vrachtbrief te downloaden.

<figure><img src="../.gitbook/assets/image (690).png" alt=""><figcaption></figcaption></figure>

4. De gedownloade PDF wordt gegenereerd met behulp van het nieuw ingeschakelde sjabloon.

<figure><img src="../.gitbook/assets/image (691).png" alt=""><figcaption></figcaption></figure>

Volg deze stappen om een sjabloon te verwijderen

1. Open de Nomadia Delivery-applicatie en ga naar het **Configuratie** tabblad.
2. Selecteer in het vervolgkeuzemenu **Documentsjablonen.**

<figure><img src="../.gitbook/assets/image (692).png" alt=""><figcaption></figcaption></figure>

3. Kies in de tabel een niet-standaard sjabloon en klik vervolgens op de **Acties** menu.
4. Selecteer **Verwijderen** om het sjabloon te verwijderen.

<figure><img src="../.gitbook/assets/image (693).png" alt=""><figcaption></figcaption></figure>

5. Bevestig de verwijdering door op **Ja**.

<figure><img src="../.gitbook/assets/image (694).png" alt=""><figcaption></figcaption></figure>

6. te klikken.

<figure><img src="../.gitbook/assets/image (695).png" alt=""><figcaption></figcaption></figure>

Het geselecteerde sjabloon wordt permanent uit de applicatie verwijderd.

Volg deze stappen om de sjablooninstellingen te wijzigen.

1. Sjablooninstellingen omvatten het type document waaraan het sjabloon is gekoppeld, zoals Routeblad, Laadblad, Stickervel, Vrachtbrief, Bezoekrapport of Missierapport, en de agentschappen waarvoor het sjabloon beschikbaar is **Bewerken** Om de instellingen te wijzigen, klikt u op de

<figure><img src="../.gitbook/assets/image (696).png" alt=""><figcaption></figcaption></figure>

2. knop naast de sjabloonnaam.

<figure><img src="../.gitbook/assets/image (697).png" alt=""><figcaption></figcaption></figure>

3. U kunt het documenttype en de bij het sjabloon horende agentschappen bijwerken. **Opslaan** Zodra de wijzigingen zijn aangebracht, klikt u op

<figure><img src="../.gitbook/assets/image (701).png" alt=""><figcaption></figcaption></figure>

### om de bijgewerkte instellingen toe te passen en op te slaan.

Type aangepaste configuratie

Configuratietype substatus

Configuratietypen voor substatus definiëren de tussenstappen of voorwaarden binnen de levenscyclus van een missie. Waar deze voorheen beperkt waren tot BASIS, INTERMEDIAIR en GEAVANCEERD, hebben planners nu de flexibiliteit om onbeperkt aangepaste substatustypen te maken die aansluiten bij specifieke bedrijfsprocessen.

Configuratietype meldingen

Configuratietypen voor meldingen bepalen hoe en wanneer klanten tijdens de levenscyclus van de missie worden geïnformeerd. In plaats van op één sjabloon te vertrouwen, kunnen planners nu meerdere meldingssjablonen instellen voor verschillende scenario’s.

Beide configuratietypen kunnen automatisch worden toegewezen op basis van missie-attributen, zoals klanttype of pakketwaarde.

Volg deze stappen om het type te configureren

1. Open de Nomadia Delivery-toepassing en ga naar de **Configuratie** tabblad.
2. Selecteer in de vervolgkeuzelijst **Configuratietypen.**
3. Standaard biedt Nomadia Delivery drie configuratietypen: BASIS, INTERMEDIAIR en GEAVANCEERD. U kunt deze bestaande typen gebruiken of vanaf nul een nieuw type maken.
4. Om een bestaand configuratietype te bewerken, klikt u op het potloodpictogram ernaast.

<figure><img src="../.gitbook/assets/image (702).png" alt=""><figcaption></figcaption></figure>

5. Activeer op het tabblad Algemeen de schakelaars op basis van uw behoeften:
   * Schakel beide schakelaars in als het configuratietype moet gelden voor substatus en meldingen.
   * Schakel ze afzonderlijk in of uit als u aparte configuraties voor substatus en meldingen wilt.
6. U kunt automatische toewijzingsregels definiëren zodat configuratietypen zonder handmatige inspanning worden toegepast. Deze regels zijn gebaseerd op velden van het missieobject:
   * Als aan een voorwaarde wordt voldaan, wordt het configuratietype automatisch toegepast op substatus en/of melding.
   * Er kunnen meerdere voorwaarden worden ingesteld, en u kunt bepalen of aan alle voorwaarden moet worden voldaan of dat één voorwaarde voldoende is door de schakelaar **Volg alle regels** in te schakelen.
7. Als meerdere configuratietypen aan de voorwaarden voldoen, wijst het systeem het type met de hoogste prioriteit toe (waarbij 1 de hoogste is).

<figure><img src="../.gitbook/assets/image (703).png" alt=""><figcaption></figcaption></figure>

8. De onderstaande tabel illustreert hoe verschillende configuratietypen, voorwaarden en regels de automatische toewijzing van waarden in het missieobject beïnvloeden.

| <p><br>Configuratietype</p> | Van toepassingop    | Regels                                                                      | Automatische toewijzing ophet missieobject                                                            |
| --------------------------- | ------------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| BASIS                       | Substatus & Melding | Pakketwaarde < 49€Prioriteit = 4Volg alle regels = NEE                      | Als de pakketwaarde van de missie = 39€Statusconfiguratietype = BASISConfiguratietype melding =BASIS  |
| INTERMEDIAIR                | Substatus & Melding | Pakketwaarde < 100€ Pakketwaarde > 50€ Prioriteit = 3Volg alle regels = JA  | Als de pakketwaarde = 99€Statusconfiguratietype = INTERMEDIAIRConfiguratietype melding = INTERMEDIAIR |
| GEAVANCEERD                 | Substatus & Melding | Pakketwaarde < 500€ Pakketwaarde > 100€ Prioriteit = 2Volg alle regels = JA | Als de pakketwaarde = 499€Statusconfiguratietype = GEAVANCEERDConfiguratietype melding = GEAVANCEERD  |
| LUXE                        | Substatus & Melding | Pakketwaarde > 500€Prioriteit = 1Volg alle regels = NEE                     | Als de pakketwaarde = 500€Statusconfiguratietype = LUXEConfiguratietype melding =LUXE                 |

Opmerking: Het substatusconfiguratietype dat aan het missieobject wordt toegewezen, krijgt de hoogste prioriteit, tenzij een zoneconfiguratie dit expliciet overschrijft.

9. Zodra de regels zijn geconfigureerd, zal elke nieuw aangemaakte of geïmporteerde missie automatisch de overeenkomstige configuratietypen overnemen, en de missiewaarden zullen dienovereenkomstig worden ingevuld.

<figure><img src="../.gitbook/assets/image (704).png" alt=""><figcaption></figcaption></figure>

10. In uitzonderlijke gevallen kunnen gebruikers handmatig substatus- of meldingsconfiguratietypen bijwerken. Als deze wijzigingen in strijd zijn met op regels gebaseerde toewijzingen, verschijnt er een bevestigingspop-up:

Als wordt bevestigd, worden de handmatige wijzigingen behouden.

Als wordt afgewezen, zal het systeem terugkeren naar automatisch toegewezen configuraties.

<figure><img src="../.gitbook/assets/image (705).png" alt=""><figcaption></figcaption></figure>
