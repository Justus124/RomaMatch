# Tour-Audio (Ovid)

- Stimme: de-DE-FlorianMultilingualNeural (männlich), rate -4 %, pitch -2 Hz
- Dienst: Microsoft Edge Read Aloud über das Python-Paket edge-tts 7.3.1 (boundary="WordBoundary")
- Format: MP3, 24 kHz mono

| Datei | Dauer (s) | Wort-Zeitstempel |
|---|---|---|
| tour-01.mp3 | 7.6 | 13 |
| tour-02.mp3 | 11.3 | 24 |
| tour-03.mp3 | 7.3 | 17 |
| tour-04.mp3 | 6.3 | 15 |
| tour-05.mp3 | 7.4 | 15 |
| tour-06.mp3 | 4.0 | 8 |
| tour-07.mp3 | 8.1 | 18 |
| tour-08.mp3 | 7.7 | 15 |
| tour-09.mp3 | 8.0 | 19 |
| tour-10.mp3 | 9.2 | 21 |
| tour-11.mp3 | 6.3 | 13 |
| tour-12.mp3 | 9.7 | 20 |
| tour-13.mp3 | 4.2 | 9 |
| tour-14.mp3 | 6.1 | 16 |
| tour-15.mp3 | 7.3 | 14 |

- `roma-match-vorstellung.mp3`: alle 15 Aufnahmen hintereinander mit je 0,8 s Stille, 48 kbit/s, ca. 121,8 s.
- `timings.json`: Wort-Zeitstempel pro Aufnahme im Format `{"01": [[start_s, end_s, "Wort"], ...], ...}` (Sekunden ab Dateibeginn, aus den WordBoundary-Ereignissen von edge-tts). Damit lassen sich die Untertitel wortgenau synchronisieren.
