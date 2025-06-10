# Detecting-and-Preventing-the-DDoS-attack-in-Network
This project implements an AI-based detection system for identifying and mitigating Distributed Denial-of-Service (DDoS) attacks in Software-Defined Networks (SDN). Using machine learning models trained on network traffic data, the system aims to enhance network security by providing early and accurate detection of malicious activity.
##🔍 Key Features

* 📊 **Data preprocessing and feature selection**
* 🧠 **Machine Learning models for DDoS detection**
* ✅ **Model evaluation using accuracy, precision, recall, and F1-score**
* 🚨 **Real-time detection and alerting capabilities (extendable)**
* 🛡️ **Support for prevention techniques based on flow rules in SDN**

## 📁 Dataset

* **Dataset Name**: `dataset_sdn`
* **Description**: The dataset includes labeled traffic data representing both normal and malicious (DDoS) activities. It consists of features such as packet sizes, flow durations, and protocol types.
* **Source**:the dataset can be found in Kaggle.
* **Format**: CSV file containing network traffic features used to train the detection models.

## 🛠️ Tools & Technologies Used

* **Language**: Python
* **Libraries**:

  * Pandas
  * Scikit-learn
  * TensorFlow / Keras
  * Matplotlib / Seaborn
* **ML Algorithms**:

  * Decision Tree
  * Random Forest
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors (KNN)
  * Neural Networks

## 📊 Results

Model  	Accuracy  	Precision	   Recall	   F1-Score
CNN	     98.1%	     0.9869   	  0.9893	   0.9881
LSTM	    97.9%	     0.9704	     0.9854	   0.9779
CNN-LSTM	98.3%	     0.9760      0.9863    0.9811

🚀 CNN-LSTM outperformed all other models, making it the optimal choice for SDN-based DDoS detection.

## 🚀 How to Run the Project

*Clone the repository: git clone <your_repo_url>
*Open the Jupyter notebook in Google Colab or Jupyter Notebook.
*Follow the steps in the notebook to train the model and generate predictions.
*Feel free to reach out if you have any questions or issues running the code!
   
