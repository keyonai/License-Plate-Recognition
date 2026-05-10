# License Plate Recognition — OpenCV + OCR

Detects and extracts text from license plates in vehicle images using OpenCV for image processing and two OCR engines (TesseractOCR and EasyOCR) for text recognition. Both engines are run on the same images to compare their output accuracy.

## What it does

- Loads vehicle images and isolates the license plate region using OpenCV
- Runs TesseractOCR and EasyOCR on the detected plate
- Compares extracted text output between both engines
- Visualizes results with Matplotlib

## Stack

- Python
- OpenCV
- TesseractOCR
- EasyOCR
- Matplotlib

## Setup

```bash
pip install opencv-python pytesseract easyocr matplotlib
```

> TesseractOCR also requires the Tesseract binary installed on your system:
> - Windows: download from [UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki)

## Usage

Open `License_Plate_Recognition.ipynb` in Jupyter and run all cells. Sample vehicle images are included in the repo.

## Sample images included

- `blue-pickup-truck-motion-power-reliability-road.jpg`
- `white-crossover-freeway-overpass-road-ahead.jpg`
