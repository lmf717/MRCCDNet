**MRCCDNet: Optical-SAR Remote Sensing Image Change Detection via Cross-Modal Feature Interaction and Region-Consistency Guidance**

## Overview

MRCCDNet is a multimodal change detection network designed for heterogeneous optical-SAR remote sensing imagery.

The proposed framework integrates modality-specific feature enhancement, multi-scale cross-modal fusion, global cross-modal interaction based on state space models, and region-consistency-guided feature decoding.

## Network Architecture

The overall architecture of MRCCDNet is shown below.

<img width="6718" height="4200" alt="MRCCDNet Architecture" src="https://github.com/user-attachments/assets/d0a45d93-333a-48f7-9a27-eca3eda55805" />

## Datasets

Experiments are conducted on three heterogeneous optical-SAR change detection datasets:

- CAU-Flood
- Ombria
- GF-HCD

## Experimental Results

### Quantitative Results

#### CAU-Flood

| Method | Precision (%) | Recall (%) | F1 (%) | IoU (%) |
|---|---:|---:|---:|---:|
| SD-Mamba | 89.10±0.18 | 82.15±0.25 | 85.48±0.20 | 74.60±0.25 |
| CCDCNet | **93.28±0.18** | 89.95±0.30 | 91.60±0.15 | 84.52±0.25 |
| HeteCD | 89.40±0.22 | 90.05±0.18 | 89.72±0.15 | 81.37±0.20 |
| WaveHFG | 82.90±0.35 | 65.20±0.40 | 72.95±0.30 | 57.45±0.35 |
| MHCDNet | 91.84±0.14 | 90.73±0.40 | 91.28±0.14 | 83.96±0.23 |
| HFA-PANet | 91.47±0.54 | **91.90±0.28** | 91.69±0.27 | 84.65±0.45 |
| **MRCCDNet** | 92.70±0.14 | 91.84±0.07 | **92.27±0.07** | **85.65±0.11** |

#### Ombria

| Method | Precision (%) | Recall (%) | F1 (%) | IoU (%) |
|---|---:|---:|---:|---:|
| SD-Mamba | 71.60±0.60 | 80.10±0.55 | 75.80±0.45 | 61.05±0.55 |
| CCDCNet | **81.10±3.75** | 77.79±0.59 | 79.35±1.50 | 65.79±2.05 |
| HeteCD | 75.00±0.70 | 84.55±0.60 | 79.60±0.55 | 66.10±0.65 |
| WaveHFG | 76.20±0.65 | 80.35±0.70 | 78.20±0.60 | 64.25±0.70 |
| MHCDNet | 78.87±1.91 | 83.55±0.05 | 81.13±0.99 | 68.27±1.40 |
| HFA-PANet | 78.61±0.93 | 84.04±0.55 | 81.24±0.76 | 68.41±1.07 |
| **MRCCDNet** | 80.74±1.01 | **85.71±1.02** | **83.14±0.26** | **71.14±0.37** |

#### GF-HCD

| Method | Precision (%) | Recall (%) | F1 (%) | IoU (%) |
|---|---:|---:|---:|---:|
| SD-Mamba | 51.30±0.80 | 38.10±0.90 | 43.80±0.75 | 28.10±0.65 |
| CCDCNet | 71.04±6.39 | 53.44±9.22 | 60.89±8.37 | 44.29±8.69 |
| HeteCD | 66.30±0.90 | 68.70±0.80 | 67.45±0.70 | 50.90±0.75 |
| WaveHFG | 69.20±0.75 | 60.40±0.90 | 64.50±0.70 | 47.60±0.65 |
| MHCDNet | 75.80±1.10 | 62.50±0.40 | 68.50±0.60 | 52.10±0.70 |
| HFA-PANet | 78.19±3.12 | **71.16±1.13** | 74.45±0.80 | 59.30±1.02 |
| **MRCCDNet** | **80.98±1.97** | 69.92±1.99 | **74.99±0.39** | **59.99±0.49** |

### Qualitative Results

Qualitative comparison results on the three heterogeneous optical-SAR change detection datasets are shown below.

#### CAU-Flood

<img width="6893" height="4525" alt="CAU对比试验" src="https://github.com/user-attachments/assets/11a7aed3-9f86-42d0-9a53-a8d014a5a45e" />

#### Ombria

<img width="6905" height="4490" alt="Ombria对比试验" src="https://github.com/user-attachments/assets/01b0ff8c-e203-4af9-985f-40a688a59d69" />

#### GF-HCD

<img width="6923" height="4398" alt="GF-HCD对比试验" src="https://github.com/user-attachments/assets/ce6d52b1-c769-42c8-bf17-a3cb60c64d71" />

## Code

The source code will be made publicly available upon publication of the paper.
