# Contributing to Sentient Manifold

Thank you for your interest in contributing to the Sentient Manifold project! This document provides guidelines and instructions for contributing.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Getting Started

### Prerequisites
- Python 3.9+
- Git
- CUDA Toolkit 12.1+ (for GPU acceleration)
- Docker (optional, for containerized development)

### Development Setup
```bash
# 1. Fork and clone the repository
git clone https://github.com/YOUR_USERNAME/SentientManifold.git
cd SentientManifold

# 2. Set up development environment
pip install -r requirements.txt
pip install -r requirements-dev.txt

# 3. Install in development mode
pip install -e .

# 4. Run tests to verify setup
pytest tests/python/ -v
