# 100 Days of Deep Learning — CampusX

![Python](https://img.shields.io/badge/python-3.x-blue.svg?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-FF6F00?logo=tensorflow&logoColor=white)
![Perceptron](https://img.shields.io/badge/Algorithm-Perceptron-6A5ACD)
![Backpropagation](https://img.shields.io/badge/Algorithm-Backpropagation-6A5ACD)
![Gradient Descent](https://img.shields.io/badge/Optimization-Gradient%20Descent-2E8B57)
![CNN](https://img.shields.io/badge/Model-CNN-1E90FF)
![RNN](https://img.shields.io/badge/Model-RNN-1E90FF)
![LSTM](https://img.shields.io/badge/Model-LSTM-1E90FF)
![GRU](https://img.shields.io/badge/Model-GRU-1E90FF)
![Classification](https://img.shields.io/badge/Task-Classification-8A2BE2)
![License](https://img.shields.io/github/license/Md-Emon-Hasan/100-Days-of-Deep-Learning-CampusX)

**A hands-on deep learning learning log with Jupyter notebooks, visual explanations, and practical model-building projects.**

This repository accompanies my **100 Days of Deep Learning** journey with CampusX. It brings together the notebooks and datasets available in this repository, progressing from perceptrons and neural-network fundamentals to CNNs, recurrent networks, and applied classification and text-generation projects.

## Table of Contents

- [About the Project](#about-the-project)
- [Learning Roadmap](#learning-roadmap)
- [Topics and Skills](#topics-and-skills)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Datasets and Requirements](#datasets-and-requirements)
- [How to Use the Notebooks](#how-to-use-the-notebooks)
- [Learning Outcomes](#learning-outcomes)
- [Contributing](#contributing)
- [License](#license)
- [Connect With Me](#connect-with-me)

## About the Project

The goal of this repository is to learn deep learning by building and inspecting models—not just by collecting theory. The notebooks cover the intuition behind core algorithms, training behavior, common techniques for improving neural networks, and end-to-end examples using familiar datasets.

The current collection includes **Jupyter notebooks**. Topics include:

- Perceptrons, decision boundaries, and perceptron loss
- Backpropagation, gradient descent, and training dynamics
- Vanishing gradients, early stopping, feature scaling, dropout, and regularization
- Weight initialization and batch normalization
- Artificial neural network classification projects
- CNN padding, strides, and pooling
- SimpleRNN, stacked RNN/LSTM/GRU models, sentiment analysis, and next-word prediction

## Learning Roadmap

| Day | Topic | What you will find |
| --- | --- | --- |
| [4](./4%20Perceptron%20Geometric%20Intuition/) | Perceptron geometric intuition | Explore a perceptron's decision boundary with a placement dataset and visualizations. |
| [5](./5%20Perceptron%20Trick/) | Perceptron trick | Build intuition for updating a linear classifier on a synthetic classification problem. |
| [6](./6%20Perceptron%20Loss%20Function/) | Perceptron loss function | Visualize and work with a loss function for a perceptron classifier. |
| [11](./11%20Customer%20Churn%20Prediction%20using%20ANN/) | Customer churn prediction with an ANN | Prepare tabular data and train a Keras neural network for binary classification. Includes `Churn_Modelling.csv`. |
| [12](./12%20Handwritten%20Digit%20Classification%20using%20ANN%20%20MNIST%20Dataset/) | Handwritten digit classification | Train an ANN on the MNIST handwritten-digit dataset. |
| [16](./16%20Backpropagation/) | Backpropagation | Compare hand-worked backpropagation examples for regression and classification. |
| [19](./19%20Gradient%20Descent%20in%20Neural%20Networks/) | Gradient descent in neural networks | Explore optimization and model training with a social-network ads dataset. |
| [20](./20%20Vanishing%20Gradient%20Problem%20in%20ANN/) | Vanishing gradient problem | Investigate how gradients and activation choices affect deep ANN training. |
| [22](./22%20Early%20Stopping%20In%20Neural%20Networks/) | Early stopping | Use validation behavior and callbacks as a training regularization technique. |
| [23](./23%20Data%20Scaling%20in%20Neural%20Network/) | Data scaling | Apply feature scaling and examine its role in neural-network optimization. Includes `Social_Network_ads.csv`. |
| [25](./25%20Dropout%20Layers%20in%20ANN/) | Dropout layers | Add dropout to an ANN and inspect its effect on generalization. |
| [26](./26%20Regularization%20in%20Deep%20Learning/) | Regularization | Explore regularization methods for reducing overfitting in neural networks. |
| [29](./29%20Weight%20Initialization%20Techniques/) | Weight initialization | Compare zero initialization with ReLU and sigmoid activations. Includes `ushape.csv`. |
| [30](./30%20XavierGlorat%20And%20He%20Weight%20Initialization%20in%20Deep%20Learning/) | Xavier/Glorot and He initialization | Study initialization strategies with a neural network and decision-region visualizations. Includes `ushape.csv`. |
| [31](./31%20Batch%20Normalization%20in%20Deep%20Learning/) | Batch normalization | Add batch normalization to a neural network. Includes `concertriccir.csv`. |
| [43](./43%20Padding%20%26%20Strides%20in%20CNN/) | Padding and strides in CNNs | Examine convolution settings and their effect on feature-map dimensions using MNIST. |
| [44](./44%20Pooling%20Layer%20in%20CNN/) | Pooling layers in CNNs | Explore max pooling in a convolutional model using MNIST. |
| [49](./49%20Cat%20Vs%20Dog%20Image%20Classification%20Project/) | Cat-vs-dog image classification | Build a CNN image-classification workflow. The notebook expects a separately downloaded `archive.zip`; sample cat and dog images are included. |
| [57](./57%20RNN%20Sentiment%20Analysis/) | Sentiment analysis with a SimpleRNN | Prepare IMDB reviews with integer encoding and train a recurrent sentiment classifier. |
| [63](./63%20Next%20Word%20Predictor%20Using/) | Next-word prediction | Prepare text sequences and train an LSTM-based next-word predictor. |
| [65](./65%20Stacked%20RNNs%20%20Stacked%20LSTMs%20%20Stacked%20GRUs/) | Stacked RNNs, LSTMs, and GRUs | Experiment with stacked recurrent architectures on the IMDB dataset. |

## Topics and Skills

### Neural-network foundations

- Perceptron geometry, classification, and loss
- Forward propagation and backpropagation
- Gradient descent and model training
- Activation functions and vanishing gradients

### Improving model training

- Feature scaling
- Early stopping
- Dropout and regularization
- Zero, Xavier/Glorot, and He weight initialization
- Batch normalization

### Applied deep learning

- ANN classification for customer churn and handwritten digits
- CNN building blocks, including convolution padding, strides, and pooling
- Image classification with a cat-vs-dog dataset
- Text preprocessing, embeddings, SimpleRNN, LSTM, and GRU models
- IMDB sentiment classification and next-word prediction

## Repository Structure

```text
.
├── 4 Perceptron Geometric Intuition/
├── 5 Perceptron Trick/
├── 6 Perceptron Loss Function/
├── 11 Customer Churn Prediction using ANN/
├── 12 Handwritten Digit Classification using ANN  MNIST Dataset/
├── 16 Backpropagation/
├── 19 Gradient Descent in Neural Networks/
├── 20 Vanishing Gradient Problem in ANN/
├── 22 Early Stopping In Neural Networks/
├── 23 Data Scaling in Neural Network/
├── 25 Dropout Layers in ANN/
├── 26 Regularization in Deep Learning/
├── 29 Weight Initialization Techniques/
├── 30 XavierGlorat And He Weight Initialization in Deep Learning/
├── 31 Batch Normalization in Deep Learning/
├── 43 Padding & Strides in CNN/
├── 44 Pooling Layer in CNN/
├── 49 Cat Vs Dog Image Classification Project/
├── 57 RNN Sentiment Analysis/
├── 63 Next Word Predictor Using/
├── 65 Stacked RNNs  Stacked LSTMs  Stacked GRUs/
├── LICENSE
└── README.md
```

Each numbered directory groups the notebook and any local data or sample images used by that topic. The table above links directly to each folder.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Md-Emon-Hasan/100-Days-of-Deep-Learning-CampusX.git
cd 100-Days-of-Deep-Learning-CampusX
```

### 2. Create and activate a virtual environment (recommended)

```bash
python -m venv .venv
```

Activate it on **Windows PowerShell**:

```powershell
.venv\Scripts\Activate.ps1
```

Activate it on **macOS/Linux**:

```bash
source .venv/bin/activate
```

### 3. Install the notebook dependencies

```bash
python -m pip install --upgrade pip
python -m pip install jupyter numpy pandas matplotlib seaborn scikit-learn tensorflow opencv-python mlxtend
```

The notebooks use these packages as needed; not every notebook requires every package. Choose Python and TensorFlow versions that are compatible with your operating system and hardware.

### 4. Start Jupyter and open a notebook

```bash
jupyter notebook
```

Open a day folder and run its notebook cells from top to bottom. Some notebooks load local CSV files by relative path, so launch Jupyter from the repository and keep each notebook's companion data file in its existing folder. MNIST and IMDB datasets are loaded through Keras and may be downloaded the first time they are used.

## Datasets and Requirements

- **Included CSV files:** `Churn_Modelling.csv`, `Social_Network_ads.csv`, `placement.csv`, `ushape.csv`, and `concertriccir.csv` are stored alongside the relevant notebooks.
- **MNIST and IMDB:** These are requested by the notebooks through Keras dataset helpers; an internet connection may be needed for the initial download.
- **Cat-vs-dog images:** The Day 49 notebook opens a file named `archive.zip` and extracts it. Download and place that dataset archive in the working directory expected by the notebook before running its data-preparation cells. The repository also includes `my_cat.jpeg` and `my_dog.jpg` sample images.
- **Compute:** Most examples can be explored on a CPU. CNN training can take longer without a GPU.

## How to Use the Notebooks

1. Pick a topic from the [learning roadmap](#learning-roadmap).
2. Read the notebook cells in order, including markdown explanations and plots.
3. Run the cells sequentially so variables and prepared data are available to later cells.
4. Change a parameter—such as a learning rate, hidden-layer size, or regularization setting—and compare the result.
5. Record what changed and why; use the visualizations to connect model behavior to the concepts.

Notebook outputs may differ with library versions, random initialization, and hardware. If a dataset path fails, check that the notebook's working directory is the corresponding day folder and that the required file is present.

## Learning Outcomes

Working through these examples can help you build practical familiarity with:

- How simple neural networks represent decision boundaries and learn from errors
- How gradients and optimization update model parameters
- Why scaling, initialization, normalization, and regularization matter
- How to structure ANN and CNN classification workflows
- How to encode text and apply recurrent layers to sequence tasks
- How to inspect training curves, predictions, and model behavior in notebooks

## Contributing

Suggestions, corrections, and learning-focused improvements are welcome. To contribute:

1. Fork this repository.
2. Create a branch for your change:

   ```bash
   git checkout -b docs/improve-notebook-guide
   ```

3. Make a focused change and include any required dataset or setup notes.
4. Commit and push your branch:

   ```bash
   git add .
   git commit -m "Improve notebook guide"
   git push origin docs/improve-notebook-guide
   ```

5. Open a pull request describing the change.

Please avoid committing large datasets, credentials, or generated environment folders. For notebook changes, clear accidental outputs or personal paths where appropriate and explain any extra dependencies.

## License

This project is distributed under the **Apache License 2.0**. See [LICENSE](./LICENSE) for the full license text.

## Connect With Me

I'm **Md Emon Hasan**, a machine learning engineer sharing my deep learning practice and projects. Feel free to connect, ask a question, or discuss collaboration.

- 🌐 **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- 💻 **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- 💼 **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- 🤗 **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- 📧 **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- 📱 **WhatsApp:** [+880 1834-363533](https://wa.me/8801834363533)

---

<p align="center">Built as part of my continuous deep learning journey. ⭐ If this repository helps you, consider giving it a star.</p>
