# Hologram Reconstruction Using Physics Consistency

Reproduction of *"Self-supervised learning of hologram reconstruction using physics consistency"* paper results.

## Setup

This repository uses a [forked version](https://github.com/ViktorooReps/GedankenNet-mps) that adds MPS support to the [original implementation](https://github.com/PORPHURA/GedankenNet).

To initialize the forked submodule:

```bash
git submodule init
git submodule update --recursive --remote
```

### Hardware

* **Machine**: Apple MacBook Air (M2, 2022)
* **Memory**: 16 GB RAM
* See `hardware_information.json` for full specs.

### Python Environment

1. Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:

   * **Exact versions** (for exact reproduction):

     ```bash
     pip install -r requirements.txt
     ```
   * **General/latest**:

     ```bash
     pip install -r requirements-general.txt
     ```
