# WarMatrix: AI-Enabled Tactical Simulation Console

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Next.js 15](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![FastAPI](https://img.shields.io/badge/FastAPI-0.109+-009688?logo=fastapi)
![React 19](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?logo=tailwind-css)
![Three.js](https://img.shields.io/badge/Three.js-r178-black?logo=three.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript)
![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.5-EE4C2C?logo=pytorch)
![NVIDIA CUDA](https://img.shields.io/badge/CUDA-12.1-76B900?logo=nvidia)

Tested on: ![](https://valid.x86.fr/cache/banner/6qegm1-6.png)

WarMatrix is a high-fidelity, situational awareness platform that bridges the gap between tactical simulations and modern AI analytics. Designed for immersive command experience, it provides a unified "Glass Cockpit" for operational commanders across Land, Air, and Sea domains.

---

## 🖼️ Mission Visuals

The WarMatrix interface is designed for high-density information display and tactical immersion.

| **Main Landing Page** | **Scenario Builder** |
| :---: | :---: |
| ![Landing Page](https://raw.githubusercontent.com/WarMatrixAI/WarMatrix/refs/heads/main/screenshots/landing.png) | ![Scenario Builder](https://raw.githubusercontent.com/WarMatrixAI/WarMatrix/refs/heads/main/screenshots/builder.png) |

---

| **2D Strategic Map** | **3D Tactical Map** |
| :---: | :---: |
| ![2D Strategic Map](https://raw.githubusercontent.com/WarMatrixAI/WarMatrix/refs/heads/main/screenshots/2d_map.png) | ![3D Tactical Map](https://raw.githubusercontent.com/WarMatrixAI/WarMatrix/refs/heads/main/screenshots/3d_map.png) |

---

| **Command Console** | **Mission AI Briefing** | **Final Mission Report** |
| :---: | :---: | :---: |
| ![Command Console](https://raw.githubusercontent.com/WarMatrixAI/WarMatrix/refs/heads/main/screenshots/console.png) | ![AI Briefing](https://raw.githubusercontent.com/WarMatrixAI/WarMatrix/refs/heads/main/screenshots/briefing.png) | ![Final Report](https://raw.githubusercontent.com/WarMatrixAI/WarMatrix/refs/heads/main/screenshots/report.png) |

---

## 🎖️ Operational User Perspective: A 4-Step Narrative

The WarMatrix experience follows a structured operational workflow. From the initial terminal uplink to the final after-action review, the user acts as the central Node of Intelligence.

### Step 1: Secure Terminal Uplink & Domain Entry
The user enters a **Classified Command Console** built with a dark-ops aesthetic—featuring scanline overlays and tactical grids. The "War Room" interface initializes with a secure system handshake, ensuring the user is placed into a focused, distraction-free strategic environment.

### Step 2: Intelligent Scenario Synthesis
Using the **AI Scenario Builder**, the commander defines the battlefield parameters:
- **Environmental Context:** Selection of terrain (Highlands, Urban, Desert) and real-time weather effects (Storm, Fog, Sandstorm).
- **ORBAT (Order of Battle):** Strategic deployment of friendly units and identification of enemy threats via a 3D tactical grid.
- **Strategist Briefing:** The embedded **AI Strategist** synthesizes the deployment data, providing a high-level narrative briefing and initial tactical objectives.

### Step 3: Real-Time Tactical Command Loop
Once the simulation is live, the user enters the active operational phase:
- **Visual Intelligence:** A 3D map (Three.js/Fiber) displays unit positions, movement vectors, and combat encounters.
- **Natural Language Command:** Orders are issued via the **Secure Comms Console** (e.g., *"Move 1st Battalion to the bridge and hold for reinforce"*) instead of rigid menu clicks.
- **Simulation Authority:** The backend Python engine processes each command, calculating maneuver success, combat attrition, and objective control in real-time.

### Step 4: Post-Operation Debrief (AAR)
Upon mission completion, the system transitions to a **Final Mission Report** (After-Action Review):
- **Casualty & Efficiency Analysis:** Detailed metrics on personnel losses, armor damage, and ammunition expenditure.
- **Strategic Scoring:** The AI evaluates the commander's performance, providing a narrative critique of the tactics employed and suggesting improvements for future engagements.
