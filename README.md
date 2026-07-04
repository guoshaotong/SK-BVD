# SK-BVD

This repository is the official implementation page for the paper:

**SK-BVD: Behavior-Aware Multimodal Software Vulnerability Detection via LLM-Generated Structured Expert Knowledge**

## Overview

SK-BVD is a behavior-aware multimodal vulnerability detection framework that incorporates LLM-generated structured expert knowledge into source-code vulnerability detection. The method integrates source-code semantics, structured expert knowledge, and program graph information to support vulnerability detection, line-level vulnerability localization, and CWE type identification.

## Release Plan

The full source code, model implementation, data preprocessing scripts, training configurations, and reproduction instructions will be released after the paper is accepted.

At the current stage, this repository is maintained as the official release page for the project. We are organizing the code and experiment materials to ensure that the released version is clean, reproducible, and easy to use.

## Planned Contents

The repository will include:

- Model implementation of SK-BVD
- Data preprocessing scripts
- Training and evaluation scripts
- Configuration files for major experiments
- Instructions for reproducing the reported results
- Additional notes on dataset preparation and graph construction

## Datasets

This work uses publicly available vulnerability detection datasets, including Devign, ReVeal, and a sampled subset derived from BigVul. Due to dataset licenses and storage considerations, raw datasets may not be redistributed directly in this repository. Instead, we will provide preprocessing scripts and detailed instructions for preparing the data.

## Citation

If you find this work useful, please cite our paper. The citation information will be updated after publication.

```bibtex
@article{guo2026skbvd,
  title={SK-BVD: Behavior-Aware Multimodal Software Vulnerability Detection via LLM-Generated Structured Expert Knowledge},
  author={Guo, Shaotong and Ren, Jiadong and Han, Minghao and Li, Mingyue},
  journal={},
  year={2026}
}
