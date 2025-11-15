# Traffic-Sign-Detection-and-Recognition
A two-stage pipeline for detecting and classifying traffic signs using YOLOv8 and ResNet18, tested on benchmark datasets and real-world video.
---

## 📝 Project Overview

This project implements a **traffic sign detection and classification pipeline** using state-of-the-art deep learning models. It is designed for educational and research purposes and tested on real-world data.

### Detection Stage
- **Model:** YOLOv8  
- **Dataset:** GTSDB 
- **Function:** Detects traffic signs in images or video frames.

### Classification Stage
- **Model:** ResNet18  
- **Dataset:** GTSRB  
- **Function:** Classifies cropped traffic signs into correct categories.

---

## 🎯 Key Features

- Two-stage pipeline: **Detection → Classification**  
- Automatically downloads datasets from Google Drive if not present locally  
- Tested on a **manually recorded video**, showing real-world performance

---

## Datasets

- The datasets are publicly available on **Google Drive**:  
  - **GTSRB:** [Drive link](https://drive.google.com/file/d/1HfmPX_O19iyQoxHphYY7XHOyvbeyKbAh/view?usp=sharing)  
  - **GTSDB:** [Drive link](https://drive.google.com/file/d/13JIMRCWMdDMK-LloLTm3qWyonfkjA09b/view?usp=sharing)  

- Kaggle links for accessing the datasets directly:  
  - **GTSRB:** [Kaggle link](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)  
  - **GTSDB:** [Kaggle link](https://www.kaggle.com/datasets/safabouguezzi/german-traffic-sign-detection-benchmark-gtsdb)  

- **Note:** In the code, the datasets are already loaded from Google Drive, so there is no need to download them manually.
