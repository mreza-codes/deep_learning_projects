This project includes an implementation of a simple Recurrent Neural Network (RNN) for sentiment analysis on the IMDB movie reviews dataset.
The RNN model consists of an embedding layer, a recurrent layer, and a fully connected output layer used to classify each review as positive or negative.

The model receives tokenized and padded input sequences, converts them into dense vector representations through the embedding layer, and processes them sequentially using the recurrent layer.
The final hidden state is passed to a fully connected layer to produce the classification output.

The RNN is trained using the Adam optimizer and cross‑entropy loss.
A prediction function is provided to evaluate custom text inputs using the trained RNN model.

Example usage:
print(predict("This movie was amazing"))
print(predict("Worst movie ever"))

Output:
+
-
