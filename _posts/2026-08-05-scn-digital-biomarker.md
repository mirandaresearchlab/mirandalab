---
title: Self-Supervised Foundation Models for Skin Barrier Assessment
image: scn_foundation_models_3
author: jen-hung-wang
tags: digital-dermatology, self-supervised-learning, foundation-models
---

This project investigates stratum corneum nanotexture (SCN), the nanoscale topography of corneocyte surfaces, as a non-invasive digital biomarker of skin barrier integrity. We assembled a multicohort dataset comprising 24,968 atomic force microscopy images from 1,251 tape-strip samples collected from 651 participants across Denmark, Taiwan, and the Netherlands.

Using masked autoencoders and DINOv2, we developed self-supervised SCN foundation models that learn transferable representations from unlabelled images. These models were adapted to diverse downstream tasks, including atopic dermatitis severity, contact dermatitis patch-test reactions, ultraviolet radiation exposure, demographic characteristics, geographic origin, and anatomical site classification.

The results show that SCN representations capture clinically and biologically meaningful variation, with the strongest performance observed for atopic dermatitis severity and occupational ultraviolet radiation exposure. Reduced performance in cross-site transfer experiments also revealed substantial site-related domain shift, underscoring the need for domain adaptation and prospective validation before clinical deployment. The broader goal is to establish scalable, objective methods for skin barrier assessment, disease monitoring, and digital biomarker discovery.
