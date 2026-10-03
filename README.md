# ISLES'22 Ensemble Strategies

This repository contains an experimental notebook that describes ensemble-model
experiments for ischemic stroke lesion segmentation with MONAI. The notebook's
description is not evidence that the workflow has been reproduced or that its
models have validated performance. This project is not for clinical use.

## Repository contents

- `isles22_ensemble_strategies.ipynb` - research notebook. It describes an
  expected data layout and dependencies, but those instructions and results
  have not been independently validated.
- `synthetic_isles22/` - ten image arrays and ten label arrays. The directory
  name suggests synthetic data, but the files' origin, generation method,
  contents, and reuse terms are not documented.
- `Medical` - an extensionless metadata file whose relationship to this project
  is unclear and should be reviewed.

## Data provenance and reproducibility

The notebook no longer contains the previously hard-coded external folder
reference or an automatic downloader. It now uses a provenance placeholder and
expects a local dataset path. This does not establish the source, citation,
access permissions, or applicable data-use terms for any dataset. The
repository does not contain a root-level license file.

Before running or redistributing this work, document the dataset citation and
license, the provenance and privacy status of the included arrays, the intended
environment, and the evaluation procedure. Do not use identifiable patient
data without documented authorization. Do not use results from this project
for diagnosis, treatment, or other clinical decisions.
