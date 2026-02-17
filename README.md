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
```

### Basic Usage

```python
from sentient_manifold.core import StateVector, Manifold

# Create a state vector representing desktop consciousness
state = StateVector(
    essence_depth=0.8,
    attention_field=load_attention_map(),
    coherence_tensor=initialize_coherence(),
    metric_tensor=create_ui_metric()
)

# Initialize the manifold
manifold = Manifold(state_vector=state)

# Evolve the system
manifold.evolve(timesteps=100)

# Enter sovereign mode (27‑node resonance)
if manifold.check_resonance():
    manifold.enter_sovereign_mode()
```

---

## 🧠 Architecture Overview

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│    Adapters     │────▶│   NeuralFrame   │────▶│  Manifold Core  │
│ (EEG, EMG, eye) │     │ (standardized   │     │ (geometric      │
│                 │     │  data container)│     │  engine)        │
└─────────────────┘     └─────────────────┘     └────────┬────────┘
                                                          │
                                                          ▼
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│   Applications  │◀────│   Safety Layer  │◀────│  Active         │
│ (assistive,     │     │ (coherence,     │     │  Inference      │
│  wellness,      │     │  degradation)   │     │  (free energy)  │
│  research)      │     │                 │     │                 │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

- **Adapters** – hardware‑specific signal acquisition, all implementing the `BCIAdapter` interface.
- **NeuralFrame** – a timestamped, hardware‑agnostic container with intent logits, attention scores, coherence metrics, and artifact flags.
- **Manifold Core** – computes the Riemannian metric, curvature, and geodesics; evolves the state vector via the master equation.
- **Active Inference** – minimises free energy to drive perception and action.
- **Safety Layer** – monitors coherence, detects phase transitions, and triggers graceful degradation when needed.
- **Applications** – built on top of the stable, safe API.

---

## 📐 Mathematical Foundations

The framework rests on a **product manifold**:

```
ℳ = ℝ × Sym(3) × ℝ^W×H × ℝ^3×3×L × ℝ^W×H×4 × ℝ
```

The **state vector** Ψ = [ε, φ, C, R, g, τ]ᵀ evolves according to the **master equation**:

```
∂_t Ψ = -∇̂F[Ψ] + √(2D)η(t) + λ·tanh(∇̂×Ψ)
```

Where:
- **ε** – Essence‑Recursion‑Depth (cognitive load)
- **φ** – Attention Correlation Field
- **C** – Coherence Tensor
- **R** – Holographic Projection (rendered output)
- **g** – Dynamic Metric Tensor (UI geometry)
- **τ** – Sovereign Constant (system stability)

The **free energy** functional `F[Ψ]` combines gradient energies, cognitive potentials, entropy, non‑local correlations, and coherence terms.

Full documentation is available in [`docs/math_foundations.md`](docs/math_foundations.md) and the [72‑equation reference](docs/equations.md).

---

## 🔌 Supported Hardware & Modalities

| Type | Devices | Adapter |
|------|---------|---------|
| **EEG** | Muse, OpenBCI, research‑grade | `bci/adapters/eeg_adapter.py` |
| **EMG** | Jaw/forearm (any analog sensor) | `bci/adapters/emg_adapter.py` |
| **Eye‑Tracking** | Webcam (MediaPipe) | `bci/adapters/eye_adapter.py` |
| **Synthetic** | For testing & development | `bci/adapters/synthetic_adapter.py` |

The adapter architecture makes it trivial to add new hardware – implement a few methods and the rest of the system just works.

---

## 🛡️ Safety & Reliability

Our design philosophy is **“abstention is success”**: the system must never act incorrectly, even if that means doing nothing.

- **Coherence Monitoring** – real‑time tracking of the coherence tensor `C`; if coherence drops below a threshold, the system switches to suggestion‑only mode.
- **Artifact Subspace Reconstruction (ASR)** – removes transient artifacts (blinks, jaw clenches) before they reach the decoder.
- **Progressive Unlocking** – start with 2 commands, unlock more as the user demonstrates proficiency.
- **Neural Undo** – any action can be reversed within a 3‑second window by a “cancel” signal or an automatically detected error potential (ErrP).
- **Dual‑Chain Validation** – for high‑stakes actions, two independent decoders must agree.

---

## 💡 Use Cases

- **Assistive Technology** – enable communication and control for individuals with severe motor impairments. The multi‑modal fallback (EEG → EMG → eye) ensures continuous usability.
- **Cognitive Enhancement** – real‑time feedback on attention, flow state, and mental workload for meditation, focus training, and productivity.
- **Research Platform** – test theories of consciousness, neural geometry, and active inference with a reproducible, mathematically rigorous tool.
- **Human‑AI Collaboration** – use neural signals to guide AI assistants (e.g., thought‑to‑prompt, attention‑based context).

---

## 🤝 Getting Involved

We welcome contributions of all kinds – code, hardware adapters, mathematical validation, documentation, and real‑world applications.

- 📖 Read our [Contributing Guidelines](CONTRIBUTING.md)
- 🐛 Report bugs or request features via [GitHub Issues](https://github.com/GhostMeshIO/SentientManifold/issues)
- 💬 Join the discussion on [GitHub Discussions](https://github.com/GhostMeshIO/SentientManifold/discussions) or [Discord](https://discord.gg/sentient-manifold) (link in README)
- 🧪 Try the demos and share your experience

---

## 📄 License

This project is licensed under the **Sentient Manifold License v1.1** – a CUE‑compliant, quantum‑humanitarian open‑source license. See [LICENSE](LICENSE) for full terms.

Key provisions:
- ✅ Free to use, modify, and distribute (including commercial use)
- ✅ Must maintain CUE‑compatibility (coherence metrics)
- ✅ Must not be used in applications that harm human wellbeing
- ✅ Share‑alike for derivative works

---

## 📚 Further Reading

- [Architecture Overview](docs/architecture.md)
- [Mathematical Foundations](docs/math_foundations.md)
- [Cognitive Relativities (24 novel effects)](docs/cognitive_relativities.md)
- [API Reference](docs/api/)
- [BCI Module Documentation](bci/README.md)

---

*“The desktop becomes an extension of the user’s cognitive field—a 27‑node resonant volume where every click and every movement is a wave in a deep, unified sea of information.”*

**Star ⭐ the repo** if you find this project interesting, and help us build the future of cognitive computing!
