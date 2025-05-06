# ⌨️ OneKey — Launch Anything with a Single Keystroke

**Tired of digging through menus?** Transform any key into instant shortcuts for apps, files, folders, and websites!  

## ✨ Features
- **Blazing fast** — Launch anything in <100ms
- **Zero config** — Simple JSON setup
- **Portable** — Single 2MB executable
- **Privacy focused** — No telemetry, no ads

## 🚀 Quick Start
1. Download the latest [release](https://github.com/EvilPolishman/OneKey/releases)
2. Run `OneKeySystem.exe` (Windows)
3. Press `F12` to activate
4. Hit your shortcuts!

## ⚙️ Configure
Edit `Service/Variables.json`:
```json
{
  "a": "C:\\Program Files\\App\\app.exe",
  "b": "D:\\Projects\\",
  "c": "https://google.com"
}
```

## 🎯 Default Controls
| Key  | Action                |
|------|-----------------------|
| F12  | Enable/disable VKS    |
| F9   | Add new shortcut      |
| F10  | List all shortcuts    |
| F11  | Reset settings        |

## 🤔 Why OneKey?
|                          | OneKey | AutoHotkey | PowerToys |
|--------------------------|--------|------------|-----------|
| Single-file executable   | ✅     | ❌         | ❌        |
| No scripting required    | ✅     | ❌         | ✅        |
| Open websites            | ✅     | ✅         | ❌        |

## 📦 Dependencies
- Python 3.10+
- [keyboard](https://pypi.org/project/keyboard/) module

## 🛠 Build from Source
```bash
pip install pyinstaller keyboard
pyinstaller --onefile --hidden-import=keyboard OneKeySystem.py
```

## 🌟 Support
- ⭐ **Star this repo** if you find it useful!
- 🐞 Found a bug? [Open an issue](https://github.com/EvilPolishman/OneKey/issues)
- 💡 Want a feature? Let me know!

---

🔹 *"Work smarter, not harder"* — Your productivity boost starts with **OneKey**!
