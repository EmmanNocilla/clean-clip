# CleanClip — Smart Clipboard Cleaner for Windows

[![Downloads](https://img.shields.io/github/downloads/EmmanNocilla/clean-clip/total?color=3b82f6&style=for-the-badge)](https://github.com/EmmanNocilla/clean-clip/releases)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![.NET 8](https://img.shields.io/badge/.NET-8.0-5c2d91?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Itch.io](https://img.shields.io/badge/itch.io-CleanClip-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white)](https://noemio.itch.io/clean-clip)
[![Product Hunt](https://img.shields.io/badge/Product%20Hunt-Live%20Now-DA552F?style=for-the-badge&logo=producthunt&logoColor=white)](https://www.producthunt.com/products/cleanclip-2?launch=cleanclip-2)
[![Ko-fi](https://img.shields.io/badge/Support%20on-Ko%E2%80%93fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/emmnkofi)


CleanClip keeps your clipboard tidy and consistent automatically.  
It removes junk formatting, line breaks, tracking links, and more — instantly when you copy.

---

## ✨ What's New in v1.2
This release adds new power features, better merge logic, and a safer workflow.

### 🧠 Smarter Merge
- New **bullet list mode** — every line properly bulleted  
- Fixed duplicate-entry bug  
- Optional dedupe toggle in Settings  

### ⚙️ App Blacklist
- Add apps CleanClip should ignore (e.g. password managers, IDEs)  
- Works by foreground process name  

### 🕓 Clipboard History
- View your last 25 cleaned clips (in-memory only)  
- Double-click to restore any previous item  

### 🧹 Pipeline Polish
- Better whitespace normalization and line endings  
- Improved URL cleaner (keeps anchors, removes utm/fbclid/ref)  
- Optional “Remove emojis/non-ASCII” rule  
- Minimum-length protection — skips very short clips  

### ⏸ Pause Auto-Clean
- Temporarily disable auto-cleaning from the tray  
- Manual “Clean Now” still available  

### 🎨 UX & Tray
- Tooltips preview current clipboard text  
- Cleaner Settings UI with rule toggles & blacklist section  
- Stability improvements (no more event loops)

---

## 💡 Core Features
- Auto-cleans clipboard instantly on copy  
- Removes web/Word formatting  
- Strips tracking from URLs  
- Merge multiple clips (newline / blank line / bullet)  
- Local-only & private — no telemetry or cloud  
- Configurable cleaning rules  

---

## 💾 Download
👉 [Latest release on GitHub](https://github.com/yourname/clean-clip/releases)

Runs on Windows 10 or 11.  
No installer needed — portable EXE (requires .NET 8 runtime, bundled).

---

## 💙 Support
If CleanClip keeps your workflow neat:  
☕ [Support on Ko-fi](https://ko-fi.com/emmnkofi)

---

## 🧭 Roadmap
**v1.3 (Pro planned)**  
- Custom regex rules  
- Per-app profiles  
- Persistent clipboard history  
- Markdown / Smart Paste  
- Auto-update installer  

---

## 📜 License
MIT © 2025 Emman Nocilla
