
# 🔐 Network Intrusion Detection Using Machine Learning  
> An IBM-SB4Academia Capstone Project using NSL-KDD Dataset

---

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Algorithms Used](#algorithms-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Outputs](#outputs)
- [Results](#results)
- [Future Scope](#future-scope)
- [License](#license)
- [Author](#author)

---

## 📖 About the Project
This project is a machine learning-based Network Intrusion Detection System (NIDS) that detects cyber-attacks like DoS, Probe, R2L, and U2R. Developed under IBM's SB4Academia Capstone Challenge 2025, the model leverages supervised learning to secure network environments.

---

## ⚙️ Tech Stack
- Python
- Scikit-learn
- Pandas / NumPy
- Matplotlib / Seaborn
- IBM Cloud Lite (for deployment)

---

## 🧠 Algorithms Used
- Random Forest (Best Accuracy: 98.6%)
- Support Vector Machine (SVM)
- Logistic Regression

---

## 🧪 Dataset
We used the NSL-KDD dataset:  
🔗 [NSL-KDD Dataset](https://www.unb.ca/cic/datasets/nsl.html)  
It contains labeled network traffic data across 41 features and 5 classes.

---

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/Network-Intrusion-Detection-ML.git
cd Network-Intrusion-Detection-ML
pip install -r requirements.txt
```

---

## 🚀 Usage
Run the main notebook from the `notebooks/` folder to:
1. Preprocess the data
2. Train and test models
3. Evaluate and visualize results

---

## 📊 Outputs

### 🔹 Confusion Matrix
![Confusion Matrix](images/ibm_confusion_matrices.png)

### 🔹 Accuracy Comparison
![Accuracy Chart](images/ibm_accuracy_comparison.png)

---

## 📈 Results

| Model              | Accuracy  |
|-------------------|-----------|
| Random Forest      | 98.6%     |
| SVM                | 93.4%     |
| Logistic Regression| 90.2%     |

✅ Random Forest was the most effective in detecting all intrusion types.

---

## 🔮 Future Scope
- Use Deep Learning models (CNN, LSTM)
- Real-time packet analysis
- Expand dataset to include modern attacks
- Integrate into firewall or SIEM systems

---

## 📄 License
This project is open-source and free to use under the MIT License.

---

## 👨‍💻 Author

**Ritesh Asole**  
B.E. – Electronics & Telecommunication  
SB4Academia | IBM Capstone Project 2025
