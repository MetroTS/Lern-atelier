# Lernperiode-4

Name: Aaron Gerteis \
Zeitraum: 24.04.2026 - 03.07.2026

## Grob-Planung

### Noten
SQL sehr stark, ICT-Arbeitsplatz zufrieden, Notenstand jetzt gerade - zufrieden, mögliche Schwäche --> M117 Netzwerk

### Veränderungen
Im moment würde ich gerne nichts verändern.

### Projekte / neue Technologien
Powershell, HTML CSS, C++, C#, WPF

### Generelle Ziele
Diese Lernperiode möchte ich mehr mit Arduinos coden, meine eigenen Software Projekte verwirklichen und wenn ich gerade nichts zu tun habe möchte ich bei der Cisco Network Academy weiter lernen.

## Tagesplanungen

### 24.04.2026
- [x] Arduino mit meinem Computer verbinden
- [x] Mit Arduino IDE Code auf den Arduino pushen
- [x] Einfachen Text auf dem Arduino zeigen

---

### Reflexion

- Arduino wurde mit dem Computer verbuden.
- Arduino IDE wurde geskipped, ich mag das IDE überhaupt nicht. Ich habe stattdessen Visual Studio Code mit PlatformIO benutzt, welches ich viel angenehmer finde.
- Ich habe die Power LED auf dem Arduino blinken lassen und den Text "Hello World!" über das Matrix-Display scrollen lassen. Es hat zwar eine Library die das Scrollen ermöglicht lässt aber den Loop leider nicht ganz durchlaufen. Deshalb habe ich eine Funktion geschrieben die den Text einfach mit X-Position verschiebt und dann wieder resettet.

---

### 01.05.2026

Ich habe im Verlauf der Woche ein kleines Projekt gestartet. Ich möchte die 12x8 LED Matrix meines Arduinos über das WiFi steuern. Ich entwickle gerade eine kleine Webseite in HTML/CSS/JS und schreibe die passende Firmware für den Arduino.
Mehr Projektdetails und das Repository:
- [x] Meine Ziele sind es heute den Arduino und den PC (bzw. die Webseite) miteinander reden zu lassen sodass die individuellen LEDs angesteuert werden können.
- [x] Ich muss mich also schlau machen wie Arduinos über das WLAN kommunizieren und wie der Webbrowser über das WLAN kommunizieren kann.
- [ ] Platzhalter für 3

### Reflexion
Ich hatte noch nicht die Chance das Programm zu testen aber die Grobe logik von Webseite --> Verbindung --> reciever Code auf Arduino ist einigermassen fertig geschrieben. 

---

### 08.05.2026
Heute möchte ich weiter an meinem Arduino Projekt arbeiten. Ich möchte mein Programm einmal testen --> C++ oder JS debuggen falls irgendwas nicht funktioniert und festhalten was für Denkfehler ich gemacht habe.
- [x] Meine Ziele sind es heute den Arduino und den PC (bzw. die Webseite) miteinander reden zu lassen sodass die individuellen LEDs angesteuert werden können.
- [x] Ich muss mich also schlau machen wie Arduinos über das WLAN kommunizieren und wie der Webbrowser über das WLAN kommunizieren kann.
- [ ] Platzhalter für 3

### Reflexion
Das Programm funktioniert jetzt! Ich konnte erfolgreich Packets an den Arduino schicken und somit das Display kontrollieren. Der Webserver hat noch ein paar bugs zum ausbügeln und ich möchte nächstes Mal noch ein "Clear All" button hinzufügen und die funktionalität zu Zeichnen hinzufügen --> es ist zwar Support im Webserver da, jedoch werden die Packets zu schnell gesendet um vom Arduino angenommen zu werden.

