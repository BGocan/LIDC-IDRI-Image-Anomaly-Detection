# LIDC-IDRI Image Anomaly Detection | Research Notes

**Status:** Historical exploratory research (2021). **Not a clinical tool.**

## Purpose
Explore preprocessing, segmentation and feature extraction for lung medical imagery using the LIDC-IDRI dataset. The original plan combined Gabor filtering for enhancement with watershed segmentation as a precursor to feature extraction and potential anomaly detection.

## Scope and evidence
The repository's original README documents the proposed pipeline and dataset organisation. It should **not** be interpreted as proof of a fully trained, independently evaluated anomaly-detection model. The recorded approach was exploratory.

## Suggested project structure
- `Dataset/`: original datasets, subject to source licensing and permission
- `Data/`: preprocessing outputs
- `Processed/`: model-ready images
- `Segmented/`: segmentation and feature-extraction artefacts
- `Layout/`: visualisation experiments

The paths above describe the historic intended structure, not a verified inventory of complete components.

## Reproducibility checklist
- Document dataset provenance, licence and exact subset
- Version preprocessing parameters and segmentation settings
- Record train/test splitting by patient rather than by image to avoid leakage
- Provide evaluation and examples before making accuracy claims
- Avoid committing patient-identifiable DICOM data or licensed datasets

## Historical context
TheiaXP developed after a short virtual medical-imaging internship at Negentra in 2021 prompted further independent learning. This repository represents the early research stage.

See the later [TheiaXP prototype](https://github.com/BGocan/streamlit-theiaxp-proto).