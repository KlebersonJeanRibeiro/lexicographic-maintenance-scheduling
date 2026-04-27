# A Lexicographic Heuristic for Preventive Maintenance Scheduling under Constraints

This repository provides supplementary material for the article:

**A Lexicographic Heuristic for Preventive Maintenance Scheduling under Constraints**

The study proposes a lexicographic constructive heuristic for preventive maintenance scheduling under criticality, deadline, and workforce capacity constraints.

## Overview

The proposed heuristic supports preventive maintenance scheduling in industrial environments with multiple operational constraints. The approach considers:

- Asset criticality based on ABC classification;
- Maintenance urgency through dynamic deadlines;
- Workforce availability by sector or specialty;
- Strict feasibility under capacity constraints;
- Diagnostic indicators for sectoral utilization and bottlenecks.

The heuristic was implemented in Python as part of the **Kairos Maintenance Scheduler (KMS)**.

## Note on Spreadsheet Language

The input spreadsheets retain their original Portuguese column names because the Kairos Maintenance Scheduler (KMS) was implemented to process this standardized structure. For clarity, the main variables and fields are described below in English.

| Spreadsheet column | English meaning |
|---|---|
| Operação | Operation |
| Periodicidade | Periodicity |
| Data da última manutenção | Last maintenance date |
| Duração normal | Normal duration |
| Código ABC | ABC criticality code |
| Setor_01 | Sector 01 |
| Setor_02 | Sector 02 |
| Setor_03 | Sector 03 |
| Setor_04 | Sector 04 |
| Setor_05 | Sector 05 |
| Setor_06 | Sector 06 |
| Setor_07 | Sector 07 |
| Setor_08 | Sector 08 |
| Tolerância | Tolerance |
| deadline | Deadline |
| Numeração | Numbering |
| Dia de execução do plano | Plan execution day |

These column names should not be changed, as they are required for compatibility with the KMS implementation.

## Data Availability

The artificial dataset used for validation is made available in this repository for reproducibility purposes.

An anonymized version of the real industrial dataset used in the case study is also provided. Confidential information related to the cooperating company, asset identification, and operational details was removed or anonymized before publication.

The original raw industrial dataset is not publicly available due to confidentiality restrictions.

## Citation

If you use this repository, please cite the associated article:

```bibtex
@article{RibeiroObal2026,
  title = {A Lexicographic Heuristic for Preventive Maintenance Scheduling under Constraints},
  author = {Ribeiro, Kleberson Jean and Obal, Thalita Monteiro},
  journal = {Information Sciences},
  year = {2026},
  note = {Manuscript submitted for publication}
}
