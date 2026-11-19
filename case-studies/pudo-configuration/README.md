# PUDO-configuratie

PUDO (afhaal- en afleverpunten) stelt chauffeurs in staat pakketten op veilige locaties achter te laten wanneer klanten niet beschikbaar zijn. Deze functie elimineert dure kosten voor opnieuw bezorgen en vermindert voertuiguitstoot. U behaalt hogere succespercentages bij de eerste poging en meer klantgemak.

#### Aan de slag

* Een voorbereide lijst met PUDO-locaties, inclusief namen en adressen.
* Gedefinieerde categorieën voor uw netwerk, zoals pakketkluizen of winkels.
* Toegang tot de **Configuratie** module in Nomadia Delivery.
* Open de **Configuratie** module.

<figure><img src="../../.gitbook/assets/image (1029).png" alt=""><figcaption></figcaption></figure>

* Selecteer de **PUDO-type** pagina om uw categorieën te definiëren.

<figure><img src="../../.gitbook/assets/image (1030).png" alt=""><figcaption></figcaption></figure>

* Navigeer naar de **PUDO** pagina om uw fysieke locaties te uploaden.

<figure><img src="../../.gitbook/assets/image (1031).png" alt=""><figcaption></figcaption></figure>

#### Functieoverzicht

* **PUDO-types**: Categorieën zoals winkels of pakketkluizen met specifieke afhandelingsvereisten.

<figure><img src="../../.gitbook/assets/image (1032).png" alt=""><figcaption></figcaption></figure>

* **PUDO-lijst**: De database met werkelijke locaties en adressen die uw operatie gebruikt.

<figure><img src="../../.gitbook/assets/image (1033).png" alt=""><figcaption></figcaption></figure>

* **PUDO-substatus**: Aangepaste labels voor de mobiele app die alleen van toepassing zijn tijdens PUDO-interacties.

<figure><img src="../../.gitbook/assets/image (1034).png" alt=""><figcaption></figcaption></figure>

* **Fallback-PUDO**: Een veld op missieniveau dat bepaalt of een PUDO-aflevering is toegestaan.

<figure><img src="../../.gitbook/assets/image (1035).png" alt=""><figcaption></figcaption></figure>

#### Hoe te: PUDO-types configureren

1. Ga naar de **Configuratie** module.

<figure><img src="../../.gitbook/assets/image (1036).png" alt=""><figcaption></figcaption></figure>

2. Klik op **PUDO-type**.
3. Definieer categorieën zoals supermarkten, partnerwinkels of pakketkluizen.

<figure><img src="../../.gitbook/assets/image (1037).png" alt=""><figcaption></figcaption></figure>

#### Hoe te: De PUDO-lijst uploaden

1. Navigeer naar de **PUDO** pagina in de **Configuratie** module.

<figure><img src="../../.gitbook/assets/image (1038).png" alt=""><figcaption></figcaption></figure>

2. Open de **Acties** menu.
3. Selecteer de **Importeren** actie om uw lijst in bulk te uploaden.

<figure><img src="../../.gitbook/assets/image (1039).png" alt=""><figcaption></figcaption></figure>

#### Hoe te: PUDO-substatussen instellen

1. Klik op het **Substatus** pagina in de **Configuratie** module.

<figure><img src="../../.gitbook/assets/image (1040).png" alt=""><figcaption></figcaption></figure>

2. Zet de schakelaar **alleen PUDO** aan.

<figure><img src="../../.gitbook/assets/image (1041).png" alt=""><figcaption></figcaption></figure>

3. Voer operationele labels in zoals "In pakketkluis gedeponeerd" of "PUDO-punt vol".
4. Klik op het **Opslaan** knop.

<figure><img src="../../.gitbook/assets/image (1042).png" alt=""><figcaption></figcaption></figure>

#### Hoe te: Fallback-PUDO op een missie inschakelen

1. Zoek het **Fallback-levering in PUDO** veld in de **Missietabel**.

<figure><img src="../../.gitbook/assets/image (1043).png" alt=""><figcaption></figcaption></figure>

2. Klik op het **Bewerken** knop om de **Missie-editor**.
3. Selecteer de **Afleveringsinformatie** **sectie**.
4. Stel het fallback-kenmerk in op **Toestaan**, **Weigeren**, of **Na herpoging**.

<figure><img src="../../.gitbook/assets/image (1044).png" alt=""><figcaption></figcaption></figure>

#### Productiviteitstips

* 💡 **Ondersteuning voor meerdere missies**: Gebruik PUDO voor zowel afhaal- als leveringsmissies om de operationele flexibiliteit te vergroten.
* 💡 **Bulkupdates**: Beheer fallback-toestemmingen op schaal met behulp van het **Importsjabloon** of de API tijdens het aanmaken van missies.
* ⚠️ **Databeheer**: Houd de **PUDO-lijst** actueel, anders kunnen chauffeurs geen nabijgelegen afleverpunten vinden.
* ⚠️ **Typeverschillen**: Maak altijd onderscheid tussen winkels en pakketkluizen, omdat zij verschillende afhandelingsprocessen vereisen, zoals **OTP** codes.
