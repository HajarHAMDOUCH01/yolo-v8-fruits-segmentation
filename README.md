# 🍌 Fruit Instance Segmentation with YOLOv8

This project demonstrates how to fine-tune a **YOLOv8** model for instance segmentation on a custom dataset of fruits. The training and deployment were done using **Roboflow**.

🔗 **Live Model on Roboflow Universe**:  
👉 [Click to view the trained model](https://universe.roboflow.com/hajarroboflow/hajar_fruitsss_1/model/1)

---

## 📊 Model Overview

| Metric       | Value    |
|--------------|----------|
| **mAP@50**   | 89.1%    |
| **Precision**| 84.8%    |
| **Recall**   | 84.1%    |

- **Model Version**: `hajar_fruitsss_11`
- **Framework**: YOLOv8s (Ultralytics)
- **Dataset Version**: `2025-06-08 6:02pm`
- **License**: AGPL-3.0

---

## 🧠 Task Description

The goal of the project was to detect and segment fruits in images using an instance segmentation model trained on a labeled dataset of **6,221 images**, containing **8 classes**.

---

## 🛠️ Tools & Tech Stack

| Tool         | Usage                                      |
|--------------|--------------------------------------------|
| **Python**   | Programming language                       |
| **YOLOv8**   | Deep learning model for instance segmentation |
| **Roboflow** | Data labeling, augmentation, training & deployment |

---

## 📝 Dataset

- Total Images: **6,221**
- Classes: **8 different fruit types**
- Annotation type: **Instance segmentation**
- Managed, labeled, and versioned via **Roboflow**

---

## 🚀 Model Training & Deployment

- Annotated images in Roboflow
- Exported dataset in YOLOv8 format
- Fine-tuned a **YOLOv8s** model using Roboflow's training interface
- Deployed the trained model on Roboflow Universe for live inference and sharing


---

