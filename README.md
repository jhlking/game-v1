# Game v1 · 游戏构建产物 v1

### Godot Game Build (v1) | Godot 游戏可执行版本 v1

> 本仓库保存游戏的第一个可运行构建版本（Windows）。
> *This repository stores the first runnable build of the game (Windows).*

---

## 项目概述 · Overview

**中文**

本仓库是游戏项目的早期构建产物存档，仅包含 Godot 引擎导出的 Windows 可执行程序、资源包（`.pck`）与运行库（.NET 依赖），**不包含游戏源码**。如需查看源码与前端界面，请访问 [`game-project`](https://github.com/jhlking/game-project)。

**English**

This repository is an archive of an early build of the game. It contains only the Windows executable exported from the Godot engine, the resource pack (`.pck`) and runtime libraries (.NET dependencies) — **no game source code**. For the source and frontend UI, see [`game-project`](https://github.com/jhlking/game-project).

---

## 技术栈 · Tech Stack

| 技术 Technology | 说明 Description |
| --- | --- |
| Godot Engine | 游戏引擎，导出 Windows 版本 Game engine (Windows export) |
| C# / .NET | Godot 脚本运行时（GodotSharp.dll 等）Scripting runtime |
| Mono / .NET Runtime | 附带完整 .NET 运行库 Bundled .NET runtime libraries |

---

## 运行方式 · How to Run

1. 下载或克隆本仓库（Download or clone this repository）
2. 直接双击运行 `game-project1.exe`（Windows）
3. 若需要调试输出，可运行 `game-project1.console.exe`

> 注意：压缩包体积较大，主要来自随附的 .NET 运行库。
> *Note: the large repository size comes mainly from the bundled .NET runtime libraries.*

---

## 目录结构 · Repository Structure

```
game-v1/
├── game-project1.exe                  # 游戏主程序 Game executable
├── game-project1.console.exe          # 带控制台的调试版本 Console build
├── game-project1.pck                  # Godot 资源包 Godot resource pack
└── data_game-project1_windows_x86_64/ # .NET / Godot 运行库 Runtime libraries
```
