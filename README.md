# 🐟 Fish Classification CNN

A machine learning application dedicated to the automated classification of fish species utilizing Convolutional Neural Networks (CNN). The primary objective is to process, evaluate, and accurately categorize image data of various fish species. By leveraging deep learning architectures, this application is engineered to extract intricate visual features from raw images, outputting structured classifications to support automated sorting systems and computer vision research.

## 🚀 Tech Stack

* **Deep Learning Framework**: TensorFlow / Keras
* **Development Environment**: Jupyter Notebook
* **Programming Language**: Python
* **Data Processing & Visualization**: NumPy, Pandas, Matplotlib / OpenCV (Standard visual pipeline libraries)

## 📂 Repository Structure

* `Sotes_CNN.ipynb`: The core execution notebook containing the full machine learning pipeline. This includes data loading, preprocessing, model architecture construction, training loops, and performance evaluation.
* `fish_model.keras`: The serialized, pre-trained Convolutional Neural Network model. This file contains the optimized weights and network architecture, ready for immediate inference or further transfer learning.
* `Deployment Testing Images/`: A dedicated directory containing a subset of unseen image data. These images are utilized to simulate real-world conditions and validate the model's predictive accuracy post-training.
* `Sotes_CNN.pdf`: A static, exported version of the primary notebook, provided for immediate academic review, presentation, and offline reference.
* `Fish_Classification_CNN/`: Source directory containing supplementary scripts and dataset structural components.

## 📋 Prerequisites

Before executing the notebook or utilizing the model, ensure your local environment has the following dependencies installed:
* **Python** (v3.8 or higher recommended)
* **Jupyter Notebook** or **JupyterLab**
* **TensorFlow** (v2.x)

## 🛠️ Installation & Usage

Follow these structural steps to replicate the environment and test the classification model:

**1. Clone the repository**
```bash
git clone [https://github.com/tenshi-janai/Fish_Classification_CNN.git](https://github.com/tenshi-janai/Fish_Classification_CNN.git)
cd Fish_Classification_CNN

```

**2. Install required Python packages**
It is highly recommended to use a virtual environment. Install the standard deep learning dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python jupyter

```

**3. Launch the Jupyter Environment**

```bash
jupyter notebook

```

**4. Execute the Pipeline**

* Open `Sotes_CNN.ipynb` within the Jupyter interface.
* Run the cells sequentially to observe the data pipeline, view the model summary, and execute the training process.
* To bypass training and test the model immediately, load the pre-trained `fish_model.keras` file and run inference directly on the files located in the `Deployment Testing Images/` folder.

## 📄 License

This project is open-source. Please adhere to standard open-source academic and developmental licensing when utilizing or modifying the model architecture.
