
# Next Word Prediction
This project is a Next Word Predictor using an LSTM (Long Short-Term Memory) model. The model is trained on a simple dataset, where text data is preprocessed, converted into numerical form, and split into input (X) and output (y). The LSTM model is then applied to learn patterns and predict the next word in a given sequence. The model achieves a maximum accuracy of 94.69%.


## Features

Data preprocessing including text tokenization and numerical conversion,
Use of LSTM for sequence prediction,
Hyperparameter tuning to optimize performance and
Loss minimization to improve accuracy

## Preprocessing Steps

Tokenization: Convert words into numerical tokens.

Padding: Ensure input sequences have uniform length.

Splitting: Divide data into input (X) and output (y).

Normalization: Scale data for better learning performance.
## Model Architecture

LSTM layers to capture sequential dependencies

Dense layers for classification

Softmax activation for predicting the next word
### Future Improvements

Train on a larger dataset for better generalization

Implement bidirectional LSTM for improved context understanding

Explore attention mechanisms for enhanced predictions