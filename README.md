# Spatial-Mini
Spatial Transcriptomic Mini Project

This repository contains all the steps and intermediate attempts I explored throughout the analysis process. Errors, redundant lines, and iterative code blocks are a natural part of my learning, experimentation, and implementation workflow.

Therefore, this repository should not be considered a production-ready or directly reusable pipeline. The primary motivation is to extract biologically meaningful insights from the data and to transparently document the analytical reasoning behind each step.

All analyses were conducted entirely on a personal local computing environment. For this reason, a relatively small dataset was intentionally selected to keep computational requirements manageable.

## Data download
- GEO accession: **GSE274103**
- Platform: 10x Genomics Visium
- Tissue: Treatment-naive PDAC
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE274103

## Analysis overview
1. Visium data loading and spatial coordinate reconstruction
2. Quality control, normalization, and clustering (Scanpy)
3. Spatial neighbor graph construction (Squidpy)
4. Neighborhood enrichment analysis
5. Marker gene identification and biological interpretation

## Key findings
- Identification of a spatially coherent immune–epithelial interaction hub
- Enrichment of plasma cell–rich immune niches adjacent to CAF-dominated stroma
- Structured spatial organization of tumor, immune, and stromal compartments




