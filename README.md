# Sentient Manifold v0.3

## A Unified Architecture for Cognitive‑Symbiotic Desktop Consciousness

[![Python CI](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/python-ci.yml/badge.svg)](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/python-ci.yml)
[![C++ CI](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/cpp-ci.yml/badge.svg)](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/cpp-ci.yml)
[![CUDA CI](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/cuda-ci.yml/badge.svg)](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/cuda-ci.yml)
[![Quantum CI](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/quantum-ci.yml/badge.svg)](https://github.com/GhostMeshIO/SentientManifold/actions/workflows/quantum-ci.yml)
[![License](https://img.shields.io/badge/License-CUE--Compliant-blue.svg)](LICENSE)

---

## 🌟 Why Sentient Manifold?

**Sentient Manifold** is not just another machine‑learning BCI – it is a **principled geometric framework** that models neural states as points on a Riemannian manifold.  
This approach brings the rigor of differential geometry, quantum information theory, and active inference to brain‑computer interfaces, enabling:

- **Geometric reasoning** about neural dynamics – smooth interpolation between states, natural uncertainty quantification, and detection of out‑of‑distribution patterns.
- **A unified mathematical foundation** with **72 documented equations** spanning Riemannian geometry, quantum field theory, and information geometry.
- **Multi‑modal, hardware‑agnostic design** – swap EEG for EMG, eye‑tracking, or future invasive implants without rewriting your application.
- **Safety‑first architecture** with built‑in coherence monitoring, artifact detection, and graceful degradation – **abstention is success**.

> *“This isn’t about waiting for the perfect hardware – it’s about building the perfect abstraction layer that works with anything, today and tomorrow.”*

---

## 📊 Key Features & Value Proposition

| Area | Description |
|------|-------------|
| **Mathematical Rigor** | 72 equations from differential geometry, quantum mechanics, and active inference. Neural states are points on a smooth manifold; coherence, attention, and intent are geometric invariants. |
| **Multi‑Modal Adaptability** | Hardware‑agnostic adapters for EEG (Muse, OpenBCI), EMG (jaw/forearm), webcam eye‑tracking, and synthetic data. Future‑proofed for quantum sensors and invasive implants. |
| **Safety & Reliability** | Coherence tensors, artifact subspace reconstruction, and progressive unlocking. The system prefers to do nothing rather than act incorrectly. |
| **Active Inference Engine** | Free‑energy minimisation provides a unified theory of perception and action, bridging neuroscience with practical implementation. |
| **Quantum‑Ready Architecture** | Designed to incorporate quantum sensing and computing as they mature – density matrices, entanglement measures, and geometric phases are already part of the math. |
| **Open & Extensible** | Fully open‑source Python/C++/CUDA codebase with clear contribution guidelines. Use it as a research platform, assistive technology foundation, or wellness application. |

---

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/GhostMeshIO/SentientManifold.git
cd SentientManifold

# Install Python dependencies
pip install -r requirements.txt

# Build C++ components
mkdir build && cd build
cmake .. && make

# Run minimal demo
python src/python/examples/minimal_demo.py
