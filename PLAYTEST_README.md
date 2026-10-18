# MeadowRealm — Stillwater Gate

An early Windows fantasy social-world preview, built in Unreal Engine 5.8.

Walk through a meadow sanctuary framed by forest, cliffs, waterfalls and distant snow-covered peaks. Choose an Epic MetaHuman traveler, add a circlet or mantle, and meet companions in a locally hosted realm.

## Start

Extract the complete download before launching `MeadowRealm.exe`. Keep the accompanying folders beside the executable. If the download is split into numbered 7-Zip volumes, place every volume in the same folder and extract the `.7z.001` file with 7-Zip.

This is a demanding desktop scene. A DirectX 12 graphics device with Shader Model 6 support is required. Minimum hardware and stable performance targets have not been established.

## Controls

| Control | Action |
|---|---|
| W / A / S / D | Move |
| Mouse | Look |
| Shift | Run |
| Space | Jump |
| Tab / Escape | Open or close the realm menu |
| V, held | Push to talk after enabling the microphone |
| 1 / 2 / 3 / 4 | Clear / overcast / rain / storm; solo player or host only |

The Avatar panel saves the traveler name, avatar, accessory choices and accent locally. Apply the selection to see it on your character. This preview offers preset MetaHumans and accessory customization; it does not include a runtime face/body sculpting editor.

## Play together

One player selects **Host a local realm** and keeps the game running. Other players on the same network use **Find nearby realms**, or enter the host's IPv4 address and game port, such as `192.168.1.12:7777`. The configured session limit is eight players. Three simultaneous local processes have been tested; eight-player performance has not.

Direct internet joining requires a reachable host. This preview has no matchmaking service, relay or persistent hosted world. Hosting ends when the host leaves. Shared weather follows the host.

## Voice

The microphone is off initially. Enable it in the Voice panel, then hold **V** while in the world. The game uses the default Windows microphone and audio output. Check Windows microphone access if input is unavailable. Incoming voices have a 25-metre attenuation radius, obstruction filtering, master volume and individual companion mute controls.

The native voice configuration and distance attenuation have been checked. End-to-end microphone transmission and remote playback still require a two-device audio playtest. Do not treat this preview as a verified public voice service.

## Preview boundaries

The environment and gameplay are under development. Expect visual, collision and performance issues. This build is not a finished AAA game. It has no accounts, cloud saves, public moderation backend or ranked systems. Profile choices are stored on the local computer.

Known art limitations include smooth distant mountain shapes, a visible straight band in the far terrain, stylized-looking snow and waterfall surfaces, and minor garment contact around the hips and waist. The main shoulder and thigh intersections were corrected and the two characters were reviewed standing, running and jumping.

The download contains a cooked game, not reusable source assets. See `CREDITS.md` for asset acknowledgments.
