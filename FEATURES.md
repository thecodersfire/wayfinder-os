# Built-in features for wayfinder-os

Purpose: travel planning

1. **organize work and records** — run wayfinder-os-workspace. It creates ~/Documents/wayfinder-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run wayfinder-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/wayfinder-os-session-plans/.
3. **check records and task readiness** — run wayfinder-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/wayfinder-os-workspace features/wayfinder-os-plan features/wayfinder-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for travel planning:

1. **QGIS** — org.qgis.qgis
2. **GNOME Maps** — org.gnome.Maps
3. **Zotero** — org.zotero.Zotero

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
