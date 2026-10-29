# Azeroth Wayfarers downloads

Azeroth Wayfarers is an incremental expedition-company addon for World of Warcraft.
This repository hosts versioned player downloads. It contains no development
checkout, test history or personal company saves.

## Windows installer

[Download AzerothWayfarers-Setup.exe](https://github.com/mammle992/azeroth-wayfarers-releases/releases/download/v0.10.0-alpha.1/AzerothWayfarers-Setup.exe)

1. Close WoW and open the installer.
2. Choose an addon version from GitHub.
3. Browse to your WoW client's existing `Interface/AddOns` folder.
4. Click **Install / Update**, then enable Azeroth Wayfarers in WoW.

No Git, source checkout or separate .NET installation is required. Windows x64
is supported. The installer replaces only the `FelEmpire` addon directory;
sibling addons and WTF/SavedVariables remain untouched.

## Manual installation

Choose a version on the [releases page](https://github.com/mammle992/azeroth-wayfarers-releases/releases).
Download `AzerothWayfarers-<version>.zip` and extract its **FelEmpire** directory
into `Interface/AddOns`. GitHub's automatic source-code archives contain this
downloads README, rather than the addon package.

Each release includes SHA-256 sidecars for the installer and addon ZIP. The
installer also verifies every runtime file against the package manifest.

## Alpha status

0.10.0 is an alpha. Native Forever addon/API compatibility is still unverified;
accepting a custom AddOns folder does not establish game-client compatibility.
Map Discoveries native credit is disabled until exact visit mappings are verified.
Keep your normal company backup before testing a build in WoW.

This is an unofficial fan project, unaffiliated with Blizzard Entertainment.
Warcraft names and assets belong to their respective owners.
