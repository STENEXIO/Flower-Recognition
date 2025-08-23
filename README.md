# FlowerVision 🌹​

A deep learning project for automatic flower recognition using
TensorFlow and CNNs. Classifies flower images from the Kaggle Flowers
Recognition dataset with high accuracy. 📊

## 📖 Overview

FlowerVision is a convolutional neural network (CNN) model built with
TensorFlow to identify flower species from images. It includes data
preprocessing, model training, evaluation, and visualization of
predictions. Perfect for computer vision enthusiasts! 🚀

## 🛠 Features

-   **Dataset**: Uses the [Kaggle Flowers Recognition
    dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition)
    🌼
-   **Model**: CNN with Conv2D, MaxPooling, and Dense layers
-   **Preprocessing**: Image normalization and optimized data loading
-   **Evaluation**: Splits data into 80% training, 10% validation, 10%
    test
-   **Visualization**: Displays predictions and incorrect
    classifications 📈

## 📋 Requirements

-   Python 3.6+ 🐍
-   TensorFlow
-   NumPy
-   Matplotlib
-   KaggleHub
-   OS

Install dependencies:

``` bash
pip install tensorflow numpy matplotlib kagglehub
```

## 🚀 Getting Started

1.  **Clone the Repository**:

    ``` bash
    git clone https://github.com/shahin-ro/FlowerVision.git
    cd FlowerVision
    ```

2.  **Download the Dataset**: Ensure Kaggle API is configured. The
    dataset is downloaded automatically via KaggleHub.

3.  **Run the Notebook**: Open `Flower_Recognition.ipynb` in Jupyter
    Notebook or Colab and execute the cells.

## 📂 Project Structure

-   `Flower_Recognition.ipynb`: Main notebook with data loading, model
    training, and visualization.
-   `README.md`: Project documentation (you're here!).

## 🧠 How It Works

1.  **Data Loading**: Downloads and splits the Kaggle dataset into
    training (80%), validation (10%), and test (10%) sets.
2.  **Preprocessing**: Normalizes images to \[0,1\] and optimizes data
    pipelines with caching and prefetching.
3.  **Model Training**: Trains a CNN with 10 epochs using Adam optimizer
    and sparse categorical crossentropy.
4.  **Evaluation**: Tests model accuracy and visualizes predictions,
    including incorrect ones.

## 📊 Results

-   **Accuracy**: Evaluated on the test set with visualized predictions.
-   **Visualizations**: Shows up to 10 test images with true/predicted
    labels and highlights incorrect predictions.

## 🤝 Contributing

Contributions are welcome! 🌟 Fork the repo, make changes, and submit a
pull request. Please follow the coding style and add tests where
applicable.

## 📜 License

This project is licensed under the MIT License. See the
[LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

-   [Kaggle](https://www.kaggle.com) for the dataset
-   TensorFlow team for the awesome library
-   Community for inspiration and support
