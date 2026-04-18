# Negative Regularization

This repository contains the reference implementation for our paper on **negative regularization** in regression. The code is designed to reproduce the experimental results reported in the paper from a single script.

## Overview

Regularization is usually used to reduce model complexity and prevent overfitting. In contrast, this project studies settings in which allowing a **negative regularization coefficient** can be beneficial, especially when standard shrinkage is overly conservative and contributes to underfitting. The experiments in this repository are designed to illustrate this behavior and to evaluate the proposed negative-capable regularization framework.

## Repository Contents

- `negative_regularization.py`  
  Main script for reproducing all experiments in the paper.

## Running the Code

The implementation is designed to run directly in **Google Colab**.

### Option 1: Run in Google Colab
1. Open Google Colab.
2. Upload `negative_regularization.py`.
3. Run the script.

### Option 2: Run locally
You can also run the script in a standard Python environment:

```bash
python negative_regularization.py
````

## Reproducibility

This repository is intended to support the reproducibility of the arXiv version of the paper. The provided script runs the full experimental pipeline and reproduces the main results reported in the manuscript.

## Paper

ArXiv link: https://arxiv.org/abs/2508.17412

## Citation

If you find this repository useful, please cite the corresponding paper:

```bibtex
@article{kim2025ridge,
  title={A Ridge Too Far: Correcting Over-Shrinkage via Negative Regularization},
  author={Kim, Dongseok and Oh, Gisung},
  journal={arXiv preprint arXiv:2508.17412},
  year={2025}
}
```
