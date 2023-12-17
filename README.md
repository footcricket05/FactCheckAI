# FactCheckAI: Automated Fact-Checking System

## Overview
FactCheckAI is an automated fact-checking system leveraging deep learning to classify statements into 'true' or 'false' categories. This project aims to assist in the verification of information, particularly useful in the context of news articles, social media posts, and speeches.

## Project Structure
- `model.py`: The main script for building and training the LSTM-based deep learning model.
- `preprocess.py`: Contains functions for data cleaning and preprocessing.
- `requirements.txt`: Lists all the Python libraries required for the project.
- `utils/`: Additional utilities for text processing and data handling.
- `data/`: Directory for storing datasets (not included in the repository due to size and privacy concerns).

## Installation
To install the required libraries, run:
```
pip install -r requirements.txt
```

## Usage
1. Place your dataset in the `data/` directory.
2. Run `preprocess.py` to clean and preprocess the data.
3. Execute `model.py` to train and evaluate the model.

## Model Description
The model uses a sequential architecture with the following layers:
- Embedding layer for text vectorization
- Bidirectional LSTM for capturing context
- Dense layers for classification

The model is trained on preprocessed text data and outputs a binary classification indicating the veracity of the input statement.

## Data
The model expects a JSON dataset with statements and corresponding truth labels. Example format:
```json
{"verdict": "true", "statement": "Fact-check statement here"}
```

## Contributing
Contributions to FactCheckAI are welcome! Please refer to the contribution guidelines for more information.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
