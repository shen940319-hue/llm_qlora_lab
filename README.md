# Code and Dataset for "Optimization Techniques for Large Language Model Completion: Addressing New Entities, Reducing Hallucinations, and Integrating Structural Features"

This repository contains the Jupyter Notebook and dataset used in the study "Optimization Techniques for Large Language Model Completion: Addressing New Entities, Reducing Hallucinations, and Integrating Structural Features", published in PLOS 2025.

## Repository Contents
- `llama3-70-qlora.ipynb` — Jupyter Notebook containing the full analysis workflow used in the study, including:
  1. Loading the pre-trained/fine-tuning model.
  2. Predicting triples from the dataset.
  3. Performing QLoRA fine-tuning.

  The notebook is organized in sequential cells. To fully reproduce the results, follow the order of execution indicated by the inline comments in the code.

- `train/` — Dataset required to fine turning the model.
- `testtiny/` — Dataset required to run the notebook and reproduce the results.
- `test/` — Dataset required to run the notebook and reproduce the results.


## Computational Environment
The notebook was originally executed on **Alibaba Cloud Data Science Workshop (DSW)** with the following configuration:
- **Operating System:** Ubuntu 20.04 LTS  
- **Python Version:** 3.8  
- **GPU:**  2 * NVIDIA A10 2 * 24 GB
- **RAM:**  376 GiB

Providing this environment information supports reproducibility, as recommended by PLOS.


```bash
