# Cecil's Win11 Cleanup
`Cleanup-Win11.bat` is a one‑shot batch script for IT admins (or everyday users) that will cleanup, debloat, and optimize for performance. It works on Windows 10 but is designed for Windows 11

> **Warning:** This script makes system and registry changes. Test it in a VM or non‑critical machine first.

---

## What it does

- **System basics**
  - Ensures it runs with admin rights 
  - Detects and shows Windows version/build
  - Runs with clean and clear output of changes / failures  

- **Performance & UX**
  - Sets Num Lock on by default (desktops only)
  - Sets timezone to Mountain Standard Time and resyncs time
  - Applies “performance” visual settings (quicker response times)  
  - Makes File Explorer open to “This PC” instead of recents
  - Cleans up cluttered context menus and Quick Access
  - Disables sleep/hibernation when plugged in (maintain availability for remote access)

- **Privacy & telemetry**
  - Blocks a large list of Microsoft telemetry/metrics endpoints via HOSTS file
  - Disables or reduces telemetry, CEIP, error reporting, and web/Bing search integration  
  - Turns off Start menu ads, tips, and other “consumer” content  
  - Tightens various privacy‑related registry settings for current and default profiles

- **Apps & bloat**
  - Optionally uninstalls and cleans up OneDrive  
  - Restores Windows Photo Viewer as an image viewer option
  - Removes various preinstalled shortcuts and promo links from the Start menu
  - Tweaks Office/Outlook defaults (prefer local save, disable forced “New Outlook” migration) when present

- **Safety**
  - Enables periodic registry backups
  - Saves a snapshot of key registry hives to a dated folder under `C:\Windows\System32\config\RegBack\`

---

## What it does *not* do

- Does **not** remove core Windows components or features required for normal operation.
- Does **not** install any third‑party software.
- Does **not** disable Windows Defender or other antivirus products.
- Does **not** join domains, enroll in MDM, or otherwise change identity/network configuration.
- Does **not** make irreversible changes without at least a basic registry backup in place.

That said, many changes are low‑level registry and policy tweaks. Always verify they match your environment’s requirements.

---

## Usage

1. Download or clone this repository.
2. Right‑click `Cleanup-Win11.bat` → **Run as administrator**.
3. Follow the on‑screen output and prompts (e.g., optional OneDrive removal).
4. Reboot when convenient to ensure all changes take effect.

---

## License & attribution

- License: **MIT** (see `LICENSE`).
- You are free to use and adapt this script. Please:
  - Keep the license and attribution.
  - Link back to this repository when sharing or recommending it.
  - Consider contacting me before publishing heavily modified versions.

---

### Author

- **Author:** OutlawCecil (`@OutlawCecil`)  
- **Contact:** OutlawCecil@gmail.com

---
