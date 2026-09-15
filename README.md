# Camper Chris – Website

Statische Seite, kein Build, kein Framework. Zwei HTML-Dateien und ein Bilderordner.

```
index.html
rechtliches.html
bilder/foto-1.jpg … foto-7.jpg
```

## Bilder

Die sieben Fotos aus dem MyCamper-Inserat 10666 herunterladen und als `foto-1.jpg`
bis `foto-7.jpg` im Ordner `bilder/` ablegen. `foto-1` ist das Hero-Bild (Querformat).

| Datei | Quelle |
|---|---|
| foto-1.jpg | https://storage.mycamper.com/assets/10666/hyIHg6YQlq53iXZewap5likOH9G4aAIN8gRPimCI-large.jpg |
| foto-2.jpg | https://storage.mycamper.com/assets/10666/2HMqqYFRqRFD78i9vMd7WSQvYoQj6k6OqoF6Pj8L-medium.png |
| foto-3.jpg | https://storage.mycamper.com/assets/10666/Z0QBhkS6ifT6Lzhzt56MDsmevAYYE58fhAUZKzbT-medium.png |
| foto-4.jpg | https://storage.mycamper.com/assets/10666/K9WCWsoRm4NARq7KFjvgtX5336B5bOwU81BwonqC-medium.jpg |
| foto-5.jpg | https://storage.mycamper.com/assets/10666/cFNnLUa4HgHh9G1dap2v2aipNVDhNEK7gkQA1upf-medium.png |
| foto-6.jpg | https://storage.mycamper.com/assets/10666/ZpVDYz7s9poHCjGU6END0o4pwgPvPV6uHNzpb6JX-medium.jpg |
| foto-7.jpg | https://storage.mycamper.com/assets/10666/km64GM73yGtMfMK3rJaX1oDQ4Tp1fj4ZYeUWvG2Q-medium.png |

Dateiendung nicht umbenennen, sondern im `index.html` anpassen, falls eine Datei als
`.png` gespeichert wird. Reihenfolge und Bildunterschriften (`alt`-Texte) danach
kontrollieren und korrigieren – sie sind aktuell geraten.

Vor dem Hochladen verkleinern: maximal 1600 px Breite, JPEG-Qualität 80,
Ziel unter 300 KB pro Bild (z.B. mit squoosh.app).

## Vor dem Livegang ersetzen

- `DEINE@EMAIL.CH` (steht in `index.html` zweimal und in `rechtliches.html`)
- `+41790000000` und `079 000 00 00` in `index.html`
- `Christian [Nachname]` in beiden Dateien
- `https://DEINE-DOMAIN.ch/` in den Meta-Tags von `index.html`
- alle `[eckigen Klammern]` in `rechtliches.html`

## Live stellen

GitHub Pages: Repository anlegen, Dateien hochladen, unter
Settings → Pages → Branch `main` / `root` veröffentlichen.
