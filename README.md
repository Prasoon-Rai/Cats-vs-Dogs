# Cats vs Dogs Image Classifier

This project contains a Jupyter notebook that demonstrates how to build and train a convolutional neural network (CNN) to classify images of cats and dogs using Keras and TensorFlow.

## Key Features

- **Data Loading:** Uses `tf.keras.utils.image_dataset_from_directory` to load and preprocess images from a directory structure.
- **Model Architecture:** Implements a simple CNN with convolutional, dense, and dropout layers for binary classification.
- **Training:** Trains the model using the AdamW optimizer and binary cross-entropy loss.
- **Evaluation:** Visualizes training history and evaluates model performance.
- **Prediction:** Loads and preprocesses new images (from local files or URLs) and predicts whether the image is a cat or a dog.

## Technologies Used

- [TensorFlow](https://www.tensorflow.org/) & [Keras](https://keras.io/): For building and training the neural network.
- [NumPy](https://numpy.org/): For numerical operations and image preprocessing.
- [Matplotlib](https://matplotlib.org/): For plotting training metrics.
- [Pillow (PIL)](https://python-pillow.org/): For image loading and processing.
- [Requests](https://docs.python-requests.org/): For downloading images from URLs.

## Usage

1. Place your dataset in a folder named `cats_vs_dogs` with subfolders for each class (e.g., `cats/`, `dogs/`).
2. Open and run the `cats_vs_dogs.ipynb` notebook.
3. Follow the notebook cells to train the model and make predictions.
