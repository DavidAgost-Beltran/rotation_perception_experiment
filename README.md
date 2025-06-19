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
- `images/`: Natural images and their distorted versions used in the experiment.

### 📁 Notebooks/

- `plot_reaction_time_distributions.ipynb` · *Fit different statistical distributions (e.g., ex-Gaussian, log-normal) to the reaction time data.*
- `plot_psychometric_curve.ipynb` · *Visualize and fit a sigmoid to the left/right responses across distortion differences.*
- `plot_mlds_curves_by_image.ipynb` · *Show MLDS perceptual scales for each image and condition.*
- `plot_mean_curve_and_fit.ipynb` · *Average perceptual curves across images and evaluate linear vs. saturating fits.*
- `plot_rmse_scaled_curves.ipynb` · *Compare perceptual curves against accumulated RMSE for physically grounded interpretation.*

🧪 You can run the notebooks to reproduce figures related to reaction times and MLDS perceptual scaling. You can select different images and distortion types to explore how humans perceive rotation in natural scenes.




## Citation
If you use this code or analysis in your research, please cite:

Agost Beltrán, D. (2025). Perceptual Sensitivity to Rotational Differences in Natural Images. [AIPR2025].



