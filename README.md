# Triangular Aperture Traffic Control Detection

## Overview

This project presents a Deep Learning-based Traffic Control Detection System for recognizing triangular traffic signs using Convolutional Neural Networks (CNN). The model is trained on labeled traffic sign images and can accurately classify triangular warning signs to support intelligent transportation systems and road safety applications.

---

## Features

* Detects triangular traffic control signs.
* Image preprocessing and normalization.
* CNN-based image classification.
* High prediction accuracy.
* Easy-to-use prediction interface.
* Suitable for academic and research purposes.

---

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn

---

## Project Structure

```
Triangular-Aperture-Traffic-Control-Detection/
│
├── dataset/
├── models/
├── notebooks/
├── images/
├── app.py
├── train.py
├── predict.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Dataset

The project uses a labeled dataset containing triangular traffic control signs. Images are preprocessed by resizing, normalization, and augmentation before training.

---

## Model Architecture

The CNN model consists of:

* Convolution Layers
* ReLU Activation
* Max Pooling
* Dropout
* Fully Connected Dense Layers
* Softmax Output Layer

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Triangular-Aperture-Traffic-Control-Detection.git
```

Move into the project directory:

```bash
cd Triangular-Aperture-Traffic-Control-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Training

Run:

```bash
python train.py
```

---

## Prediction

```bash
python predict.py
```

or

```bash
python app.py
```

---

## Results

* Accurate classification of triangular traffic signs.
* Robust image preprocessing pipeline.
* Suitable for intelligent transportation and traffic monitoring applications.

---

## Future Improvements

* Real-time webcam detection.
* YOLO-based object detection.
* Mobile application integration.
* Deployment using Streamlit or Flask.
* Support for multiple traffic sign categories.

---

## Applications

* Autonomous Vehicles
* Driver Assistance Systems (ADAS)
* Smart Traffic Management
* Road Safety Monitoring
* Intelligent Transportation Systems

---

## Author

**Pranavi**

---

## License

This project is licensed under the MIT License.

