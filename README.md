
# DeepLearning-CNN-FMNIST-Experiments

This repository contains Jupyter Notebooks for training Convolutional Neural Networks (CNNs) on the Fashion MNIST (FMNIST) dataset using PyTorch. The focus is on understanding the effects of regularization and data augmentation techniques on model performance.

## Notebooks

- `PytorchCNNFnistWithoutRegularization.ipynb`: Training a CNN on FMNIST without regularization.
- `PytorchCNNFnistWithRegularization.ipynb`: Applying regularization methods to train the CNN.
- `dataAugmentation.ipynb`: Using data augmentation techniques to enhance model performance.

## What is Regularization?

Regularization involves techniques to prevent overfitting, ensuring the model generalizes well to new data. Common methods include:

- **L1 Regularization**: Adds the absolute value of coefficients as a penalty term to the loss function, promoting sparsity.
- **L2 Regularization**: Adds the squared value of coefficients as a penalty term to the loss function, discouraging large weights.
- **Dropout**: Randomly drops neurons during training to prevent co-adaptation of features.
- **Batch Normalization**: Normalizes the inputs of each layer to accelerate training and improve stability.
- **Data Augmentation**: Generates new training examples through random transformations, increasing the diversity of the training set.
- **Early Stopping**: Stops training when the validation performance deteriorates to prevent overfitting.


## What is Data Augmentation?

Data augmentation involves creating modified versions of the dataset to improve model robustness and performance. Common techniques include:

- **Rotation**: Rotating images by a random angle.
- **Translation**: Shifting images horizontally or vertically.
- **Scaling**: Resizing images.
- **Flipping**: Horizontally flipping images.
- **Noise Addition**: Adding random noise to images.

Explore these notebooks to see the impact of each technique on the training process and the final model accuracy.

## Getting Started

To run the notebooks, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FMNIST-Regularization-CNN.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd FMNIST-Regularization-CNN
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
