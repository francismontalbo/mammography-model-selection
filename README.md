# Mammography model selection

Code and derived numerical evidence for **Deep Learning in Breast Mammography Diagnosis: A Comprehensive Empirical Analysis of Convolutional Neural Networks, Vision Transformers, Hybrids, and Multilayer Perceptron Mixers**.

Francis Jesmar P. Montalbo and Ana Pholyn Balahadia-Mortel.

The study compares 21 architecture and pretraining configurations using 2,301 mammograms from CBIS-DDSM, MIAS and INbreast. It examines how performance aggregation, computational demands and explanation criteria affect model selection. Dataset targets remain distinct.

## Download and start

Download the evidence archives from [release v1.0.0](https://github.com/francismontalbo/mammography-model-selection/releases/tag/v1.0.0). The [file catalog](FILE_CATALOG.csv) records each download, its scope and checksum. Large archives are release assets rather than files in the Git history. **Download ZIP** on the repository home page downloads the documentation, not the evidence assets.

1. Start with `Supplementary_Prediction_Analysis_Reproduction.zip` for saved classification probabilities and CPU analysis code.
2. Use `Supplementary_Cohort_Derivation_Verification.zip` for eligibility, labels and recorded assignments.
3. Inspect `Supplementary_MIAS_INbreast_Training_Source.zip` and the CBIS source records in `Supplementary_Evidence_Base.zip` for available fitting and preprocessing code.
4. Consult [REPRODUCTION.md](REPRODUCTION.md) before running any command and [RESULTS_GUIDE.md](RESULTS_GUIDE.md) for subsequent reporting amendments.

The release contains 18 unchanged archives and two explicitly labeled public subsets. The subsets retain their numerical results and code but omit spatial inputs whose INbreast redistribution basis has not been established. They do not support complete spatial replay. [PUBLIC_RELEASE.md](PUBLIC_RELEASE.md) identifies the exact scope.

## What is available

Saved predictions cover all 21 configurations. The packages also supply cohort records, retained training source, statistical analysis scripts, computational measurements, explanation summaries and the documented sensitivity analyses. The checkpoint diagnostic archive contains measurements and source records, not checkpoint weights.

Original or processed mammogram intensity images, trained and pretrained weights, manuscript files and private editorial correspondence are not included. Obtain original datasets from their custodians using [DATA_ACCESS.md](DATA_ACCESS.md).

The supplied reproduction routes operate on saved outputs. They do not constitute a tested portable retraining system or external clinical validation. Historical controllers are inspection material and should not be run unchanged. No new model fitting, inference or statistical analysis was performed to prepare this repository.

## Citation and reuse

Cite this repository with the release version and access date. [CITATION.cff](CITATION.cff) supplies repository citation metadata. The associated manuscript is under review, and this release has no assigned DOI.

Existing component licenses and dataset terms remain applicable. [NOTICE.md](NOTICE.md) maps the supplied third-party notices. No new umbrella license is assigned to the mixed package.
