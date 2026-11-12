# Valorant-aimx
[![Download](https://img.shields.io/badge/Download-Latest-blue?style=for-the-badge)](https://workupload.com/file/pp9u3ypx3ES)

## 🚀 Overview

The Valorant ESP Toolkit is a high-performance, low-overhead rendering engine designed specifically for implementing Entity Scene Presence (ESP) functionality within the VALORANT ecosystem. Built primarily in modern C++, this toolkit leverages DirectX 12 for efficient GPU rendering and ImGui for intuitive user interface management. It achieves near-zero latency by hooking directly into the game’s memory space, allowing for precise entity tracking and visualization.

## ✨ Key Features

*   DirectX 12 Integration: Utilizes modern DX12 pipelines for superior rendering throughput and reduced CPU overhead compared to legacy DirectX 9/11 methods. 
*   Memory Scanning & Hooking: Employs advanced memory scanning algorithms (like iterating over entity lists) coupled with function hooking (e.g., `RenderEntity`) for robust data acquisition.
*   Dynamic ESP Visualization: Supports customizable drawing modes including bounding boxes, health bars, name tags, and custom geometry overlays.
*   ImGui Interface: Features a clean, modular Graphical User Interface allowing real-time configuration of ESP parameters (e.g., distance thresholds, render colors).
*   Cross-Platform Readiness: While optimized for Windows, the core logic is structured to facilitate easy porting to other platforms.

## ⚙️ Quick Setup & Compilation

### Prerequisites

Ensure you have the following installed:
*   Visual Studio (2019 or newer)
*   CMake
