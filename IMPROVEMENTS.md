# Improvements & Enhancements

Forked and extended by **Sreenivasulu Reddy Settipalli** ([@23sreenu](https://github.com/23sreenu))  
Research context: Precision livestock management @ Texas A&M University

---

## About This Paper

> **YOLO-TransT: Detection and tracking of estrus cow based on improved YOLOv8n and TransT models**  
> Zheng Wang, Xingshi Xu et al. — *Biosystems Engineering*, 2025

This repo contains the official implementation of a published paper combining:
- **YOLOv8n** (improved) for cattle detection
- **TransT** (Transformer Tracking) for single-object tracking
- Applied to estrus (heat) detection — a key livestock management task

---

## What I Added

### 1. Inference Demo Notebook
Added `demo.ipynb` — step-by-step Colab notebook to run inference on
your own cattle video with the pretrained YOLOv8n-TransT model.

### 2. Cleaned Dependencies
- Pinned all package versions in `requirements.txt`
- Added `environment.yml` for conda users
- Fixed Python 3.10 compatibility issues

### 3. Improved README
- Added paper citation in BibTeX format
- Added architecture diagram description
- Added quick-start commands

### 4. Integration with SAM Pipeline
This tracker's outputs (bounding boxes + track IDs) can be piped directly
into the [cattle-vision-pipeline](https://github.com/23sreenu/cattle-vision-pipeline)
for simultaneous tracking + segmentation.

---

## Citation

```bibtex
@article{wang2025yolotranst,
  title={YOLO-TransT: Detection and tracking of estrus cow based on improved YOLOv8n and TransT models},
  author={Wang, Zheng and Xu, Xingshi and others},
  journal={Biosystems Engineering},
  year={2025},
  publisher={Elsevier}
}
```

---

## Original Work

All original code belongs to [@XingshiXu](https://github.com/XingshiXu).
