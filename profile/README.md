<div align="center">

<!-- HERO BANNER -->
<img src="https://raw.githubusercontent.com/RobotFlow-Labs/.github/main/assets/hero-banner.png" alt="ROBOTFLOW LABS — MISSION CONTROL" width="100%">

<br>

### THE ROBOTICS INTELLIGENCE COMPILER

*Apple Silicon-native robotics infrastructure. ANIMA agent suite.*
*39 modules. 3 pillars. Growing weekly.*
*Built by one person using AI agents. Imagine what a funded team does.*

<br>

[![Website](https://img.shields.io/badge/WEBSITE-robotflowlabs.com-FF3B00?style=flat-square&labelColor=050505)](https://robotflowlabs.com)
[![Status](https://img.shields.io/badge/SYSTEM-ONLINE-FF3B00?style=flat-square&labelColor=050505)](https://github.com/RobotFlow-Labs)
[![Modules](https://img.shields.io/badge/MODULES-39-FF3B00?style=flat-square&labelColor=050505)](https://github.com/RobotFlow-Labs)
[![HQ](https://img.shields.io/badge/HQ-HONG_KONG-FF3B00?style=flat-square&labelColor=050505)](https://robotflowlabs.com)

---

</div>

## ▌ THREE PILLARS

### PILLAR 01 — MLX INFRASTRUCTURE (17 PUBLIC)

Apple Silicon-native robotics tools. Porting the CUDA-only stack to MLX.

| MODULE | FUNCTION | TESTS | STATUS |
|--------|----------|-------|--------|
| [`LeRobot-mlx`](https://github.com/RobotFlow-Labs/LeRobot-mlx) | HuggingFace LeRobot on Apple Silicon — 10 policies | 739+ | `PUBLIC` |
| [`diffusion-policy-mlx`](https://github.com/RobotFlow-Labs/diffusion-policy-mlx) | RSS 2023 Best Paper — 6 variants | 472 | `PUBLIC` |
| [`gsplat-mlx`](https://github.com/RobotFlow-Labs/gsplat-mlx) | 3D Gaussian Splatting native MLX | 405 | `PUBLIC` |
| [`realsense-mlx`](https://github.com/RobotFlow-Labs/realsense-mlx) | 330x faster depth camera processing | 1048 | `PUBLIC` |
| [`curobo-mlx`](https://github.com/RobotFlow-Labs/curobo-mlx) | NVIDIA cuRobo motion planning on Mac | — | `PUBLIC` |
| [`open3d-mlx`](https://github.com/RobotFlow-Labs/open3d-mlx) | 3D perception: ICP, TSDF, raycasting | — | `PUBLIC` |
| [`container-toolkit-mlx`](https://github.com/RobotFlow-Labs/container-toolkit-mlx) | GPU MLX inference containers | — | `PUBLIC` |
| [`IsaacLab-mlx`](https://github.com/RobotFlow-Labs/IsaacLab-mlx) | NVIDIA Isaac Lab on Apple Silicon | — | `PUBLIC` |
| [`IsaacSim-mlx`](https://github.com/RobotFlow-Labs/IsaacSim-mlx) | NVIDIA Isaac Sim on Apple Silicon | — | `PUBLIC` |
| [`Mujoco-mlx`](https://github.com/RobotFlow-Labs/Mujoco-mlx) | MuJoCo physics on Apple Silicon | — | `PUBLIC` |
| [`Triton-mlx`](https://github.com/RobotFlow-Labs/Triton-mlx) | OpenAI Triton on Apple Silicon | — | `PUBLIC` |
| [`unitree_sdk2_mlx`](https://github.com/RobotFlow-Labs/unitree_sdk2_mlx) | Unitree LiDAR SDK for Mac | — | `PUBLIC` |

### PILLAR 02 — ANIMA SUITE (RESTRICTED)

**A**gentic **N**eural **I**ntegration for **M**odular **A**utonomy — The Intelligence Compiler.

```
┌─────────────────────────────────────────────────────────────┐
│ AGENT LAYER .... Understands intent, discovers hardware     │
│ 3 GATES ........ Schema ✓ · Semantic ✓ · Resolution ✓      │
│ COMPILER ....... Resolves modules, generates pipeline       │
│ SIMULATION ..... MuJoCo dry-run, agent watches + approves   │
│ RUNTIME ........ 30fps perception, behavior tree, safety    │
└─────────────────────────────────────────────────────────────┘
```

| MODULE | TYPE | STATUS |
|--------|------|--------|
| `AZOTH` | Open-vocab detection | `PRODUCTION` |
| `CHRONOS` | Depth estimation | `PRODUCTION` |
| `MONAD` | Segmentation + tracking | `BETA` |
| `NEXUS` | 3D mapping | `PRODUCTION` |
| `PRISM` | SLAM | `PRODUCTION` |
| `LOCI` | Place recognition | `BETA` |
| `ATOMOS` | Vision-Language-Action (1-bit BitVLA) | `PRODUCTION` |
| `PYGMALION` | VLA + behavior shaping | `PRODUCTION` |
| `HERMES` | Navigation + message bus | `PRODUCTION` |
| `DAEDALUS` | Manipulation | `BETA` |
| `SIBYL` | World model | `PRODUCTION` |
| `TITAN` | Reinforcement learning | `BETA` |
| `AGORA` | Fleet management | `BETA` |
| `ELYSIUM` | Simulation | `BETA` |
| `FORGE` | Deployment | `BETA` |

> 8 Production · 13 Beta · 18 Scaffold · **39 Total**

### PILLAR 03 — FRONTIER RESEARCH (RESTRICTED)

| PROJECT | DOMAIN |
|---------|--------|
| `ATOMOS` | 1-bit VLA — 3.35x compression |
| `CHIRON` | VLA-to-physical manipulator control (Franka, KUKA, Kinova) |
| `PETRA` | Depth foundation model — DINOv2 backbone |
| `PANOPTES` | Zero-shot metric depth from any camera |
| `GENESIS` | One-shot manipulation via 3D Gaussian Splatting |

## ▌ SYSTEM TELEMETRY

```
┌─────────────────────────────────────────────────────────────┐
│ TOTAL MODULES .............. 39 ACTIVE                      │
│ PUBLIC REPOS ............... 17 (MLX INFRASTRUCTURE)        │
│ ANIMA AGENTS ............... 13 (RESTRICTED)                │
│ RESEARCH PROJECTS .......... 11 (RESTRICTED)                │
│ TESTS WRITTEN .............. 3000+                          │
│ RUNTIME TARGET ............. APPLE SILICON M-SERIES         │
│ ROS2 BRIDGE LATENCY ........ < 1MS                          │
│ BITVLA COMPRESSION ......... 3.35X                          │
│ GLOBAL OPERATIONS .......... HK // USA // GLOBAL            │
└─────────────────────────────────────────────────────────────┘
```

## ▌ ENTRY POINTS

| DESTINATION | LINK |
|-------------|------|
| `WEBSITE` | [robotflowlabs.com](https://robotflowlabs.com) |
| `MISSION CONTROL` | [Dashboard](https://robotflow-labs.github.io) |
| `DATA ACCESS` | [Request Partnership](https://robotflowlabs.com/#contact) |
| `COLLABORATION` | [Submit Intake](https://github.com/RobotFlow-Labs/.github/issues/new?template=collab-intake.yml) |

## ▌ CONTRIBUTION PROTOCOL

```
INTAKE CHANNELS:
├── Bug Signal ............ Issues → bug-signal template
├── Feature Request ....... Issues → feature-request template
├── Dataset Request ....... Issues → dataset-request template
└── Collaboration ......... Issues → collab-intake template
```

---

<div align="center">

`ROBOTFLOW LABS` // `HK HEADQUARTERS` // `GLOBAL_NET`

**REINDUSTRIALIZING INTELLIGENCE**

*The soul of every robot.*

[robotflowlabs.com](https://robotflowlabs.com) · [Contact](https://robotflowlabs.com/#contact)

</div>
