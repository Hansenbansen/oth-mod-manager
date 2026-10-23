# OTH Mod Manager

A mod manager for **over the hill** (MelonLoader) that runs in your browser: install mods from
Nexus or archives, switch profiles, share profiles with friends, and set up MelonLoader in one click.

**[Download the latest version](https://github.com/Hansenbansen/oth-mod-manager/releases/latest)**:
get `OTHModManager-X.Y.Z-portable.zip`, unzip it somewhere you can write to (not Program Files) and
start `OTHModManager.exe`. Nothing is installed; delete the folder to remove it.

Once it runs, the manager keeps itself up to date: when a new version is out, a bar at the top of
its page offers to update and restart.

This repository only holds the releases. Each one has two files:

- `OTHModManager-X.Y.Z-portable.zip`: the whole manager, for a new install.
- `OTHModManager-X.Y.Z-app.zip`: only the manager's code, which installed managers update from.

The manager's code is readable in both (`app/othmm.py` and `app/static/`).
