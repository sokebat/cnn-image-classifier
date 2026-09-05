# CNN Image Classifier

Cats vs dogs image classification with TensorFlow and Keras.

## Dataset

Images live under `data/` in ImageFolder layout:

```text
data/
├── train/
│   ├── cats/    # 10,000 images
│   └── dogs/    # 10,000 images
└── test/
    ├── cats/    # 2,500 images
    └── dogs/    # 2,500 images
```

## Project Structure

```text
cnn-image-classifier/
├── data/                 # Train and test images
├── notebooks/
│   └── eda.ipynb         # Exploratory data analysis
├── models/               # Saved model artifacts
├── requirements.txt
└── README.md
```

## Setup

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
# venv\Scripts\activate   # Windows

pip install -r requirements.txt
```

## Exploratory Analysis

Activate the virtual environment, then open `notebooks/eda.ipynb`.

The notebook covers:

- Class balance across train and test splits
- Image width and height distributions
- Sample cat and dog images
- Pixel intensity comparison
- Data augmentation previews (flip, rotation, zoom, contrast, translation)
