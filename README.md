# Indonesian Peranakan Etawa Goat WGS Selection Analysis

This repository contains curated scripts used for whole-genome sequencing (WGS) data analysis of Indonesian Peranakan Etawa (PE) goats, focusing on population structure, runs of homozygosity (ROH), weighted FST, integrative ROH–FST overlap, functional annotation, and final visualization.

## Study overview

Peranakan Etawa (PE) goats represent an important Indonesian goat genetic resource. This repository was organized to support the reproducibility of analyses used in a WGS-based study of genomic differentiation and selection signatures in Indonesian PE goats.

The curated workflow includes:
- reference indexing and read mapping
- variant calling and filtering
- Beagle imputation
- population structure analysis (PCA and ADMIXTURE)
- ROH analysis
- weighted FST analysis
- integrative ROH–FST analysis
- functional annotation
- final visualization, including Circos plots

## Repository structure

```text
scripts/
  01_preprocessing/
  02_variant_dataset_construction/
  03_population_structure/
  04_roh/
  05_fst/
  06_integrative_selection/
  07_functional_annotation/
  08_visualization/

config/
environment/
metadata/
docs/
example_outputs/
