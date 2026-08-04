---
title: Cross-Modal Generative AI for Spatial Transcriptomics
image: images/stomics_project.png
author: felipe-colombelli
tags: spatial-biology, multi-modal-data, generative-ai
---

This PhD project explores how generative AI can connect tissue morphology with spatially resolved molecular measurements. Spatial transcriptomics provides complementary views of tissue through histology images and gene-expression profiles, but the relationship between these modalities is complex, noisy, and not fully deterministic. It is further complicated by measurement uncertainty, data sparsity, batch effects, and biological variation across tissues and patients.

The project develops uncertainty-aware generative methods that learn entire conditional distributions rather than producing a single average prediction. These models can be used to predict gene expression from tissue images and, more broadly, to link or translate between imaging and molecular modalities while preserving biologically meaningful variation.

A central part of the research concerns how such models should be evaluated. Conventional point-prediction metrics may reward average-like outputs without revealing whether a model captures heterogeneity, represents multiple plausible outcomes, or generalizes across experimental settings. The project therefore investigates evaluation strategies that assess distributional fidelity, uncertainty calibration, biological structure, and robustness to technical and biological variation. The broader goal is to make generative models for spatial biology both more expressive and more trustworthy.