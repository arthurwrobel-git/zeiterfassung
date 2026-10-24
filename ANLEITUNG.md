# Zeiterfassung – Installation auf dem iPhone

Die App besteht nur aus den Dateien im Ordner `zeiterfassung/`. Sie braucht keinen Server mit Datenbank: Alle Daten bleiben auf deinem iPhone. Sie muss nur einmal über **https** erreichbar sein, damit Safari sie installieren kann. Am einfachsten und kostenlos geht das mit **GitHub Pages**.

## 1. Auf GitHub Pages hochladen (einmalig, ca. 10 Minuten)

1. Auf https://github.com ein kostenloses Konto anlegen (falls noch nicht vorhanden).
2. Oben rechts **+ → New repository**. Name z. B. `zeiterfassung`, Sichtbarkeit **Public**, „Create repository“.
3. Auf der leeren Repo-Seite **„uploading an existing file“** wählen und den **Inhalt** des Ordners `zeiterfassung/` hineinziehen (also `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` und den Ordner `icons`). „Commit changes“.
4. **Settings → Pages**: Bei „Source“ *Deploy from a branch*, Branch **main**, Ordner **/ (root)**, „Save“.
5. Nach 1–2 Minuten steht dort die Adresse, z. B. `https://DEINNAME.github.io/zeiterfassung/`.

Hinweis: Bei einem öffentlichen Repository ist der *Programmcode* öffentlich sichtbar, **nicht** deine Arbeitszeiten. Die liegen nur im Speicher deines iPhones.

## 2. Auf den Home-Bildschirm legen

1. Die Adresse auf dem iPhone in **Safari** öffnen.
2. Unten auf **Teilen** (Quadrat mit Pfeil) → **Zum Home-Bildschirm** → „Hinzufügen“.
3. Ab jetzt die App **immer über das Icon „Arbeitszeit“** starten. Sie läuft im Vollbild und auch offline.

Wichtig: Die installierte App hat ihren eigenen Speicher, getrennt von Safari. Trag deine Zeiten deshalb nur in der App vom Home-Bildschirm ein.

## 3. Erste Schritte in der App

- **Einstellungen**: „Erfassung ab“ auf deinen Starttag setzen und deinen aktuellen **Gleitzeit-Übertrag** eintragen (z. B. `+12:30` oder `-3:15`).
- **Spesen-Stufen prüfen**: Voreingestellt sind ab 6 Std. 12,00 € und ab 8 Std. 15,50 €. Die 10-Stunden-Stufe steht auf 0 € (= aus). Bitte mit deiner Firmenregelung abgleichen.
- **Feiertagssatz**: Voreingestellt 28 €/Std. wie Sonntag. Bei Bedarf anpassen.
- Arbeitsorte und Tätigkeiten (Rubriken) kannst du unten in den Einstellungen umbenennen, ergänzen oder entfernen.

## 4. Monatsbericht

Reiter **Monat → „Monatsbericht senden“** öffnet das iOS-Teilen-Menü. Dort **Mail** wählen: PDF und CSV hängen schon an. Am letzten Tag des Monats und in der ersten Woche danach erinnert dich die App auf „Heute“ daran.

Tipp für eine echte Erinnerung: In der iOS-App **Kurzbefehle → Automation → Uhrzeit**, z. B. am Monatsletzten um 18:00 „App öffnen: Arbeitszeit“.

## 5. Backup

Einstellungen → **Backup sichern** speichert alle Daten als Datei (z. B. in iCloud Drive). Mit **Backup laden** holst du sie zurück, etwa nach einem iPhone-Wechsel. Am besten einmal im Monat zusammen mit dem Bericht.

## Updates

Neue Version = geänderte Dateien im GitHub-Repository ersetzen. Die App lädt das Update beim nächsten Start mit Internet. Deine Daten bleiben dabei erhalten.
