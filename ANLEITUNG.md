# TrainingsApp als App aufs Handy

## 1. Einmalig online stellen (GitHub Pages, kostenlos)

1. Auf github.com ein Konto anlegen.
2. Oben rechts **+ → New repository**. Name z. B. `training`, Sichtbarkeit **Public**, **Create repository**.
3. Auf der leeren Repository-Seite **uploading an existing file** anklicken.
4. Den Inhalt dieses Ordners hineinziehen: `index.html`, `manifest.webmanifest`, `sw.js` und den Ordner `icons`. Unten **Commit changes**.
5. **Settings → Pages**: bei *Source* „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, **Save**.
6. Nach 1–2 Minuten ist die App erreichbar unter `https://DEINNAME.github.io/training/`.

Die Schrift kommt aus deinem Adobe-Fonts-Paket „TrainingsApp“. Es ist für `*.github.io` freigegeben. Nutzt du einen anderen Hoster, trägst du dessen Domain unter fonts.adobe.com → Web-Projekte nach.

## 2. Installieren

**Android (Chrome):** Adresse öffnen → Drei-Punkte-Menü → **App installieren** bzw. **Zum Startbildschirm hinzufügen**.

**iPhone (Safari, nicht Chrome):** Adresse öffnen → Teilen-Symbol → **Zum Home-Bildschirm** → Hinzufügen.

Jedes Handy hat seine eigenen Daten. Ihr stört euch gegenseitig nicht.

## 3. Daten sichern

Die Daten liegen nur auf dem Handy. Unter **Plan speichern → Sicherung** regelmäßig **Alle Daten als Datei sichern** (z. B. in Google Drive oder iCloud ablegen). Mit **Sicherung laden** holst du sie auf ein neues Handy. Die App erinnert dich, wenn die letzte Sicherung älter als 14 Tage ist.

## 4. Updates

Neue Version von `index.html` auf GitHub hochladen und in `sw.js` die Zeile `VERSION = "trainingsapp-v1"` hochzählen (v2, v3 …). Die App lädt das Update beim übernächsten Öffnen.
