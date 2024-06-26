# Cyber My Admin

## Einleitung

Cyber My Admin ist eine benutzerfreundliche Webanwendung, die es ermöglicht, Datenbanken zu verwalten und SQL-Abfragen auszuführen. Diese Anwendung bietet eine intuitive Benutzeroberfläche und eine Reihe von Funktionen zur einfachen Verwaltung von Datenbanken.

---

## Installieren und Einrichten

### Voraussetzungen
- Ein Webserver (z.B. Apache, Nginx)
- PHP (empfohlen: PHP 7 oder höher)
- MySQL-Datenbank

### Schritte
1. **Dateien herunterladen**: Lade die Dateien der Cyber My Admin-Anwendung auf deinen Webserver hoch. [buchladen-master.zip](https://github.com/tsuki-kami-studios/buchladen/archive/refs/heads/master.zip)
2. **Für Xampp**: Zip Datei entpacken und Ordner **buchladen** in `./xampp/htdocs/` verschieben. Wenn das Standard Datenbank Passwort verwendet wird: `./credentials.json` löschen, ansonsten die Daten anpassen.
3. **Datenbank einrichten**: Erstelle eine MySQL-Datenbank und importiere bei Bedarf Testdaten aus den bereitgestellten SQL-Dateien.
4. **Konfiguration**: Passe die Datei `./credentials.json` an, um die Verbindungsdaten zur MySQL-Datenbank einzutragen.
5. **Zugriffsrechte**: Stelle sicher, dass die Dateien die richtigen Zugriffsrechte haben, um vom Webserver ausgeführt zu werden.

---

## Verwendung

### Benutzeroberfläche

Die Benutzeroberfläche von Cyber My Admin ist einfach und intuitiv gestaltet. Hier sind die wichtigsten Elemente:

- **Sidebar**: Hier werden die verfügbaren Datenbanken angezeigt.
- **Topbar**: Zeigt die verfügbaren Tabellen in der ausgewählten Datenbank an.
- **SQL-Konsole**: Ermöglicht das direkte Ausführen von SQL-Abfragen.
- **Datenanzeige**: Zeigt die Daten der ausgewählten Tabelle an.

### Verbinden mit einer Datenbank

1. Wähle eine Datenbank aus der Sidebar aus.
2. Wähle eine Tabelle aus der Topbar aus, um die Daten anzuzeigen.

### Daten bearbeiten

1. Klicke auf eine Zelle, um sie zu bearbeiten. Änderungen werden automatisch gespeichert.
2. Füge neue Daten hinzu, indem du auf den "+" Button klickst und die erforderlichen Informationen eingibst.
3. Lösche eine Zeile, indem du auf den "Delete" Button klickst.

### SQL-Abfragen ausführen

1. Gebe eine SQL-Abfrage in das Textfeld der SQL-Konsole ein.
2. Klicke auf "Execute", um die Abfrage auszuführen.
3. Die Ergebnisse werden unterhalb der Konsole angezeigt.

---

## Weitere Funktionen

- **Sortieren von Daten**: Klicke auf die Spaltenüberschriften, um die Daten in aufsteigender oder absteigender Reihenfolge zu sortieren.
- **Filtern von Daten**: Gib einen Suchbegriff in das Suchfeld ein, um die angezeigten Daten zu filtern.
- **Reset der Datenbank**: Setze die Datenbank auf den Ausgangszustand zurück, indem du auf den entsprechenden Button klickst.

---

## Support und Kontakt

Wenn du Fragen oder Probleme hast, zögere nicht, uns zu kontaktieren. Wir helfen dir gerne weiter.

Kontaktiere uns unter support@kami-hub.com.

Besuche auch unsere [Website](https://www.kami-hub.com) für weitere Informationen und Updates.

---

## Screenshots

...
![image](https://github.com/tsuki-kami-studios/buchladen/assets/160274072/f106ddc2-4820-486e-a88c-0c0bc51669ae)

---

## Lizenz

...

---

## Autor

Entwickelt von Kami-Studios Team in Zusammenarbeit mit Zabrak

© 2024 Kami-Studios. Alle Rechte vorbehalten.
