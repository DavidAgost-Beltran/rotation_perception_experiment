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



## 📂 Repository Structure

- `mlds_rotation_results.csv`: MLDS results for rotational distortions using Maloney’s R package.
- `mlds_gaussian_results.csv`: MLDS results for Gaussian noise distortions.
- `rmse_consecutive_results.csv`: Accumulated RMSE between consecutive distortion levels for each image.
- `responses.csv`: Normalized MLDS response values per image, transformation, and distortion level.
- `images/`: Natural images and their distorted versions used in the experiment.

### Notebooks/:


- [01_plot_mlds_curves.ipynb](notebooks/01_plot_mlds_curves.ipynb)  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j0rvjP5NI0G8R_0hbER4fYd7FcN0gfoy#scrollTo=eGdv7Q_EoWB5)  


  
  *Plot MLDS perceptual curves and visualize inter-image variability.*

- [02_Reaction_time_and_psychometric_curve_plots.ipynb.ipynb](notebooks/02_compare_rmse_and_perception.ipynb)  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mM3OcdC5-MD0HoFRLxlaFWBUFyVS79_q#scrollTo=Q451qSp-jP5u)  
  *Compare accumulated RMSE with perceptual scaling curves.*



> 💡 You can run all notebooks in Google Colab to visualize the figures used in the paper.



## Citation
If you use this code or analysis in your research, please cite:

Agost Beltrán, D. (2025). Perceptual Sensitivity to Rotational Differences in Natural Images. [AIPR2025].



