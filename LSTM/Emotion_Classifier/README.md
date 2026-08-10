This project implements a simple LSTM-based emotion classifier using PyTorch.
It tokenizes text, converts tokens to IDs using a vocabulary, and feeds them into an embedding layer followed by an LSTM.
The final hidden state is passed to a linear layer to predict one of six emotions.
A custom collate function pads sequences for batching.
The model is trained with CrossEntropyLoss and Adam.
A predict function allows inference on new sentences.
Requirements:
python>=3.8
torch>=2.0
numpy>=1.20
tqdm
