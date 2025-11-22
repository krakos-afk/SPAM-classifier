## Overview

This project uses BERT (Bidirectional Encoder Representations from Transformers) to classify messages as spam or not spam. The primary goal is to provide a robust and accurate model for spam detection using state-of-the-art natural language processing techniques.

## Features

- Leverages BERT for advanced text understanding and classification
- Developed and trained in Jupyter Notebook for easy experimentation and iteration
- Clean, well-organized, and reproducible codebase
- Easily customizable for different spam datasets

## Requirements

- Python 3.7+
- Jupyter Notebook
- PyTorch **or** TensorFlow (depending on your chosen BERT implementation)
- [Transformers](https://pypi.org/project/transformers/) library (`pip install transformers`)
- `pandas`, `numpy`, `scikit-learn`

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/krakos-afk/SPAM-classifier.git
   cd SPAM-classifier
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open the main notebook and follow the instructions to load your data, train the model, and evaluate its performance.

## Usage

1. Prepare your dataset (CSV or similar format) with labeled spam/not-spam messages.
2. Update the notebook with the path to your dataset.
3. Run the notebook cells to train the classifier.
4. Use the trained model to classify new messages.


## License

This project is licensed under the MIT License.
