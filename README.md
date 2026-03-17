# Separation-Aware Downsampling for Vehicle Detection

This repository is the official implementation of:

Guo, Y.; Yamamoto, Y. and Taniguchi, Y. (2026). Separation-Aware Downsampling for Vehicle Detection. In Proceedings of the 21st International Conference on Computer Vision Theory and Applications - Volume 1, ISBN 978-989-758-804-4, ISSN 2184-4321, pages 483-490.

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
