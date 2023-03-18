# Webcam-Barcode-Scanner
Barcode detection with Deep Learning (YOLO) and decoding barcode using Pyzbar in Python

At present, our barcode reader project utilizes the YOLOv5 model. Going forward, we intend to provide additional resources in the form of notebooks detailing how to train barcode detection YOLO models and barcode reading programs for each subsequent model that we [release](https://github.com/Ng-Tuan-Anh/Webcam-Barcode-Scanner/releases/tag/Barcode-detection-models).

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
<p align="center">
<img src="https://github.com/Ng-Tuan-Anh/Webcam-Barcode-Scanner/blob/main/barcode_reader.png" width="500" height="394" />
</p>

## Training
**1. Data preparation**

Download the images (train, val, test) and labels for our [BarcodeEpu2](https://doi.org/10.5281/zenodo.7465864) dataset
Our dataset contains over 3000 barcode images that have been labeled in the YOLO format, making it easy to use for training and testing computer vision models that can detect and decode barcodes.

**2. Train**

Our training is based on the YOLOv5 model (Check out our [notebook](https://github.com/Ng-Tuan-Anh/Webcam-Barcode-Scanner/blob/main/train.ipynb) to learn how to train a model)

The barcode detection model was trained in several other versions of YOLO ([see](https://github.com/Ng-Tuan-Anh/Webcam-Barcode-Scanner/releases/tag/Barcode-detection-models))
