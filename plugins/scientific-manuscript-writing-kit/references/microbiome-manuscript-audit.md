# Microbiome Manuscript Audit

## Common microbiome manuscript problems

- Research question is too broad.
- Study design cannot support causal claims.
- Results repeat figures without explaining patterns.
- Discussion overstates taxonomy, function, AMG, or host prediction results.
- Methods omit software versions, database details, or filtering thresholds.

## Compositionality reporting

- State whether count, relative abundance, transformed, or distance data were analyzed.
- Explain normalization or transformation choices.
- Avoid interpreting relative abundance as absolute abundance unless supported.

## Diversity analysis reporting

- Report alpha diversity metrics and model/test design.
- Report beta diversity distance metrics.
- Describe ordination methods and sample grouping variables.

## PERMANOVA and dispersion caveats

- Report distance metric and permutation design.
- Check and report group dispersion where relevant.
- Avoid interpreting PERMANOVA as location-only if dispersion differs strongly.

## Differential abundance reporting

- Report method, filtering, normalization, covariates, effect direction, effect size, and multiple testing correction.
- Avoid p-value-only reporting.

## Viral/phage host prediction caveats

- Distinguish predicted host from experimentally validated infection.
- Report evidence type and confidence level.
- Avoid treating weak host predictions as confirmed biology.

## AMG interpretation caveats

- Do not rely only on keywords.
- Check contig quality, viral confidence, gene context, contig-edge proximity, and host contamination risk.
- Describe AMGs as candidates unless validated.

## Reproducibility checklist

- Software names and versions.
- Database names, versions, and download dates.
- Parameters and thresholds.
- Input and output file types.
- Statistical formulas and correction methods.
- Data and code availability.
