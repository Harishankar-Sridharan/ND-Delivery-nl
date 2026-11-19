# Studie-aanmaak met primaire zone

Beheer leveringsgebieden effectief tijdens piekseizoenen en fluctuerende volumes. Organiseer de dekking door seizoensplannen te maken die automatisch op het juiste moment worden geactiveerd. Bereik nauwkeurige logistieke operaties die de dekking in de praktijk weerspiegelen voor uw buitendienstteams.

#### Aan de slag

* Om studies te maken en te beheren, zorg ervoor dat u over de juiste beheerdersrechten beschikt:
  * Toegang tot de configuratiemodule
  * Recht voor zones maken en bijwerken
  * Recht voor studies maken en bijwerken
* Klik op de module Configuratie in de bovenste banner.

<figure><img src="../.gitbook/assets/image (841).png" alt=""><figcaption></figcaption></figure>

* Selecteer de **Gebruikers beheren** pagina.

<figure><img src="../.gitbook/assets/image (842).png" alt=""><figcaption></figcaption></figure>

* Bewerk de specifieke gebruiker en klik op de **Rollen en rechten** tabblad.

<figure><img src="../.gitbook/assets/image (843).png" alt=""><figcaption></figcaption></figure>

* Rechten inschakelen voor **Zones maken en bijwerken** en **Lijst met zones**.
* Klik op het **Opslaan** knop om de rechten toe te passen.

<figure><img src="../.gitbook/assets/image (844).png" alt=""><figcaption></figcaption></figure>

#### Functieoverzicht

* **Studie**: Een gestructureerd object dat bepaalt hoe leveringsgebieden zijn georganiseerd.
* **Primaire zone**: Een geografisch gebied op hoofdniveau dat aan een team is toegewezen en gekoppeld is aan postcodes.
* **Pagina Studiebeheer**: Uw centrale plek voor het maken en bewerken van studies en zones.

#### Hoe: Een studie maken

1. Navigeer naar de **Studies en zones** pagina onder de **Levering** sectie in **Configuratie**.

<figure><img src="../.gitbook/assets/image (845).png" alt=""><figcaption></figcaption></figure>

2. Klik op het **Acties** menu rechtsboven.

<figure><img src="../.gitbook/assets/image (846).png" alt=""><figcaption></figcaption></figure>

3. Selecteer **Lege studie maken**.
4. Voer de **Identificatie**, **Naam**, en **Agentschap**.
5. Stel de **Begindatum geldigheid** en **Einddatum geldigheid**.
6. Zet de studie op **Schakel**.
7. Selecteer de actieve dagen van de week voor dit plan.
8. Definieer de specifieke periode van seizoensactivatie.
9. Klik op het **Opslaan** knop.

<figure><img src="../.gitbook/assets/image (847).png" alt=""><figcaption></figcaption></figure>

#### Hoe: Een primaire zone maken

1. Open de **Zone** tabblad binnen uw nieuwe studie.

<figure><img src="../.gitbook/assets/image (848).png" alt=""><figcaption></figcaption></figure>

2. Open de **Acties** menu.
3. Selecteer **Een postcodezone toevoegen**.

<figure><img src="../.gitbook/assets/image (849).png" alt=""><figcaption></figcaption></figure>

4. Vul het **Identificatie**, **Naam**, en **Agentschap**.
5. Selecteer de **Land** in en stel de **Genormaliseerde lengte van postcode**.
6. Selecteer **Primaire zone** in de **Toewijzingsmodus** veld.

<figure><img src="../.gitbook/assets/image (850).png" alt=""><figcaption></figcaption></figure>

7. Voer postcodes handmatig in met de **Plus** knop.

<figure><img src="../.gitbook/assets/image (851).png" alt=""><figcaption></figcaption></figure>

8. Klik op het **Opslaan** knop.

<figure><img src="../.gitbook/assets/image (852).png" alt=""><figcaption></figcaption></figure>

#### Productiviteitstips

* 💡 **Bulkimport**: Gebruik de **Importeren** optie in het **Acties** menu om grote lijsten met postcodes te uploaden.
* 💡 **Directe visualisatie**: Bekijk de kaart rechts om te zien hoe postcodepolygonen automatisch worden weergegeven.
* 💡 **API-automatisering**: Gebruik de **studie maken** eindpunt om het maken van studies programmatisch te activeren voor grote workflows.
* ⚠️ **Toewijzingsmodus**: Selecteer altijd **Primaire zone** voor gebieden op hoofdniveau om te voorkomen dat er per ongeluk subzones worden gemaakt.
