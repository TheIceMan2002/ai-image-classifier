# ai-image-classifier

Two small computer-vision demos built with pre-trained models.

## Image classifier (`ImgClassification.py`)
A web-based image classification app using a pre-trained ResNet-18 model to classify images across 1,000 ImageNet categories.

- Real-time inference pipeline built with PyTorch
- Outputs 3 predictions with confidence scores for each
- Interactive web interface via Gradio

**Run it:**
1. Install dependencies: `pip install torch torchvision gradio requests`
2. Run the app: `python ImgClassification.py`
3. Open the local URL shown in your terminal and upload an image

## Image captioning (`BLIP2.py`)
A script that uses Salesforce's BLIP model (`blip-image-captioning-large`) from Hugging Face Transformers to describe a sample image in words. The result is printed to the terminal.

**Run it:**
1. Install dependencies: `pip install transformers torch pillow requests`
2. Run the script: `python BLIP2.py`

The model is downloaded the first time it runs.

## Technologies
Python, PyTorch, Gradio, Hugging Face Transformers
