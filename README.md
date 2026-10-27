# Ali Rasheed Gaming Hub

Persönliche Gaming-Webseite. Reines HTML, CSS und JavaScript, kein Build-Schritt nötig.

## Veröffentlichen mit GitHub Pages

1. Auf github.com anmelden und oben rechts auf **+** → **New repository** klicken.
2. Namen vergeben, zum Beispiel `gaming-seite`. Sichtbarkeit **Public** wählen (bei kostenlosen Konten nötig für Pages). **Create repository** klicken.
3. Im neuen Repository auf **uploading an existing file** klicken und diese Dateien hochladen: `index.html`, `.nojekyll`, `README.md`. Mit **Commit changes** bestätigen.
4. **Settings** → **Pages** öffnen.
5. Unter **Build and deployment** bei **Source** die Option **Deploy from a branch** wählen, Branch **main** und Ordner **/ (root)** einstellen, dann **Save**.
6. Nach ein bis zwei Minuten steht oben auf der Pages-Einstellung der Link:
   `https://DEIN-BENUTZERNAME.github.io/gaming-seite/`

Tipp: Heißt das Repository `DEIN-BENUTZERNAME.github.io`, lautet der Link nur `https://DEIN-BENUTZERNAME.github.io/`.

## Mit Git auf dem Computer

```bash
git init
git add .
git commit -m "Erste Version der Gaming-Seite"
git branch -M main
git remote add origin https://github.com/DEIN-BENUTZERNAME/gaming-seite.git
git push -u origin main
```

Danach Schritt 4 bis 6 oben durchführen.

## Vor dem Veröffentlichen prüfen

- **Impressum:** In `index.html` steht unter „Angaben gemäß § 5 DDG“ nur „Hanau, Deutschland“. Für eine öffentliche Seite in Deutschland gehört dort deine vollständige Anschrift hin. Suche nach `Hanau, Deutschland` und ersetze die Stelle.
- **Datenschutz:** Der Text nennt Google Fonts und einen externen Hosting-Anbieter. Bei GitHub Pages ist das GitHub, Inc. Ergänze das bei Bedarf im Abschnitt „Hosting“.
- **Änderungen:** Neue Version hochladen oder per `git push` senden, GitHub Pages aktualisiert die Seite automatisch.
