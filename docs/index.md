---
layout: default
title: Home
nav_order: 1
---

# Flyby-Denial Presents: Protein Comparison Pipeline

![Artemis II Crew](https://www.nasa.gov/wp-content/uploads/2023/04/artemis-ii-crew-photo-nhq202304030010.jpg)

A bioinformatics pipeline built in Google Colab for analyzing and comparing protein sequences. Designed to be straightforward to use and modify, making it accessible for students and researchers exploring protein analysis for the first time.

The pipeline accepts protein sequences either as uploaded FASTA files or as pasted input, then computes physicochemical properties, pairwise sequence similarity, and clustering visualizations to reveal how your proteins relate to one another.

---

## Pipeline Overview

Given a set of protein sequences, the pipeline will:

- **Calculate physicochemical properties** — sequence length, molecular weight, amino acid composition, and isoelectric point (pI) for each protein
- **Perform pairwise sequence comparisons** — align every protein against every other and generate a similarity score table
- **Visualize relationships** — cluster proteins by physicochemical features, sequence similarity, or both, displayed as dendrograms

---

## Try the Workflow Yourself

[Open on GitHub — Flyby-Denial](https://github.com/luquelab/Flyby-Denial)
