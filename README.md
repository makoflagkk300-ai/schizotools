SchizoTools
============

Unified Windows launcher for locally installed arcade games.

Backends
--------
- Spice2x for Konami / BEMANI game folders
- Segatools for SEGA game folders
- Direct launch for other executables or batch files

First run
---------
SchizoTools scans C:\games for Spice2x launchers and installed Segatools
launch.bat + segatools.ini pairs. It does not copy, patch, decrypt, or modify
game data. Profiles are saved in schizotools-profiles.xml beside the EXE when
the folder is writable, or under Local AppData otherwise.

Controls
--------
- Add: create a profile manually
- Scan C:\games: find newly installed games without deleting existing profiles
- Open Config: launch spicecfg.exe or open segatools.ini
- Launch Game: starts the selected launcher using its configured working folder

If a game needs special command-line switches, enter them in Arguments.
