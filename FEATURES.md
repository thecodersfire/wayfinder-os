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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
2. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
3. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
6. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
9. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
10. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
11. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
12. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
13. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.
14. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.
15. **Flatseal** (com.github.tchx84.Flatseal) — review Flatpak app permissions.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
2. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
3. **KGeoTag** (org.kde.kgeotag) — add GPS coordinates to photos from a GPX track or map.
4. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
5. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
6. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
7. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
8. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
9. **Ark** (org.kde.ark) — open and create common project archive files.
10. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
11. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
12. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
13. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
14. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.
