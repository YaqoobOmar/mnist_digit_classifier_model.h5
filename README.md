# MNIST Digit Classifier

A simple image classifier built using a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset.

## Dataset
- Source: MNIST (70,000 grayscale images, 28x28 pixels)
- Classes: Digits 0–9

## Model
- Architecture: CNN with Conv2D, MaxPooling, Dense, Dropout
- Output Layer: Softmax (10 classes)
- Accuracy: ~98%

## Installation & Setup
```bash
git clone https://github.com/YaqoobOmar/image_projects.git
cd image_projects
python -m venv venv
source venv/Scripts/activate  # Use `source venv/bin/activate` on Linux/Mac
pip install -r requirements.txt
jupyter notebook
