# 🍎 FoodSafe AI

An AI-based computer vision system for detecting the freshness of fruits and vegetables using images.

FoodSafe AI uses **deep learning and image classification** to analyze food images and classify them as **Fresh** or **Spoiled**. The project aims to support automated food-quality inspection and help reduce food waste.

## Key Features

- Fruit freshness classification
- Vegetable freshness classification
- Fresh and spoiled food detection
- Image preprocessing
- Deep learning-based image classification
- Food image analysis
- Expandable fruit and vegetable dataset

## Tech Stack

| **Component**        | **Technology** |
| -------------------- | -------------- |
| Programming Language | Python         |
| Development          | Jupyter Notebook |
| Deep Learning        | MobileNetV2    |
| Computer Vision      | Image Classification |
| Data Processing      | NumPy, Pandas  |
| Visualization        | Matplotlib     |

## Supported Food Categories

The current dataset contains images of:

### Fruits

- Banana
- Orange

### Vegetables

- Cucumber
- Okra
- Potato

The dataset can be expanded with additional fruits and vegetables.

## How It Works

The system follows an image classification pipeline:

```text
Food Image
     │
     ▼
Image Preprocessing
     │
     ▼
Deep Learning Model
     │
     ▼
Feature Extraction
     │
     ▼
Fresh / Spoiled Classification
     │
     ▼
Prediction Result
