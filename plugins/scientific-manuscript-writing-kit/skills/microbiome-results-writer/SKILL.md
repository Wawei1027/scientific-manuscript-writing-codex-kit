---
name: microbiome-results-writer
description: Use when turning amplicon, shotgun metagenomics, virome, phage, QIIME2, DADA2, CheckV, HUMAnN, MetaPhlAn, ordination, diversity, PERMANOVA, differential abundance, or model outputs into cautious manuscript Results paragraphs.
---

# Microbiome Results Writer

Use this skill when the user wants to write Results paragraphs from microbiome, metagenomics, virome, viral contig, phage-host, or statistical outputs.

## Safety rules

- Do not invent significance, p-values, effect sizes, sample sizes, taxa, pathways, host predictions, AMG results, or ecological explanations.
- Do not add citations or new facts in Results unless supplied by the user.
- Mark missing values as `[missing]` rather than filling them in.
- Separate observed patterns from statistical evidence and avoid mechanistic overreach in Results.

## Accepted inputs

Inputs may include:

- Result tables.
- Figures.
- Statistical model outputs.
- R logs.
- QIIME2, DADA2, phyloseq, vegan, ANCOM-BC, ALDEx2, or DESeq2 outputs.
- CheckV, HUMAnN, MetaPhlAn, Kraken2/Bracken, or viral contig summaries.
- vOTU abundance tables.
- Host prediction summaries.
- AMG candidate summaries.

## Results writing order

Write Results in this order:

1. Main pattern.
2. Statistical evidence.
3. Direction and effect size.
4. Brief factual link to figure or table.

Avoid extended mechanism discussion in Results. Save mechanisms, caveats, and broad ecological interpretation for Discussion.

## Suitable result types

This skill can draft Results text for:

- Alpha diversity.
- Beta diversity.
- PERMANOVA.
- Ordination.
- Differential abundance.
- Soil chemistry associations.
- Viral contig or vOTU abundance.
- Host prediction summaries.
- AMG candidate summaries.
- Functional pathway summaries.

## Missing information to flag

Flag missing:

- Effect size.
- Test statistic.
- Adjusted p-value.
- Raw p-value.
- Sample size.
- Model formula.
- Distance metric.
- Multiple testing correction.
- Feature filtering rule.
- Software or database source.

## Output format

When triggered, provide:

- A missing information checklist.
- A cautious Results paragraph.
- A more concise Results version if requested.
- A claim-to-evidence table.
- Notes on wording that should move to Discussion.
