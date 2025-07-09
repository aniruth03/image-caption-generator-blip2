# Image Caption Generator

The Image Caption Generator is a web-based application that uses AI to generate natural language captions for uploaded images.  
It integrates the BLIP2-Flan-T5 model to interpret image content and produce accurate, context-aware descriptions.  
The system is built using Python, Flask, HTML, CSS, and JavaScript.  
It runs locally on CPU or GPU, offering a clean and responsive interface for real-time caption generation.

---

## Features

- Upload and preview images in-browser
- Generate human-like image captions using BLIP2-Flan-T5
- Works with both CPU and GPU (CUDA-enabled)
- Fully local execution – no cloud API or internet dependency
- Simple and clean desktop-focused user interface

---

## How It Works

1. User uploads an image via the interface.
2. Image is previewed before submission.
3. Clicking “Generate Caption” sends the image to the Flask backend.
4. The backend processes the image and uses BLIP2 to generate a caption.
5. The caption is returned and displayed under the image.

---

## Project Structure
ImageCaptionGenerator/
├── app.py # Flask backend
├── templates/
│ └── index.html # Frontend UI
├── static/
│ └── style.css # CSS styling
├── README.md # Documentation
└── requirements.txt # Python dependencies


## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/image-caption-generator.git
cd image-caption-generator

### 2. Create Virtual Environment (Optional)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

### 3. Install Requirements
pip install -r requirements.txt
