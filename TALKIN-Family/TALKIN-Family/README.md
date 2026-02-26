# TALKIN-Family Dataset (Synthetic Version)

## Overview
TALKIN-Family is a multimodal synthetic dataset designed for research in audio-visual kinship verification.

⚠ This dataset does NOT contain real human data.

## Features
- Multimodal (Video + Audio)
- Family-wise kinship pairs
- Benchmark-ready format
- Fully synthetic and reproducible

## Structure
data/
  videos/
  audio/
  pairs/
  metadata.csv

scripts/
  generate_dataset.py

examples/
  pytorch_dataloader.py

docs/
  dataset_card.md

## Generate Dataset
python scripts/generate_dataset.py

## Ethical Statement
This dataset is fully synthetic. No real human subjects are involved.
No IRB approval is required.

## License
Academic and non-commercial research use only.
