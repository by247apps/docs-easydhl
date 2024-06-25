# Einzelausführung

-   [Allgemein](#general)
-   [Artikel wählen](#items)
-   [Blätterfunktion](#pagination)
-   [Versandoptionen](#options)
    -   [Produkt](#product)
    -   [Gesamtgewicht](#total-weight)
    -   [Labelformat](#format)
    -   [Services](#services)
-   [Labeldaten](#label-info)
    -   [Lieferadresse](#shipping-address)
    -   [Absendeadresse](#sender-address)
    -   [Rechnungsadresse](#billing-address)
    -   [Telefonnummer des Kunden](#phone-number)
-   [Versandlabel erstellen](#create-label)
-   [Retourenlabel erstellen](#create-return)
-   [FAQ](#faq)

<a name="general"></a>

## Allgemein

Es gibt zwei Wege, um die Einzelansicht aufzurufen. Zum einen gelangst du dorthin, wenn du eine Bestellung im Dashboard von easyDHL anklickst. Zum anderen kannst du sie auch aus einer Bestellung in Shopify heraus ansteuern, indem du über \*Weitere Aktionen" easyDHL anklickst.

Die Einzelansicht bietet die bequemste und umfangreichste Form der Labelerstellung. Die Seite besteht aus insgesamt 4 Kacheln: Versandartikel, Dokumentenhistorie, Optionen und Versandinformationen.

Damit lassen sich alle Einstellungen der Labelerstellung ändern bzw. überschreiben.

<a name="items"></a>

## Artikel wählen

Sollen nicht alle Artikel der Bestellung sofort verschickt werden, d.h. es soll eine teilausführung gemacht werden, so kann die Anzahl derjeniger Artikel auf 0 gesetzt, die nicht ausgeführt werden sollen.

Beim Versand außerhalb der EU erscheint die Maske zur Eingabe der HS-Codes (Zolltarifnummern) und der Herkunftsländer. Diese Infos nimmt easyDHL automatisch aus den Shopify-Produktstammdaten. Daher empfehlen wir generell, diese Informationen für alle Produkte in Shopify zu pflegen.

Bereits ausgeführte Artikel werden beim Aufruf der Seite automatisch als solche gekennzeichnet und deren Anzahl wird entsprechend auf 0 gesetzt.

<a name="pagination"></a>

## Blätterfunktion

Eine weitere Annehmlichkeit der Einzelansicht ist die Möglichkeit, die nächste offene Bestellung aufzurufen. Dies kann über den Klick auf den Pfeil nach rechts neben _Weiteren Aktionen_ getan werden.

<a name="options"></a>

## Versandoptionen

Die Versandoptionen bieten dir erweiterte DHL-Einstellungen für die Labelerstellung.

Sollte eine Regel für die vorliegende Bestellung greifen, so werden das Produkt und die mit der Regel gewählten Services direkt übernommen.

<a name="product"></a>

### Produkt

Lege fest, für welches Versandprodukt das Label erstellt werden soll. Zur Verfügung stehen alle im DHL-Geschäftskundenportal (GKP) aktiven Produkte.

> [!NOTE]  
> Sollten hier etwaige Produkte fehlen, so prüfe, ob du mit diesem Produkt manuell ein Label über das GKP erstellen kannst. Wenn dies nicht funktioniert, kontaktiere DHL und lasse es dir freischalten.

<a name="total-weight"></a>

### Gesamtgewicht

Das Gesamtgewicht errechnet sich aus den Einzelgewichten der gewählten Artikel sowie dem Verpackungsgewicht des jeweiligen Versandprodukts. Es kann jedoch beliebig überschrieben werden.

> [!NOTE]  
> Beachte, dass für Sendungen außerhalb der EU das Gesamtgewicht nicht überschrieben werden kann, da das Gewicht jedes einzelnen Artikels explizit an DHL für die Verzollung übergeben werden muss. Jedoch kann in diesem Fall das Verpackungsgewicht angepasst werden.

<a name="format"></a>

### Labelformat

Wähle hier das Format des Labels.

<a name="services"></a>

### Services

Anhängig vom gewählten Produkt können für den Versand weitere Services dazugebucht werden. Dies sind momentan:

-   Transportversicherung
-   Filial-Routing
-   Sperrgut
-   Nachnahme
-   Empfängerunterschrift
-   Alterssichtprüfung
-   Ident-Check
-   Persönliche Übergabe
-   Keine Nachbarschaftszustellung
-   Wunschtag

Zusätzlich kann zum Versandlabel gleichzeitig auch eine Retourenlabel erzeugt werden.

<a name="label-info"></a>

## Labeldaten

Ändere hier Informationen wie Rechungs- und Lieferadresse, deine Absendeadresse oder füge die Telefonnummer des Kunden hinzu.

<a name="shipping-address"></a>

### Lieferadresse

easyDHL erlaubt es, die Lieferadresse des Kunden, die Shopify liefert komplett zu überschreiben. Zudem lässt sich die Sendung auch an eine Filiale oder Packstation leiten.

<a name="sender-address"></a>

### Absendeadresse

Soll eine andere Absenderadresse auf dem Label erscheinen, so kannst du hier zwischen deinen in Shopify erfassten Standorten wählen. Falls du eine Absenderreferenz nutzt, kann diese hier ebenfalls aktiviert werden.

<a name="billing-address"></a>

### Rechnungsadresse

Analog zur Lieferadresse kann die Rechnungsadresse angepasst werden.

<a name="phone-number"></a>

### Telefonnummer des Kunden

Trage hier die Telfonnummer des Kunden ein. Sie erscheint nicht auf dem Label, wird jedoch elektronisch an DHL übertragen.

<a name="create-label"></a>

## Versandlabel erstellen

Nachdem alle Einstellungen vorgenommen worden sind, kann das Versandlabel über den Button _Versandlabel erstellen_ erzeugt werden.

<a name="create-return"></a>

## Retourenlabel erstellen

Neben dem normalen Versandlabel kann über den Button _Retourenlabel erstellen_ in die Retouen-Ansicht gewechselt werden. Dort hast du die Möglichkeit, die (Absende-)Adresse des Kunden zu bearbeiten. Auf den Klick auf _Retourenlabel erstellen_ kann das Label schließlich erzeugt werden.

<a name="faq"></a>

## FAQ

<div class="faq-list">
<dl class="space-y-8">
<div>
<dt>Erstellung von Retourenlabels nicht möglich</dt>
<dd>Bitte beachte beim Benutzername die Groß und Kleinschreibung. Scheinbar wird bei der Retouren API der DHL zwischen Groß und Kleinschreibung unterschieden, wobei es bei der Versand Schnittstelle der DHL keine Unterscheidung gibt. So kann es sein, dass die Zugangsdaten für den Versand angenommen werden in easyDHL jedoch das laden der Receiver ID für die Retouren fehlschlägt. kontrolliere daher noch einmal genau dein Benutzername im DHL Geschäftskunden Portal auf Groß und Kleinschreibung innerhalb des Benutzernamens.

Die Erstellung von länderspezifischen Retourenlabels kann nur über die DHL Vertragsabteilung deinem DHL-Account freigeschaltet werden.</dd>

</div>

<div>
<dt>easyDHL moniert Adresse als falsch, obwohl diese laut Google Maps korrekt ist.</dt>
<dd>Das Problem lässt sich am einfachsten über die Leitcodierung lösen. Diese kann über <strong>Einstellungen --> Versand</strong> aktiviert werden. Prüfe zudem, ob deine Absenderadresse korrekt ist. Dies kann einen ähnlichen Fehler verursachen, obwohl die Empfängeradresse korrekt ist.</dd>

</div>

<div>
<dt>Keine physischen Artikel gewählt, die den Versand erfordern.</dt>
<dd>Dieser Fehler tritt dann auf, wenn ein Artikel in der Bestellung vorhanden ist, bei dem unter der Shopify-Produktverwaltung das Häkchen "Das Produkt erfordert Versand" fehlt. Wenn das Häkchen nachträglich gesetzt wird, werden diese Änderungen nicht in vorherige Shopify-Bestellung übernommen. Für bereits vorhanden Bestellungen kann die Fehlermeldung aus diesem Grund nicht übergangen werden. Ein möglicher Lösungsweg ist, das Label manuell "Label ohne Bestellung" (oben rechts über das easyDHL-Dashboard) zu erzeugen.

![Shopify - Produkt erfordert Versand](https://media.247apps.de/storage/easydhl/manual/produkt-erfordert-versand.png)</dd>

</div>

<div>
<dt>Gewicht einer Sendung überschreiben.</dt>
<dd>Das Gesamtgewicht einer Sendung setzt sich zusammen aus den Gewichten der einzelnen Produkte und dem Verpackungsgewicht. Es kann jedoch in der Einzelansicht überschrieben werden. Beachte jedoch, dass für Sendungen außerhalb der EU wegen der Verzollung nur das Verpackungsgewicht geändert werden kann.</dd>

</div>
</div>
