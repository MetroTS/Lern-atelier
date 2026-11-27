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

- [x] Entwicklungsumgebung auf dem Arch-Laptop einrichten (Node.js, npm, Git, Editor) und mit `yo code` ein TypeScript-Erweiterungsgerüst erzeugen. Mit F5 starten, bis der Beispielbefehl in der Befehlspalette erscheint
- [x] `lernatelier-checker-js` in die Erweiterung einbinden und in `extension.ts` mit einem Testtext aufrufen. Das Prüfergebnis erscheint im Output-Fenster
- [x] Die Prüfung auf die aktuell geöffnete `.md`-Datei beschränken: Text aus dem aktiven Editor lesen, andere Dateitypen überspringen
- [x] Prüfergebnisse als Diagnostics im Problems-Panel von VS Code anzeigen, jeweils mit Zeilenangabe
- [x] Prüfung automatisch beim Speichern ausführen, kurzes README mit Installation und Funktionsumfang schreiben und den Stand auf GitHub pushen


#### Tagesreflexion
<!--
Mögliche Themen: Was lief erstaunlich gut/schlecht? Wo ging der Plan nicht auf
und wieso? Was konnten Sie daraus für Ihr Vorgehen lernen?
Nicht wiederholen, was die Checkboxen schon aussagen.
Umfang: 50 - 100 Wörter (ungefähr 3 - 6 Sätze)
-->

Der Plan ist komplett aufgegangen, vor allem weil jedes Arbeitspaket ein eindeutiges Ergebnis hatte: «erscheint in der Befehlspalette», «erscheint im Problems-Panel». So wusste ich nach jedem Schritt sofort, ob er fertig ist. Besonders hilfreich war, dass lernatelier-checker-js schon als Bibliothek existierte, sodass ich die Prüflogik nicht neu schreiben musste. Die Diagnostics-API war am Anfang ungewohnt, mit den Zeilenangaben funktionierte sie dann aber gut. Für das nächste Mal nehme ich mit, dass ich die Pakete ruhig etwas grösser planen darf.

<!--
Fügen Sie hier die weiteren Tage der Lernperiode ein.
-->

### Planung 30.10.2026

- [x] Abweichung des Plans
- [ ] Markdown Editor - Groben Plan für die Applikation definieren. Was will ich? Was soll es machen? Wie?
- [x] Kaffegespräch mit Herr Lauk ;p
- [ ] Mit der Umsetzung von der Notizen Applikation starten.


#### Tagesreflexion
<!--
Mögliche Themen: Was lief erstaunlich gut/schlecht? Wo ging der Plan nicht auf
und wieso? Was konnten Sie daraus für Ihr Vorgehen lernen?
Nicht wiederholen, was die Checkboxen schon aussagen.
Umfang: 50 - 100 Wörter (ungefähr 3 - 6 Sätze)
-->

Ich habe zuerst, wie bei jedem Projekt so üblich, das Projektverzeichnis angelegt, git darauf angesetzt und mit dotnet ein template geladen. Ich habe mich entschieden dieses Projekt in C# umzusetzen. Mal schauen, was wird :p.

Meilensteine für mein Projekt:
- Eine Notizen Applikation, mit welcher man in Markdown arbeiten kann, entweder in einem Terminal User Interface oder im Graphical User Interface
- Sie kann durch sogenannte "Packs" expandiert werden und ist somit für den Individuellen Nutzer angepasst (z.B. Nutzer in der IMS brauchen etwas um Notizen für FRW oder Wirtschaft zu erleichtern.)
- Das Programm wird in C# geschrieben

<!--
Fügen Sie hier die weiteren Tage der Lernperiode ein.
-->

### Planung 06.11.2026

- [x] Vorbereitung für das Fachgespräch zu Modul 320
- [x] Weiterarbeit an Metro Editor, die Notizen Applikation: Package Manifest, Package Tests TOML
- [ ] AP


#### Tagesreflexion
<!--
Mögliche Themen: Was lief erstaunlich gut/schlecht? Wo ging der Plan nicht auf
und wieso? Was konnten Sie daraus für Ihr Vorgehen lernen?
Nicht wiederholen, was die Checkboxen schon aussagen.
Umfang: 50 - 100 Wörter (ungefähr 3 - 6 Sätze)
-->

Ich war heute extrem Nervös über das Fachgespräch heute. Hatte mich so gut wie es geht vorbereitet, jedoch gab es für mich immernoch ein paar schwierige Holpersteine. Metro Editor hat ein wenig neuen Zuschuss an funktion bekommen. Ich probiere zuerst einmal eine Klasse zu befüllen für die Packs die ich machen werde, sodass ich die Klasse befüllt werden kann und der Editor die nötigen Werte zum weiterarbeiten bekommt.

<!--
Fügen Sie hier die weiteren Tage der Lernperiode ein.
-->

### Planung 20.11.2026

- [x] Weiterarbeit an Metro Editor, die Notizen Applikation: Package Manifest, Package Tests TOML, bis wir aus einer TOMLpackage Datei weiterhin auslesen können
- [x] ggf. weiterarbeiten??
- [x] The Farmer was replaced: Sonnenblumen Loop schreiben.



