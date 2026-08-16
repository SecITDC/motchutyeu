# Changelog — motchutyeu.com Birthday App

Project path: `e:\Coding Projects\Ngoc`

## 2026-08-16

### Entry point
- **Main file:** `index.html` (only entry point)
- Removed `v1 index.html` redirect stub

### Assets fixed
- Renamed `audio/risk-it-all.mp3.mp3` → `audio/risk-it-all.mp3`
- Gallery wired to local photos:
  - `pictures/mem1.PNG`
  - `pictures/mem2.png`
  - `pictures/mem3.png`
  - `pictures/mem4.png`
- Video placeholder: `video/message.mp4` (not added yet — modal shows friendly fallback)

### Map locations saved
Defined in `index.html` under `LOCATIONS`:

| Pin | Place | Coordinates | Label |
|-----|-------|-------------|-------|
| 🏮 Met | **Bắc Giang** | `21.280984, 106.214260` | "Bắc Giang — This is where everything started" |
| ❤️ Next adventure | **Sa Pa** | `22.3402, 103.8214` | "Sa Pa — Our next adventure" |

Map auto-zooms to fit both pins. Section subtitle: *"From Bắc Giang to Sa Pa — one story still being written."*

### iOS & CSS fixes (merged from fixed build)
- `100vh` + `100dvh` min-height on `html, body` for Safari dynamic URL bar
- Blush text tiers: `.text-blush-soft`, `.text-blush-subtle`, `.text-blush-faint` (replaces Tailwind opacity modifiers)
- Lantern color variants: pink and beige, weighted random mix in `spawnLanterns()`
- Touch-friendly `min-height: 44px` on interactive buttons

### Other behavior
- Unlock date: **August 19, 2026 at 00:00:00** (Hanoi / Vietnam time, UTC+7)
- Dev toggle: bottom-center "Dev Preview / Unlock Now" bypasses countdown for testing
