# Chatbot
Sem-4 python lab project

# Chatbot using NLTK and TensorFlow

This Python script implements a basic chatbot using NLTK for natural language processing and TensorFlow for machine learning. The chatbot is designed to respond to user input based on predefined patterns and responses.

## Getting Started

### Prerequisites

- Python 3.x
- NLTK (Natural Language Toolkit)
- TensorFlow (and tflearn)

### Installation

1. Install the necessary Python libraries:

```bash
pip install nltk tflearn
```

2. Download NLTK resources for tokenization and WordNet:

```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

## Usage

1. Run the main Python script `chatbot.py`.
2. The chatbot will start interacting with you. Type `quit` to exit the chat.

## Model Training

The chatbot uses a simple bag-of-words approach combined with a neural network model. The training data is stored in `intents_chatbot.json`. If you want to train a new model or update the training data, you can modify this JSON file.

## File Descriptions

- `chatbot.py`: Contains the main chatbot script.
- `intents_chatbot.json`: Defines intents, patterns, and responses for the chatbot.
- `data.pickle`: Serialized data for faster loading of training data.
- `model.tflearn`: Trained model for the chatbot.

## Credits

- The Natural Language Toolkit (NLTK): [https://www.nltk.org/](https://www.nltk.org/)
- TensorFlow: [https://www.tensorflow.org/](https://www.tensorflow.org/)

## Dataset
- https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset
