# 🕵️ FactCheckAI: Automated Fact-Checking System

## 🌟 Overview
FactCheckAI is a cutting-edge automated fact-checking system that leverages the power of deep learning. It is adept at classifying statements as 'true' or 'false', making it a valuable tool in the battle against misinformation in news, social media, and speeches.

## 📂 Project Structure
- `FactCheckAI.ipynb`: The heart of the project, containing functions for data cleaning, preprocessing, and building and training the LSTM-based deep learning model.
- `requirements.txt`: A list of necessary Python libraries for the smooth operation of the project.

## 🔧 Installation
Ensure you have all the tools to get started:
```
pip install -r requirements.txt
```

## 🚀 Usage
1. 📁 Place your dataset in the `data/` directory.
2. 🧹 Run `FactCheckAI.ipynb` to perform data cleaning, preprocessing, and to train and evaluate the model.

## 🧠 Model Description
The model is a marvel of engineering with a sequential architecture, featuring:
- An **Embedding layer** for efficient text vectorization.
- **Bidirectional LSTM** layers to capture the intricate context within the text.
- **Dense layers** adept at classification tasks.

Trained on meticulously preprocessed text, the model outputs a binary classification, shedding light on the veracity of input statements.

## 📊 Data
FactCheckAI works with JSON formatted datasets, expecting statements and corresponding truth labels:
```json
{"verdict": "true", "statement": "The earth orbits the sun"}
```

## 👐 Contributing
Got ideas to make FactCheckAI even better? Contributions are more than welcome! Check out the contribution guidelines for more details.

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.
