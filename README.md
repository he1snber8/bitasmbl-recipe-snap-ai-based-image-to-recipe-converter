# RecipeSnap – AI-Based Image to Recipe Converter

## Description
RecipeSnap is a user-friendly Flask web application that enables users to upload food images and receive automatically generated recipes using AI-powered image recognition. Perfect for AI enthusiasts, developers, and food lovers experimenting with computer vision and web apps.

## Tech Stack
- Python
- Flask
- torchvision (PyTorch)
- TensorFlow Hub (optional, for model options)
- ReportLab (for PDF generation)
- HTML/CSS (for frontend)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/bitasmbl-recipe-snap-ai-based-image-to-recipe-converter.git
```
2. Navigate into the directory:
```bash
cd bitasmbl-recipe-snap-ai-based-image-to-recipe-converter
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the Flask app:
```bash
flask run
```
2. Open your browser and go to `http://127.0.0.1:5000/`
3. Upload a food image, then view and download the generated recipe.

## Implementation Overview
- Upload an image through the web form.
- The backend processes the image with a pretrained model to identify food items.
- The app retrieves a matching recipe from a static database.
- Users can view the recipe on the page or download it as a PDF.

## When you are done, submit the project from your profile: [https://bitasmbl.com/home/profile](https://bitasmbl.com/home/profile)