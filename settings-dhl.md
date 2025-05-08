# DHL

-   [Zugangsdaten erfassen](#credentials)
-   [Teilnahmenummern überschreiben](#override-billing)
-   [Receiver-Ids](#inactivate-receiver)
-   [FAQ](#faq)

<a name="credentials"></a>

## Zugangsdaten erfassen

Für die Verknpfung von easyDHL mit deinem DHL-Geschäftskonto ist lediglich die Erfassung der Zugangsdaten des DHL-Geschäftakundenportals notwendig. easyDHL importiert die dort erfassten Abrechnungsnummern und Receiver-Ids dann automatisch. <a class="video">https://youtu.be/7GEaQC02t5s</a>

> [!NOTE]
> Solltest du noch kein DHL-Geschäftskunde sein, kannst du dich hier registrieren: [DHL-Geschäftskunde werden](https://www.dhl.de/de/geschaeftskunden/paket/kunde-werden/angebot-dhl-geschaeftskunden-online.html)

<a name="override-billing"></a>

## Teilnahmenummern überschreiben

Solltest andere Teilnahmenummern als die importierten verwenden, so können diese bequem überschrieben werden.

> [!NOTE]
> Sollte ein Produkt nicht aufgelistet sein wie z.B. Kleinpaket (Warenpost) kann dies nur duch die DHL Vertragsabteilung freigeschaltet werden. Das Problem ist bei DHL technisch im System. Neue Nummer (Produkte) werden oft nicht automatisch freigegeben. Das heißt, man muss da bei der technischen Abteilung anrufen, damit diese das manuell freischalten. 

<a name="inactivate-receiver"></a>

## Receiver-Ids deaktivieren

Solltest du mehrere Receiver-Ids für ein Land haben, hast du die Möglichkeit, nicht relevante Receiver-Ids zu deaktivieren.



<a name="faq"></a>

## FAQ

<div class="faq-list">
<dl class="space-y-8">
<div>
<dt><h4>Ungültige Zugangsdaten</h4></dt>
<dd>In dem Fall scheinbar ist das Passwort abgelaufen oder wurde bereits erneuert. Melde dich dazu einmal im DHL Geschäftskunden Portal an. Dann in der App unter Einstellung DHL und dort noch einmal das gleiche Passwort eintragen / speichern. Warum ist das so? Die Passwörter laufen bei der DHL nach drei Monaten ab</dd>
</div>

<div>
<dt><h4>Benutzername und Password stimmen aber ich kann mich nicht anmelden, woran liegt das?</h4></dt>
<dd>Solltest du die 2FA Authentifizierung im DHL Geschäftskunden Portal aktiviert haben, dann wird es höchstwahrscheinlich am gewählten Sicherheitsproblem liegen. Hier entweder die 2FA komplett deaktiviert oder aber das Sicherheitsprofil wie folgt geändert werden, siehe Screenshot:

![DHL-2fa-Problem](https://media.247apps.de/storage/faq/dhl-2fa-problem.png)</dd>

</div>

<div>
<dt><h4>Receiver Ids können nicht geladen werden, woran liegt das?</h4></dt>
<dd>Stelle sicher, dass in deinem DHL Vertrag die Möglichkeit für Retouren hinterlegt ist. 

<img width="700" alt="retouren-im-dhl-vertrag" src="https://github.com/user-attachments/assets/649b49e9-9469-42cb-9004-fe39257b51a9">
  
Wenn im DHL Geschäftskundenportal, keine Retouren Receiver IDs zu finden sind (siehe Screenshot), melde dich bei der DHL Vertragsabteilung um dies freizuschalten. Erwähne dabei, dass es sich um den Versand über die DHL Retouren Schnittstelle handelt und entsprechende Receiver IDs für alle Länder, aus denen du Retouren empfangen möchtest hinterlegt werden sollen. Wir haben auf vertragliche Angelegenheiten keinen Zugriff.

</dd>

</div>

<div>
<dt><h4>Die ausgewählte Abrechnungsnummer steht nicht zur Verfügung</h4></dt>
<dd>Aus unserer Erfahrung kann dieses Problem am schnellsten durch den telefonischen DHL Kundenservice behoben werden. In der Regel liegt hier ein Problem im Vertrag beziehungsweise DHL Geschäftskunden-Konto vor</dd>

</div>
</dl>
</div>
