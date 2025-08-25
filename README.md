# Sugarcane Leaf Disease Detection

This project implements a machine learning model to detect diseases in sugarcane leaves using TensorFlow and Keras.

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies**:
   Make sure you have Python installed. Then, install the required libraries using pip:
   ```bash
   pip install tensorflow
   ```

3. **Prepare the dataset**:
   Place your dataset in the `dataset_filter` directory. The directory structure should be as follows:
   ```
   dataset_filter/
       ├── not_sugarcane_leaf/
       │   ├── image1.jpg
       │   └── image2.jpg
       └── sugarcane_leaf/
           ├── image1.jpg
           └── image2.jpg
   ```

## Running the Project

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook filter-image.ipynb
   ```

2. Run the cells in the notebook to train the model. The model will be saved as `sugarcane_filter.h5` after training.

## Model Architecture

The model uses MobileNetV2 as a base with additional layers for classification. It is trained to classify images into two categories: sugarcane leaves and not sugarcane leaves.

## Acknowledgments

- TensorFlow and Keras for providing the framework for building and training the model.
- The dataset used for training and validation.
