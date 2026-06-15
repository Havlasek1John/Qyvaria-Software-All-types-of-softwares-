# Qyvaria Softwares

**Qyvaria Softwares** is a growing collection of desktop tools, utilities, optimizers, editors, and data-compression apps built with a clean Qyvarian design style.

This repository will be updated **daily** with new software, improvements, fixes, installers, UI upgrades, and experiments I make.

> Big tools. Clean UI. Simple installs. Practical software.

---

## Repository Name Recommendation

Recommended GitHub repository name:

```text
qyvaria-softwares
```

Other good names:

```text
qyvaria-software-suite
qyvaria-desktop-tools
qyvaria-tools
qyvaria-labs
qyvaria-apps
```

Best choice: **`qyvaria-softwares`** because it matches your wording, is simple, and can hold many different apps.

---

## Included Software

### 1. AI Inspector Editor

A desktop app for inspecting, editing, reviewing, and improving AI-related reports, JSON outputs, notes, and structured data.

**Main goals:**

- Cleaner inspection workflow
- Modern Qyvarian UI
- Report viewing and editing
- Safer handling of files
- Windows and Linux support

---

### 2. QTask Optimizer

A productivity and task-optimization app for organizing work, improving task flow, and helping users manage actions more efficiently.

**Main goals:**

- Task planning
- Optimization suggestions
- Cleaner workflow UI
- Desktop setup support
- Windows and Linux support

---

### 3. Qyvaria Zip Resizer

An advanced ZIP optimization app that turns large ZIP files into smaller optimized ZIP files when possible.

**Main goals:**

- Analyze ZIP archives
- Detect duplicate files
- Remove junk/cache/temp files
- Recompress archives
- Verify output ZIP files
- Create compression reports
- Create Qyvaria proof traces
- Windows and Linux support

Important: already-compressed files such as videos, JPGs, PNGs, PDFs, MP3s, 7Z files, RAR files, and existing ZIP files may not shrink much. The software reports this honestly.

---

### 4. SafeSpeed Optimizer

A safer system-optimization utility focused on improving performance without risky or destructive changes.

**Main goals:**

- Clean optimization controls
- Safety-first actions
- Clear warnings
- Desktop app setup
- Windows and Linux support

---

## Qyvaria Design Direction

The Qyvaria software style focuses on:

- Clean modern UI
- White-space-first layout
- Technical cockpit panels
- Crisp labels
- Clear warnings
- Proof reports where needed
- Simple installation
- Windows and Linux support
- No fake promises
- Safer defaults

---

## Installation

Each app includes setup scripts for both Windows and Linux.

### Linux

From the software folder:

```bash
chmod +x scripts/install_linux.sh
./scripts/install_linux.sh
```

For the full suite:

```bash
chmod +x install_all_linux.sh
./install_all_linux.sh
```

The Linux setup should install app launchers into:

```text
~/.local/share/applications
~/Desktop
~/.local/bin
```

### Windows

Double-click:

```text
install_all_windows.bat
```

Or run the PowerShell installer:

```powershell
powershell -ExecutionPolicy Bypass -File install_all_windows.ps1
```

The Windows setup should create:

```text
Desktop shortcuts
Start Menu shortcuts
Local app folders under %LOCALAPPDATA%\Qyvaria
```

---

## Build From Source

Most apps are Python-based.

Basic development setup:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m pip install -r requirements-build.txt
```

Build with PyInstaller where supported:

```bash
python -m PyInstaller --onefile your_app_entry.py
```

Some apps include ready-made build scripts:

```bash
scripts/build_linux.sh
scripts/build_windows.bat
scripts/build_windows.ps1
```

---

## Daily Updates

I will be updating this GitHub repository daily with:

- New Qyvaria software
- Bug fixes
- Cleaner UIs
- More installers
- Better Windows support
- Better Linux support
- New app icons
- More stable setup systems
- More tests
- New proof/report features
- Better documentation

---

## Planned Improvements

- Add a universal Qyvaria launcher
- Add automatic updater
- Add signed Windows builds
- Add Linux AppImage builds
- Add Debian `.deb` packages
- Add Fedora/RPM packages
- Add Flatpak packaging
- Add GitHub Actions build pipeline
- Add screenshots and demo videos
- Add full release notes for every app

---

## Safety Notes

These tools are designed to be practical and safe, but users should still:

- Keep backups before modifying important files
- Read warnings before optimization
- Test on copies first
- Keep original ZIP archives when audit accuracy matters
- Avoid uploading private data to public issues

---

## License

This repository is licensed under the **Apache License 2.0**.

See [`LICENSE`](LICENSE) for details.

---

## Author / Project

Created by **Qyvaria Softwares**.

This is an active software collection and will continue growing.
