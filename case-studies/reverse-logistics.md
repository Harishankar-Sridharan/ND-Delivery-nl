# Retourlogistiek

Nomadia Delivery integreert reverse logistics rechtstreeks in de standaard levenscyclus van uw missie. Met deze functie kunt u retouren activeren, plannen en uitvoeren zonder het platform te verlaten. U krijgt volledig inzicht en geoptimaliseerde routing voor elke retourreis.

#### Aan de slag

* Toegang tot de **Nomadia Delivery Back Office**.
* Het **Missie-ID** van de mislukte of niet-opgehaalde levering.
* API-toegang tot het **Reverse Logistics** eindpunt.
* Open de **Back Office** en zoek de specifieke route die de missie bevat die moet worden geretourneerd.
* Bepaal of het item terug moet naar de oorspronkelijke afzender of alleen naar het agentschap.

#### Functieoverzicht

* **Missie-ID**: Een unieke code met een **\_r** achtervoegsel dat wordt gebruikt om retouren terug te volgen naar hun oorsprong.

<figure><img src="../.gitbook/assets/image (1082).png" alt=""><figcaption></figcaption></figure>

* **Terug naar afzender**: Een parameter die bepaalt of een item naar de afzender gaat of bij het agentschap blijft.
* **Nieuw missie-type**: Gebruik de **Opdrachttype** instelling om de retour te classificeren als een **Cross Docking**, **Levering**, of **Afhaling** missie.
* **Bewerkknop**: Hiermee worden de missiegegevens geopend om te controleren of de ophaal- en afleveradressen correct zijn omgewisseld.

<figure><img src="../.gitbook/assets/image (1083).png" alt=""><figcaption></figcaption></figure>

#### Zo werkt het: een Cross Docking-retour aanmaken

Gebruik deze taak wanneer het item via het agentschap moet terugkeren naar de oorspronkelijke afzender.

1. Kopieer de **Missie-ID** van de oorspronkelijke missie in de **Back Office** of haal via de API de lijst op van missies die naar de afzender moeten worden teruggestuurd.

<figure><img src="../.gitbook/assets/image (1084).png" alt=""><figcaption></figcaption></figure>

2. Voeg de lijst met missie-ID's toe in de Mission Ids-array.&#x20;
3. Stel de **Terug naar afzender** parameter op **Waar**.
4. Stel de **Nieuw missie-type** in op **Cross Docking**.
5. Selecteer **Uitvoeren** om de retourmissie**s in één keer**.

<figure><img src="../.gitbook/assets/image (1085).png" alt=""><figcaption></figcaption></figure>

6. **Vernieuw** de **Back Office** UI om de nieuwe missie met het **\_r** achtervoegsel te zien.
7. Neem de nieuwe **Cross-docking** missie op in de volgende planningscyclus voor optimalisatie.

#### Zo werkt het: een Delivery Return aanmaken

Gebruik deze taak wanneer het item alleen naar het agentschap hoeft te gaan voor afhaling door de afzender.

1. Kopieer de **Missie-ID** voor de mislukte leveringsmissie of haal via de API de lijst op van missies die naar het agentschap moeten worden teruggestuurd.
2. Voeg de lijst met missie-ID's toe aan de **Mission IDs** array.
3. Stel de **Terug naar afzender** parameter op **Onwaar**.
4. Stel de **Nieuw missie-type** in op **Afhaling**.
5. Selecteer **Uitvoeren** om de missie aan te maken.
6. Vernieuw de **Back Office** interface om de nieuwe missie met het `_r` achtervoegsel te bekijken..

#### Productiviteitstips

* 💡 **Geünificeerde tracking**: Gebruik de **\_r** achtervoegsel om elke retour direct te koppelen aan de oorspronkelijke uitgaande levering.
* 💡 **Naadloze planning**: Behandel retourmissies als standaardmissies om ze op te nemen in geautomatiseerde routeoptimalisatie.
* ⚠️ **Handmatige workarounds**: Vermijd het gebruik van spreadsheets om retouren buiten het systeem bij te houden om datachaos te voorkomen.
