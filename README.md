# dataset-automaticArtifactRemoval

**Dataset: EEG recordings containing typical artifacts (EOG, facial/neck EMG, movement)**

This repository provides an EEG dataset designed for **benchmarking artifact removal and denoising methods**.  
It contains recordings with **typical physiological and movement-related artifacts**, including:

- **EOG / ocular artifacts** (eye blinks, eye movements)
- **EMG artifacts** (facial and neck muscle activity)
- **movement artifacts** (motion-related disturbances)

> **Note:** This dataset and its documentation were created as part of an internal research effort and **were never published as a paper**. The repository is released to support reproducible research and method benchmarking.

---

## What this dataset is for

The dataset is intended for:
- evaluating automatic EEG artifact removal pipelines
- training / testing ML models for EEG denoising (supervised or self-supervised)
- comparing artifact correction strategies (e.g., regression, ICA-based removal, ASR, deep learning, etc.)
- studying artifact characteristics across modalities

---

## Repository contents

This repository includes:

- `data/`  
  EEG recordings used for artifact removal evaluation and testing.

- `documentation_dataset-automaticArtifactRemoval.pdf`  
  **Primary documentation** describing study setup, recording procedure, signal details, and data format.

- `event_markers.xlsx`  
  Marker definitions and coding scheme for events / artifact segments.

- `comments_experiment.xlsx`  
  Notes and comments on recordings / participants / sessions.

- `README.md`  
  Repository-level overview (this file).

---

## Dataset description (in brief)

### Recording intent
The recordings were designed to capture EEG segments with both:
- **clean resting-state / baseline-like EEG**, and
- **controlled or naturally occurring artifacts**, including ocular, muscle, and movement artifacts.

### Artifact categories
The dataset includes artifacts that commonly impair EEG in real-world experiments:
- ocular activity (EOG)
- facial muscle tension or jaw activity (EMG)
- neck muscle activity (EMG)
- head/body movement artifacts

For the exact artifact taxonomy and marker coding, refer to:
- `documentation_dataset-automaticArtifactRemoval.pdf`
- `event_markers.xlsx`

