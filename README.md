# Webcam-Barcode-Scanner
Barcode detection with Deep Learning (YOLOv5) and decoding barcode using Pyzbar in Python

## Installation
Clone repo and install requirements.txt
```bash
git clone https://github.com/Ng-Tuan-Anh/Webcam-Barcode-Scanner
cd Webcam-Barcode-Scanner
pip install -r requirements.txt
```

## Usage
```bash
python barcode_reader.py
```

# Training
**1. Data preparation**

Download the images (train, val, test) and labels for our [BarcodeEpu2](https://doi.org/10.5281/zenodo.7465864) dataset
Our dataset contains over 3000 barcode images that have been labeled in the YOLO format, making it easy to use for training and testing computer vision models that can detect and decode barcodes.

**2. Train**
Our training is based on the YOLOv5 model, and our dataset is compatible with other YOLO models
See the Training section of our notebook.
![alt text](https://raw.githubusercontent.com/Ng-Tuan-Anh/Webcam-Barcode-Scanner/main/results.png)
Here are the relevant data curves that visualize the experimental results of our model.
