# NahiDeck Releases

This repository hosts official production builds, desktop client installers, and release checksums for **NahiDeck**.

## About NahiDeck

NahiDeck turns your Android device into a customizable control deck, system monitor, and media controller for your PC. It works over local Wi-Fi and low-latency USB connections without requiring cloud relay for daily operation.

- **System Monitoring:** Real-time CPU, GPU, RAM, and disk telemetry.
- **Media & Browser Control:** Control Spotify, YouTube, Apple Music, and active browser tabs via the companion extension.
- **Macros & Actions:** Trigger hotkeys, launch applications, and manage scenes (OBS Studio).

---

## Downloads

Download the latest Windows installer and its integrity checksum from the **[Releases](https://github.com/NahiDeck/nahideck-releases/releases)** page:

| Platform | File | Architecture |
|---|---|---|
| Windows 10 / 11 | `NahiDeck_1.0.0_x64-setup.exe` | 64-bit (x64) |

### Integrity Verification

Every release includes a `SHA256SUMS.txt` file. To verify your download on Windows PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\NahiDeck_1.0.0_x64-setup.exe
```

Compare the resulting hash with the published checksum in `SHA256SUMS.txt`.

---

## Companion Apps

- **Mobile App (Android):** Available on [Google Play Store](https://play.google.com/store/apps/details?id=app.nahideck.mobile)
- **Browser Extension:** Available on [Chrome Web Store](https://chromewebstore.google.com/detail/nahideck-connect/nmmbmnggepnogpdpbocjafmapkhlijhb)
- **Official Website:** [nahideck.github.io](https://nahideck.github.io)

---

## Bug Reports & Support

If you encounter issues or have feature requests, please report them through the app's built-in **Settings > Support** menu or open an issue on the main issue tracker.
