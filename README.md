# Webcam-Barcode-Scanner
Barcode detection with Deep Learning (YOLO) and decoding barcode using Pyzbar in Python

Our barcode reader project currently uses YOLOv5 model. We plan to release notebooks with instructions on training YOLO models for barcode detection and reading for our upcoming models that we [release](https://github.com/Tyan-Ng/Webcam-Barcode-Scanner/releases/tag/Barcode-detection-models).

🚀🚀🚀The study was a collaborative effort involving [Tyan-Ng](https://github.com/Tyan-Ng) and [TaThanh200320](https://github.com/TaThanh200320)

<p align="center">
<img src="https://github.com/Tyan-Ng/Webcam-Barcode-Scanner/blob/main/barcode_reader.png" width="500" height="394" />
</p>

## Installation
Clone repo and install requirements.txt
```bash
git clone https://github.com/Tyan-Ng/Webcam-Barcode-Scanner
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

Our training is based on the YOLOv5 model (Check out our [notebook](https://github.com/Tyan-Ng/Webcam-Barcode-Scanner/blob/main/train.ipynb) to learn how to train a model)

The barcode detection model was trained in several other versions of YOLO ([see](https://github.com/Tyan-Ng/Webcam-Barcode-Scanner/releases/tag/Barcode-detection-models))
