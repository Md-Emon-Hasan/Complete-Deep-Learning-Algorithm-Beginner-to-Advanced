# Complete Deep Learning: Beginner to Advanced

<p align="center">
  <a href="https://github.com/Md-Emon-Hasan/Complete-Deep-Learning-Algorithm-Beginner-to-Advanced"><img src="https://img.shields.io/badge/Repository-Deep%20Learning-0A192F?style=for-the-badge&logo=github&logoColor=white" alt="Deep Learning repository"></a>
  <img src="https://img.shields.io/badge/Notebooks-46-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="46 Jupyter notebooks">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-Deep%20Learning-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Algorithms-Perceptron%20%7C%20Backpropagation-6A5ACD?style=flat-square" alt="Perceptron and backpropagation badges">
  <img src="https://img.shields.io/badge/Optimization-Gradient%20Descent%20%7C%20SGD%20%7C%20Mini--Batch-228B22?style=flat-square" alt="Gradient descent badges">
  <img src="https://img.shields.io/badge/Activations-Sigmoid%20%7C%20Tanh%20%7C%20ReLU-8A2BE2?style=flat-square" alt="Activation function badges">
  <img src="https://img.shields.io/badge/Models-ANN%20%7C%20CNN%20%7C%20RNN%20%7C%20LSTM%20%7C%20GRU-1E90FF?style=flat-square" alt="Deep learning model badges">
  <img src="https://img.shields.io/badge/NLP-Embeddings%20%7C%20Word2Vec-4B8BBE?style=flat-square" alt="NLP badges">
  <img src="https://img.shields.io/badge/Techniques-Dropout%20%7C%20BatchNorm%20%7C%20Augmentation-FF8C00?style=flat-square" alt="Training technique badges">
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square" alt="Apache 2.0 license">
</p>

<p align="center">
  <img src="Deep%20Learning.png" alt="Deep Learning banner" width="100%">
</p>

A practical, notebook-first deep learning learning path that moves from mathematical foundations and classical neural-network algorithms to computer vision, sequence models, NLP, and TensorFlow data pipelines. The repository brings together two complementary collections with **Jupyter notebooks**, datasets, visual explanations, and hands-on projects.

## Contents

