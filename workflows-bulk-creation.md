# Bulkausführung

-   [Allgemein](#general)
-   [Filter](#filters)
-   [Labels erstellen](#create-labels)
-   [FAQ](#faq)

<a name="general"></a>

## Allgemein

Über das Dashboard hast du Zugriff auf bis zu 1000 Bestellungen, für die du in einem Rutsch Labels erstellen kannst. Es bietet dir eine Übersicht über den Status der Bestellung, die Adresse des Kunden sowie etwaige Validierungsfehler.

<a name="filters"></a>

## Filter

Die auf dem Dashboard angezeigten Bestellungen können auch gefiltert werden. Zum einen kann nach Bestellnummern gesucht werden, zum anderen stehen folgende Filteroptionen zur Verfügung:

-   National / International
-   Versandart
-   Markiert mit
-   Validierung

Damit kann die Auswahl der Aufträge entsprechend eingerenzt werden. Ferner kann über den Klick auf die Flagge neben der Adresse der Filter _National / International_, über den Klick auf einen Tag unterhalb der Bestellnummer der Filter _Markiert mit_ aktiviert werden.

> [!NOTE]  
> Sollten diese Filter nicht ausreichen, empfehlen wir einen alternativen Workflow: Die Auswahl der Bestellungen machst du zunächst in Shopify, markierst die relevanten Bestellungen und wechselst dann über _Weitere Aktionen_ zu easyDHL. Im Dashboard erscheint dann genau die getroffene Auswahl. Beachte jedoch, dass auf diese Weise maximal 50 Bestellungen aufgerufen werden können.

<a name="create-labels"></a>

## Labels erstellen

Um Labels in Bulk zu erzeugen, wähle zunächst die relevanten Bestellungen aus. Die Auswahl kann auch bequem über alle angezeigten Bestellungen erfolgen. Anschließend erscheint der Dialog, um den Modus der Labelerstellung festzulegen. Hier hast du folgende Optionen:

-   Nationales Produkt (Paket oder Warenpost, sofern alle Bestellungen innerhalb Deutschlands verschickt werden)
-   Internationales Produkt (Paket, Europaket oder Warenpost, sofern alle Bestellungen außerhalb Deutschlands verschickt werden)
-   Nationales und internationales Produkt (Sofern gemischte Bestellungen ausgewählt wurden)
-   Labels nach Regeln erstellen (Sofern Regeln erfasst wurden)
-   Pickliste erstellen

> [!NOTE]  
> Wenn eine Bestellung mit Validierungsfehlern selektiert wurde, so wird die Fehlermeldung _Mindestens 1 Bestellung ausgewählt, die manuell ausgeführt werden muss. Diese Bestellung(en) werden nicht ausgeführt._ angezeigt.

Nach Klick auf einen der obigen Buttons, wird die Labelerstellung durchgeführt. Sobald alle Dokumente (Label, Lieferschein, Rechnung, Zollerklärung, Pickliste) erzeugt wurden, wechselt easyDHL in die Ergebnisseite, auf der alle Unterlagen heruntergeladen werden können.

Grundsätzlich werden alle selektierten Bestellungen in einzelne Packs zu je 50 Stück aufgeteilt. Die Anzahl je Pack kannst du jedoch unter _Einstellungen --> Allgemein_ ändern.

<a name="faq"></a>

## FAQ

<div class="faq-list">
<dl class="space-y-8">
<div>
<dt>Statt der Name unserer Firma wird einfach unsere Firmenadresse (Straße) angezeigt. Wie können wir das ändern?</dt>
<dd>In dem Fall werdet ihr voraussichtlich keine Absender Referenz verwenden und zwar die Adressen, die ihr in Shopify hinterlegt habt. dazu müsst ihr einmal in die Shopify Einstellungen unten links im Shopify Admin und dann unter Standorte beziehungsweise in Englisch Locations eure Adressen überprüfen. Dort ist oft als Standort Name die Straße oder Adresse eingetragen. Hier bitte die Standorte entsprechend korrigieren. Dann einen Moment warten und wieder in die App easy DHL unter Einstellungen Versand wechseln. Dort habt ihr dann in einem dropdown eure Standorte zur Auswahl. Sollten die Änderung noch nicht sichtbar sein, dann bitte einmal eine halbe Minute warten und einen browser-reload der App durchführen.</dd>
</div>

<div>
<dt>Benutzername und Password stimmen aber ich kann mich nicht anmelden, woran liegt das?</dt>
<dd>Solltest du die 2FA Authentifizierung im DHL Geschäftskunden Portal aktiviert haben, dann wird es höchstwahrscheinlich am gewählten Sicherheitsproblem liegen. Hier entweder die 2FA komplett deaktiviert oder aber das Sicherheitsprofil wie folgt geändert werden, siehe Screenshot - "Absicherung sicherheitsrelevanter Änderungen"

![DHL-2fa-Problem](https://media.247apps.de/storage/faq/dhl-2fa-problem.png)

</dd>
</dl>
</div>
</div>
