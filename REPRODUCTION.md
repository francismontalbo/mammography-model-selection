# Reproduction and source inspection

Download the required assets from the release and read each archive's README. Keep original ZIP filenames together where an analysis uses another archive as input. On Windows, use a short extraction path. Install only the dependencies specified by the relevant package in a separate environment.

## Classification

Extract `Supplementary_Prediction_Analysis_Reproduction.zip`. Its README documents Python 3.12 and the supplied requirements. From the extraction directory:

```text
python -B run_reproduction.py --verify-only
python -B run_reproduction.py --component all --output ../reproduced_results
```

The first command verifies package bytes. The second recomputes covered statistics from saved predictions on the CPU. The output directory must be new, outside the package, with an existing parent. Read the package's recorded verification receipts and coverage before interpreting a successful run.

This historical package covers original decision rules and primary discrimination inference. Apply the separate MCC and operating-point packages when reproducing the amended decision columns, as explained in RESULTS_GUIDE.md. Do not compare an original-rule result against an amended table without applying the corresponding analysis.

## Training source

Extract `Supplementary_MIAS_INbreast_Training_Source.zip`. Its safe source-inspection command is:

```text
python -I -B verify_source_package.py
```

This checks the delivered source and recorded bindings. It does not train models. Do not launch the historical scripts under `retained/` unchanged. They retain experiment paths and campaign operations. Raw images, exact upstream weights, omitted artifacts and the recorded runtime would be needed for a new training campaign. The source package is not a tested portable retraining environment.

## Other analyses

Each unchanged archive documents its own inputs and replay scope. Follow its instructions rather than running all Python files. Timing replay summarizes saved sessions and does not measure the GPU again. Checkpoint diagnostics preserve existing measurements and do not rerun models.

The two `Public_Subset.zip` assets contain omission ledgers. Their original full-package integrity checks and spatial replay commands require omitted inputs and are not expected to pass on the subsets. All retained original member bytes and reported numerical results are unchanged. Do not bypass checks or invent replacement arrays.

The repository publication step inspected files and verified packaging. It did not rerun these scientific analyses. Historical verification receipts refer to the documented original package and environment.
