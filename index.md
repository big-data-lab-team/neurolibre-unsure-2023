---
title: "Abstract"
date: 2024-12-12
---

This paper investigates the numerical uncertainty of Convolutional Neural Networks (CNNs) inference for structural brain MRI analysis. It applies Random Rounding---a stochastic arithmetic technique---to CNN models employed in non-linear registration (SynthMorph) and whole-brain segmentation (FastSurfer), and compares the resulting numerical uncertainty to the one measured in a reference image-processing pipeline (FreeSurfer recon-all). Results obtained on 32 representative subjects show that CNN predictions are substantially more accurate numerically than traditional image-processing results (non-linear registration: 19 vs 13 significant bits on average; whole-brain segmentation: 0.99 vs 0.92 Sørensen-Dice score on average), which suggests a better reproducibility of CNN results across execution environments.