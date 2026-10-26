# Checking the results

Read the README inside each package before using its code. Extract files to a short path on Windows and install the listed dependencies in a separate environment. Keep the original ZIP filenames when a script reads another package.

## Classification

Extract `Supplementary_Prediction_Analysis_Reproduction.zip`. Use Python 3.12 with its listed requirements, then run these commands from the extracted folder.

```text
python -B run_reproduction.py --verify-only
python -B run_reproduction.py --component all --output ../reproduced_results
```

The first command checks file integrity. The second recalculates the covered statistics from saved predictions using the CPU. Choose a new output folder outside the package. Its parent folder must already exist.

The package covers the original decision rules and primary discrimination analyses. For the updated decision columns, use the separate MCC and operating-point packages identified in [RESULTS_GUIDE.md](RESULTS_GUIDE.md). The package README and verification records specify what each check covers.

## Training source

Extract `Supplementary_MIAS_INbreast_Training_Source.zip` and check its source files with this command.

```text
python -I -B verify_source_package.py
```

The command checks source files without training models. Do not run the older scripts under `retained/` unchanged. They use the original experiment paths and can launch or modify runs. Retraining requires the original inputs, exact upstream weights and recorded environment, including assets not supplied here. A portable retraining setup has not been tested.

## Other packages

Follow each package's instructions. Timing replay summarizes saved measurements without measuring the GPU again. Checkpoint diagnostics supply recorded findings and source for inspection.

The two `Public_Subset.zip` packages list their omitted spatial inputs. Their original checks and full spatial replay require those inputs. Do not bypass the checks or substitute invented arrays. Retained files and results are unchanged.

Published verification records describe the original packages and their tested environments. Preparing this release did not repeat training, inference or statistical analysis.
