# Gary Vanderlaan

Computational biologist building reproducible, contract-driven bioinformatics systems for genomics, transcriptomics, rare disease analysis, and clinical data harmonization.

My portfolio is structured as an interconnected computational system rather than a set of isolated projects, with clearly defined layers for data generation, storage, integration, and reasoning. The goal is to bridge domain-rich biological insight with rigorous computational architecture suitable for clinical and research environments.

---

## System Architecture

This diagram illustrates the structure of the portfolio and the flow of data across system layers.

[🔗 architecture diagram ](assets/system_architecture.pdf)

This portfolio is organized as a layered computational system:

**Pipeline Layer**
- reproducible_pipeline_framework `(RPF)` → execution framework for reproducible pipelines  
- variant_annotation_pipeline `(VAP)` → variant-level evidence generation  
- rnaseq_pipeline `(RSP)` → functional (RNA-seq) evidence generation  

**Data Layer**
- variant_database `(VDB)` → structured storage of variant and annotation data  

**Evidence Layer**
- gene_set_consensus `(GSC)` → gene-level consensus evidence integration  

**Reasoning Layer**
- rare_disease_gene_prioritization `(RDGP)` → rare disease gene prioritization  

**Parallel Clinical Analytics Branch**
- SeroStrat → cohort engineering and longitudinal clinical data analysis  

These layers interact through well-defined data and transformation contracts.

---

## Portfolio Repositories

### reproducible_pipeline_framework (RPF)

Framework for building modular, reproducible computational pipelines with configuration-driven execution, logging, validation hooks, and run-level auditability.

### variant_annotation_pipeline (VAP)

Pipeline for transforming raw sequencing data into structured, annotated variant-level evidence suitable for downstream database ingestion and interpretation.

### variant_database (VDB)

Relational database system for storing, indexing, and querying variant and annotation data with full provenance tracking.

### gene_set_consensus (GSC)

System for integrating gene-level evidence across multiple biological sources into consensus representations with explicit provenance and scoring.

### rnaseq_pipeline (RSP)

Pipeline for generating gene-level functional evidence from RNA-seq datasets, including differential expression and network-level interpretation.

### rare_disease_gene_prioritization (RDGP)

Reasoning layer for prioritizing candidate genes using integrated variant, functional, and consensus evidence.

### SeroStrat

Clinical data engineering pipeline for cohort construction and longitudinal analysis of ICU-style laboratory data using serology-based stratification.

### inherited_anemias

Analysis and visualization codebase supporting *Total et al., 2025*, focused on clinical and genetic patterns in inherited anemia datasets.

---

## Portfolio Glossary

* **RPF** — reproducible_pipeline_framework
* **VAP** — variant_annotation_pipeline
* **VDB** — variant_database
* **GSC** — gene_set_consensus
* **RSP** — rnaseq_pipeline
* **RDGP** — rare_disease_gene_prioritization
* **SeroStrat** — serology-based cohort engineering pipeline
* **inherited_anemias** — publication support repository

---

## Technical Focus

**Programming & Systems**

* Python
* Bash
* SQL
* Linux environments

**Bioinformatics**

* Variant annotation
* RNA-seq analysis
* Rare disease genomics

**Data Engineering**

* Relational database design
* Data normalization and integration
* Reproducible pipeline development

**Clinical Data**

* Cohort engineering
* Longitudinal data analysis
* Clinical data harmonization

---

## Philosophy

I build computational workflows that are:

* biologically meaningful
* reproducible and auditable
* modular and extensible
* well documented
* grounded in real-world datasets
* useful for both research and teaching

---

## Status

This portfolio is under active development, with a focus on building a fully integrated system for genomic and clinical data analysis.

Several repositories are currently in early implementation stages following detailed design and milestone mapping.
