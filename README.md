# Detecting-and-Preventing-the-DDoS-attack-in-Network
This project implements an AI-based detection system for identifying and mitigating Distributed Denial-of-Service (DDoS) attacks in Software-Defined Networks (SDN). Using machine learning models trained on network traffic data, the system aims to enhance network security by providing early and accurate detection of malicious activity.
🔍 Key Features

* 📊 Data preprocessing and feature selection
* 🧠 **Machine Learning models for DDoS detection**
* ✅ **Model evaluation using accuracy, precision, recall, and F1-score**
* 🚨 **Real-time detection and alerting capabilities (extendable)**
* 🛡️ **Support for prevention techniques based on flow rules in SDN**

---

## 📁 Dataset

* **Dataset Name**: `_sdn`
* **Description**: The dataset includes labeled traffic data representing both normal and malicious (DDoS) activities. It consists of features such as packet sizes, flow durations, and protocol types.
* **Source**: Add source or dataset link if available publicly.
* **Format**: CSV file containing network traffic features used to train the detection models.

---

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

---

## 📊 Results

| Model          | Accuracy | Precision | Recall | F1-Score |
| -------------- | -------- | --------- | ------ | -------- |
| Random Forest  | 99%      | 0.99      | 0.98   | 0.985    |
| Neural Network | 98.5%    | 0.985     | 0.97   | 0.977    |
| SVM            | 96%      | 0.96      | 0.94   | 0.95     |
| KNN            | 97%      | 0.965     | 0.95   | 0.957    |

> 🏆 **Best-performing models**: Random Forest and Neural Network

---

## 🚀 How to Run the Project

1. **Clone the repository**:

   ```bash
   git clone <your_repo_url>
   ```
2. **Open the notebook**:

   * Use **Jupyter Notebook** or **Google Colab**
3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```
4. **Run the notebook and follow the steps**:

   * Load and preprocess the dataset
   * Train and evaluate the models
   * Analyze performance metrics

---

## 📫 Contact

For questions, issues, or contributions, feel free to open an issue or contact me directly!

---

Let me know if you'd like to include diagrams, a live demo link, a flowchart of the architecture, or specific prevention mechanisms in SDN (like using OpenFlow rules).
