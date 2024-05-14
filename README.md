# Image Classification with PyTorch

This repository contains the code for an image classification model implemented in PyTorch. The model is trained and evaluated on a custom dataset. The dataset consists of 5000 images across 10 classes, with images split into training, validation, and test sets.

## Dataset

The dataset is structured as follows:
- **Number of images**: 5000
- **Number of classes**: 10
- **Resolution of each image**: 64 x 64

### Splits
- **Train**: 3000 images
- **Validation**: 500 images
- **Test**: 1500 images

### Folder Structure
After extracting the dataset, the folder structure should be:

### CSV Files
Each CSV file contains the following columns:
- `image_name`: Name of the image
- `image_path`: Relative path to the image
- `class_id`: ID of the class the image belongs to (not available in test.csv)
- `class_name`: Name of the class the image belongs to (not available in test.csv)

## Requirements

- Python 3.x
- PyTorch
- torchvision
- pandas
- numpy
- matplotlib
- tqdm

You can install the required libraries using pip:
```bash
pip install torch torchvision pandas numpy matplotlib tqdm