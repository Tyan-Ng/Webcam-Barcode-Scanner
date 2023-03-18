# Webcam-Barcode-Scanner
Barcode detection with Deep Learning (YOLOv5) and decoding barcode using Pyzbar in Python

🚀🚀🚀The study was a collaborative effort involving [Ng-Tuan-Anh](https://github.com/Ng-Tuan-Anh) and [TaThanh200320](https://github.com/TaThanh200320)

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

## Training
**1. Data preparation**

Download the images (train, val, test) and labels for our [BarcodeEpu2](https://doi.org/10.5281/zenodo.7465864) dataset
Our dataset contains over 3000 barcode images that have been labeled in the YOLO format, making it easy to use for training and testing computer vision models that can detect and decode barcodes.

**2. Train**

Our training is based on the YOLOv5 model (Check out our [notebook](https://github.com/Ng-Tuan-Anh/Webcam-Barcode-Scanner/blob/main/train.ipynb) to learn how to train a model)

The barcode detection model was trained in several other versions of YOLO (see)