#### Tagesreflexion
<!--
Mögliche Themen: Was lief erstaunlich gut/schlecht? Wo ging der Plan nicht auf
und wieso? Was konnten Sie daraus für Ihr Vorgehen lernen?
Nicht wiederholen, was die Checkboxen schon aussagen.
Umfang: 50 - 100 Wörter (ungefähr 3 - 6 Sätze)
-->

Ich hatte probleme mit 2 Dimensionalen Arrays in Python. Wie kann man sie Strukturieren darin speichern und sie richtig auslesen. Wie checkt man dann wo die grössten Blumen wachsen und wie kommt man dahin? Das mache ich nächstes mal. Mehr habe ich nichts zu sagen aber 50 Wörter brauche ich noch.

<!--
Fügen Sie hier die weiteren Tage der Lernperiode ein.
-->

### Planung 27.11.2026

- [x] The Farmer was replaced: Algorithmus zum Ermitteln der Sonnenblumenposition und die Drohne auf die grössten Sonnenblumen zuerst zu navigieren.
- [x] AP
- [x] AP


#### Tagesreflexion

Letztes mal hatte ich erstaunlich viele Probleme mit Arrays in meinem Code. Mit diesen Problemen nun gelöst, habe ich mich dem zweiten Teil des Programms gewappnet. Nun wissen wir ja wieviel von den grössten Sonnenblumen wir gepflanzt haben und haben die genaue X- und Y-Koordinaten dessen Blumen. Nun besteht die neue Challenge darin, dass wir die Drohne zuerst zu den grössten Sonnenblumen leiten, sodass Sie sie ernten kann. 

Dabei habe ich mir mein Code so vorgestellt:
'code'
'for i in range(len(grid)):'
```  if grid
    for i in range(len(grid)):
        if grid[i][2]==15:                              #Falls das Array i im zweiten Element die Zahl 15 enthält dann:
            if grid[i][0] != get_pos_x():               #gleiche ab, ob du auf der gleichen X-Position bist wie das Element in der Liste
                while grid[i][0] != get_pos_x():        #solange du nicht die gleiche X-Position erreicht hast, bewege dich nach Osten.
                    move(East)
                if grid[i][1] != get_pos_y():           #dann gleiche ab, ob du auf der gleichen Y-Position bist wie das Element in der Liste
                    while grid[i][1] != get_pos_y():    #solange du das nicht bist, bewege dich nach Norden.
                        move(North)
                    harvest()                           #Wenn diese Bedingungen erfüllt sind, baue die Sonnenblume ab.
            else:
                if grid[i][1] != get_pos_y():           #Dies ist der wichtige Teil des Codes!!!! Hier war mein Denkfehler. Ich hatte gedacht mit der ersten Abfrage werden alle cases abgefangen! 
                    while grid[i][1] != get_pos_y():    #Jedoch muss man beachten, dass die Y-Koordinate oder X-Koordinate per Zufall schon von der Drohne erreicht wurden. 
                        move(North)                     #Sonst würde die Drohne es einfach ignorieren. 
                    harvest()
                else:
                    harvest()
    if get_pos_x() != 0:                                #Nun kommt der Rest der Sonnenblumen dran. Wir wollen die Drohne wieder "home" leiten. Also leiten wir sie mit der Frage "bist du auf anfang x/y?" wieder zum start. 
        while get_pos_x() != 0:
            move(West)
    if get_pos_y() != 0:
        while get_pos_y() != 0:
            move(South)
    for i in range(worldsize*worldsize):               #Wir löschen die Elemente des Arrays Stück für Stück, sodass die neuen Elemente nicht einfach addiert werden.
        grid.pop()
    for c in range(worldsize):                         #Zweiter Loop zum neuen Befüllen des Arrays. Folgt dem gleichen Prinzip wie nächstes Mal.
            coordinate_x = get_pos_x()
            for r in range(worldsize):
                harvest()
                field=[]
                if get_entity_type() == Entities.Grass:
                    till()
                plant(Entities.Sunflower)
                use_item(Items.Fertilizer)
                coordinate_y = get_pos_y()
                size = measure() 
                field.append(coordinate_x)
                field.append(coordinate_y)
                field.append(size)
                grid.append(field)
                move(North)
            move(East)
```


Was lief nun Schwierig?:

Die Logik um die Drohne zu den grössten Sonnenblumen zuerst zu bewegen bräuchte ein Paar Anläufe. Ich hatte mich ein Paar mal den Tagen danach hingesetzt und alles nochmals überdacht. Etwas was für uns so selbstverständlich klingt ist eigentlich ein langer Gedankenprozess von Auschlusskriterien.

Was möchte ich das nächste mal machen? Ich möchte die Kakteen anfangen.

### Planung 04.12.2026

- [x] The Farmer was replaced: Kakteen Sortierungsalgorithmus
- [x] AP
- [x] AP


#### Tagesreflexion
<!--
Mögliche Themen: Was lief erstaunlich gut/schlecht? Wo ging der Plan nicht auf
und wieso? Was konnten Sie daraus für Ihr Vorgehen lernen?
Nicht wiederholen, was die Checkboxen schon aussagen.
Umfang: 50 - 100 Wörter (ungefähr 3 - 6 Sätze)
-->


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

