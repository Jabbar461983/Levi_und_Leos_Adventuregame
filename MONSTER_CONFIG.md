# Monster Sprite Sheet Konfiguration

## 🎬 Aktuelle Konfiguration

```javascript
const SPRITE_CONFIG = {
    wald:    { frameCount: 4,  direction: 'horizontal', speed: 8 },
    wasser:  { frameCount: 4,  direction: 'horizontal', speed: 8 },
    feuer:   { frameCount: 36, direction: 'grid',       speed: 8 }, // 6x6 Grid!
    gift:    { frameCount: 4,  direction: 'horizontal', speed: 8 },
    blitz:   { frameCount: 4,  direction: 'horizontal', speed: 8 },
    gebirge: { frameCount: 4,  direction: 'horizontal', speed: 8 },
    leere:   { frameCount: 4,  direction: 'horizontal', speed: 8 }
};
```

## 🚀 So aktualisierst du die Konfiguration:

### Wenn dein Monster-Sprite eine andere Anzahl Frames hat:

**Beispiel 1: Wasser Monster mit 8 Frames (horizontal)**
```javascript
wasser: { frameCount: 8, direction: 'horizontal', speed: 8 }
```

**Beispiel 2: Gift Monster mit 3x3 Grid (9 Frames)**
```javascript
gift: { frameCount: 9, direction: 'grid', speed: 8 }
```

**Beispiel 3: Blitz Monster mit 6 Frames (vertikal)**
```javascript
blitz: { frameCount: 6, direction: 'vertical', speed: 8 }
```

## 📋 Parameter erklären:

| Parameter | Wert | Bedeutung |
|-----------|------|-----------|
| `frameCount` | Zahl | Gesamtzahl der Animations-Frames |
| `direction` | 'horizontal' \| 'vertical' \| 'grid' | Layout-Format |
| `speed` | 1-15 | Animation-Geschwindigkeit (8=normal, höher=langsamer) |

## 🎯 Animation-Geschwindigkeit:

- `speed: 4` = Sehr schnell
- `speed: 8` = Normal (Standard)
- `speed: 12` = Langsam
- `speed: 15` = Sehr langsam

## 📝 Deine Monster-Dateien:

Gib mir für **jedes Monster**:

1. **Name**: (wald, wasser, feuer, etc.)
2. **Dateiname**: 
3. **Frame-Layout**: (horizontal / vertikal / grid)
4. **Anzahl Frames**: 
5. **Gesamtgröße**: (z.B. 400x100)
6. **Gewünschte Geschwindigkeit**: (schnell/normal/langsam)

### Beispiel:

```
Feuer Monster:
- Dateiname: feuer.png
- Größe: 600x600 Pixel
- Layout: 6x6 Grid (36 Frames)
- Geschwindigkeit: Normal (8)
- Status: ✅ Konfiguriert!
```

## ✅ Checkliste - Welche Monster hast du noch?

- [ ] Wald Monster - Format?
- [ ] Wasser Monster - Format?
- [ ] Feuer Monster - ✅ 6x6 Grid, 36 Frames
- [ ] Gift Monster - Format?
- [ ] Blitz Monster - Format?
- [ ] Gebirge Monster - Format?
- [ ] Leere Monster - Format?

## 🔧 Wenn du den Code verändern möchtest:

Öffne `index.html` und suche nach:
```javascript
const SPRITE_CONFIG = {
```

Ersetze die Werte für deine Monster und speichere!

---

**Bereit?** Sag mir die Details für deine anderen Monster! 🎮
