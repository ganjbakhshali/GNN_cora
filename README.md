# GNN Citations Analysis

This project analyzes citations using Graph Neural Networks (GNNs) in a Jupyter Notebook. It includes functions for data preprocessing, graph construction, training, and evaluating GNN models on citation data.

## Table of Contents
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

---

## Getting Started

To run the project locally, clone this repository and install the required packages as explained below. The notebook provides step-by-step instructions to run each part of the analysis.

### Prerequisites
This project requires:
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Git

Additionally, you will need the following Python packages:
- numpy
- pandas
- torch (PyTorch)
- networkx
- matplotlib

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ganjbakhshali/GNN_cora.git
   cd GNN_cora

2. **Install the required Python packages:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # on Windows, use `venv\Scripts\activate`

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt

4. **Start Jupyter Notebook:**
    ```bash
    jupyter notebook

5. Open the `gnn_citations.ipynb` notebook in your browser to get started.

## Usage

To use this notebook:
1. **Data Loading**: Load the dataset in the initial cell and prepare it for processing.
2. **Data Preprocessing**: Follow the data preprocessing steps to create the graph structures required for GNN training.
3. **GNN Training**: Train the GNN model on the citation dataset.
4. **Evaluation and Analysis**: Use evaluation metrics to analyze the model performance and interpret the results.

---

## File Structure

- **gnn_citations.ipynb** - Main notebook for data processing, model training, and evaluation.
- **requirements.txt** - Lists the required dependencies for this project.
- **README.md** - Project overview and instructions.

---

## Features

- **Graph Construction**: Builds graphs from citation data for GNN training.
- **Training Pipeline**: Defines a GNN training pipeline using PyTorch.
- **Evaluation Metrics**: Calculates accuracy, F1-score, and other metrics to assess model performance.
- **Visualization**: Provides plots to visualize the training progress and graph structure.

---

## Contributing

1. Fork the repository.
2. Create a new branch with a descriptive name (e.g., `feature-new-feature`).
3. Make and commit your changes.
4. Push to your fork and submit a pull request.

---

## License

This project is licensed under the MIT License.

---

If you encounter any issues or have questions, please feel free to open an issue in the repository.
