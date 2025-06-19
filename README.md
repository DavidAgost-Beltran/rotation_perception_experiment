# Perceptual Sensitivity to Rotational Differences in Natural Images

This repository contains the code and data analyses for the paper **"Perceptual Sensitivity to Rotational Differences in Natural Images"**. The study investigates how humans perceive and discriminate angular differences in natural images using psychophysical experiments and perceptual scaling methods (MLDS).

You can execute the Jupyter notebooks to reproduce the figures shown in the paper, including reaction time distributions, psychometric bias curves, and MLDS perceptual scales for selected images.

## Overview

The project includes:

- Analysis of psychometric response curves derived from human judgments of rotated images.
- Computation of perceptual scales and their relation to internal noise (σ).
- Comparison between rotation and Gaussian noise using RMSE as a common physical distortion metric.
- Reaction time modeling using multiple distribution fits (Normal, Ex-Gaussian, Skew Normal, Log-Normal, etc.).
- Visualization tools for generating all plots included in the paper.

## Folder Structure

📁 notebooks/
├── mlds_curves_analysis.ipynb
├── rmse_comparison.ipynb
├── reaction_times_fitting.ipynb
└── psychometric_bias_curve.ipynb
📁 data/
📁 figures/
📄 requirements.txt
📄 README.md

csharp
Copiar código

## Dependencies

Install required libraries using:

```bash
pip install -r requirements.txt
Citation
If you use this code or analysis in your research, please cite:

Agost Beltrán, D. (2025). Perceptual Sensitivity to Rotational Differences in Natural Images. [AIPR2025].



