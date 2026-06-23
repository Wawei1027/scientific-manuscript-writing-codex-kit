---
name: methods-reproducibility-auditor
description: Use when auditing Methods for reproducibility, missing software versions, database names, database dates, parameters, file types, filtering thresholds, statistical formulas, and bioinformatics workflow details.
---

# Methods Reproducibility Auditor

Use this skill to audit whether a Methods section contains enough information for another researcher to reproduce the work.

## Safety rules

- Do not fabricate software versions, database dates, command-line parameters, sample details, or statistical formulas.
- Mark missing details as `[missing]`.
- Preserve the user's actual workflow and do not substitute a different pipeline unless asked.
- Keep private data, unpublished manuscripts, and sensitive materials out of public repositories.

## Required reproducibility fields

Check whether the Methods record:

- Software name.
- Software version.
- Database name.
- Database version.
- Database download date.
- Command-line parameters.
- Input file type.
- Output file type.
- Filtering thresholds.
- Statistical model formula.
- Random seed when relevant.
- Hardware or compute environment when relevant.
- Data and code availability statements when relevant.

## Workflows to audit

This skill is especially suited for:

- QIIME2.
- DADA2.
- phyloseq.
- vegan.
- DESeq2.
- ANCOM-BC.
- ALDEx2.
- MetaPhlAn.
- HUMAnN.
- Kraken2 and Bracken.
- MEGAHIT and metaSPAdes.
- VirSorter2.
- geNomad.
- VIBRANT.
- CheckV.
- iPHoP.
- DRAM-v.

## Output format

When triggered, provide:

- Missing information checklist.
- Methods revision suggestions.
- Reproducibility risk score with rationale.
- A Methods paragraph rewrite that keeps unknown items as `[missing]`.
- A table of software, versions, databases, parameters, inputs, and outputs.
