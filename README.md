# Separation-Aware Downsampling for Vehicle Detection

This repository is the official implementation of:

```
@inproceedings{guo2026separation,
  author={Yupei Guo and Yota Yamamoto and Yukinobu Taniguchi},
  title={Separation-Aware Downsampling for Vehicle Detection},
  booktitle={Proceedings of the 21st International Conference on Computer Vision Theory and Applications - Volume 1: VISAPP},
  year={2026},
  pages={483-490},
  publisher={SciTePress},
  organization={INSTICC}
}
```

## Overview

- Baseline: YOLO11
- Proposed modules are implemented in: `ultralytics/nn/modules/own_block.py`
- Main modules:
  - `WaveletDownsampleWrapper`
  - `PSD`

## Quick Start

```bash
pip install -r requirements.txt
python train_yolo.py
```

## Notes

This project is built on the Ultralytics codebase and extends YOLO11 with separation-aware downsampling modules for vehicle detection.
