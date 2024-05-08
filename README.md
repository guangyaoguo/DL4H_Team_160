# Peptide Detectability Prediction with 1D-2C-CNN

This repository contains the implementation of a 1D Convolutional Neural Network (1D-2C-CNN) designed to predict peptide detectability based on amino acid sequences, as described in the associated research paper. This project aims to reproduce the results of the original study and explore the effectiveness of the model under various conditions.

## Dataset Description

The dataset used in this project is derived from the Global Proteome Machine Database (GPMDB), which provides a comprehensive collection of peptide detectability data from mass spectrometry experiments.

- **Source**: The original data is hosted by the Global Proteome Machine Database (GPMDB).
  - [GPMDB Website](https://www.thegpm.org/gpmdb/index.html)

For easier access and reproducibility, the dataset has also been made available through the GitHub repository of the original paper:
- **Download Link**: [Dataset GitHub Repository](https://github.com/vsegurar/DeepMSPeptide/tree/master/Datasets)

## Environment Setup

To run the code in this repository, you will need a Python environment with specific libraries installed. Below is the guide to setting up your environment and running the code.

### Python Version

- Python 3.8 is required for compatibility with all dependencies.

### Required Libraries

The following libraries are required to run the project:
- NumPy
- pandas
- TensorFlow
- Keras
- scikit-learn

### Installation

Install the required libraries using pip:

```bash
pip install numpy pandas tensorflow keras scikit-learn
```

### Running the Code
To run the model training and evaluation scripts, download the dataset documents, place them in suitable place after unzip, furthermore, ensure you have navigated to the correct directory where data is located, or adjust the path in the command accordingly.

### Reproduction Instructions
- **Download the Dataset: Follow the links provided in the Dataset section to download the necessary data.
- **Set up your Environment: Use the instructions under Environment Setup to prepare your Python environment.
- **Run the Scripts: Execute the scripts provided in the repository to train the model and reproduce the results.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
For any queries related to this repository, please contact:

Guangyao GUO
gg39@illinois.edu

