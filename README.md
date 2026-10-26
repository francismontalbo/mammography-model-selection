# Mammography model selection

We compare 21 deep learning configurations using 2,301 mammograms from CBIS-DDSM, MIAS and INbreast. Our study examines why model rankings change with performance summaries and how computational demands and explanation measures affect selection. Each dataset keeps its own prediction target.

## Get the code and results

Download the files from [release v1.0.0](https://github.com/francismontalbo/mammography-model-selection/releases/tag/v1.0.0). Start with the [classification package](https://github.com/francismontalbo/mammography-model-selection/releases/download/v1.0.0/Supplementary_Prediction_Analysis_Reproduction.zip) for saved predictions and analysis code. The [file catalog](FILE_CATALOG.csv) lists the other packages, including dataset splits, training source and supporting analyses.

Follow the [reproduction guide](REPRODUCTION.md) to check results from saved predictions. The available training source documents the experiments but does not provide a tested setup for retraining on another computer. Older training scripts should not be run unchanged.

Use the individual release downloads for the study files. GitHub's **Source code** downloads contain the repository documentation only.

## What the files cover

The release preserves results for all 21 configurations. Eighteen archives are unchanged from the submission files. Two explanation packages omit some spatial inputs because permission to redistribute those INbreast derivatives remains unverified. Their numerical results and retained code are unchanged, but repeating the full explanation analysis requires the omitted inputs. See the [release scope](PUBLIC_RELEASE.md) for details.

The [results guide](RESULTS_GUIDE.md) explains which packages support the current tables and later analyses. Original mammogram images and model weights are not included. [Dataset access](DATA_ACCESS.md) provides the relevant references. These internal evaluations do not establish clinical validity.

## About the study

Francis Jesmar P. Montalbo and Ana Pholyn Balahadia-Mortel.

*Deep Learning in Breast Mammography Diagnosis: A Comprehensive Empirical Analysis of Convolutional Neural Networks, Vision Transformers, Hybrids, and Multilayer Perceptron Mixers.* Manuscript under review.

Use [CITATION.cff](CITATION.cff) to cite the repository with its version and access date. The release has no DOI. Existing dataset and software terms apply, as explained in [NOTICE.md](NOTICE.md). [Checksums](ALL_ASSET_CHECKSUMS.sha256) let you confirm that downloads match the published files.
