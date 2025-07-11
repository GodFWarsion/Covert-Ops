# Covert Ops: AI for Real-Time Crime Detection

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)](https://opencv.org/)

![Covert Ops Banner](assets/banner.png)


## 📌 Abstract

**Covert Ops** is an AI-powered surveillance system designed to enhance real-time crime detection capabilities. Using a DenseNet121 backbone with transfer learning, this project identifies and classifies suspicious or criminal incidents from video feeds. Activities such as arson, vandalism, traffic accidents, and fire are recognized via a robust model fine-tuned on crime-specific datasets.

## 🧠 Key Features

- 📹 Real-time video classification using CNN
- 🔍 Fine-tuned DenseNet121 model
- 🔄 Data preprocessing and augmentation
- 📊 Model testing and evaluation via Jupyter Notebooks
- 📁 Modular structure for reproducibility and scalability

## 🛠️ Tech Stack

- **Languages**: Python 3.8+
- **Libraries**: TensorFlow, Keras, OpenCV, NumPy, Matplotlib
- **Model**: DenseNet121 (with transfer learning)
- **Interface**: Jupyter Notebooks

## 🔧 Installation

### ✅ Prerequisites

- Python 3.8 or above
- pip
- virtualenv (optional but recommended)

### ⚙️ Setup

```bash
# Clone the repository
git clone https://github.com/GodFWarsion/Covert-Ops.git
cd Covert-Ops

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

```
## 🔗 Datasets

This project uses two publicly available datasets:

### 🔥 Fire Detection Dataset (Kaggle)
- Source: [https://www.kaggle.com/datasets/phylake1337/fire-dataset](https://www.kaggle.com/datasets/phylake1337/fire-dataset)
- Structure: Contains `fire` and `non-fire` image classes.
- Place it under:  

### 🎥 UCF-Crime Dataset
- Official site: [https://www.crcv.ucf.edu/projects/real-world/](https://www.crcv.ucf.edu/projects/real-world/)
- Kaggle alternative input: [https://www.kaggle.com/code/odins0n/video-anomaly-detection/input](https://www.kaggle.com/code/odins0n/video-anomaly-detection/input)
- You’ll need to manually download and extract videos.
- More Crime DataSet - Arson,Vandalism,Murder,Explosion ... on the way

⚠️ Note: These datasets are large and cannot be included in this GitHub repo. Please download them manually and place them in the recommended directory structure.

