# S4 Matrizen‑Rechner – Komplettes Repo (Canvas-Version, unverändert)

Dieses ZIP ist **sofort nutzbar**:
- `index.html` → **Canvas-Version 1:1 unverändert** (App läuft sofort).
- `manifest.json` + `assets/icons/*` sind enthalten.
- **Optional**: `index.icons.html` = gleiche App, aber mit verknüpften Icon-/Manifest-Tags im `<head>`.
  - Wenn du Icons ohne jede Änderung aktiv haben willst, **benenne `index.icons.html` in `index.html` um**.

## Struktur
- `index.html`
- `index.icons.html` (optional, vorverkabelte Icon-Variante)
- `manifest.json`
- `assets/icons/`
  - `favicon.svg`
  - `app-icon.png` (512×512 Placeholder)
  - `icon-192.png` (192×192 Placeholder)
  - `apple-touch-icon.png`

## GitHub Pages
Pushen → `Settings > Pages` auf `Deploy from branch / main / root` → App unter `https://<user>.github.io/matrizenrechner/`.

## Hinweis zu Icons
Die Canvas-Version ändert **keinen** Code. Für aktive Icons nutze `index.icons.html` (oder kopiere die 3 Link-Zeilen + `theme-color` in deinen `<head>`).
