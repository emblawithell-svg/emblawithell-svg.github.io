# ✨ Garderoben — Digital Klädkammare

En fancy digital garderob för dig! Öppna `index.html` direkt i webbläsaren eller använd Live Server i VS Code.

## 🚀 Kom igång

### Alternativ 1 — Live Server (Rekommenderat)
1. Installera tillägget **"Live Server"** i VS Code
2. Högerklicka på `index.html` → **"Open with Live Server"**
3. Sidan öppnas automatiskt i webbläsaren

### Alternativ 2 — Direkt i webbläsare
1. Dubbelklicka på `index.html`
2. Klart!

---

## 🎀 Funktioner

| Funktion | Beskrivning |
|---|---|
| 👗 **Kläder** | Ladda upp bilder, sortera per kategori, markera favoriter och senast använda |
| 🪄 **Ta bort bakgrund** | Välj bakgrundsfärg + toleransnivå — perfekta cutouts direkt i appen |
| 📅 **Kalender** | Planera outfits dag för dag med miniatyrbilder |
| 🎲 **Shuffle** | Slumpa en hel outfit + spara direkt i kalendern |
| 🎨 **Moodboard** | Dra och släpp plagg, byt bakgrundsfärg, ladda ner |
| 🧳 **Packlista** | Skapa resor med datum, bocka av plagg när du packar |

---

## 💾 Lagring
All data sparas automatiskt i **localStorage** i din webbläsare.  
Max ca 5 MB — bilder komprimeras automatiskt.

### Ladda ner Moodboard som bild
Lägg till html2canvas i projektet för att aktivera nedladdning:

```html
<!-- Lägg till i <head> i index.html -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
```

---

## 📁 Struktur
```
garderob/
└── index.html    ← hela appen (en enda fil, inga beroenden)
```

---

## 🎨 Färgpalett
- Blush / Rosa — `#F0A8C0`
- Lavendel — `#E2D4F8`
- Mint — `#C8F0DC`
- Guld — `#E8C870`
- Kräm — `#FFF8F4`
