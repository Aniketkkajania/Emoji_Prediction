# Emoji_Prediction using LSTM

## Overview
This repository implements a machine learning model capable of predicting emojis for a given sentence or text. The model is built using LSTM (Long Short-Term Memory) neural networks, which are effective in handling sequential data. Given an input sentence, the model uses natural language processing techniques to predict the most appropriate emoji associated with that sentence.

## How to Use
To use the Emoji Prediction Model with LSTM, follow these steps:

1. Clone the repository to your local machine.
2. Open the EmojiPrediction.ipynb notebook using Jupyter Notebook or Jupyter Lab.
3. Run the notebook cells to train the LSTM model on the provided dataset.
4. Run all the cells and use the model on your Dataset.

## Dataset
The training data used for this project is provided in the repository. The Comment-Emoji Dataset.csv file contains the TEXT and its corresponding label, here label is denoting a particular emoji type. to check which label denotes to which emoji checkout the emoji-mapping.csv file.

## Tokenization and Padding
Before training the LSTM model, the text data is tokenized, converting each word into a unique integer representation. Additionally, sequences are padded to ensure they have the same length, as LSTMs require fixed-length sequences. This process is performed in the notebook EmojiPrediction.ipynb before training the model.

## Model Architecture
The emoji prediction model is built using LSTM neural networks. LSTM is chosen for its ability to handle sequential data effectively. The details of the LSTM model architecture can be found in the EmojiPrediction.ipynb notebook.

## Contributing
We welcome contributions to improve the model or its usage. If you wish to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

We appreciate your contributions and will review them as soon as possible.
