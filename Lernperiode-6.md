# Lern-Periode 6
- Name: Gerteis  Lucy
- Zeitraum: 23.10.2026 bis 18.12.2026

## Grob-Planung

### Noten
<!--
Wo stehen Sie mit Ihren Noten? In welchen Modulen waren Sie besonders stark;
in welchen sind die ungenügend? Welche davon sind besonders wichtig?
-->

Noten werden im Verlauf vom Jahr noch eingefügt.

### Veränderungen
<!--
Was möchten Sie generell im Vergleich zur letzten Lernperiode anpassen?
-->

Im Vergleich zur letzten Lernperiode möchte ich meine Ziele klarer und überprüfbarer formulieren. Statt allgemeiner Vorhaben lege ich für jedes Projekt ein konkretes Ergebnis fest (z. B. «veröffentlicht», «läuft», «entschieden»). Ausserdem plane ich meine Arbeitspakete so, dass sie jeweils in 30 bis 60 Minuten zu schaffen sind und am Ende des Tages eindeutig abgehakt werden können.

Ich will mich auf wenige Projekte konzentrieren, statt an allen gleichzeitig zu arbeiten, damit ich sie wirklich abschliesse. Zusätzlich setze ich einen festen Schwerpunkt auf Linux, den ich in der Planung bewusst einbaue, statt ihn nur nebenbei zu lernen.

### Projekte / neue Technologien
<!--
Was für Projekte/neue Technologien möchten Sie gerne in dieser Lernperiode lernen?
Verlinken Sie zu den GitHub Repos Ihrer Projekte.
(Können Sie später nach und nach einfügen.)
-->

**Projekte**

- **Lernatelier-Checker:** Prüfwerkzeug für Lernatelier-Dokumente mit einer Python-CLI, einer JS-Bibliothek ([lernatelier-checker-js](https://github.com/MetroTS/lernatelier-checker-js)) und einer VS-Code-Erweiterung. In dieser Lernperiode baue ich die Erweiterung fertig und veröffentliche sie.
- **BaseStationBoss:** SteamVR-Plugin, das Lighthouse-Basisstationen beim Start ein- und beim Beenden ausschaltet. Ziel ist eine öffentliche Version auf GitHub. Repo: [LINK EINFÜGEN]
- **Opencept Utility:** WPF-Anwendung, die das USB-Protokoll der Sensoren der HP Reverb G2 Omnicept per Reverse Engineering anspricht. Als Nächstes folgt die Face-Tracking-Kamera für die Anbindung an VRChat. Repo: [LINK EINFÜGEN]
- **Haptic-Trackpad-PCB:** Eigenes Trackpad mit haptischem Feedback als Ersatz für das ASUS-ROG-G14-Trackpad. Ich schliesse die Schaltplanentscheidungen ab. Repo: [LINK EINFÜGEN]

**Neue Technologien**

- **VS-Code-Erweiterungen:** Aufbau, Diagnostics-API, Bündeln mit esbuild und Veröffentlichen im Marketplace
- **Linux:** Shell-Skripte, systemd und Konfiguration meines Arch-/Hyprlanland-Setups
- **Reverse Engineering:** USB-Protokolle mit Wireshark analysieren

### Generelle Ziele
<!--
Was haben Sie für klare und messbare Ziele in dieser Lernperiode?
-->

In dieser Lernperiode will ich meine laufenden Projekte zu einem vorzeigbaren Stand bringen und mein Linux-Wissen vertiefen.

Projekte abschliessen:

- BaseStationBoss (SteamVR-Plugin für Lighthouse-Basisstationen): Ich veröffentliche eine funktionierende Version auf GitHub, die 1.0- und 2.0-Basisstationen     unterstützt und Einstellungen in SteamVR bietet. (vorallem C++)
- Opencept Utility (Reverse Engineering der HP Reverb G2 Omnicept): Der Zugriff auf den Eye-Chip funktioniert stabil. Als nächsten Sensor nehme ich die Face-Tracking-Kamera in Angriff, mit dem Ziel VRChat-Anbindung. (vorallem C#)
- Lernatelier-Checker (Python-CLI, JS-Bibliothek, VS-Code-Erweiterung): Die VS-Code-Erweiterung läuft und ist im Marketplace veröffentlicht. (Typescript, HTML + CSS)
Haptic-Trackpad-PCB: Das Schema ist fertig geprüft, und die Bauteilwahl (Piezo, FSR) ist entschieden.

Jedes Projekt erhält ein README, und der Stand wird auf GitHub nachgeführt.

Linux: Ich nutze Linux täglich und möchte es nun gezielter vertiefen: Shell-Skripte schreiben, Dienste mit systemd steuern und mein Arch-/Hyprland-Setup sauber konfigurieren und dokumentieren. Mein Ziel ist, dass ich Linux-Systeme selbstständig einrichten und Probleme eigenständig lösen kann. Das ist eine nützliche Basis für spätere Bewerbungen.

## Tagesplanungen
<!--
Planen Sie die Lernperiode. Dazu planen Sie Arbeitspakete (jeweils für den
kommenden Arbeitstag) und erstellen am Ende jedes Tages eine kurze Reflexion.

Wenn Sie an einem Tag gefehlt haben, schreiben Sie direkt unter die
Tagesüberschrift eines dieser Schlüsselwörter allein auf eine Zeile:
absence, absent, Absenz, abwesend, krank, Krankheit.
-->

### Planung 23.10.2026

- [ ] Entwicklungsumgebung auf dem Arch-Laptop einrichten (Node.js, npm, Git, Editor) und mit `yo code` ein TypeScript-Erweiterungsgerüst erzeugen. Mit F5 starten, bis der Beispielbefehl in der Befehlspalette erscheint
- [ ] `lernatelier-checker-js` in die Erweiterung einbinden und in `extension.ts` mit einem Testtext aufrufen. Das Prüfergebnis erscheint im Output-Fenster
- [ ] Die Prüfung auf die aktuell geöffnete `.md`-Datei beschränken: Text aus dem aktiven Editor lesen, andere Dateitypen überspringen
- [ ] Prüfergebnisse als Diagnostics im Problems-Panel von VS Code anzeigen, jeweils mit Zeilenangabe
- [ ] Prüfung automatisch beim Speichern ausführen, kurzes README mit Installation und Funktionsumfang schreiben und den Stand auf GitHub pushen


#### Tagesreflexion
<!--
Mögliche Themen: Was lief erstaunlich gut/schlecht? Wo ging der Plan nicht auf
und wieso? Was konnten Sie daraus für Ihr Vorgehen lernen?
Nicht wiederholen, was die Checkboxen schon aussagen.
Umfang: 50 - 100 Wörter (ungefähr 3 - 6 Sätze)
-->

...Ihr Text...


<!--
Fügen Sie hier die weiteren Tage der Lernperiode ein.
-->

## Lernperiode Reflexion
<!--
Am Ende der Lernperiode schreiben Sie eine Reflexion über die gesamte Lernperiode.
Mögliche Themen: Wie gut passt Ihr Endresultat zu dem, was Sie sich vorgenommen
hatten? Unterm Strich, was ist Ihr grösstes Lernresultat? Was nehmen Sie für die
Zukunft mit aus dieser Lernperiode?
Umfang: 100 - 200 Wörter (ungefähr 6 - 12 Sätze)
-->
...Ihr Text...

