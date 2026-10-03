# MRCCDNet

MRCCDNet: Optical-SAR Remote Sensing Image Change Detection via Cross-Modal Feature Interaction and Region-Consistency Guidance.

## Overview

MRCCDNet is a multimodal change detection network designed for heterogeneous optical-SAR remote sensing imagery.

The proposed framework integrates modality-specific feature enhancement, multi-scale cross-modal fusion, global cross-modal interaction based on state space models, and region-consistency-guided feature decoding.

## Network Architecture

The overall architecture of MRCCDNet is shown below.
<img width="6718" height="4200" alt="MRCCDNet" src="https://github.com/user-attachments/assets/d0a45d93-333a-48f7-9a27-eca3eda55805" />

## Datasets

Experiments are conducted on three heterogeneous optical-SAR change detection datasets:

- CAU-Flood
- Ombria
- GF-HCD

## Experimental Results

Qualitative comparison results of MRCCDNet on heterogeneous optical-SAR change detection datasets are shown below.
## Quantitative Results

### CAU-Flood

| Method | OA (%) | Precision (%) | Recall (%) | F1 (%) | IoU (%) |
|---|---:|---:|---:|---:|---:|
| SD-Mamba [29] | 98.01±0.03 | 89.10±0.18 | 82.15±0.25 | 85.48±0.20 | 74.60±0.25 |
| CCDCNet [17] | 98.81±0.03 | **93.28±0.18** | 89.95±0.30 | 91.60±0.15 | 84.52±0.25 |
| HeteCD [23] | 98.55±0.04 | 89.40±0.22 | 90.05±0.18 | 89.72±0.15 | 81.37±0.20 |
| WaveHFG [33] | 96.57±0.06 | 82.90±0.35 | 65.20±0.40 | 72.95±0.30 | 57.45±0.35 |
| MHCDNet [22] | 98.77±0.02 | 91.84±0.14 | 90.73±0.40 | 91.28±0.14 | 83.96±0.23 |
| HFA-PANet [14] | 98.81±0.05 | 91.47±0.54 | **91.90±0.28** | 91.69±0.27 | 84.65±0.45 |
| **MRCCDNet** | **98.90±0.01** | 92.70±0.14 | 91.84±0.07 | **92.27±0.07** | **85.65±0.11** |

### Ombria

| Method | OA (%) | Precision (%) | Recall (%) | F1 (%) | IoU (%) |
|---|---:|---:|---:|---:|---:|
| SD-Mamba [29] | 84.90±0.20 | 71.60±0.60 | 80.10±0.55 | 75.80±0.45 | 61.05±0.55 |
| CCDCNet [17] | 87.86±1.19 | **81.10±3.75** | 77.79±0.59 | 79.35±1.50 | 65.79±2.05 |
| HeteCD [23] | 86.90±0.25 | 75.00±0.70 | 84.55±0.60 | 79.60±0.55 | 66.10±0.65 |
| WaveHFG [33] | 86.55±0.30 | 76.20±0.65 | 80.35±0.70 | 78.20±0.60 | 64.25±0.70 |
| MHCDNet [22] | 88.37±0.76 | 78.87±1.91 | 83.55±0.05 | 81.13±0.99 | 68.27±1.40 |
| HFA-PANet [14] | 88.38±0.50 | 78.61±0.93 | 84.04±0.55 | 81.24±0.76 | 68.41±1.07 |
| **MRCCDNet** | **89.59±0.22** | 80.74±1.01 | **85.71±1.02** | **83.14±0.26** | **71.14±0.37** |

### GF-HCD

| Method | OA (%) | Precision (%) | Recall (%) | F1 (%) | IoU (%) |
|---|---:|---:|---:|---:|---:|
| SD-Mamba [29] | 95.00±0.15 | 51.30±0.80 | 38.10±0.90 | 43.80±0.75 | 28.10±0.65 |
| CCDCNet [17] | 96.52±0.62 | 71.04±6.39 | 53.44±9.22 | 60.89±8.37 | 44.29±8.69 |
| HeteCD [23] | 96.60±0.20 | 66.30±0.90 | 68.70±0.80 | 67.45±0.70 | 50.90±0.75 |
| WaveHFG [33] | 96.60±0.18 | 69.20±0.75 | 60.40±0.90 | 64.50±0.70 | 47.60±0.65 |
| MHCDNet [22] | 97.05±0.30 | 75.80±1.10 | 62.50±0.40 | 68.50±0.60 | 52.10±0.70 |
| HFA-PANet [14] | 97.49±0.14 | 78.19±3.12 | **71.16±1.13** | 74.45±0.80 | 59.30±1.02 |
| **MRCCDNet** | **97.60±0.03** | **80.98±1.97** | 69.92±1.99 | **74.99±0.39** | **59.99±0.49** |

## Code

The source code will be made publicly available upon publication of the paper.
