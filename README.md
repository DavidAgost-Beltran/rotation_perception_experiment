# Perceptual Sensitivity to Rotational Differences in Natural Images

This repository contains the code and data analyses for the paper **"Perceptual Sensitivity to Rotational Differences in Natural Images"**. The study investigates how humans perceive and discriminate angular differences in natural images using psychophysical experiments and perceptual scaling methods (MLDS).

You can execute the Jupyter notebooks to reproduce the figures shown in the paper, including reaction time distributions, psychometric bias curves, and MLDS perceptual scales for selected images.

## Overview

The project includes:

-Plot of MLDS perceptual scales.

-Fitting linear functions to the mean MLDS response curves.

-Analysis of psychometric response curves derived from human judgments of rotated images.

-Reaction time modeling using multiple distribution fits (Normal, Ex-Gaussian, Skew Normal, Log-Normal, etc.).

-Analysis of the relationship between reaction time and task difficulty.




## 📂 Repository Structure

- `mlds_rotation_results.csv`: MLDS results for rotational distortions using Maloney’s R package.
- `mlds_gaussian_results.csv`: MLDS results for Gaussian noise distortions using Maloney’s R package.
- `rmse_consecutive_results.csv`: Accumulated RMSE across distortion levels, summing differences between consecutive levels for each image.
- `responses.csv`: Perceptual responses from subjects participating in the experiment.
- `Notebooks/`: Jupyter notebooks to generate all figures and analyses.

  - [Plot_MLDS_curves.ipynb](Notebooks/Plot_MLDS_curves.ipynb)  
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j0rvjP5NI0G8R_0hbER4fYd7FcN0gfoy#scrollTo=eGdv7Q_EoWB5)  
    *Plot MLDS perceptual curves and visualize inter-image variability.*

  - [Reaction_Time_and_Psychometric_Curve_Analysis.ipynb](Notebooks/Reaction_Time_and_Psychometric_Curve_Analysis.ipynb)  
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mM3OcdC5-MD0HoFRLxlaFWBUFyVS79_q#scrollTo=Q451qSp-jP5u)  
    *Analyze reaction times and generate psychometric curves.*

> 💡 You can run all notebooks in Google Colab to reproduce the figures used in the paper.




## Citation
If you use this code or analysis in your research, please cite:

Agost Beltrán, D. (2025). Perceptual Sensitivity to Rotational Differences in Natural Images. [AIPR2025].



