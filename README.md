# Lightable 📷

A fast, keyboard-driven photo triage tool that runs entirely in your browser.
Drop a session folder, hit ← to reject and → to keep, export the keepers.
No server, no install — a single HTML file.

## Features
- Opens a folder via the File System Access API (Chrome/Edge)
- EXIF thumbnail extraction for near-instant previews (no full 26 Mpx decode)
- RAW+JPEG pair detection and linked keep/reject decisions
- Burst detection by EXIF timestamp with configurable threshold
- Filmstrip sidebar with lazy-loaded thumbnails
- Session persistence via localStorage (resume where you left off)
- Export: copies kept files (RAW + JPEG) to a destination folder

## Keyboard shortcuts
| Key | Action |
|-----|--------|
| → | Keep & advance |
| ← | Reject & advance |
| ↑ / ↓ | Navigate without deciding |

## Usage
1. Open `lightable.html` in Chrome or Edge
2. Click **Ouvrir un dossier** and pick your session folder
3. Triage with keyboard or buttons
4. Click **Exporter les gardées** to copy keepers

## Browser support
Requires the [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_Access_API) — Chrome 86+ or Edge 86+. Firefox not supported.

## License
MIT