- [Learning collections](#learning-collections)
- [What you will learn](#what-you-will-learn)
- [Algorithm and technique map](#algorithm-and-technique-map)
- [Repository structure](#repository-structure)
- [Getting started](#getting-started)
- [Datasets and practical notes](#datasets-and-practical-notes)
- [How to study the notebooks](#how-to-study-the-notebooks)
- [Contributing](#contributing)
- [License](#license)
- [Connect with me](#connect-with-me)

## Learning collections

The repository is organized into two independent collections. Each one has its own detailed README, learning roadmap, and setup guidance.

| Collection | Focus | Lessons |
|---|---|---|
| [100 Days of Deep Learning — CampusX](./100-Days-of-Deep-Learning-CampusX/README.md) | Neural-network intuition and practice: perceptrons, backpropagation, optimization, training improvements, ANN/CNN, and recurrent models. | 24 notebooks across the available day folders |
| [Deep Learning with TensorFlow and Keras — Codebasics](./Deep-Learning-with-Tensorflow-and-Keras-From-Codebasics/README.md) | Foundations through TensorFlow/Keras applications: classification, evaluation, image models, transfer learning, embeddings, Word2Vec, and input pipelines. | 22 notebooks across the numbered lessons |

The collections are useful independently. For a guided route, begin with the perceptron and matrix lessons, continue through gradient-based learning and training techniques, then explore CNN, RNN, and NLP applications.

## What you will learn

### Foundations and optimization

- Matrix operations and neural-network building blocks
- Perceptron geometry, the perceptron trick, and perceptron loss
- Forward propagation, backpropagation, and gradient-based learning
- Batch, stochastic, and mini-batch gradient descent
- Sigmoid, tanh, ReLU, and leaky ReLU activation functions
- Loss functions, predictions, and decision boundaries

### Training and evaluation

- Data preparation, feature scaling, and encoding
- Weight initialization, including Xavier/Glorot and He methods
- Early stopping, dropout, regularization, and batch normalization
- Confusion matrices, accuracy, precision, recall, and F1 score
- Class imbalance strategies, including class weighting, resampling, and SMOTE
- Training curves and practical ways to compare model behavior

### Computer vision

- ANN classification for handwritten digits
- CNN fundamentals: padding, strides, convolution, and pooling
- CIFAR-10 image classification
- Cat-vs-dog image classification
- Image augmentation and transfer learning

### Sequences and language

- Keras embedding layers and Word2Vec with Gensim
- SimpleRNN, stacked RNN, LSTM, and GRU architectures
- IMDB sentiment analysis and next-word prediction

### TensorFlow workflow

- `tf.data.Dataset` pipelines and transformations
- Dataset filtering, mapping, shuffling, and batching
- Caching and prefetching to improve input-pipeline throughput
- TensorBoard for inspecting model training

## Algorithm and technique map

| Category | Algorithms and methods in the notebooks |
|---|---|
| Linear classifiers | Perceptron, perceptron trick, perceptron loss |
| Optimization | Gradient descent, batch gradient descent, stochastic gradient descent, mini-batch gradient descent, backpropagation |
| Activations | Sigmoid, tanh, ReLU, leaky ReLU |
| Loss and evaluation | Mean absolute error, binary cross-entropy, confusion matrix, accuracy, precision, recall, F1 score |
| Neural architectures | Artificial neural networks (ANN), convolutional neural networks (CNN), SimpleRNN, stacked RNN, LSTM, GRU |
| Generalization | Dropout, regularization, early stopping, data augmentation, batch normalization |
| Initialization | Zero, Xavier/Glorot, and He initialization |
| Imbalanced learning | Class weights, undersampling, oversampling, SMOTE, and ensemble-style undersampling |
| NLP | Trainable word embeddings and Word2Vec |
| Input pipeline | `tf.data`, caching, and prefetching |

## Repository structure

```text
.
├── 100-Days-of-Deep-Learning-CampusX/
│   ├── README.md
│   └── numbered day folders with notebooks and lesson data
├── Deep-Learning-with-Tensorflow-and-Keras-From-Codebasics/
│   ├── README.md
│   └── numbered lesson folders with notebooks and lesson data
├── Deep Learning.png
├── LICENSE
└── README.md
```

Open the README inside a collection for its complete lesson-by-lesson index. Notebooks use files in their own lesson folders, so preserve the directory layout when opening or running them.

## Getting started

### Requirements

- Python 3.x (use a Python version supported by the TensorFlow release available for your operating system)
- Jupyter Notebook or JupyterLab
- Common packages used across the collections: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn, TensorFlow, Gensim, `imbalanced-learn`, OpenCV, and `mlxtend`

Not every notebook requires every package. The collection-specific README files list additional dataset requirements and setup details.

### Set up an environment

Clone the repository and move into its directory:

```bash
git clone https://github.com/Md-Emon-Hasan/Complete-Deep-Learning-Algorithm-Beginner-to-Advanced.git
cd Complete-Deep-Learning-Algorithm-Beginner-to-Advanced
```

Create and activate a virtual environment.

**Windows PowerShell**

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**macOS/Linux**

```bash
python -m venv .venv
source .venv/bin/activate
```

Install the libraries commonly used by the notebooks:

```bash
python -m pip install --upgrade pip
python -m pip install jupyter numpy pandas matplotlib seaborn scikit-learn tensorflow gensim imbalanced-learn opencv-python mlxtend
```

Start Jupyter from the repository root:

```bash
jupyter notebook
```

Choose a collection, open one of its lesson folders, and run a notebook from top to bottom. If a notebook needs a different package or a separately downloaded dataset, follow the notes in that collection's README and notebook.

## Datasets and practical notes

- Many lessons include their CSV, JSON, image, or other supporting files in the lesson folder. Keep those files beside the notebook and preserve relative paths.
- MNIST, CIFAR-10, and IMDB examples use Keras dataset helpers; an internet connection may be required the first time the dataset is downloaded.
- The CampusX cat-vs-dog project expects an `archive.zip` dataset that is not included. See that collection's README before running its data-preparation cells.
- The Codebasics Word2Vec lessons use review data. Git LFS is configured for JSON files in that collection; install Git LFS and run `git lfs pull` if a cloned file contains an LFS pointer instead of data.
- One Codebasics lesson folder currently contains its dataset without the corresponding lesson notebook. The collection README identifies this gap.
- Most examples are suitable for CPU experimentation; image-model training may take longer without a GPU.
- Results can vary with package versions, random initialization, hardware, and dataset availability. These notebooks are educational examples rather than benchmark guarantees.

## How to study the notebooks

1. Choose a topic from the roadmap in either collection's README.
2. Read the notebook's explanations before running its cells.
3. Run cells in order, from the correct lesson folder, so relative data paths resolve.
4. Change one setting at a time—such as learning rate, activation, model size, or regularization—and compare the result.
5. Use plots, metrics, and predictions to connect the algorithm to its behavior.

## Contributing

Corrections, clearer explanations, and focused lessons are welcome.

1. Fork the repository and create a branch.
2. Keep new material in the appropriate collection and follow its numbered folder style where practical.
3. Include data instructions and package requirements for any new notebook.
4. Avoid committing credentials, generated environments, caches, or large datasets without a clear need.
5. Open a pull request describing the change and how to follow or review it.

## License

This project is distributed under the Apache License 2.0. See [LICENSE](./LICENSE) for details.

## Connect with me

I'm **Md Emon Hasan**, a machine learning engineer interested in deep learning, applied machine learning, and practical AI projects. Reach out for questions, feedback, or collaboration.

- 🌐 **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- 💻 **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- 💼 **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- 🤗 **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- 📧 **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- 📱 **WhatsApp:** [+8801834363533](https://wa.me/8801834363533)

---

<p align="center">If these learning notes help you, please consider starring the repository. ⭐</p>
