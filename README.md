# LSTM Human Activity Recognition

This project applies a Long Short-Term Memory (LSTM) neural network to classify different human activities based on time-series data from smartphone sensors. The dataset used is a preprocessed version of the **Human Activity Recognition with Smartphones** dataset.

## 📊 Dataset
This project uses a preprocessed version of the **Human Activity Recognition with Smartphones** dataset.

- **Original Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)
- **Processed Version**: Provided on [Kaggle](https://www.kaggle.com/code/ahmedelshamy1/lstm-human-activity-project) with `train.csv` and `test.csv` files

## 🧠 Model
The LSTM model is built using TensorFlow/Keras and consists of:
- Input preprocessing with Label Encoding and MinMax Scaling
- LSTM layers for capturing temporal dependencies
- Dense layers for classification
- Dropout for regularization

## 📁 Files
- `lstm-human-activity-project.ipynb`: Full notebook with preprocessing, model training, evaluation, and plotting.

## 📈 Results
The model is evaluated using accuracy and performance metrics. Training and validation curves are plotted to show learning trends.

## 🔗 Project on Kaggle
👉 [Kaggle Notebook](https://www.kaggle.com/code/ahmedelshamy1/lstm-human-activity-project)
