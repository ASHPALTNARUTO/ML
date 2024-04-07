
# LeNet-5 Implementation with PyTorch

This Jupyter notebook provides a complete implementation and training of the LeNet-5 convolutional neural network using the PyTorch framework. The model is trained and evaluated using the MNIST dataset of handwritten digits.

## Prerequisites

- Python 3.x
- PyTorch
- torchvision
- matplotlib (for plotting training loss and visualizing images)

## Installation

Clone this repository and install the required Python packages:

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## Dataset

The notebook uses the MNIST dataset, which is automatically downloaded via the `torchvision.datasets` module.

## Model

LeNet-5 is a convolutional neural network suitable for various image classification tasks. In this notebook, it is used for recognizing handwritten digits.

## Training

The training process is detailed in the notebook, including data preprocessing, model initialization, loss function definition, and the training loop.

## Evaluation

The notebook includes a section for evaluating the trained model's accuracy on the test dataset.

## Visualization

Functions for plotting training loss and visualizing sample images from the dataset are included, providing insights into the model's learning process.

## Running the Notebook

Ensure you have Jupyter installed, then start the Jupyter notebook server:

```bash
jupyter notebook
```

Navigate to the `LeNet_5.ipynb` file in the Jupyter UI to open and run the notebook.

## Contributing

Feel free to fork the repository, make changes, and submit pull requests to contribute to this project.
