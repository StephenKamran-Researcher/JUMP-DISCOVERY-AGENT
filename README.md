# JUMP DISCOVERY-AGENT

**Evidence-grounded AI-assisted cellular phenotype discovery with statistical assurance.**

AI4S Life Science competition research package. Authors: Stephen Kamran and Farah Saman.

## Project overview

Exploratory morphological phenotype analysis of public JUMP Cell Painting profiles for AKT1, BRCA1, EGFR, MTOR and TP53. We map official gene/perturbation metadata, contrast treatment profiles to plate-matched negative controls, and report plate-level directional statistics and false-discovery-rate adjustment. Separate archived outputs include exploratory literature evidence and governance benchmarks; these do **not** prove autonomous biological discovery.

## Research results

- CRISPR: AKT1, BRCA1, MTOR, TP53 passed exploratory within-modality BH q < 0.05; EGFR did not.
- ORF: no evaluated target passed exploratory q < 0.05.
- CRISPR and ORF results are not directly comparable due to different feature sets and protocols.
- Statistical significance here does not establish causal gene interactions, mechanisms, or independent biological replication.

## Files

- `notebooks/JUMP_CLEAN_REPRODUCIBLE_ANALYSIS.ipynb`: minimal two-cell reproduction notebook; its successful fresh Kaggle `Save & Run All` status has **not** been verified.
- `results/FINAL_PLATE_VALIDATION.csv`: plate-level hypothesis results (primary analysis).
- `results/CRISPR_PROFILE_RESULTS.csv`, `results/ORF_PROFILE_RESULTS.csv`: profile-level outputs.
- `figures/CRISPR_FIGURE.png`, `figures/ORF_FIGURE.png`: primary validation figures.
- `results/JUMP_*`, `figures/JUMP_*`: supplementary prior exploratory experiment outputs; see manifests and limitations before citing.

## Reproduction

Run `notebooks/JUMP_CLEAN_REPRODUCIBLE_ANALYSIS.ipynb` on Kaggle with internet enabled and dependencies listed in `requirements.txt`. Source data are fetched from the public Cell Painting Gallery / JUMP metadata repositories by the notebook. No paid LLM API credentials are required for the primary statistical validation. The original exploratory multi-agent notebook is linked below, but past `Save & Run All` executions failed; do not present the original as verified end-to-end reproducible.

Original working notebook: https://www.kaggle.com/code/stephenkamran/notebookda15c10c43

## Limitations

Results are exploratory. Plate independence and external biological replication are unverified. Treatment-normalization and statistical testing choices require further robustness assessment. Human verification of primary literature and independent agentic reasoning evaluation remain incomplete. Code and archived results are supplied transparently for inspection rather than as a claim of deployment-ready discovery.

## Data provenance

JUMP Cell Painting public profile and metadata archives, fetched from canonical URLs in the notebook. Users must comply with underlying dataset licences and conditions.

## Competition artifacts

IEEE-formatted technical report and demonstration video: pending publication. Add public links before final submission.