### Additional Resources:
[Link zum Repo für Arduino Firmware](https://github.com/MetroTS/Arduino_WiFi_Display)/
[Link zur Webseite/Webserver für den Arduino](https://github.com/MetroTS/LEDControlWebsite)

---

### 22.05.2026

Heute möchte ich an meinen Aufträgen für die Kanti arbeiten, dabei habe ich noch 2 Aufträge aufzuarbeiten. Einen für Bio und einen für Wirtschaft. Sobald ich die Aufträge abgearbeitet habe, werde ich weiterhin ein wenig am Programmieren von HTML und CSS arbeiten, da dies für unser neues Modul wichtig ist. 

- [x] Bio Auftrag
- [x] Wirtschaft Auftrag
- [ ] Platzhalter für 3

### Reflexion
Ich habe den Wirtschaftsauftrag mit meinen Partnern fertiggestellt. Der Bio Auftrag hat sich etwas länger als erwartet herausgestellt und ich habe ihn noch nicht ganz fertig. Fürs Programmieren hatte ich heute nur sehr wenig Zeit.

---

### 29.05.2026

Heute möchte ein wenig an meinen Programmierfähigkeiten mit Lua arbeiten. 

- [x] Lua loops
- [x] Lua functions
- [x] Lua variables

### Reflexion
Es ist mir gelungen weiterhin an Lua zu arbeiten, ich baue gerne sachen auf der Platform Roblox nach und programmiere es mit Grundfunktionen. Ich habe mich für die, am kommenden Juli, Waschanlagenschau in Roblox. Ich bin dort in der "Waschanlagen Community" bei Auto Waschstrasssen.

---

### 05.06.2026

- [x] GitHub Repository aktualisieren und richtig formatieren.
- [x] Für den Bio Test Lernen
- [ ] Powershell weiterhin an meinem Projekt arbeiten

### Reflexion

Github Repository aktualisiert - sie ist nun richtig formatiert.
Bio Test so gut wie möglich gelernt und repetiert. Drücken sie mir die Daumen!
PowerShell nicht weiterhin an meinem Projekt gearbeitet

---

### 12.06.2026

- [ ] Powershell Projekt arbeiten
- [ ] HTML CSS Projekt arbeiten
- [ ] Weiterhin am Lua arbeiten für meine Waschanlagen simulation
- [x] USB Reverse Engineering --> Tobii Eye Tracker vom VR Headset ansteuern

### Reflexion
Ich habe heute nur eines meiner groben Projekte verfolgt. Ich habe ziemlich viel Zeit aufgebraucht einen groben Plan für mein VR-Projekt zu formulieren. Zwar geht es dabei darum, die Sensoren der HP Reverb G2 Omnicept anzusteuern. Ich möchte ein nativen Treiber für Windows und/oder Linux schreiben der die Hardware enumeriert und exposed. 

Grober Plan wurde bis jetzt (mithilfe von Herr Lauk und Claude) so formuliert:
- Wie verbindet man sich mit dem Headset?
  - Wo findet man das Headset?
    - Was macht dieser USB überhaupt?
    - Headset Verbindung
  - Auf was hört es?
  - Auf was spricht es an?
  - Omnicept dekompilieren, vielleicht mehr herausfinden.
- Endgoal: Starten der ET Hardware!!!
  - Auf was hört es um zu starten?
  - Was spricht es?

---

### 19.06.2026

- [x] Verbinden mit Headset --> Dazu gehört: Adresse?, USB Interface?, WireFormat?
- [x] Test Nachrichten schicken --> auf was hört das Headset??
- [ ] Abhören --> Falls es spricht, was spricht es zurück??

### Reflexion
Mir ist es gelungen die Verbindung mit dem Headset herzustellen. Ich habe mittels Wireshark ein wenig den USB abgehört um zu ermitteln was für Sachen zum und vom Headset geschickt werden. Dabei ist mir aufgefallen, dass die Omnicept Runtime das Headset anderst enumeriert wie wenn ich es einfach normal ohne Runtime in den PC einstecken würde. Manche USB Devices werden zwar als Devices erkannt jedoch werden ihre Treiber nicht normal gestartet ausser sie werden für ein Programm gefordert.

Ich habe probiert ein paar test Nachrichten zu schicken à la Wireshark was ich gesehen habe, jedoch ist nie etwas zurück gekommen.

---

### 26.06.2026

- [x] Test Nachricht = Response
- [x] Abhören
- [ ] Eye Tracking Hardware aus dem schlaf erwachen lassen

### Reflexion
Ich habe bereits die Kommunikation mit dem Gerät etablier. Nachrichten senden und empfangen funktioniert, und das passive Abhören läuft. Der nächste kritische Schritt, das Eye-Tracking-Modul aus dem Ruhezustand zu wecken, ist noch offen und wahrscheinlich der schwierigste Teil, da er das genaue Wake-up-Protokoll auf dem USB/HID-Bus erfordert. Das Fundament steht aber solide.

---
# Lernperiode Reflexion
Eine Zusammenfassung über die Lernperiode an sich:
Ich finde in dieser Lernperiode habe ich vieles dazugelernt. Ich habe viel neues ausprobiert, manchmal lief es gut, manchmal jedoch auch schlecht. Alles in allem denke ich habe ich viel gutes gelernt und meistens positive Ergebnisse gehabt.
