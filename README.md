# CfxLua IntelliSense (FiveM / RedM)

[![Version](https://img.shields.io/badge/version-1.10.16-blue)](https://github.com/AnishBplayz/cfxlua-vscode-openvsx/releases)
[![Open VSX](https://img.shields.io/badge/Open_VSX-Registry-8732a0?logo=openvscode)](https://open-vsx.org/extension/anishbplayz/cfxlua-vscode-openvsx)
[![VS Marketplace](https://img.shields.io/badge/VS_Marketplace-Install-007acc?logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=AnishBplayz.cfxlua-vscode-openvsx)

> **Note**  
> Community-maintained fork of the archived [overextended/cfxlua-vscode](https://github.com/overextended/cfxlua-vscode). Published under the `anishbplayz` namespace on [Open VSX Registry](https://open-vsx.org/extension/anishbplayz/cfxlua-vscode-openvsx) and [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=AnishBplayz.cfxlua-vscode-openvsx).
>
> *This extension is not authored, published, sponsored, nor endorsed by Cfx.re.*

---

## Features

- **IntelliSense & diagnostics** — Provided by [sumneko's Lua Language Server](https://marketplace.visualstudio.com/items?itemName=sumneko.lua): diagnostics, annotations, and auto-completion.
- **Runtime globals** — Support for environment globals (e.g. `CreateThread`, promises, `json`, statebags).
- **Natives** — Support for FiveM, RedM, and CFX natives.
- **LuaGLM** — Support for Cfx's [Lua implementation (LuaGLM)](https://github.com/citizenfx/lua/tree/luaglm-dev/cfx):
  - Vector, quat, and matrix types.
  - Partial support for extended syntax / [power patches](https://github.com/citizenfx/lua/blob/luaglm-dev/cfx/README.md#power-patches).  
    *Use with caution — some patches have been known to cause crashes.*

---

## Screenshots

![IntelliSense preview](https://github.com/user-attachments/assets/586b960c-3b1e-4911-80dd-788a0917b0f8)

![Auto-completion preview](https://github.com/user-attachments/assets/22bb5f61-9b4d-4461-98f3-0eaba196839b)

---

## Configuration

| Setting        | Options   | Description              |
|----------------|-----------|--------------------------|
| `cfxlua.game`  | `gtav`, `rdr3` | Choose GTA V or RDR3 natives. |

**Commands (Command Palette):**

- **CfxLua: Use GTAV natives** — Switch to GTA V natives.
- **CfxLua: Use RDR3 natives** — Switch to RDR3 (RedM) natives.

---

## Credits

Thanks to CitizenFX, gottfriedleibniz, alloc8or, iTexZoz, TasoOneAsia,  Overextended and CommunityOX.
