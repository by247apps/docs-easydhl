# Automatisierung

-   [Allgemein](#general)
-   [Automatisierung aktivieren](#activation)
-   [Abläufe](#workflows)
    -   [Versandlabel erstellen](#create-labels)
    -   [Rechnung erstellen](#create-invoices)
    -   [Tag hinzufügen](#create-tag)
-   [FAQ](#faq)

<a name="general"></a>

## Allgemein

Alles rund um das Regelwerk findest du unter **Einstellungen --> Automatisierung**.

Mit der Automatisierung lassen sich bspw. Labels ganz bequem sofort nach Bestell- oder Zahlungseingang erstellen und zusenden lassen. Damit erspart man sich die manuellen Schritte des gesamten Ausführungsprozesses.

> [!NOTE]  
> Die Automatisierung gehört zu den Premium-Plus-Features und ist entsprechend nur im Premium-Plus-Tarif verfügbar. Ferner greift sie ausschließlich bei DHL-Produkten, und nicht bei Internetmarke.

<a name="activation"></a>

## Automatisierung aktivieren

Um mit den automatischen Abläufen zu beginnen, muss die Automatisierung zunächst aktiviert werden. Anschließend ist der Auslöser, bei dem die Automatisierung greift, zu wählen. easyDHL bietet hierzu den Bestelleingang oder den Zahlungseingang an.

<a name="workflows"></a>

## Abläufe

Innerhalb der Automatisierung können nun die zu ausführenden Schritte angegeben werden.

<a name="create-labels"></a>

### Versandlabel erstellen

Soll ein Versandlabel erstellt werden, so kann es hier aktiviert werden. Dann sind weitere Optionen zu wählen.

#### Regeln anwenden

Bei der Labelerstellung können die zuvor erfassten Regeln ebenfalls beachtet werden.

#### Nationales Produkt

Sofern die Regelerstellung nicht aktiv ist, kann das nationale Produkt angegeben werden. Damit weiß easyDHL, welches Versandprodukt beim nationalen Versand angewendet werden soll.

> [!NOTE]  
> Soll die Automatisierung nur beim internationalen Versand greifen, so wählt man hier **Kein Versandlabel erstellen**.

#### Internationales Produkt

Sofern die Regelerstellung nicht aktiv ist, kann das internationale Produkt angegeben werden. Damit weiß easyDHL, welches Versandprodukt beim internationalen Versand angewendet werden soll.

> [!NOTE]  
> Soll die Automatisierung nur beim nationalen Versand greifen, so wählt man hier **Kein Versandlabel erstellen**.

#### Downloadlink senden

Soll das erstellte an dich Label per Mail versandt werden, so kannst du hier die Email-Adresse angeben.

Zusätzlich kannst du auch angeben, ob das Label sofort und/oder zu einer gewissen Uhrzeit verschickt werden soll.

#### Bestellung ausführen

Lege hier fest, ob die Bestellkung nach erfolgreicher Labelerstellung ausgeführt werden soll. Zusätzlich kannst du auch die Shopify-Versandbestätigung auslösen lassen.

<a name="create-invoices"></a>

### Rechnung erstellen

Neben dem Versandlabel kann gleichzeitig auch eine Rechnung erzeugt werden. easyDHL bietet zudem einen Link an, den du in deiner Shopify-Versandbestätigung einfügen kannst, damit Kunden sie bequem herunterladen können.

<a name="create-tag"></a>

### Tag hinzufügen

Jede durch die Automatisierung verarbeitete Bestellung in Shopify kann mit dem Tag _easyDHL-automation-ok_ versehen werden, sodass du auf Anhieb siehst, was bereits durchgeführt wurde.

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
