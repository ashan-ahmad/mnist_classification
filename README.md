# MNIST Classification with Neural Networks

This project demonstrates the classification of the MNIST dataset using neural networks built with Keras. The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9) and is a standard benchmark for machine learning models.

## Features

- **Data Preprocessing**: 
  - Flattening 28x28 images into 1D vectors.
  - Normalizing pixel values to the range [0, 1].
  - One-hot encoding of target labels.

- **Model Architectures**:
  - A neural network with 3 dense layers.
  - A neural network with 6 dense layers for comparison.

- **Training and Evaluation**:
  - Training models for 10 epochs and evaluating their accuracy.
  - Saving and loading models for further training.

- **Comparison**:
  - Comparing the performance of models with different architectures.
  - Further training a pre-trained model to observe improvements.

## Files

- **MNIST_Classification.ipynb**: Jupyter Notebook containing the code for data preprocessing, model building, training, and evaluation.

## Requirements

- Python 3.x
- Keras
- TensorFlow
- Matplotlib

## How to Run

1. Clone the repository.
2. Install the required libraries using `pip install keras tensorflow matplotlib`.
3. Open the `MNIST_Classification.ipynb` file in Jupyter Notebook.
4. Run the cells sequentially to preprocess the data, build models, train them, and evaluate their performance.

## Results

- The project compares the accuracy of a 3-layer neural network and a 6-layer neural network.
- It also demonstrates how further training a pre-trained model can improve accuracy.

## Dataset

The MNIST dataset is included in the Keras library and is automatically downloaded when running the code.

## References

- [Keras Documentation](https://keras.io/)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

## License

This project is licensed under the MIT License.
