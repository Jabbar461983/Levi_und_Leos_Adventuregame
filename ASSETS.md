# Game Assets Struktur

## 📂 Ordnerstruktur

```
assets/
└── sprites/
    ├── link/
    │   ├── classic.png (100x100)
    │   ├── red.png (100x100)
    │   ├── blue.png (100x100)
    │   ├── dark.png (100x100)
    │   ├── gold.png (100x100)
    │   └── crystal.png (100x100)
    └── enemies/
        ├── wald.png (100x100)
        ├── wasser.png (100x100)
        ├── feuer.png (100x100)
        ├── gift.png (100x100)
        ├── blitz.png (100x100)
        ├── gebirge.png (100x100)
        └── leere.png (100x100)
```

## 📋 Dateiformat

- **Format**: PNG oder GIF (mit Transparenz empfohlen)
- **Größe**: **100x100 Pixel** pro Sprite
- **Hintergrund**: Transparent (PNG) oder einfarbig
- **Qualität**: Mindestens 100x100 für beste Darstellung

## 🎮 Wo man Bilder hochlädt

1. **Für Link-Skins** → `assets/sprites/link/`
   - `classic.png` - Grüner Link (Standard)
   - `red.png` - Roter Link
   - `blue.png` - Blauer Link
   - `dark.png` - Schwarzer Link
   - `gold.png` - Gold Link
   - `crystal.png` - Kristall Link

2. **Für Monster/Enemies** → `assets/sprites/enemies/`
   - `wald.png` - Waldfeind (Level 1-4)
   - `wasser.png` - Wasserfeind (Level 6-9)
   - `feuer.png` - Feuerfeind (Level 11-14)
   - `gift.png` - Giftfeind (Level 16-19)
   - `blitz.png` - Blitzfeind (Level 21-24)
   - `gebirge.png` - Gebirgsfeind (Level 26-29)
   - `leere.png` - Leerfeind (Level 31-35)

## 🚀 Wie man Bilder hochlädt

1. Erstelle die PNG-Dateien (100x100 Pixel)
2. Lade sie in den richtigen Ordner hoch:
   ```bash
   git add assets/sprites/
   git commit -m "Add sprite assets"
   git push origin claude/zelda-adventure-game-b8j67j
   ```

## 💡 Tipps

- Verwende PNG für beste Kompatibilität
- Mache den Hintergrund transparent (Alpha-Kanal)
- Zentrier die Figur im 100x100-Bild
- Alle Sprites sollten ähnliche Größe haben (ca. 70-90x70-90 im 100x100 Frame)

## 📝 Status

- [ ] Link Classic-Skin hochgeladen
- [ ] Link Red-Skin hochgeladen
- [ ] Link Blue-Skin hochgeladen
- [ ] Link Dark-Skin hochgeladen
- [ ] Link Gold-Skin hochgeladen
- [ ] Link Crystal-Skin hochgeladen
- [ ] Waldfeind-Sprite hochgeladen
- [ ] Wasserfeind-Sprite hochgeladen
- [ ] Feuerfeind-Sprite hochgeladen
- [ ] Giftfeind-Sprite hochgeladen
- [ ] Blitzfeind-Sprite hochgeladen
- [ ] Gebirgsfeind-Sprite hochgeladen
- [ ] Leerfeind-Sprite hochgeladen
