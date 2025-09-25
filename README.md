# SQL Playground - Unterrichtsedition (verbesserte, nutzerfreundliche Version)

![SQL Playground Screenshot](screenshot.png)  

## Kurze Beschreibung
Ein nutzerfreundlicher SQLite SQL Manager für Schüler und Lehrer.  
Bietet interaktiven SQL-Editor, klickbare History, Vorlagen, CSV-Import/Export, EXPLAIN-Auswertung, Visualisierung numerischer Daten und integrierte SQL-Hilfe mit Beispielbefehlen – ideal für Unterricht und Lernzwecke.

---

## Übersicht

Der **SQL Playground** ist ein interaktiver SQLite SQL Manager für den Unterricht.  
Er ermöglicht das Erstellen, Öffnen, Bearbeiten und Abfragen von SQLite-Datenbanken mit einer **benutzerfreundlichen Oberfläche**.  

### Hauptfeatures:
- **Klickbare History & gespeicherte Vorlagen**
- **CSV Import/Export**
- **Tabellarische Ergebnisse, sortierbar und kopierbar**
- **EXPLAIN Plan für SQL-Abfragen**
- **Visualisierung numerischer Ergebnisse (Matplotlib)**
- **Integrierte SQL-Hilfe mit Beispielbefehlen**
- **Statusleiste mit Feedback & Fehlermeldungen**
- **Aufgeräumte, responsive UI mit CustomTkinter** (fällt automatisch auf Tkinter zurück, falls nicht installiert)

---

## Installation

Benötigt:
- Python 3.8 oder höher
- Optional: [customtkinter](https://github.com/TomSchimansky/CustomTkinter)
- Optional: [matplotlib](https://matplotlib.org/) für Visualisierung

```bash
pip install customtkinter matplotlib
```

---

## Funktionen im Detail

### 1. Datenbankverwaltung
- **Neue In-Memory DB erstellen** – für Tests oder Unterricht.
- **Beispiel-DB laden** – enthält Tabellen `students`, `teachers`, `subjects`, `grades`.
- **Bestehende DB öffnen / speichern**
- **Zuletzt geöffnete DBs** werden automatisch angezeigt.

### 2. SQL Editor
- Syntaxfreundlicher Editor mit **History**
- **Verlauf & Vorlagen**: per Doppelklick laden
- **SQL-Hilfe / Beispiele**: zeigt alle wichtigen Befehle (`SELECT`, `INSERT`, `UPDATE`, `DELETE`, `JOIN`, ...) mit Beispielabfragen

### 3. Ergebnisse
- Tabellarische Darstellung
- **Sortierbare Spalten**
- **Rechtsklick-Menü**: Kopieren, Exportieren, Alles auswählen
- **Statusleiste**: zeigt Anzahl Zeilen und Statusmeldungen

### 4. CSV Import / Export
- **Import**: erkennt Header und Datentypen automatisch
- **Export**: exportiert sichtbare Ergebnisse oder Auswahl

### 5. SQL Explain
- EXPLAIN QUERY PLAN in eigenem Fenster
- Kopierbarer Text für Analyse

### 6. Visualisierung
- Bar-Charts für numerische Spalten
- Automatische Achsenbeschriftung und Layout

### 7. Nutzerfreundlichkeit
- Übersichtliches Layout, Tooltips, Statusmeldungen
- Maximal 400 Einträge in History
- Wiederherstellung letzter DB und Einstellungen

---

## Nutzung der SQL-Hilfe
1. Klicke auf **„SQL-Hilfe / Beispiele“**.
2. Wähle ein Beispiel oder markiere den Text.
3. Mit **„Ausgewählten Befehl einfügen“** wird der Befehl in den Editor übernommen.
4. Führe den Befehl wie gewohnt aus.

---

## Hinweise für den Unterricht
- Am besten erst mit **In-Memory DB** oder **Beispiel-DB** arbeiten
- Änderungen jederzeit als neue `.db` Datei speichern
- Ideal für Übungen zu SELECT, JOIN, Aggregationen und Datenmanipulation

---

## Lizenz
- Freie Nutzung für Unterricht und persönliche Lernzwecke  
- Keine Haftung für Datenverlust oder Schäden
- Weitere Lizenzinformationen: MIT License


---

## Autor
- Lukas1120987 / SchulSystem
