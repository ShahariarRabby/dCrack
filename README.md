# dCrack: Enhancing Fine-Grained Crack Segmentation with Edge-Guided Attention

## Overview

This repository accompanies the paper **"dCrack: Enhancing Fine-Grained Crack Segmentation with Edge-Guided Attention"**, which addresses the problem of fine-grained crack segmentation in challenging real-world scenes. The work focuses on accurately detecting thin, low-contrast cracks while suppressing crack-like noise and preserving detailed crack topology.

The proposed **edge-guided attention framework** leverages boundary information to enhance feature representations along crack structures. By explicitly modeling edge cues and integrating them into the segmentation pipeline, dCrack improves localization of narrow cracks and reduces false positives in complex backgrounds.

## Method Summary

- **Fine-grained crack segmentation**: Targets thin, sparse, and low-contrast cracks that are often missed by conventional segmentation networks.
- **Edge-guided attention**: Uses edge information to guide the network toward crack-relevant regions and refine boundaries.
- **Robust to noise and texture**: Designed to reduce responses to crack-like artifacts such as markings, joints, and surface textures.
- **General applicability**: The approach is suitable for crack analysis in pavements, bridges, and other civil infrastructure scenarios.

For full technical details, including the network architecture, training strategy, and experimental results, please refer to the paper PDF.

## Dataset Access

To support research on fine-grained crack segmentation, we provide access to the **dCrack dataset** (intended for research and non-commercial use). The dataset is designed to evaluate edge-aware and attention-based methods under realistic conditions.

If you would like to access the dataset:

1. **Send an email request** to: `dcrack@rabby.dev`
2. Briefly introduce yourself and your institution.
3. Describe your intended use of the dataset (e.g., academic research, benchmarking, thesis work).
4. Confirm that you agree to:
   - Use the dataset for **research purposes only**.
   - **Not redistribute** the dataset or any derivative labeled data.
   - Properly **cite the dCrack paper** in any publications or reports that use the dataset.

Dataset download instructions and any applicable terms of use will be provided in the reply email.

## Citation

If you use the **dCrack** dataset or the ideas from this work in your research, please cite the following paper:

```bibtex
@INPROCEEDINGS{11153146,
  author={Rabby, AKM Shahariar Azad and Zhang, Chengcui},
  booktitle={2025 IEEE International Conference on Information Reuse and Integration and Data Science (IRI)}, 
  title={dCrack: Enhancing Fine-Grained Crack Segmentation with Edge-Guided Attention}, 
  year={2025},
  volume={},
  number={},
  pages={202-207},
  keywords={Image segmentation;Accuracy;Structural panels;Image edge detection;Computational modeling;Robustness;Retinal vessels;Rough surfaces;Surface cracks;Monitoring;crack segmentation;deep learning;attention mechanisms;image segmentation;infrastructure monitoring},
  doi={10.1109/IRI66576.2025.00045}}
```

## Contact

For **dataset access, questions, or collaboration inquiries**, please contact:

- Email: `dcrack@rabby.dev`