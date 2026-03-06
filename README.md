
# Automated Blood Cell Detection using YOLOv5

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Framework](https://img.shields.io/badge/Framework-PyTorch-orange)
![Model](https://img.shields.io/badge/Model-YOLOv5-red)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)
![Dataset](https://img.shields.io/badge/Dataset-BCCD-green)

This project implements a deep learning based system for detecting and classifying blood cells from microscopic blood smear images using the YOLOv5 object detection framework.

The model identifies three primary blood cell types:

- Red Blood Cells (RBC)
- White Blood Cells (WBC)
- Platelets

The system is trained on the **BCCD (Blood Cell Count Dataset)** and demonstrates the use of computer vision techniques for automated medical image analysis.

---

# Project Overview

Manual blood cell counting in laboratories is time-consuming and susceptible to human error. This project explores the application of **deep learning based object detection** to automatically identify and classify blood cells from microscopic images.

The YOLOv5 model predicts bounding boxes and labels for each detected blood cell, enabling automated counting and classification.

---

# Technologies Used

- Python
- PyTorch
- YOLOv5
- OpenCV
- Google Colab
- Roboflow

---

# Dataset

The model is trained using the **BCCD (Blood Cell Count Dataset)**.

Dataset Link:

https://github.com/Shenggan/BCCD_Dataset

The dataset contains annotated microscopic blood smear images with bounding boxes for:

- Red Blood Cells (RBC)
- White Blood Cells (WBC)
- Platelets

---

# Repository Structure

```
automated-blood-cell-detection
│
├── docs
│   └── project_report.pdf
│
├── notebook
│   └── blood_cell_detection.ipynb
│
├── screenshots
│   ├── training_results.png
│   ├── detected_image.png
│   ├── ground_truth_augmented.png
│   └── test_image.png
│
└── README.md
```
---

# Model Training

The YOLOv5 object detection model was trained on annotated blood smear images to detect and classify different blood cell types. The training process was conducted using **Google Colab with GPU acceleration**.

The model learns spatial features and predicts bounding boxes around detected blood cells along with their corresponding class labels.

---

# Detection Results

Example outputs from the trained YOLOv5 model.

### Model Detection Output

![Detected Image](screenshots/detected_image.png)


### Ground Truth with Augmented Labels

![Ground Truth](screenshots/ground_truth_augmented.png)

### Test Input Image

![Test Image](screenshots/test_image.png)

### Training Performance

![Training Results](screenshots/training_results.png)

---

# References

- YOLOv5 – Ultralytics  
- BCCD Dataset  

[1] D. Trong Luong et al., "Distinguish normal white blood cells from leukemia cells by detection, classification, and counting blood cells using YOLOv5," ATiGB 2022.

[2] V. B. Inchur et al., "Implementation of Blood Cell Counting Algorithm using Digital Image Processing Techniques," RTEICT 2020.



