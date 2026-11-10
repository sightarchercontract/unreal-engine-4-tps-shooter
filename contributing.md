# 🎯 Unreal Engine 4 TPS Shooter

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,8,19&height=210&section=header&text=Unreal%20Engine%204%20TPS%20Shooter&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Complete%20Third-Person%20Shooter%20Template&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.9.0-1D3557?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Engine](https://img.shields.io/badge/Unreal%20Engine-4.27-457B9D?style=for-the-badge&logo=unrealengine&logoColor=white)](https://www.unrealengine.com)
[![License](https://img.shields.io/badge/license-MIT-A8DADC?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Blueprints](https://img.shields.io/badge/blueprints-100%25-F1FAEE?style=for-the-badge&logo=blueprint&logoColor=black)](https://github.com)

<br/>

### 🔫 A full-featured third-person shooter template built entirely in Blueprints

*🎮 Player Controller • 🔫 Weapon System • 🤖 Enemy AI • 🎨 Polished UI*

<br/>

<a href="https://share.google/lQ9BxahV2MICN0M9K">
  <img src="https://img.shields.io/badge/📥_GET_TEMPLATE-1D3557?style=for-the-badge&logo=unrealengine&logoColor=white&labelColor=132539" alt="Get Template" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/lQ9BxahV2MICN0M9K">
  <img src="https://img.shields.io/badge/🎮_LIVE_DEMO-457B9D?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=2E5368" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/lQ9BxahV2MICN0M9K">
  <img src="https://img.shields.io/badge/📚_DOCS-A8DADC?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=7EA8AC" alt="Docs" height="45"/>
</a>

</div>

<img width="1280" height="720" alt="maxresdefault - 2026-11-10T202026 797" src="https://github.com/user-attachments/assets/72effff4-2aa9-4bf3-aa47-016049f61b8e" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Unreal Engine 4 TPS Shooter** is a **complete third-person shooter template** you can open in UE4 and play immediately. Everything works out of the box — movement, aiming, shooting, enemy AI, health, ammo, UI, and game flow.

It's built **100% in Blueprints**, making it beginner-friendly and easy to customize without writing any C++. Use it as a learning reference, a prototyping base, or the foundation of your next shooter.

> 💡 **Perfect for:** UE4 learners, game design students, indie devs prototyping a TPS, and anyone who wants to see a full game loop assembled in Blueprints.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎮 **Player Controller** | 🔫 **Weapon System** | 🤖 **Enemy AI** |
|:---:|:---:|:---:|
| Movement, aiming,<br/>crouch & sprint | Hitscan & projectile,<br/>recoil & reload | Patrol, chase,<br/>attack & cover |

| ❤️ **Health System** | 🎨 **Full UI** | 🗺️ **Sample Level** |
|:---:|:---:|:---:|
| Damage, regen,<br/>death & respawn | HUD, ammo, health<br/>bars & menus | Ready-to-play<br/>arena level |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Template

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ✅ **100% Blueprints** | No C++ required — learn and modify everything visually |
| 🎮 **Complete Game Loop** | From main menu to game over — every state is implemented |
| 🔫 **Production-Quality Weapon** | Recoil, spread, reload, damage falloff & hit markers |
| 🤖 **Smart Enemy AI** | Behavior Tree + Blackboard, ready to extend with new tactics |
| 🎨 **Polished UI** | HUD, health bars, ammo counters and pause menu included |
| 🚀 **Well-Organized** | Clean folder structure, commented nodes, easy to navigate |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Gameplay Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🎯  UE4 TPS Shooter  v2.9.0                     ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║     🎯 Aim: Over Shoulder                        ║
║     ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░  Ammo: 17/30           ║
║     ❤️ Health: ████████░░ 80%                    ║
║                                                  ║
║      👤 ← Player                                 ║
║           │                                      ║
║           ▼  crosshair                           ║
║                  🤖 ← Enemy (AI)                 ║
║                                                  ║
║  🎯 [ Left Click ] Shoot   [ R ] Reload          ║
║  🎮 [ WASD ] Move  [ Shift ] Sprint  [ C ] Crouch║
║                                                  ║
║  📊 Enemies defeated: 4/10   ⏱️ Time: 2:14       ║
║  🎨 Full Blueprints   ✅ Ready to play           ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎯 ue4-tps-shooter/
├── 🎮 Content/
│   ├── Blueprints/
│   │   ├── Player/            # Character & controller
│   │   ├── Weapons/           # Weapon system
│   │   ├── Enemy/             # AI & Behavior Trees
│   │   └── UI/                # HUD & menus
│   ├── Maps/                  # Arena level
│   ├── Animations/            # Locomotion & weapon anims
│   └── Materials/             # Shader & VFX materials
├── 🧪 Tests/                  # Functional test maps
└── 📖 docs/                   # Setup & customization guide
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Unreal](https://img.shields.io/badge/Unreal_Engine_4.27-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Blueprints](https://img.shields.io/badge/Blueprints-1D3557?style=for-the-badge&logo=blueprint&logoColor=white)
![Behavior Tree](https://img.shields.io/badge/Behavior_Tree-457B9D?style=for-the-badge&logo=diagramsdotnet&logoColor=white)
![UMG](https://img.shields.io/badge/UMG_UI-A8DADC?style=for-the-badge&logo=unrealengine&logoColor=black)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want to add new weapons or enemy types?

<div align="center">

<a href="https://share.google/lQ9BxahV2MICN0M9K">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/lQ9BxahV2MICN0M9K">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-1D3557?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/lQ9BxahV2MICN0M9K">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-A8DADC?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🎯 Made with 🔫 by the TPS Shooter Team

*If this template kick-started your game — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,8,19&height=120&section=footer" width="100%"/>

</div>
