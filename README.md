# Face Degradation

This project evaluates how blur, JPEG compression, resolution reduction, and illumination changes affect face identification performance.

The experiments use LFW and a pretrained ArcFace compatible InsightFace model. Each identity has three clean gallery images and two probe images. Probe images are evaluated under clean and degraded conditions.

## Setup

Install the required packages:
```
pip install insightface onnxruntime opencv-python scikit-learn pandas matplotlib seaborn tqdm
```
The LFW dataset is downloaded through scikit-learn. The InsightFace model downloads automatically when needed.

## Running the Project

Run the notebooks in numerical order:

1. 01_dataset_eda.ipynb
2. 02_gallery_probe_protocol.ipynb
3. 03_baseline_identification.ipynb
4. 04_arcface_baseline.ipynb
5. 05_degradation_pipeline.ipynb
6. 06_degradation_experiments.ipynb
7. 07_failure_analysis.ipynb


## Repository

https://github.com/msyed03/face-degradation