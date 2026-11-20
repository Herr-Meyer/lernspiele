# Die Lichtwerke von Umbra

Ein düsteres Browser-Lernspiel für **Technik und Naturwissenschaften (TuN), Klasse 9** zur Reihe **Elektrotechnik und Löten**. Es begleitet die Unterrichtsreihe ab Doppelstunde 3 als Wiederholung und Hausaufgabe.

**Spielen:** https://herr-meyer.github.io/lernspiele/lichtwerke-umbra/

| Titel | Kupfergasse | Frage mit Erklärung |
| --- | --- | --- |
| ![Titel](screenshots/1-titel.jpg) | ![Kupfergasse](screenshots/2-kupfergasse.jpg) | ![Erklärung](screenshots/4-erklaerung.jpg) |
| **Leuchtfeuer-Dioden** | **Schaltzeichen** | **Umbra leuchtet** |
| ![Dioden](screenshots/5-dioden.jpg) | ![Schaltzeichen](screenshots/6-schaltzeichen.jpg) | ![Ende](screenshots/7-umbra-leuchtet.jpg) |

## Worum es geht

Seit dem Großen Kurzschluss liegt die Stadt Umbra im Dunkeln. Als Lehrling der Lichtschmiede-Gilde reparierst du mit der zynischen Glühlampe **Wolfram** (60 W, im Ruhestand) in fünf Bezirken je drei Lichtwerke – und vermasselst Baron **Talgmund von Docht** vom Kerzenkartell das Geschäft. Jeder fertige Bezirk lichtet das Nebeltor zum nächsten und macht die Stadt heller.

| Bezirk | Minispiele | Inhalt |
| --- | --- | --- |
| Kupfergasse | Stromkreis-Drehrätsel, Fragen | Stromkreis, Leiter/Isolator, Sicherheit, Atombau, Ladung, Coulomb |
| Altes Pumpwerk | Zuordnen, Fragen | Wassermodell, Spannung, Stromstärke, Stromrichtung, Potenzial, „Strom wird nicht verbraucht“ |
| Archiv der Zeichen | Zuordnen (Schaltzeichen), Farbcode-Tresor, Stromkreis | Schaltzeichen, Widerstands-Farbcode |
| Halbleiterhafen | Ohm-Rechner, LED-Polung, Fragen | U = R · I, LED/Diode, Breadboard, Transistor, LDR, EVA |
| Zinnschmiede | Lötstellen beurteilen, Lötschritte ordnen, Fragen | Weichlöten, Flussmittel, Lötstellen, Sicherheit |
| Großes Lichtwerk | Stromkreis, Reihenfolge, gemischte Fragen | alles |

- Falsche Antworten werden erklärt und kommen am Ende der Runde noch einmal.
- **Mit Hilfen** (beim Start wählbar): Bei Multiple-Choice-Fragen ist eine falsche Antwort durchgestrichen.
- Steuerung: Pfeiltasten/WASD, E oder Leertaste; Rätsel mit der Maus. Gedacht für Laptops.
- Spielstand im Browser (`localStorage`, Schlüssel `lichtwerke-umbra-v1`).

## Technik

Eine einzige HTML-Datei, Canvas und reines JavaScript, keine Bibliotheken, keine externen Anfragen (keine Webfonts, kein Tracking). Die Lerninhalte stehen gesammelt im Abschnitt `INHALTE` am Anfang des Skripts und lassen sich dort anpassen.
