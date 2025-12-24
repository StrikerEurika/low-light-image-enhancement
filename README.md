# Low-Light Image Enhancement

This project focuses on enhancing images captured in low-light conditions using advanced image processing and deep learning techniques.

## Project Overview

Low-light images often suffer from poor visibility, noise, and color distortion. This project aims to improve the visual quality of such images, making them clearer and more suitable for further analysis or display.

## Features

- Image enhancement algorithms for low-light conditions
- Deep learning-based enhancement models
- Evaluation metrics for image quality
- Support for batch processing

## Data Description

### Dataset

The project uses a dataset of paired low-light and normal-light images. Each pair consists of:

- **Low-light image:** Captured under poor lighting conditions.
- **Reference image:** The same scene captured under normal lighting.

#### Data Structure

```
dataset/
├── low/
│   ├── img1.png
│   ├── img2.png
│   └── ...
└── normal/
    ├── img1.png
    ├── img2.png
    └── ...
```

- `low/`: Contains low-light images.
- `normal/`: Contains corresponding normal-light reference images.

### Data Sources

- Public datasets such as LOL (Low-Light) Dataset, SID, or custom-collected images.

## Getting Started

1. Clone the repository.
2. Prepare the dataset as described above.
3. Follow the instructions in the code to train or test the enhancement models.

## Requirements

- Python 3.7+
- PyTorch or TensorFlow
- OpenCV
- NumPy

## Usage

Refer to the scripts in the `src/` directory for training and testing.

## License

This project is licensed under the MIT License.

## Acknowledgements

- LOL Dataset: https://daooshee.github.io/BMVC2018website/
- SID Dataset: https://see-in-the-dark.mit.edu/
- Open-source contributors

meow
