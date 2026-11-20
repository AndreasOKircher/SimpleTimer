# SimpleTimer

Ein einfacher Intervalltimer fürs iPhone, als Web-App. Eine einzige Datei (`index.html`), kein Framework, keine Anmeldung, keine Werbung.

Entstanden als Ersatz für **TimerPlus**: Die App hat mich jahrelang begleitet und wurde dann plötzlich kostenpflichtig. Jetzt gibt es eine eigene Lösung.

**App:** https://andreasokircher.github.io/SimpleTimer/

## Was sie kann

- Nach „Start“ läuft zuerst ein **10-Sekunden-Countdown**, dann die Intervalle.
- Einstellbar: **Anzahl der Intervalle**, **Belastung** und **Pause**. Die Werte bleiben gespeichert.
  Standard: 20 × (60 s Belastung + 10 s Pause) = 23:20. Die letzte Pause zählt mit.
- Große Anzeige: Restzeit, „Belastung“ oder „Pause“, „Runde X von Y“ und Gesamt-Restzeit.
- **Töne:** kurzer Ton bei jedem Phasenwechsel (hoch = Belastung, tief = Pause), Ticks beim Countdown (3, 2, 1) und in den letzten 5 Sekunden jeder Belastung, eine Fanfare am Ende.
- Start, Anhalten, Fortsetzen, Zurücksetzen. Große Tasten für Hochformat.
- Die Restzeit wird aus dem Startzeitpunkt berechnet, nicht aus einem Sekundenzähler. Verzögerungen summieren sich daher nicht.

## Aufs iPhone installieren

1. **https://andreasokircher.github.io/SimpleTimer/** in **Safari** öffnen (nicht in einer anderen App).
2. Teilen-Symbol (Quadrat mit Pfeil) antippen.
3. **„Zum Home-Bildschirm“** wählen und **„Hinzufügen“** tippen.
4. Die App startet danach per Icon im Vollbild.

## Hinweise

- **Stumm-Schalter auf laut stellen**, sonst bleiben Töne oft aus. Der erste Ton kommt erst nach dem Tippen auf „Start“ (iOS erlaubt vorher keinen Ton).
- **Bildschirm anlassen.** Die App hält ihn selbst wach. Sperrst du das Display, pausiert iOS die Seite und es kommen keine Töne. Die Zeit stimmt beim Zurückkommen trotzdem.
- Zum ersten Laden ist Internet nötig. Offline-Betrieb ist nicht eingebaut.
- Neue Version nicht sichtbar? App ganz schließen und neu öffnen, notfalls die Seite einmal in Safari neu laden.

## Selbst hosten

Die Datei `index.html` auf einen beliebigen Webserver legen oder per GitHub Pages veröffentlichen (Branch `main`, Ordner `/`). Es gibt nichts zu bauen.
