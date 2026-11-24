# TBCC Utility

Public home for **TBCC Operator** — the Chrome MV3 extension used with AOF / PowerCore workflows:

- **X overlay gallery** — harvest profile or home-feed media, 1 / 2 / 3 scrollbar lanes, zoom + Space-drag pan, per-pane download
- **X feed download** — one-click save to TBCC inbox (AOF naming)
- Site enhancers and gallery handoff when the full Operator build is loaded

Hub / overlay **Get TBCC** buttons point here:  
**https://github.com/ianmxaof/tbcc-utility**

## Install (sideload)

1. Open a [Release](https://github.com/ianmxaof/tbcc-utility/releases) and download the latest `tbcc-operator-*.zip` (or load from your Operator build folder).
2. Unzip to a permanent folder.
3. Chrome → `chrome://extensions` → enable **Developer mode**.
4. **Load unpacked** → select the unzipped `extension` folder (the one with `manifest.json`).
5. Confirm the card shows **TBCC Operator**.

> **Not** PowerCore Browser Hub — that is a separate free shell. X overlay + ZIP/Gallery need **TBCC Operator**.

## Userscript twin

Community Tampermonkey cut (lightbox without ZIP/Gallery chrome APIs):

- Script: [AOF X Profile Gallery](https://sleazyfork.org) — search **AOF X Profile Gallery**
- Source build lives in the TBCC monorepo under `tbcc/userscripts/x-profile-enhancer/`

## What this repo is

| This public page | Private Operator source |
|------------------|-------------------------|
| Find-us URL, install notes, release zips | Full extension tree (`tbcc-operator` / monorepo) |
| Safe to share in overlays & listings | Admin-only modules stay private |

## Links

- AOF Main Hub: https://t.me/aofmainhub  
- Packs & VIP: https://t.me/aof_chat_farm_2bot  
- PowerCore: https://powercore.app  

## License

MIT for docs and public packaging scripts in this repository. Extension binaries may carry additional notices in their release zip.
