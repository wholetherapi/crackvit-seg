# crackvit-seg

Reference implementation for **"Vision Transformers for Fine-Grained Pavement Crack Segmentation"** (Automation in Construction).

This repository contains the complete training and evaluation pipeline used in the
paper: dataset loaders, the model, the training loop, the evaluation script and the
released metrics.

## Contents

```
configs/
  default.yaml
src/
  __init__.py
  vitseg.py
train.py
eval.py
results/
  metrics.md
requirements.txt
```

## Quick start

```
pip install -r requirements.txt
python train.py --config configs/default.yaml
python eval.py --checkpoint checkpoints/best.pt
```

The released checkpoint reproduces the numbers in `results/metrics.md`.

## Citation

```bibtex
@inproceedings{crackvit-seg2026,
  title={Vision Transformers for Fine-Grained Pavement Crack Segmentation},
  booktitle={Automation in Construction},
  year={2026}
  
}
```
