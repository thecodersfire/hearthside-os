# Built-in features for hearthside-os

Purpose: household planning

1. **prepare a creative project** — run hearthside-os-workspace. It creates ~/Documents/hearthside-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run hearthside-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/hearthside-os-session-plans/.
3. **check project and export readiness** — run hearthside-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/hearthside-os-workspace features/hearthside-os-plan features/hearthside-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for household planning:

1. **GNOME Calendar** — org.gnome.Calendar
2. **Audacity** — org.audacityteam.Audacity
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for household planning:

1. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
2. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
3. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
4. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
2. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
3. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
4. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
5. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
6. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
7. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
8. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
9. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
10. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
13. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.
14. **Inkscape** (org.inkscape.Inkscape) — create vector illustrations and diagrams.
15. **GNOME Sound Recorder** (org.gnome.SoundRecorder) — capture voice and field notes.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
2. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
3. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
4. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
5. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
6. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
7. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
8. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
9. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
10. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
11. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
12. **Ark** (org.kde.ark) — open and create common project archive files.
13. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
14. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
15. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.
