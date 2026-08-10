This project includes an implementation of an LSTM-based model for sentiment analysis on the IMDB movie reviews dataset.
The objective is to classify each review as positive or negative using a recurrent neural network architecture capable of capturing long‑term dependencies in text.

The LSTM model consists of an embedding layer, an LSTM layer, and a fully connected output layer.
Input text is lowercased, tokenized, converted into a twenty‑thousand‑word vocabulary, and padded to ensure uniform sequence length for batch processing.
The dataset contains fifty thousand samples and is loaded using the datasets library.

The model is trained using the Adam optimizer and cross‑entropy loss.
A prediction function is provided for evaluating custom text inputs using the trained LSTM model.

Example usage:

print(predict("This movie was amazing"))

print(predict("Worst movie ever"))

Output:

+
-

Requirements:

torch
datasets
numpy

