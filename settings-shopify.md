# Shopify

-   [Fulfillment](#fulfillment)
    -   [Fulfillment-Standort](#location)
    -   [Shopify-Versandbestätigung](#notification)
    -   [Shopify-Versandbestätigung erzwingen](#notification-force)
    -   [Fulfillments löschen bei Label-Stornierung](#cancel)
    -   [Tracking-Updates aktivieren](#tracking)
-   [Tags](#tags)
-   [Zusätzliche Berechtigungen](#rights)
-   [FAQ](#faq)

<a name="fulfillment"></a>

## Fulfillment

Wie soll Shopify bei der Erstellung von Versandlabels reagieren. Wenn die Bestellungen ausgeführt werden sollen, wird die Tracking-Nummer der entsprechenden Bestellung in Shopify hinterlegt. <a class="video">https://youtu.be/cD0A-1ZVYBQ</a>

<a name="location"></a>

### Fulfillment-Standort

Die Auswahl erzwingt das Fulfillment von dem ausgewählten Standort. Mit Automatisch verwendet die App die in der Bestellung zugewiesenen Standorte und wird für die meisten Shops empfohlen.

<a name="notification"></a>

### Shopify-Versandbestätigung erzwingen

easyDHL triggert die Versandbestätigung nur in dem Falle, wenn auch eine Sendungsverfolgungsnummer vorliegt. Möchtest du die Shopify-Benachrichtigung auch dann senden, wenn keine Sendungsnummer exisitiert, dann aktiviere diese Option.

<a name="cancel"></a>

### Fulfillments löschen bei Label-Stornierung

Wenn Labels in easyDHL storniert werden, können mit dieser Option auch die entsprechenden Fulfillments in Shopify gelöscht werden.

<a name="tracking"></a>

### Tracking-Updates aktivieren

easyDHL aktualisiert den Versandstatus der Sendungen und triggert dabei die Shopify-Benachrichtigung, wenn eine Sendung zugestellt wurde.

> [!NOTE]
> Beachte, dass diese Funktion nur im Premium-Plus-Tarif zur Verfügung steht.

<a name="tags"></a>

## Tags

Mit dieser Option werden Bestellungen die über die Bulk-Erstellung verarbeitet werden mit den Tags 'easydhl-ok' oder easydhl-failed' markiert. Das kann hilfreich sein, um Bestellungen anhand der Tags in Shopify entprechend filtern zu können. <a class="video">https://youtu.be/cD0A-1ZVYBQ</a>

<a name="rights"></a>

## Zusätzliche Berechtigungen

Um auf weitere Daten des Shops zuzugreifen, benötigt die App zusätzliche Berechtigungen. Klicke auf den jeweiligen Link, um die entsprechende Berechtigung zu gewähren.

<a name="faq"></a>

## FAQ

<div class="faq-list">
<dl class="space-y-8">
<div>
<dt>
<h4>Wir haben noch offene Bestellungen, die älter als 60 Tage sind. Leider ist es für uns nicht möglich, diese Bestellungen aufzurufen. Was kann da machen?</h4>
</dt>
<dd>Innerhalb easyDHL unter <strong>Einstellungen --> Shopify</strong> kannst du Zugriff auf Bestellungen freigeben, die älter als 60 Tage sind.

![Shopify-Bestellungen-Älter-Als-60-Tage](https://media.247apps.de/storage/easydhl/manual/Shopify-Bestellungen-Aelter-Als-60-Tage.png)

</dd>
</div>
<div>

<dt>
<h4>Weshalb werden Fulfillment und Versandbestätigung nicht ausgelöst?</h4>
</dt>
<dd>Wenn nach der Labelerstellung kein Fulfillment und somit keine Versandbestätigung getrriggert wird, kann es an drei Gründen liegen:

-   Das automatische Fulfillment ist in der App unter <strong>Einstellungen --> Shopify</strong> deaktiviert.
-   Die Bestellung war bereits vorher schon ausgeführt. Dann überschreibt die App dieses Fulfillment auch nicht.
-   Das Feature benötigt einen bezahlten Tarif, der noch gebucht wurde</dd>
</div>

</div>
