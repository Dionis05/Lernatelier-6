# Lernatelier-6

- Name: Dionis Beqa
- Zeitraum: 23.10.2026 bis 18.12.2026

## Grob-Planung

### Noten

Im Modul Informatik liege ich aktuell bei einem Notenschnitt von 5.0. In keinem Modul bin ich ungenügend, und ich bin insgesamt in allen Fächern solide. Mein Ziel ist ein Schnitt von mindestens 5.5, da ich für die Praktikumssuche ein möglichst starkes Zeugnis brauche. Besonders wichtig ist das Modul von Herrn Thut (C#), weil es mehrfach als zentral für den weiteren Ausbildungsverlauf bezeichnet wurde. Dort möchte ich mich gezielt verbessern.

### Veränderungen

In der letzten Lernperiode habe ich teilweise Projekte umgesetzt, mit deren Endresultat ich nicht zufrieden war. Zudem blieben einzelne Probleme (z. B. beim Memory-Template) über mehrere Wochen ungelöst. In dieser Lernperiode möchte ich Probleme strukturierter eingrenzen (Fehlermeldungen lesen, schrittweise testen) und sie in der Woche lösen, in der sie auftreten. Ausserdem möchte ich die Projekte sauberer abschliessen und dokumentieren (Commits mit klaren Beschreibungen, nachvollziehbare Repositories).

### Projekte / neue Technologien
Ich entwickle eine Konsolenanwendung, mit der man Aufgaben erfassen, anzeigen, als erledigt markieren und löschen kann. Die Aufgaben werden in einer JSON-Datei gespeichert, damit sie nach dem Beenden des Programms erhalten bleiben.

Projekt 1
- Die Klasse `Aufgabe` hat die Eigenschaften Titel, Beschreibung, Fälligkeitsdatum, Priorität und Status. Die Daten sind gekapselt (Properties mit `get`/`set` und Validierung).
- Die Klasse `Aufgabenverwaltung` verwaltet die Aufgaben in einer `List<Aufgabe>` und bietet die Methoden `Hinzufuegen`, `Loeschen`, `AlsErledigtMarkieren` und `Filtern`.
- Ein Menü in der Konsole (Schleife mit `switch`) steuert den Ablauf.
- Die Persistenz läuft über Serialisierung und Deserialisierung mit `System.Text.Json`.
- Eine Fehlerbehandlung mit `try`/`catch` fängt ungültige Eingaben ab (z. B. ein falsches Datumsformat)

### Generelle Ziele

1. Das C#-Projekt «Aufgabenverwaltung» bis zum 18.12.2026 vollständig abschliessen: Aufgaben können hinzugefügt, angezeigt, als erledigt markiert, gelöscht und in einer JSON-Datei gespeichert werden.
2. Den Vokabeltrainer bis zum 18.12.2026 fertigstellen und über GitHub Pages veröffentlichen.
3. Im Modul von Herrn Thut und von Herrn Colic aufmerksam mitarbeiten, um den Notenschnitt in Informatik auf mindestens 5.5 zu verbessern.

## Tagesplanungen

### Planung 23.10.2026

- [ ] Neues C#-Konsolenprojekt «Aufgabenverwaltung» in Visual Studio erstellen, das Repository anbinden und den ersten Commit pushen
- [ ] Klasse `Aufgabe` mit den Eigenschaften Titel, Beschreibung, Fälligkeitsdatum, Priorität und Status als Properties (`get`/`set`) umsetzen
- [ ] Klasse `Aufgabenverwaltung` mit einer `List<Aufgabe>` und der Methode `Hinzufuegen` erstellen
- [ ] Konsolenmenü mit `switch` bauen, das Aufgaben hinzufügt und mit `foreach` ausgibt, und die Funktion manuell testen

#### Tagesreflexion
Der Start mit einem neuen Projekt war einfacher als erwartet, weil ich zuerst das Klassendesign geplant habe, bevor ich Code geschrieben habe. Dadurch wusste ich bei `Aufgabe` und `Aufgabenverwaltung` genau, welche Eigenschaften und Methoden nötig sind. Beim Menü mit `switch` musste ich die Schleife mehrmals testen, bis die Eingaben richtig verarbeitet wurden. Daraus nehme ich mit, dass ich kleine Schritte sofort teste, statt erst am Ende. So finde ich Fehler früher und bleibe nicht wochenlang hängen wie beim Memory-Projekt.


### Planung 30.10.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

### Planung 06.11.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

### Planung 13.11.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

### Planung 20.11.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

### Planung 27.11.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

### Planung 04.12.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

### Planung 11.12.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

### Planung 18.12.2026

- [ ] ...Ihr Text...
- [ ] ...Ihr Text...
- [ ] ...Ihr Text...

#### Tagesreflexion

...Ihr Text...

## Lernperiode Reflexion

...Ihr Text...

