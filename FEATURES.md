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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for travel planning:

1. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
2. **darktable** — develop RAW photos (org.darktable.Darktable)
3. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
