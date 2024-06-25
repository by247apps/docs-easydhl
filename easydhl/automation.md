# Automatisierung

-   [Allgemein](#general)
-   [Automatisierung aktivieren](#activation)
-   [Abläufe](#workflows)
    -   [Versandlabel erstellen](#create-labels)
    -   [Rechnung erstellen](#create-invoices)
    -   [Tag hinzufügen](#create-tag)

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
