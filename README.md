# AI-Based Fake Content Detection System

An AI system that detects deepfake images and fake news using deep learning models.

## Features
- Fake News Detection using BERT transformer model
- Deepfake Image Detection using Vision Transformer (ViT)
- Web-based demo interface built with Gradio

## Models Used
- Fake News: jy46604790/Fake-News-Bert-Detect
- Deepfake Image: dima806/deepfake_vs_real_image_detection

## Results
| Module | Samples Tested | Accuracy |
|--------|---------------|----------|
| Fake News Detection | 200 | 85.5% |
| Deepfake Image Detection | 61 | 70.49% |

## How to Run
1. Open `AI_Fake_Content_Detector.ipynb` in Google Colab
2. Run all cells
3. Click the Gradio link to open the web demo

## Technologies
- Python
- HuggingFace Transformers
- Gradio
- Google Colab
