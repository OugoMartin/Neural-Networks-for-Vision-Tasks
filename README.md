# Neural Networks for Vision Tasks

A PyTorch learning lab covering automatic differentiation and neural-network workflows for image classification.

## What the notebook demonstrates
The notebook begins with PyTorch autograd and then works with the MNIST handwritten-digit dataset using torchvision. It demonstrates tensor operations, image preprocessing, data loaders, neural-network training concepts, and visual inspection of image data.

## Dataset
MNIST is downloaded through `torchvision.datasets.MNIST` when the notebook runs.

## Primary artifact
- `Neural_Networks_for_Vision_Tasks.ipynb`

## Tools
Python · PyTorch · torchvision · MNIST · Matplotlib · Jupyter/Colab

## Reproducibility
The notebook downloads MNIST automatically, but the repository does not yet include a pinned dependency file or standalone training package. Run the notebook sequentially in an environment with PyTorch, torchvision, and Matplotlib available.

## Portfolio positioning
This repository is best presented as a foundational deep-learning lab rather than a production computer-vision application. The more applied urban-scene repository demonstrates a broader classification workflow.

## Next improvements
Add `requirements.txt`, deterministic seeds, a concise architecture summary, recorded evaluation metrics, confusion-matrix output, and reusable training/evaluation functions.

## Author
Martin Ngare
