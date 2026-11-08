# Shear modulus classification from SLDV wave fields

Classifies the stiffness of tissue-mimicking phantoms from scanning laser Doppler
vibrometry (SLDV) wave data, using a CNN pre-trained on synthetic waves and
fine-tuned on measurements. Published: J. Mech. Behav. Biomed. Mater. 170 (2025) 107079.

## What it does
- Generates synthetic wave fields from an analytical model (Green's function)
- Pre-trains a CNN on synthetic data, fine-tunes on measured data
- Binary and five-class stiffness classification (84.4 % and 76.7 % accuracy on held-out data)

## Install
pip install -r requirements.txt

## Quick start (no private data needed)
python examples/run_synthetic_demo.py

## Data
Measured data cannot be shared (privacy and copyright). The synthetic generator
reproduces the input format; see docs/data_format.md.

## Tests
pytest tests/

## Limitations
Classification, not regression; homogeneous phantoms; sector-level split.

