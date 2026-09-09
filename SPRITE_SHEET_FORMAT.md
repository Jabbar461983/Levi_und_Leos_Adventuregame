# Sprite Sheet Format

## 📐 Sprite Sheet Struktur

### Für Enemies (Monster):

Dein Monster-Sprite Sheet kann **mehrere Frames nebeneinander** haben:

```
[Frame 1] [Frame 2] [Frame 3] [Frame 4]
100x100   100x100   100x100   100x100

Total: 400x100 Pixel (für 4 Frames)
oder: 300x100 (für 3 Frames)
```

### Format Optionen:

**Option A: Horizontal (empfohlen)**
```
wald.png: 100x100 (1 Frame)
wald-animation.png: 400x100 (4 Frames nebeneinander)
```

**Option B: Vertikal**
```
wald.png: 100x400 (4 Frames übereinander)
```

**Option C: Grid (2x2, 3x3, etc.)**
```
wald.png: 200x200 (2x2 Frames = 4 Frames total)
```

## 🎬 Wie wir die Sprites verwenden:

Der Code erkennt automatisch mehrere Frames und animiert sie.

### Beispiele für deine Dateien:

```
assets/sprites/enemies/
├── wald.png (100x100) - statisch ODER
├── wald.png (400x100) - 4 Frames animation
├── wasser.png (300x100) - 3 Frames
├── feuer.png (200x200) - 2x2 Frames
└── ...
```

## 📋 Was du hochladen sollst:

Gib mir folgende Informationen für **jede Datei**:

1. **Dateiname**: z.B. `wald.png`
2. **Größe**: z.B. 400x100 Pixel
3. **Frames**: z.B. 4 Frames nebeneinander
4. **Richtung**: Horizontal / Vertikal / Grid

**Beispiel:**
```
wald.png: 400x100 (4 Frames horizontal)
wasser.png: 100x400 (4 Frames vertikal)
feuer.png: 300x100 (3 Frames horizontal)
```

## 🚀 Upload Anleitung:

1. **Bereite deine PNG-Dateien vor**
2. **Schreib mir die genauen Dimensionen**
   - z.B.: "wald.png ist 400x100 mit 4 Frames horizontal"
3. **Ich passe den Code an** für deine Formate
4. **Hochladen in `assets/sprites/enemies/`**

## ✨ Was möglich ist:

- ✅ Automatische Animation
- ✅ Loop oder Stop nach X Frames
- ✅ Verschiedene Animationsgeschwindigkeiten
- ✅ Verschiedene Frames pro Monster-Typ
- ✅ Fallback auf statische Grafik

## 📝 Deine Dateien:

Schreib mir:
- **Link Skins**: Statisch (100x100) oder animiert?
- **Wald Monster**: Format? (z.B. "400x100, 4 Frames")
- **Wasser Monster**: Format?
- **Feuer Monster**: Format?
- (usw.)

Dann passe ich alles automatisch an! 🎮
