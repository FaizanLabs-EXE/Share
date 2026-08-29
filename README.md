# ⚡ Faizan SwiftShare

GitHub-only static Android ↔ Windows sharing UI.

### Included
- P2P WebRTC file transfer
- Multi-file and folder selection
- Text / code / scripts
- URLs
- Clipboard
- Live activity, speed and totals
- Responsive premium UI
- Android/Windows detection
- Optional local ADB bridge

### GitHub Pages
Upload `index.html`, `style.css`, `app.js`, and `adb-bridge.ps1` to a repository and enable GitHub Pages.

### Important architecture limitation
A static GitHub Pages site cannot run ADB or discover arbitrary LAN devices by itself, and WebRTC needs signaling. This build uses a serverless manual offer/answer exchange so the actual file data remains peer-to-peer. For automatic nearby-device discovery, a signaling/native companion is required.

### ADB
Install Android Platform Tools and run on Windows:
`powershell -ExecutionPolicy Bypass -File .\adb-bridge.ps1`

Signature:
━━━ 𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐁𝐲 • 𝐅𝐚𝐢𝐳𝐚𝐧 𝐋𝐚𝐛𝐬 ━━━
