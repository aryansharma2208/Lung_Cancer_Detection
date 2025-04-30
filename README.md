# Lung Cancer Detection using Deep Learning

This repository contains a deep learning-based solution for detecting lung cancer from medical images. The project includes preprocessing utilities, training scripts, and evaluation modules tailored for object detection and classification models like YOLO, Faster R-CNN, and RetinaNet.

---

## Repository Structure

| File/Folder               | Description |
|--------------------------|-------------|
| `Classification.ipynb`   | Notebook for lung cancer classification using CNN techniques |
| `Detection.ipynb`        | Object detection notebook (YOLO/Faster R-CNN based) |
| `app.py`                 | (Optional) Flask or Streamlit-based application file (for deployment) |
| `coco_eval.py`           | Evaluation script using COCO metrics |
| `coco_utils.py`          | Helper functions to handle COCO-format datasets |
| `engine.py`              | Core training and evaluation loop for PyTorch |
| `group_by_aspect_ratio.py` | Utility for optimizing image batching |
| `train.py`               | Training script for the model |
| `transforms.py`          | Custom data augmentation and transformation functions |
| `utils.py`               | Miscellaneous utility functions |

---

## Features

- Supports custom and COCO-style datasets
- Implements deep learning models for both classification and detection
- Modular codebase (easy to extend or reuse)
- Compatible with PyTorch
- Uses advanced transforms and augmentation
- Evaluation using COCO metrics

---

## 🛠️ Requirements

- Python 3.8+
- PyTorch
- torchvision
- OpenCV
- Matplotlib
- NumPy
- tqdm
- jupyter / notebook
