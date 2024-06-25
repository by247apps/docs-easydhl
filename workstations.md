# easyPrint und Workstations

-   [Allgemein](#general)
-   [Installation easyPrint](#easyprint-setup)
    -   [Einstellungen](#easyprint-settings)
-   [Einstellungen Workstation](#workstation-settings)
-   [FAQ](#faq)

<a name="general"></a>

## Allgemein

Alles rund um die Workstations findest du unter **Einstellungen --> Workstations**.

easyDHL bietet dir die Möglichkeit, mit einem Barcodescanner Barcodes auf unseren Pick- und Packlisten zu scannen und damit den automatischen Druck eines Versandlabels zu starten. Dazu muss unsere Anwendung [easyPrint](https://github.com/by247apps/easyPrint-public?tab=readme-ov-file#downloads---latest-version){:target="\_blank"} lokal auf deinem Computer heruntergeladen und installiert werden.

Mit easyPrint ist dann auch möglich, die in easyDHL erstellten Versandlabels auch direkt an deinen lokalen Durcker zu senden, ohne diese zunächst herunterzuladen und dann manuell drucken zu müssen.

<a name="easyprint-setup"></a>

## Installation easyPrint

Die aktuelle Version von easyPrint für MacOS und Windows findest du [hier](https://github.com/by247apps/easyPrint-public?tab=readme-ov-file#downloads---latest-version){:target="\_blank"}.

Lade die Anwendung dort herunter und installiere sie auf einem deiner lokalen Computer - im Weiteren _Workstation_ genannt.

<a name="easyprint-settings"></a>

### Einstellungen easyPrint

Nach der Installation von easyPrint sollten zunächst ein paar Einstellungen gemacht werden.

#### Auswahl der App

Wähle hier easyDHL aus.

#### Verbindung mit Workstation

Den Workstation-API-Key erhältst du, wenn du in easyDHL eine neue Workstation anlegst. Der API-Key wird dir dann unten zum Kopieren bereitgestellt. Kopiere ihn und füge dann hier ein.

#### Verbindung mit Drucker

Möchtest du, dass erstellte Dokumente direkt an deinen Drucker geschickt werden, so wähle den _Silent Mode_. Nun kannst du angeben, welchen Drucker du für welche Dokumente verwenden möchtest. Insgesamt kannst du je einen Drucker für folgende Dokumente festlegen:

-   Versandlabel
-   Retourenlabel
-   Restliche Dokumente

Damit wäre die Verknüpfung mit deinem Drucker hergestellt. Solltest du keinen direkten Druck wollen, so kannst du den Silent Mode deaktivieren. Damit erscheinen die erstellten Dokumente einzeln als PDF-Dateien.

<a name="workstation-settings"></a>

## Einstellungen Workstation

Vergebe beim Erstellen einer neuen Workstation zunächst einen Namen. Anschließend steht eine Reihe von Optionen bereit, um die Verarbeitung zu konfigurieren. Hier kannst du diejenigen Dokumente anklicken, die für dich relevant sind.

Abschließend musst du noch angeben, ob die erstellten Dokumente in der Einzelerstellung und/oder Bulkerstellung direkt an den Drucker geschickt werden sollen.

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
