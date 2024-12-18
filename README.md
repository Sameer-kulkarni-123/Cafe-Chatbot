# Chatbot with PyTorch

This repository contains a simple chatbot built using PyTorch. The chatbot is trained on a set of predefined intents and can respond to user inputs based on these intents.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sameer-kulkarni-123/Cafe-Chatbot.git
   cd Cafe-Chatbot
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have NLTK data installed if you are running it for the first time:
   ```python
   import nltk
   nltk.download('punkt')
   ```
   You can also uncomment "nltk.download('punkt')" in the model.py and run it once.

## Usage

### Training the Model

To train the model, run the `train.py` script. This will process the intents from `intents.json`, train a neural network, and save the trained model to `data.pth`.

### Accessing the Chatbot

To run the chat bot, run the `chat.py` file
