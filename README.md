# Lernperiode 4 (24.04.2026 - 03.07.2026)

## Grobplanung
Diese Lernperiode möchte ich mehr mit Arduinos coden, meine eigenen Software Projekte verwirklichen und wenn ich gerade nichts zu tun habe möchte ich bei der Cisco Network Academy weiter lernen.

## Feinplanung
### 24.04.2026
- Arduino mit meinem Computer verbinden
- Mit Arduino IDE Code auf den Arduino pushen
- Einfachen Text auf dem Arduino zeigen

---

### Reflexion

- Arduino wurde mit dem Computer verbuden.
- Arduino IDE wurde geskipped, ich mag das IDE überhaupt nicht. Ich habe stattdessen Visual Studio Code mit PlatformIO benutzt, welches ich viel angenehmer finde.
- Ich habe die Power LED auf dem Arduino blinken lassen und den Text "Hello World!" über das Matrix-Display scrollen lassen. Es hat zwar eine Library die das Scrollen ermöglicht lässt aber den Loop leider nicht ganz durchlaufen. Deshalb habe ich eine Funktion geschrieben die den Text einfach mit X-Position verschiebt und dann wieder resettet.

---

### 01.05.2026

Ich habe im Verlauf der Woche ein kleines Projekt gestartet. Ich möchte die 12x8 LED Matrix meines Arduinos über das WiFi steuern. Ich entwickle gerade eine kleine Webseite in HTML/CSS/JS und schreibe die passende Firmware für den Arduino.
Mehr Projektdetails und das Repository:
- Meine Ziele sind es heute den Arduino und den PC (bzw. die Webseite) miteinander reden zu lassen sodass die individuellen LEDs angesteuert werden können.
- Ich muss mich also schlau machen wie Arduinos über das WLAN kommunizieren und wie der Webbrowser über das WLAN kommunizieren kann.

### Reflexion
Ich hatte noch nicht die Chance das Programm zu testen aber die Grobe logik von Webseite --> Verbindung --> reciever Code auf Arduino ist einigermassen fertig geschrieben. 

---

### 08.05.2026
Heute möchte ich weiter an meinem Arduino Projekt arbeiten. Ich möchte mein Programm einmal testen --> C++ oder JS debuggen falls irgendwas nicht funktioniert und festhalten was für Denkfehler ich gemacht habe.

### Reflexion
Das Programm funktioniert jetzt! Ich konnte erfolgreich Packets an den Arduino schicken und somit das Display kontrollieren. Der Webserver hat noch ein paar bugs zum ausbügeln und ich möchte nächstes Mal noch ein "Clear All" button hinzufügen und die funktionalität zu Zeichnen hinzufügen --> es ist zwar Support im Webserver da, jedoch werden die Packets zu schnell gesendet um vom Arduino angenommen zu werden.

### Additional Resources:
[Link zum Repo für Arduino Firmware](https://github.com/MetroTS/Arduino_WiFi_Display)/
[Link zur Webseite/Webserver für den Arduino](https://github.com/MetroTS/LEDControlWebsite)

---

### 22.05.2026

Heute möchte ich an meinen Aufträgen für die Kanti arbeiten, dabei habe ich noch 2 Aufträge aufzuarbeiten. Einen für Bio und einen für Wirtschaft. Sobald ich die Aufträge abgearbeitet habe, werde ich weiterhin ein wenig am Programmieren von HTML und CSS arbeiten, da dies für unser neues Modul wichtig ist. 
