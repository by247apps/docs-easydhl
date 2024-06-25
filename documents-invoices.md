# Rechnungen

-   [Allgemeine Einstellungen](#general)
    -   [Rechnungserstellung aktivieren](#activate-invoices)
    -   [Handelsrechnung erstellen](#create-commercial-invoices)
-   [Template bearbeiten](#template)
    -   [Zusatzinformationen](#header)
    -   [Mitteilungen](#messages)
    -   [Fußzeile](#footer)
-   [Weitere Einstellungen](#further-settings)
    -   [Format Rechnungsnummer](#number-format)
    -   [Rechnungsdatum](#date)
    -   [Preise exkl. MwSt. (B2B)](#b2b)
    -   [Währung des Kunden verwenden](#customer-currency)
    -   [Artikelhersteller angezeigen](#vendor)
    -   [Steuerfreie Ausfuhrlieferung](#tax-free-export)
    -   [Umsatzsteuerbefreiuung](#tax-free-domestic)
    -   [Differenzbesteuerung](#diff-taxing)
    -   [Rechnung in Versandbestätigung](#notification)
-   [FAQ](#faq)

<a name="general"></a>

## Allgemeine Einstellungen

Alles rund um Rechnungen findest du unter **Einstellungen --> Dokumente**. <a class="video">https://youtu.be/\_XEoZMgMRVM</a>

<a name="activate-invoices"></a>

### Rechnungserstellung aktivieren

Damit zu jedem Label auch eine Rechnung erstellt wird, sollte dies hier aktiviert werden.

<a name="activate-commercial-invoices"></a>

### Handlesrechnung erstellen

Damit zu jedem Label auch eine Rechnung erstellt wird, sollte dies hier aktiviert werden.

<a name="template"></a>

## Template bearbeiten

Erfasse hier die wichtigsten Informationen zu deinem Unternehmen.

<a name="header"></a>

### Zusatzinformationen

Gebe hier beispielsweise deine Absende- und Email-Adresse an. Diese Infos werden dann rechts oben auf der Rechnuing abgebildet.

<a name="messages"></a>

### Mitteilungen

Hier kannst du weitere wichtige Infos sowie Mitteilungen erfassen, die direkt an den Kunden gerichtet sind.

<a name="footer"></a>

### Fußzeile

In der Fußzeile wird gewöhnlich

<a name="further-settings"></a>

## Weitere Einstellungen

Lege hier fest, welche weiteren Informationen auf der Rechnung dargestellt werden.

<a name="number-format"></a>

### Format Rechnungsnummer

Wähle hier, ob die Rechnungsnummer allein aus der Bestellnummer hervorgeht oder um das Erstellungsdatum erweitert wird.

<a name="date"></a>

### Rechnungsdatum

Lege fest, ob das Rechnungsdatum dem Bestelldatum oder dem Erstellungsdatum entspricht.

<a name="b2b"></a>

### Preise exkl. MwSt. (B2B)

Lege fest, ob die Preise im Shop ohne die Umsatzsteuer angezeigt werden. Entsprechend ändert sich intern die Berechnung und der Ausweis der Steuern in easyDHL.

<a name="customer-currency"></a>

### Währung des Kunden verwenden

Für Bestellungen aus dem Ausland empfiehlt es sich, diese Option zu aktivieren, damit auf der Rechnung die Währung des Kunden steht.

<a name="vendor"></a>

### Artikelhersteller angezeigen

Für Bestellungen aus dem Ausland empfiehlt es sich, diese Option zu aktivieren, damit auf der Rechnung die Währung des Kunden steht.

<a name="tax-free-export"></a>

### Steuerfreie Ausfuhrlieferung

Lege fest, ob für Sendungen außerhalb der EU der Vermerk **Steuerfreie Ausfuhrlieferung i.S.d. §6 UstG** angezeigt werden soll.

<a name="tax-free-domestic"></a>

### Umsatzsteuerbefreiuung

Lege fest, ob für inländische Sendungen der Vermerk **Gemäß § 19 UStG wird keine Umsatzsteuer berechnet** angezeigt werden soll.

<a name="diff-taxing"></a>

### Differenzbesteuerung

Für den Second-Hand-Handel empfiehlt es sich, diese Option zu aktivieren. Damit wird auf der Rechnung keine Mehrwertsteuer ausgewiesen, da diese bereits beim Neukauf entrichtet wurde.

<a name="notification"></a>

### Rechnung in Versandbestätigung

Füge diesen Link in das Liquid-Template der Versandbestätigung ein, damit der Kunde die Rechnung selbst herunterladen kann. [In unserem Video](https://www.youtube.com/watch?v=DPrkwx3-SiA){:target="\_blank"} erklären wir, wie es funktioniert.

<a name="faq"></a>

## FAQ

<div class="faq-list">
<dl class="space-y-8">
<div>
<dt><h4>Wir benötigen alle Rechnungen in einem bestimmten Zeitraum, wie kann ich diese gebündelt herunterladen?</h4></dt>
<dd>Dazu gibt es die Export-Funktion innerhalb der App unter dem Reiter Archiv. Den Button dazu findet ihr oben rechts im Archiv</dd>
</div>

<div>
<dt><h4>Wie kann ich beim Rechnungstemplate die fortlaufende Rechnungsnummer ändern?</h4></dt>
<dd>Es kann kein Nummernkreis frei gewählt werden. Unsere Shipping Apps bieten als Rechnungsnummer die Bestellnummer (#4711) oder eine Kombination aus Bestellnummer/Bestelldatum (#4711/2023-09-18) an</dd>
</div>
</div>
