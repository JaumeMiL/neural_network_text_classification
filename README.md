# Neural_Network_Text_Classification_Project 🧠

**Exploring Advanced Architectures for Text Data Processing**

## Overview 📑

This project focuses on building, training, and evaluating neural network models for text classification tasks. It explores various architectures, including convolutional and recurrent networks, while experimenting with different configurations and regularization techniques.

## Key Features 🛠️

- **Data Preparation**:
  - Text preprocessing and conversion into numerical sequences.
  - Padding sequences to ensure uniform length.
  - Encoding labels into categorical values.
- **Model Architectures**:
  - Convolutional Neural Networks (CNNs).
  - Recurrent Neural Networks (RNNs) using LSTM and GRU.
  - Bidirectional and hybrid models.
- **Regularization**: Utilization of dropout layers to reduce overfitting.
- **Performance Metrics**:
  - Evaluation using F1-score, accuracy, and confusion matrices.
- **Learning Curves**: Visualization of training and validation progress.

## Project Structure 📂

1. **Data Preprocessing**:
   - Converting raw text into tokenized sequences.
   - Padding and truncating sequences to a fixed length.
   - Transforming categorical labels into numerical encodings.
2. **Training and Validation**:
   - Experimenting with multiple architectures and configurations.
   - Assessing the impact of embedding dimensions and regularization techniques.
3. **Evaluation**:
   - Confusion matrix visualization with normalization for better interpretability.
   - Comparing key metrics to identify the best-performing models.

## Execution 🚀

1. Ensure Python and required libraries (TensorFlow, Keras, Pandas, Matplotlib, etc.) are installed.
2. Run the Jupyter Notebook file `P2_1_notebook_Marta_Jaume_Abril.ipynb`.
3. Analyze the results, including metrics, confusion matrices, and learning curves.

## Key Results 🔍

- **Best Configurations**: Models combining high-dimensional embeddings with convolutional and recurrent layers showed the highest F1-scores.
- **Regularization Impact**: Dropout layers significantly improved generalization and reduced overfitting in deeper models.
- **Visual Insights**: Normalized confusion matrices provided detailed performance analysis for each class.

## Conclusion 📝

This project demonstrates the effectiveness of neural network architectures for text classification. It provides a solid foundation for further experimentation, such as leveraging pre-trained embeddings or deploying deeper, more complex models.

**Developed by**: Marta Juncarol, Jaume Mora, Abril Risso
