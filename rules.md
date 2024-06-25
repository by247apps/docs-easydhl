# Regeln

-   [Allgemein](#general)
-   [Regeln bearbeiten](#manage-rules)
    -   [Regel erfassen](#create-rule)
    -   [Regel deaktivieren](#inactivate-rule)
    -   [Regel löschen](#delete-rule)
-   [FAQ](#faq)

<a name="general"></a>

## Allgemein

Alles rund um das Regelwerk findest du unter **Einstellungen --> Regeln**.

Das Regelwerk von easyDHL dient dazu, das Versandprodukt einer Sendung anhand definierter Kriterien automatisch ermitteln zu lassen. Dies erleichtert die Abwicklung deiner Sendungen enorm und hilft dabei, bei der Wahl der richtige Versandart Fehler zu vermeiden.

<a name="manage-rules"></a>

## Regeln bearbeiten

Auf der Übersichtsseite hast du die Möglichkeit, neue Regeln zu erstellen, bestehende Regeln zu bearbeiten oder zu löschen.

Hier kannst du zudem festlegen, was passiert, wenn keine der erfassten Regeln zutrifft:

-   kein Label erstellen
-   Label anhand definierter Standard-Produkte erstellen

Diese Einstellung ist insbesondere dann sinnvoll, wenn man parallel mehrere Versandanbieter hat oder auch die Internetmarke nutzt. In diesen Fällen sollten Bestellungen bei nicht zutreffender Regelnanwendung weiterhin unberührt/offen bleiben, d.h. es sollte kein Label erstellt werden.

Darüberhinaus lassen sich Regeln priorisieren. Dies geschieht entweder direkt bei der Reihenfolge der erfassten Regeln oder aber nachgelagert über den "Pfeil nach oben". Klickt man diesen an, so wandert die Regel um eins nach oben und wird auf diese Weise zuerst angewendet.

<a name="create-rule"></a>

### Regel erfassen

Für die Erfassung einer Regel müssen folgende Felder mindestens befüllt werden:

-   Name
-   Anbieter (DHL oder Internetmarke)
-   Versandprodukt
-   eines der Kriterien

Zusätzlich können für DHL-Produkte weitere Optionen wie _Sperrgut, Altersprüfung und Höherversicherung_ dazugebucht werden.

> [!NOTE]  
> Halte den Mauszeiger über das Lämpchen des jeweiligen Kriteriums, um weitere Informationen zu erhalten.

<a name="inactivate-rule"></a>

### Regel deaktivieren

Soll eine Regel zwischenzeitlich deaktiviert, aber weiterhin erhalten werden, so klicke auf _Bearbeiten_ und anschließend auf _Deaktivieren_.

<a name="delete-rule"></a>

### Regel löschen

Soll eine Regel komplett entfernt werden, so klicke auf _Bearbeiten_ und anschließend auf _Löschen_.

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
