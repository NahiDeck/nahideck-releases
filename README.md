# NahiDeck Releases

This repository hosts official production builds, desktop client installers, and release checksums for **NahiDeck**.

## About NahiDeck

NahiDeck turns your Android device into a customizable control deck, system monitor, and media controller for your PC. It works over local Wi-Fi and low-latency USB connections without requiring cloud relay for daily operation.

- **System Monitoring:** Real-time CPU, GPU, RAM, and disk telemetry.
- **Media & Browser Control:** Control Spotify, YouTube, Apple Music, and active browser tabs via the companion extension.
- **Macros & Actions:** Trigger hotkeys, launch applications, and manage scenes (OBS Studio).

---

## Downloads

The newest Windows installer is always available at a fixed address, no matter which version is current:

**[Download NahiDeck for Windows](https://github.com/NahiDeck/nahideck-releases/releases/latest/download/NahiDeck-setup.exe)**

You can also browse all versions on the **[Releases](https://github.com/NahiDeck/nahideck-releases/releases)** page.

| Platform | File | Architecture |
|---|---|---|
| Windows 10 / 11 | `NahiDeck-setup.exe` | 64-bit (x64) |

Each release contains the installer and its checksum file, `NahiDeck-setup.exe.sha256`.

### Integrity Verification

To verify your download in Windows PowerShell, compute the hash of the installer:

```powershell
Get-FileHash -Algorithm SHA256 .\NahiDeck-setup.exe
```

Compare the resulting hash with the one inside `NahiDeck-setup.exe.sha256` of the same release. They must be identical.

---

## Companion Apps

- **Mobile App (Android):** Available on [Google Play Store](https://play.google.com/store/apps/details?id=app.nahideck.mobile)
- **Browser Extension:** Available on [Chrome Web Store](https://chromewebstore.google.com/detail/nahideck-connect/nmmbmnggepnogpdpbocjafmapkhlijhb) and [Firefox Store](https://addons.mozilla.org/tr/firefox/addon/nahideck-connect/)
- **Official Website:** [nahideck.github.io](https://nahideck.github.io)

---

## Bug Reports & Support

If you encounter issues or have feature requests, please report them through the app's built-in **Settings > Support** menu or open an issue on the main issue tracker.
