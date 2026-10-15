# Einbürgerungstest-Quiz (Kanton Aargau)

Lernspiel zum staatsbürgerlichen Test (Einbürgerungstest Kanton Aargau, Fragenkatalog gültig ab 29.09.2025).

👉 **[Quiz öffnen](https://bom5400.github.io/einbuergerungstest-quiz/)**

## Funktionen
- 325 Multiple-Choice-Fragen aus dem offiziellen PDF (inkl. 7 Bildfragen), in 5 Themenbereichen
- Fragen werden in zufälliger Reihenfolge gestellt (optional auch die Antworten gemischt)
- Anzahl Fragen pro Runde frei wählbar, Themenbereiche filterbar
- Sofortiges Feedback und Auswertung am Ende (richtig/falsch, Prozent, Übersicht aller Antworten, „Falsche wiederholen“)
- Zu einfache Fragen lassen sich aussortieren; die Auswahl wird im Browser (localStorage) gespeichert, beim nächsten Öffnen automatisch wieder eingelesen und kann jederzeit rückgängig gemacht werden
- Sicherung der aussortierten Fragen als Datei („Sicherung herunterladen“ / „Sicherung laden“), z. B. für Browser, die Websitedaten beim Beenden löschen, oder zum Wechsel auf ein anderes Gerät
- Nach jeder Runde lässt sich die nächste Runde neu einrichten (Anzahl Fragen, Themenbereiche) oder mit gleichen Einstellungen wiederholen
- Tastaturbedienung: `1`–`4` bzw. `A`–`D` antworten, `Enter` weiter, `X` aussortieren

## Aufbau
- `index.html` – die App (reines HTML/CSS/JavaScript, ohne Build-Schritt)
- `questions.js` – Fragenkatalog
- `img/` – Bilder zu den Bildfragen

Lokal starten: `index.html` im Browser öffnen.
