# HOB-project
human oral bioavailability
# Chemprop Model Usage

## Installation

Before using this model, ensure you have Chemprop installed:

```bash
conda create -n chemprop python=3.11
conda activate chemprop
pip install chemprop

Use the following command to make predictions with the model:
chemprop predict --test-path data.csv --model-path ./model --molecule-featurizers v1_rdkit_2d_normalized

---
