# Computational Biology Context

## Purpose
Curated external method and workflow references for single-cell, spatial,
multi-omics, somatic genomics, RNA-seq, and neoantigen prioritization.

## Canonical references

| Domain | Repository | Intended use |
|---|---|---|
| Single-cell transcriptomics | https://github.com/scverse/scanpy | AnnData conventions, QC, preprocessing, clustering, DE |
| Spatial omics | https://github.com/scverse/squidpy | Spatial graphs, neighborhood analysis, spatial statistics |
| Multimodal omics | https://github.com/scverse/muon | MuData structures and multimodal workflows |
| Neoantigen prioritization | https://github.com/griffithlab/pVACtools | Candidate generation and prioritization reference |
| WES/WGS variant analysis | https://github.com/nf-core/sarek | Reproducible germline and somatic Nextflow workflow patterns |
| Bulk RNA-seq | https://github.com/nf-core/rnaseq | Reproducible RNA-seq QC and quantification workflow patterns |

## Usage guardrails
- These repositories are methodological references, not clinical decision-support systems.
- Pin a release/tag before reproducing any workflow.
- Record genome build, reference files, tool/container versions, and parameter settings.
- Validate on appropriate controls before any biological or clinical interpretation.
- Do not store patient identifiers, secrets, cloud credentials, or regulated data here.
