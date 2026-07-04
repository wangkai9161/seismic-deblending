# Seismic Deblending

Self-supervised deep learning experiments for seismic deblending and signal restoration.

This repository is planned as a research-oriented project for organizing algorithms, experiments, notes, and reproducible workflows around seismic blended-data separation.

## Focus

- Self-supervised learning for seismic deblending
- DnCNN, U-Net, blind-spot networks, and Transformer-based separation methods
- Signal restoration under complex noise and limited labeled data
- Experiment comparison, metric evaluation, and visualization

## Repository Structure

```text
seismic-deblending/
├── README.md
├── requirements.txt
├── configs/
├── docs/
├── notebooks/
├── scripts/
├── src/
│   ├── datasets/
│   ├── models/
│   └── utils/
└── results/
    └── figures/
```

## Dataset

Large seismic datasets are not stored directly in this repository. Full datasets should be hosted externally, such as on institutional storage, cloud object storage, Zenodo, Hugging Face Datasets, or another data platform.

Small sample data may be added later for demonstration and quick tests.

## Roadmap

- Add data loading utilities
- Add baseline DnCNN and U-Net models
- Add self-supervised training scripts
- Add evaluation metrics and visualization examples
- Add experiment notes and reproducibility instructions
