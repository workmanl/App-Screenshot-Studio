# App Screenshot Studio

A browser-based tool for creating polished **App Store / Play Store marketing screenshots** from raw screenshots — with device frames, backgrounds, typography, badges, overlays, and quick exports.

**Live demo (GitHub Pages):** https://workmanl.github.io/App-Screenshot-Studio/  
**Repo:** https://github.com/workmanl/App-Screenshot-Studio

---

## What it does

App Screenshot Studio helps you turn plain screenshots into store-ready compositions:

- Device frames (optional) + frame color/styles
- Headline + subheadline typography controls
- Backgrounds (gradients / mesh / image / patterns)
- Layout controls (scale / position / rotation / shadow / reflection)
- Badges, logo overlays, callout arrows, QR codes, watermark text
- Single + Batch workflows
- Export PNG/JPG/ZIP and multiple target sizes

---

## Features

### Platform & device presets
- Platform selector: **iOS / Android / Mac / Watch**
- Common store/export sizes, including:
  - iPhone: **6.9" (1320×2868)**, **6.7"**, **6.5"**, **5.5"**
  - iPad: **13" (2064×2752)**, **12.9"**, **11"**
- **Landscape mode** toggle

### Input modes
- Upload or drag & drop screenshots
- **Batch mode**: apply the same design/text settings to multiple images
- Optional second device layout (two devices on one screenshot)

### Typography
- Headline + subheadline
- Font family + weight controls (includes System/SF Pro option)
- Auto text color option
- Size + letter spacing
- Effects: **Normal / Neon / Sticker / Wave / Glitch**
- Stroke/outline + custom shadow
- Optional “pill” background behind text (color/opacity/padding/radius)

### Backgrounds
- Gradient (with angle)
- Mesh (multi-point gradient + complexity)
- Background image upload + fit modes (Cover / Contain / Stretch / Tile)
- Pattern overlays (type / opacity / scale)
- Blur + vignette controls

### Frames & layout
- Toggle device frame on/off
- Realistic frame style + frame colors (White/Black/Gold/Silver/Custom)
- Drop shadow + reflection effect
- 3D rotation (tilt/turn) controls
- Device scale, vertical position, corner radius
- Screenshot zoom, X/Y offset, and padding

### Overlays & callouts
- Badge/label with corner placement + badge colors
- Optional star rating display
- Logo/icon overlay (position grid, size, offsets, shadow)
- Callout arrows: draw arrows on the preview (click & drag), adjust color/size, clear all
- QR code generator (position + size)
- Watermark text (alignment + opacity)

### Templates, projects, export
- Templates: Minimal Dark, Vibrant, Clean Light, Neon, Nature, Sunset
- Save / Load project
- Undo / Redo shortcuts (⌘Z / ⌘Y)
- Custom font upload (.ttf/.woff/.woff2)
- Color picker from screenshot
- Export: **PNG**, **JPG**, **ZIP**
- Export current size or export multiple sizes

---

## Getting started

### Option A: Use the hosted version
Open the live demo:  
https://workmanl.github.io/App-Screenshot-Studio/

### Option B: Run locally
This is a static, single-page app.

```bash
git clone https://github.com/workmanl/App-Screenshot-Studio.git
cd App-Screenshot-Studio
python3 -m http.server 8000
```

Then visit:  
http://localhost:8000

---

## Quick workflow

1. Choose a **platform** and **device size** (toggle Landscape if needed).
2. Upload a screenshot (or switch to **Batch** and select multiple).
3. Add **Headline/Subheadline** and tune typography.
4. Pick a **Background** (gradient/mesh/image/pattern) and adjust blur/vignette.
5. Toggle **Device Frame** and dial in layout (scale/position/rotation/shadow/reflection).
6. Optionally add badges, logo, arrows, QR, watermark.
7. **Export** PNG/JPG/ZIP (and optionally multiple target sizes).

---

## Project structure

- `index.html` — the entire app (UI + styling + logic)

---

## Contributing

Issues and PRs are welcome. Please keep changes lightweight and offline-friendly where possible.

---

## License

`MIT LICENSE`
