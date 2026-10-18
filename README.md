# MeadowRealm — Stillwater Gate

A free Windows fantasy social-world development preview made in Unreal Engine 5.8.

![Stillwater Gate — actual Unreal viewport capture](https://github.com/twoastronauts/meadowrealm/releases/download/v0.1.0-preview/MeadowRealm-sanctuary.png)

Explore a meadow sanctuary surrounded by a layered forest, cliffs, waterfalls and mountain peaks. Choose a MetaHuman traveler, customize fantasy accessories and colors, and host a local realm for companions.

## Download and play

Use the [Windows development preview](https://github.com/twoastronauts/meadowrealm/releases/tag/v0.1.0-preview). Download both numbered `.7z.001` and `.7z.002` parts into one folder (approximately 2.11 GB combined). Extract `.001` with 7-Zip, then run the extracted `MeadowRealm.exe`. Keep its accompanying folders intact.

The actual Shipping executable passed a fresh-profile startup check, with the scene, fitted MetaHuman, animation and menu verified. Both archive parts passed an integrity check.

A DirectX 12 graphics device with Shader Model 6 is required. Minimum hardware and stable frame-rate targets have not been established.

## In the preview

- Stillwater Gate, a central stone ruin with luminous inscriptions.
- Forest and fern understory, cliff formations, animated falls and environmental sound.
- Clear, overcast, rain and storm weather, with wind and wetness responses.
- Two Epic MetaHuman presets with fantasy clothing, circlets, shoulder mantles and accent choices.
- Third-person walking, running and jumping, plus local appearance profiles.
- Local hosting, LAN discovery and direct-address joining. Three simultaneous local processes have been tested; the configured limit is eight.
- Opt-in push-to-talk configuration, proximity attenuation and companion mute controls.

**Controls:** WASD to move, mouse to look, Shift to run, Space to jump, Tab for the realm menu, V held for push-to-talk after enabling the microphone. The host selects weather with 1–4.

## Current boundaries

This is an early development preview, not a finished AAA release. The visual target remains in progress, including distant terrain and water polish. Customization uses preset characters, accessories and colors; full runtime face/body sculpting is not included.

Microphone transmission and remote playback still need a two-device audio playtest. Native voice configuration and distance attenuation checks are not end-to-end voice verification. There is no public matchmaking relay, permanent hosted world, account service or moderation backend. Direct internet play requires a reachable host.

Read `PLAYTEST_README.md`, `PLAYTEST_TERMS.txt` and `CREDITS.md` in the download. This repository distributes a cooked playtest and documentation; it is not a raw asset pack or an Unreal source-project license.
