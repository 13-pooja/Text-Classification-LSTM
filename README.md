# Text Classification using Embedding Layer and LSTM

## Aim

Build a text classification model for a binary classification task using an Embedding layer and an LSTM network, and evaluate the model's performance using appropriate classification metrics.

## Project Description

This project implements a binary sentiment classification model using TensorFlow and Keras.

The model classifies text into two categories:

- Positive
- Negative

The text is first tokenized and converted into numerical sequences. The sequences are then padded to a fixed length and passed through an Embedding layer and LSTM network.

## Model Architecture

Embedding
↓
SpatialDropout1D
↓
LSTM
↓
Dense (ReLU)
↓
Dropout
↓
Dense (Sigmoid)

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Data Preprocessing

1. Text data is collected with positive and negative sentiment labels.
2. Text is tokenized using Keras Tokenizer.
3. Text is converted into numerical sequences.
4. Sequences are padded to a fixed length.
5. Dataset is divided into training and testing sets.

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## Results

The actual evaluation scores are generated after training the model and are available in the Jupyter Notebook.

## Visualizations

The project includes:

- Training and Validation Accuracy Curve
- Training and Validation Loss Curve
- Confusion Matrix
- ROC Curve

## Files

- `Practical_02_Text_Classification_LSTM.ipynb` – Complete implementation of the project.
- `README.md` – Project documentation.

## Conclusion

A binary text classification model was successfully developed using an Embedding layer and LSTM network. The model was trained and evaluated using multiple classification metrics and visualization techniques.
