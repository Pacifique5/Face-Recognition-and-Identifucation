# Text Extraction - OCR Application

This folder contains an OCR (Optical Character Recognition) application that extracts text from images and camera feeds using Tesseract OCR.

## Features

- **Load Images**: Load image files from your system
- **Live Camera Feed**: Capture text from a live camera feed in real-time
- **Region of Interest (ROI)**: Select a specific area of the image for text extraction
- **Text Detection & Annotation**: Automatically detects text and annotates it with bounding boxes
- **Image Preprocessing**: Applies filtering and thresholding to improve OCR accuracy

## Prerequisites

### System Requirements

1. **Python 3.7+** - Install from [python.org](https://www.python.org/)
2. **Tesseract OCR Engine** - Required system dependency
   - **Windows**: Download and install from [GitHub Tesseract Release](https://github.com/UB-Mannheim/tesseract/wiki)
     - Download `tesseract-ocr-w64-setup-v5.x.exe` (or latest version)
     - During installation, note the installation path (default: `C:\Program Files\Tesseract-OCR`)
   - **macOS**: `brew install tesseract`
   - **Linux**: `sudo apt-get install tesseract-ocr`

## Installation

### 1. Install Python Dependencies

Navigate to the Text Extraction folder and install required packages:

```bash
pip install -r requirements.txt