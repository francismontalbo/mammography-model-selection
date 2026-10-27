# Finding the results

Use the package that matches the analysis you want to inspect. The later analyses preserve the original benchmark.

| Analysis | Where to start |
| --- | --- |
| Primary classification | Prediction Analysis Reproduction contains saved probabilities and covered analyses for all configurations. CBIS-DDSM averages metrics from three checkpoints. MIAS and INbreast pool ensemble probabilities. |
| Tuning-selected CBIS-DDSM decisions | CBIS Operating Point Sensitivity supplies the six decision columns using thresholds selected on tuning data for all 63 original checkpoints. AUROC, AP and their primary inference remain unchanged. |
| Original MCC reporting | MCC Reporting Addendum applies the stated zero-denominator convention and retains constant-prediction flags. Earlier exports remain available. Genuine zeros are preserved. |
| Aggregation and decision rules | Within Fold AUROC Sensitivity, MIAS Decision Rule Sensitivity and Explanatory Diagnostics examine the same saved predictions. |
| Computational measurements | Evidence Base gives standardized profiles of initialized models. Fitted Predictor Timing contains the separate check using fitted models. |
| Explanations | Evidence Base contains localization and agreement summaries. XAI Location Prior and Seed Pair Agreement add results and code, with the spatial-input omissions listed in their public subsets. |
| Learning rate | CBIS Training Sensitivity reports tuning results. CBIS Adjusted Test Sensitivity contains the separate post hoc test analysis. Neither replaces the primary benchmark. |
| Precision and normalization | Precision Diagnostic and Checkpoint Precision Normalization report the bounded investigations using fitting data. They change no primary predictions or results and do not establish precision equivalence. |

The [file catalog](FILE_CATALOG.csv) gives exact filenames and downloads. Package READMEs explain older figure numbers and reporting labels. Keep each dataset's target and uncertainty assumptions in mind. These retrospective internal comparisons do not establish clinical readiness or a general ranking of model families.
