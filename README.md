# Fraud Detection Using Autoencoders

This project focuses on detecting fraudulent transactions using Deep Learning Autoencoders built with Keras.

## 📂 Contents
- Data preprocessing
- Building and training an Autoencoder model
- Detecting anomalies (fraud cases) based on reconstruction error
- Model evaluation and visualization

## 🛠️ Tools & Libraries
This project was built using:
- **Python 3.x**
- **NumPy** – Numerical computations
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Data preprocessing and metrics evaluation
- **TensorFlow / Keras** – Building and training the deep Autoencoder model

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection-autoencoder.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook `fraud-detection-using-autoencoders-in-keras.ipynb` and run all cells.

## 🧀 Model Description
The Autoencoder model is trained to reconstruct normal transactions.  
Transactions with high reconstruction errors are flagged as potential fraud.

## 📊 Evaluation
- Reconstruction error analysis
- Precision, Recall, F1-Score (if evaluated)
- Visualization of error distributions

## 📋 Dataset
The dataset consists of transaction records with labels indicating fraud/non-fraud.


