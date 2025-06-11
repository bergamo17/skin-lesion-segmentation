# Skin Lesion Segmentation with Semi-Supervised GAN

This project focuses on segmenting skin lesions using a semi-supervised Generative Adversarial Network (GAN) approach implemented in PyTorch. The goal is to improve segmentation accuracy when labeled data is limited by leveraging unlabeled images.

## Features

- Semi-supervised learning using GAN
- PyTorch-based model architecture
- Image preprocessing and augmentation
- Evaluation metrics such as Dice Score and IoU

## Folder Structure

```
├── Semi-supervised GAN for Lesion Segmentation.ipynb     # Jupyter notebook with full implementation
├── README.md             # This documentation file
```

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/skin-lesion-segmentation.git
   cd skin-lesion-segmentation
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Run the Notebook

Open the notebook using Jupyter:

```bash
jupyter Semi-supervised GAN for Lesion Segmentation.ipynb
```

## Requirements

- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- scikit-learn
- torchvision
- OpenCV (cv2)

> You may create a `requirements.txt` using:
```bash
pip freeze > requirements.txt
```

## License

This project is licensed under the MIT License.
