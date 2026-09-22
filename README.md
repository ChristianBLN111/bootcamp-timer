# Bootcamp Timer

Intervall-Timer für BOOTcamp BERLIN – installierbar als App (PWA), funktioniert offline.

## Auf GitHub online stellen (einmalig, ca. 5 Minuten)

1. Auf github.com einloggen → oben rechts **+** → **New repository**.
2. Name: `bootcamp-timer`, auf **Public** stellen → **Create repository**.
3. Auf der leeren Repo-Seite: **uploading an existing file** anklicken.
4. Den **Inhalt** des entpackten Ordners hineinziehen (index.html, manifest.webmanifest, sw.js, README.md und den Ordner `icons`) → **Commit changes**.
5. Im Repo: **Settings** → links **Pages** → bei *Branch* `main` und `/ (root)` wählen → **Save**.
6. Nach 1–2 Minuten ist die App erreichbar unter:
   `https://DEIN-GITHUB-NAME.github.io/bootcamp-timer/`

## Auf dem Handy installieren

- **Android (Chrome):** Link öffnen → oben rechts auf *Installieren* tippen (oder Menü ⋮ → *App installieren*).
- **iPhone (Safari):** Link öffnen → *Teilen* → *Zum Home-Bildschirm*. Wichtig: Stummschalter am iPhone aus, sonst bleiben die Töne stumm.

## Eigene Sounds

Unter *Töne → Eigene Sounds* MP3/WAV/M4A hochladen (bis 5 MB). Die Dateien werden auf dem jeweiligen Handy gespeichert und stehen danach in jeder Ton-Auswahl zur Verfügung. Jedes Gerät hat seine eigenen Sounds.

## Updates einspielen

Geänderte Dateien wieder hochladen und in `sw.js` die Zeile `const VERSION = 'bct-v1';` hochzählen (`bct-v2`, …). Dann holen sich die installierten Apps die neue Version beim nächsten Öffnen.

## Icon tauschen

Im Ordner `icons` diese Dateien ersetzen (gleiche Namen, PNG, quadratisch):
`icon-192.png` (192×192), `icon-512.png` (512×512), `icon-maskable-512.png` (512×512, Logo mit Rand), `apple-touch-icon.png` (180×180).

## Hinweis

Wenn der Bildschirm gesperrt wird, pausiert das Handy die App – beim Entsperren springt der Timer auf die richtige Zeit. Deshalb ist „Bildschirm bleibt an“ standardmäßig aktiv.
