# Deep Learning-Based Periodontal Disease Detection

This project presents a deep learning pipeline for the automatic diagnosis of periodontal diseases (dental cavities) from dental X-ray images using YOLOv5s and Grad-CAM.

# Project Goals
- Train a deep learning model to classify X-rays as `with cavity` or `without cavity`
- Leverage Grad-CAM for visual model explainability

## Project Structure
- `outputs/` – Heatmaps, graphs, and confusion matrices
- `presentation/` – Final PDF presentation slides
- `periodontal_model_training.py` – Fully commented training script
- `final_dataset.zip` – Zipped training, validation, and test dataset folders
- 

## Model Details
- Architecture: YOLOv5s (Image Classification)
- Backbone: CSPNet with SPP and PANet
- Input Size: 128x128
- Training Epochs: 40
- Accuracy: 91.1%

## Results
- Top-1 Accuracy: 91.1%
- Confusion Matrix: Improved class separation
- Grad-CAM: Visual cues confirm model attention on diseased areas

##  Demo & Resources
- [YouTube Video Demo](https://youtu.be/109-I9Ij9Jg)
- [GitHub Repository](https://github.com/26-shamy/deep-learning-periodontal-detection-project)

## How to Run
```bash
pip install -r requirements.txt
python periodontal_model_training.py
```
Use Jupyter or Google Colab to visualize Grad-CAM results and logs.

---
© 2025 Shamiso Mubatsa | Health Informatics | For Academic Submission
