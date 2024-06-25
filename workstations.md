# easyPrint und Workstations

-   [Allgemein](#general)
-   [Installation easyPrint](#easyprint-setup)
    -   [Einstellungen](#easyprint-settings)
-   [Einstellungen Workstation](#workstation-settings)

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
