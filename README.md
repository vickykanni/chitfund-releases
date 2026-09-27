# Chit Fund Manager — Releases

> **This is the public distribution repository for Chit Fund Manager.**
> No source code is published here — only installer downloads and version releases.
> Source code is maintained separately as a private repository by Visom Technologies.

---

## 📥 Download & Install

1. Go to the [**Releases**](https://github.com/vickykanni/chitfund-releases/releases) page.
2. Download the latest `ChitFundManager_Setup_x.x.x.exe` installer.
3. Run the installer — **no administrator rights required**.
4. Launch the app from the **Start Menu** shortcut created during installation.

---

## 🎨 Application Features

- Chit group and member management
- Payment tracking and auction management
- Custom font selection and font size
- Multiple theme support
- Multi-language support (English, Tamil)
- Configurations stored in `AppData/config.json`
- Built-in auto-update — new versions install automatically

---

## 🔄 Automatic Updates

Once installed, the app checks for updates automatically every time it starts.

When a new version is available:

1. A small popup appears: **"A new version (x.x.x) is available. Update now?"**
2. Click **Yes** — a progress bar shows the download.
3. The installer runs silently in the background.
4. The app relaunches automatically on the new version.

> Your data (groups, members, payments) is **never touched** during an update.
> You can also check manually via **About → Check for Updates...** at any time.

---

## 🚀 First Launch

- On first launch, the app may ask for a **Serial Key**.
- Settings such as font, theme, and language are saved to `AppData\ChitFundManager\config.json`.

---

## 🗑 Uninstallation

Uninstall from **Control Panel → Programs and Features → Chit Fund Manager**.

The uninstaller will remove:
- The installed program directory
- The config file at `AppData\ChitFundManager\config.json`

> Your database files (groups, members, payment data) are stored separately and are **not deleted** by the uninstaller unless you choose to remove them manually.

---

## ⚠️ Troubleshooting

| Problem | Solution |
|---|---|
| Theme not applied | Ensure `.qss` theme files exist in the app's `assets/` folder |
| Serial Key prompt | The app will exit if no valid key is provided — contact Visom Technologies |
| Update not appearing | Check internet connection; try **About → Check for Updates...** manually |
| App won't start after update | Redownload the latest installer from the [Releases](https://github.com/vickykanni/chitfund-releases/releases) page and reinstall |

---

## 📜 License & Compliance

This application uses **PySide6 (Qt for Python)**, licensed under the **LGPLv3** (Lesser General Public License version 3).

1. Qt & PySide6 are valid trademarks of The Qt Company Ltd.
2. This software is dynamically linked to the Qt libraries (or bundles them in a way that allows replacement).
3. Source code for the Qt libraries: [https://www.qt.io](https://www.qt.io)
4. Full LGPLv3 license text: [https://www.gnu.org/licenses/lgpl-3.0.html](https://www.gnu.org/licenses/lgpl-3.0.html)
5. Users have the right to modify the Qt libraries used by this application and re-link the application to use the modified libraries.

---

Developed by **Visom Technologies**.
