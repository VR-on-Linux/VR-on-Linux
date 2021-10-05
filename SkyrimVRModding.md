# Modding Skyrim VR

Force Proton version: 6.3

Run once. Check if you can hear NPC dialog in the Intro. 
If not, install xact via protontricks:

	protontricks 611670 xact

And change your launch command to:

	WINEDLLOVERRIDES="xaudio2_7=n,b;x3daudio1_7=n,b" %command%

## SKSEVR

Required for all mods which use scripting.
The official SKSEVR release will not work with wine.

This build does work: https://drive.google.com/file/d/1SBzd-yIGHA0dnQEWqkSt-sbzNyGJna_R/view

- unpack in: `steamapps/common/SkyrimVR`
- rename `SkyrimVR.exe` to `SkyrimVR-bak.exe`
- rename `sksevr_loader.exe` to `SkyrimVR.exe`
- Create `Data/SKSE/skse.ini` with content:

		[Loader]
		RuntimeName=SkyrimVR-bak.exe 



## SkyUI VR

The standard UI is a bit cumbersome to use in VR. 
SkyUI is a nicer replacement and a requirement for VRIK.

https://github.com/Odie/skyui-vr/releases/download/v1.0-beta.4/SkyUI-VR.v1.0-beta.4.7z

- unpack in: `steamapps/common/SkyrimVR`
- in `SkyUI - VR` directory:
  - rename `interface` to `Interface`
  - rename `script`s to `Scripts`
  - move contents of directory into `Data`

## HIGGS

Adds hand interaction and Alyx style gravity gloves.

https://www.nexusmods.com/skyrimspecialedition/mods/43930

- unpack in: `steamapps/common/SkyrimVR/Data`


## VRIK

Adds a player avatar, weapon holsters and gestures.

https://www.nexusmods.com/skyrimspecialedition/mods/23416

- download both VRIK + optional bindings file
- unpack both in: `steamapps/common/SkyrimVR/Data`
- in SteamVR settings change bindings for SkyrimVR to "VRIK Index Controller Bindings V2.1.0"

## Config

In `steamapps/compatdata/611670/pfx/drive_c/users/steamuser/AppData/Local/Skyrim VR`

### Create `plugins.txt` with content:

	*SkyUI_SE.esp
	*vrik.esp
	*higgs_vr.esp


### Create `loadorder.txt` with content:

	Skyrim.esm
	Update.esm
	Dawnguard.esm
	HearthFires.esm
	Dragonborn.esm
	SkyrimVR.esm
	SkyUI_SE.esp
	vrik.esp
	higgs_vr.esp


## True 3D Sound

For binaural/positional audio.

https://www.nexusmods.com/skyrimspecialedition/mods/1897

extract in `steamapps/common/SkyrimVR`

Change your launch command to:

	WINEDLLOVERRIDES="xaudio2_7=n,b;x3daudio1_7=n,b" %command%


## Non-essential

Some basic mods for better visuals.
Need a mod manager to install these.

See:
- https://github.com/frostworx/steamtinkerlaunch
- https://www.reddit.com/r/SteamTinkerLaunch/comments/q1785a/vortex_mod_manager_mod_organizer_2_specialk_added/

### Visual
- SMIM: https://www.nexusmods.com/skyrimspecialedition/mods/659/
- WICO: https://www.nexusmods.com/skyrimspecialedition/mods/2136
- Onyx VR Weathers: https://www.nexusmods.com/skyrimspecialedition/mods/36227
- Flora Overhaul (hurts performance a bit): https://www.nexusmods.com/skyrimspecialedition/mods/2154
- Textures:
	- https://www.nexusmods.com/skyrimspecialedition/mods/2347

### Other
- achievements mods enabler (Don't get punished for making the game playable): https://www.nexusmods.com/skyrimspecialedition/mods/245
