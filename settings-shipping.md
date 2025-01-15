# Versand

-   [Standardprodukte](#products)
-   [Absenderadresse](#address)
-   [Verpackungsgewicht](#weight)
-   [Labelerstellung](#label)
    -   [Labelformat](#format)
    -   [Leitcodierung](#coding)
    -   [Validerungsfehler](#dhl-validation)
    -   [Telefonnummer des Absenders](#phone)
    -   [Max. Anzahl Artikel](#max-labels)
-   [Validierung der Bestellungen](#app-validation)
    -   [Email obligatorisch](#email)
    -   [Hausnummer ermitteln](#housenumber)
-   [Zolldokumente](#customs)
-   [Paketankündigung](#notification)
-   [Retouren](#retoures)
-   [Magnalister](#magnalister)
-   [Nachnahme](#cod)
-   [Zusatzoptionen](#options)
-   [FAQ](#faq)

<a name="products"></a>

## Standardprodukte

Als Vorauswahl in Bulk- und Einzelansicht sollten das nationale und internationale Versandprodukt gewählt werden.

Zudem kann hier festgelegt werden, ob für den internationalen Versand standardmäßig die Premium-Option gebucht werden soll. <a class="video">https://youtu.be/kQMqFhnEYx0</a>

> [!NOTE]
> DHL Premium Versand gilt nicht automatisch für einige Länder, die außerhalb der Hauptversandzonen liegen. Hier sind einige Beispiele:

-   Zone 9: Einige Inselstaaten in der Karibik und im Pazifik
-   Zone 10: Einige afrikanische Länder, die nicht in Zone 6 oder 7 fallen
-   Zone 11: Einige Länder in Zentralasien und im Nahen Osten, die nicht in Zone 6 fallen
-   Für diese Länder kann es sein, dass der Premium Versand nicht automatisch verfügbar ist und zusätzliche Gebühren oder spezielle Versandoptionen erforderlich sind.

<a name="address"></a>

## Absenderadresse

Die Absenderadresse kann entweder über die Standorte in Shopify oder durch die Absenderreferenz im DHL GKP festgelegt werden. Vorrang erhält dabei die Absenderreferenz, über die auch **Logos** auf dem Versandlabel dargesellt werden können. <a class="video">https://youtu.be/0x3HSBggxvY</a>

<a name="weight"></a>

## Verpackungsgewicht

Erfasse hier das Verpackungsgewicht für den Paket- und Warenpostversand. Dieses Gewicht wird dem Artikelgewicht hinzuaddiert wird. Zusätzlich kannst du hier auch ein Fallback-Gewicht festlegen, das dann greift, wenn die Produkte in einer Bestellung keine eigenen Gewichte haben. <a class="video">https://youtu.be/BYjJqYXt2xU</a>

Das Versandgewicht ergibt sich aus der Summe der Artikelgewichte aus der Bestellung plus dem Verpackungsgewicht. Wenn ihr das Gewicht einer Bestellung überschreiben möchtet, müsstet ihr die Bestellung einmal in der App in der Detailansicht öffnen. Dort könnt ihr auf der rechten Seite, vor Erstellung des Versandlabels, des Gewicht editieren. Da die Gewichte innerhalb der Bestellungen manifestiert sind, ist eine nachträgliche Änderung des Gewichts innerhalb der Bestellung durch die Gewicht-Anpassung im Produktkatalog nicht möglich. Nach Anpassung der Gewichte im Produktkatalog haben dann zukünftige Bestellungen dieses Artikelgewicht.

Beachte auch diese Funktion -> [Video zum regelbasierten Verpackungsgwicht.](https://www.youtube.com/watch?v=I87Ci2wdgqo)

<a name="label"></a>

## Labelerstellung

Lege zusätzliche Optionen bei der Labelerstellung fest. Wie z.B. den Umgang mit Fehlerhaften aber leitcodierbaren Adressen. <a class="video">https://youtu.be/3U49hH-AefU</a>

<a name="format"></a>

### Labelformat <a class="video">https://youtu.be/VLyJ5Wp2G5A</a>

<a name="coding"></a>

### Leitcodierung

In manchen Fällen kann DHL fehlerhafte Adressen trotzdem zuordnen und ein Label erstellen. Diesen Service berechnet DHL dann mit einer zusätzlichen Gebühr. Lege fest, ob dieser Service immer gebucht werden soll. <a class="video">https://youtu.be/VLyJ5Wp2G5A</a>

<a name="dhl-validation"></a>

### Validerungsfehler

Sollte auch bei unkritischen Validierungsfehlern kein Label erstellt werden, kann dies aktiviert werden. <a class="video">https://youtu.be/3U49hH-AefU</a>

<a name="phone"></a>

### Telefonnummer des Absenders

Füge hier deine Telefonnummer ein, die dann auf dem Label erscheint.

<a name="max-labels"></a>

### Max. Anzahl Artikel

In manchen Fällen ist es sinnvoll, ein Label je X Artikel in der Bestellung zu erstellen. Lege hier fest, wieviele Artikel maximal je Label genommen werden sollen.

Verwendest du hier den Wert 2, werden für eine Bestellung mit fünf Artikeln, drei Versandlabels erstellt. In dem Fall entstehen drei Sendungsnummern, welche den entsprechenden Positionen, für die Sendungsverfolgung, zugordnet werden.

<a name="app-validation"></a>

## Validierung der Bestellungen

Lege fest, welche Prüfungen beim Laden der Bestellungen durchgeführt werden sollen. <a class="video">https://youtu.be/3U49hH-AefU</a>

<a name="max-labels"></a>

### Max. Anzahl Artikel

In manchen Fällen ist es sinnvoll, ein Label je X Artikel in der Bestellung zu erstellen. Lege hier fest, wieviele Artikel maximal je Label genommen werden sollen.

<a name="housenumber"></a>

### Hausnummer ermitteln

easyDHL kann die Hausnummer für Adressen außerhalb DACH aus der Adresszeile zu großem Teil korrekt herauslesen und trennt dann Hausnummer und Straßenname. Dennoch kann es es dabei zu Fehlern kommen. Aktiviere die Option, wenn dennoch das Ermitteln der Hausnummer erzwingen möchtest. Wenn deaktiviert, übergibt easyDHL die Adresse 1:1 an DHL.

<a name="customs"></a>

## Zolldokumente

Trage hier die für die Verzollung relevanten Informationen ein. Diese werden dann entsprechend an DHL bzw. auf die Handelsrechnung übertragen. <a class="video">https://youtu.be/2do4eRyYgks</a>

> [!NOTE]
> Wenn du noch keine EORI-Nummer hast, kannst du diese kostenlos beim Zoll beantragen. Weitere Informationen findest du [hier](https://www.zoll.de/DE/Fachthemen/Zoelle/EORI-Nummer/eori-nummer_node.html).

<a name="notification"></a>

## Paketankündigung

Stelle ein, ob die Email-Adresse des Kunden für die Paketankündigung an DHL übertragen werden soll. <a class="video">https://youtu.be/vijrlOFnFww</a>

<a name="retoures"></a>

## Retouren

Zu jedem Versandlabel kann ein Retourenlabel erzeugt werden. Dies verlangsamt jedoch die Bulk-Ausführung um ca. eine halbe Sekunde pro Label. <a class="video">https://youtu.be/UIKbGer5Yys</a>

#### Druckformat des Retourenlabels

Das Druckformat des Retourenlabels kann im [DHL Geschäftskundenportal](https://geschaeftskunden.dhl.de/) wie folgt geändert werden:

<img width="590" alt="Screenshot 2024-09-12 at 16 31 05" src="https://github.com/user-attachments/assets/f57a519a-4209-49a7-99d8-fbc5503c5c3d">
<br><br/>
<img width="1013" alt="Screenshot 2024-09-12 at 16 30 58" src="https://github.com/user-attachments/assets/dc075d94-aab3-4cc2-9d72-b3f3c45910d1">




<a name="magnalister"></a>

### Magnalister

Wenn aktiviert, befüllt easyDHL die Magnalister Otto-Felder mit Verfolgungsnummer und Carrier.

<a name="cod"></a>

## Nachnahme

Gebe deine Kontaktdaten und Bankverbindung für die Nachnahmesendungen an. <a class="video">https://youtu.be/Ud4B0N4batg</a>

<a name="options"></a>

## Zusatzoptionen

Lege hier fest, welche Zusatzservices bei jeder Labelerstellung gebucht werden sollen. <a class="video">https://youtu.be/OCax3DANT94</a>

<a name="faq"></a>

## FAQ

<div class="faq-list">
<dl class="space-y-8">
<div>
<dt><h4>Wie kann ich die Absenderadresse in easyDHL ändern?</h4></dt>
<dd>Unter <strong>Einstellungen --> Versand</strong> innerhalb der App kannst du eine alternative Absendeadresse auswählen. Die dort zur Verfügung stehenden Adressen kommen aus deinen Shopify Standorten. Die Shopify Standorte kannst du in deinem Shopify Admin unter <strong>Einstellungen --> Standorte</strong> einsehen, editieren und neu hinzufügen.

In easyDHL kannst du alternativ über die sogenannte _Absenderreferenz_, die Versand Adressen aus deinem DHL Geschäftskunden Portal verwenden. Dazu haben wir hier ein [Video](https://www.youtube.com/watch?v=Ppcaf6PWOw0){:target="\_blank"}</dd>

</div>

<div>
<dt><h4>Statt Firmenname wird unsere Firmenadresse (Straße) angezeigt. Wie können wir das ändern?</h4></dt>
<dd>In dem Fall werdet ihr voraussichtlich keine Absender Referenz verwenden und zwar die Adressen, die ihr in Shopify hinterlegt habt. dazu müsst ihr einmal in die Shopify Einstellungen unten links im Shopify Admin und dann unter Standorte beziehungsweise in Englisch Locations eure Adressen überprüfen. Dort ist oft als Standort Name die Straße oder Adresse eingetragen. Hier bitte die Standorte entsprechend korrigieren. Dann einen Moment warten und wieder in die App easy DHL unter Einstellungen Versand wechseln. Dort habt ihr dann in einem Dropdown eure Standorte zur Auswahl. Sollten die Änderung noch nicht sichtbar sein, dann bitte einmal eine halbe Minute warten und einen Browser-Reload der App durchführen</dd>
</dl>
</div>

<div>
<dt><h4>Wie bekomme ich unser Shop-Logo auf das Versandlabel?</h4></dt>
<dd>Um ein (Shop-)Logo auf dem Versandlabel darzustellen, muss zunächst eine gültige DHL-Absenderreferenz im Geschäftskundenportal unter <strong>Versenden --> Adressbuch --> Absender</strong> angelegt werden. Es muss eine Absenderadresse erfasst und optional ein Logo hochgeladen werden. Sobald dies erfolgt ist, muss die Absenderreferenz entsprechend auch in easyDHL übernommen werden, und zwar unter <strong>Einstellungen --> Versand</strong>. Anschließend erscheint auf dem Label neben der neuen Adresse auch das hochgeladene Logo.

Dazu haben wir auch ein [Video](https://www.youtube.com/watch?v=Ppcaf6PWOw0){:target="\_blank"}</dd>

</dl>
</div>

<div>
<dt><h4>Ist es möglich eine abweichende Adresse für Retouren zu hinterlegen?</h4></dt>
<dd>Die Empfänger Adresse ist der jeweiligen Receiver-ID hinterlegt. Das heißt, innerhalb der Shopify App kann diese Adresse nicht geändert werden sondern nur über das DHL Geschäftskundenportal und zwar an der Receiver-ID des entsprechenden Landes. Sollte dies dort nicht möglich sein, muss Kontakt zur DHL Geschäftskundenbetreuung aufgenommen werden</dd>

</dl>
</div>
</div>
