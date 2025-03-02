# Resnet-Metrics

This project contains a ResNet-based deep learning model implemented in Python. It can be used for training, evaluating, and tracking metrics of the model. You can specify various configurations for the optimizer, CUDA usage, and data loading options through command-line arguments.

## Features

- ResNet model for image classification tasks.
- Configurable command-line options for training.
- Support for CUDA acceleration (GPU).
- Multiple optimizer options (e.g., Adam, SGD).
- Customizable data loading settings.

## Requirements

To run the code, ensure that you have the following Python libraries installed:

- `torch` (PyTorch)
- `torchvision`
- `numpy`
- `matplotlib` (for visualization)
- `pandas` (for logging and metrics)

You can install these dependencies using `pip`:

bash
pip install torch torchvision numpy matplotlib pandas

## Usage

To run the script, use the following command structure:

```bash
python lab2.py --cuda <y/n> --dataloaders <num_workers> --opt <optimizer> --datapath <path_to_data> 


