# CNN Performance Comparison on MNIST Dataset

This project compares the performance of three different Convolutional Neural Network (CNN) architectures on the MNIST dataset using TensorFlow and Keras. The MNIST dataset is sourced from Kaggle in CSV format. For reference, we use the loaders from `tf.keras.datasets.mnist` to obtain the data directly.

### CNN Architectures:
1. **Regular CNN** - Increases the number of filters with network depth.
2. **Inverted CNN** - Decreases the number of filters with network depth.
3. **Hourglass CNN** - Increases filters up to the middle layer, then decreases.

### Requirements
Please install the required packages using:
```bash
pip install -r requirements.txt
