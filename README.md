# SecureCard-AI: Credit Card Fraud Detection System 🛡️

![Banner](./assets/banner-SecureCard-AI.jpg)

## Project Overview

**Author:** Camille Maslin  
**Contact:**  
- [LinkedIn](https://www.linkedin.com/in/camille-maslin/)
- [GitHub](https://github.com/camille-maslin)
- [Email](mailto:camillemaslin@gmail.com)  
- [Portfolio](https://camille-maslin.github.io/Portfolio/)

**Description:**
This project implements a high-performance credit card fraud detection system using advanced machine learning techniques. The model achieves **99.97% accuracy** on real transaction data.

## Dataset Information 📊

**Source:** [Kaggle - Credit Card Fraud Detection Dataset 2023](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)  
**Size:** 57,000+ transactions  

**Features:**
- Transaction amount
- Time of transaction
- 28 anonymized features (V1-V28)
- Target: Binary classification (Fraud/Non-Fraud)

**Data Quality:**
- No missing values
- Preprocessed and anonymized for privacy
- Standardized numerical features
- Reflects real-world transaction patterns

---

## Key Features

### 📊 Data Analysis
- Comprehensive data exploration
- Advanced feature engineering
- Robust data quality checks

### 📈 Visualizations
- Interactive correlation matrices
- Distribution analysis
- Pattern recognition plots

### 🤖 Machine Learning Model
- **99.97% accuracy rate**
- Only **18-19 errors** per 57,000 transactions
- SMOTE implementation for class balancing

### 📉 Performance Metrics
- Cross-validation scores: [0.9996 - 0.9997]
- Balanced precision and recall
- Minimal false positives/negatives

---

## Technical Stack

- 🐍 Python 3.12
- 📝 Scikit-learn
- 📊 Pandas & NumPy
- 🔄 Matplotlib & Seaborn
- 🔄 SMOTE for imbalance handling

---

## Installation 🔧

1. Clone the repository:
```bash
$ git clone https://github.com/camille-maslin/SecureCard-AI.git
$ cd SecureCard-AI
```

2. Create a virtual environment and activate it:
```bash
$ python3 -m venv venv
$ source venv/bin/activate  # Linux/MacOS
$ .\venv\Scripts\activate  # Windows
```

3. Install dependencies:
```bash
$ pip install -r requirements.txt
```

---

## Usage

1. Run the Jupyter Notebook:
```bash
$ jupyter notebook
```

2. Open `SecureCard-AI.ipynb` in your Jupyter environment.

3. Follow the instructions and run each cell to:
   - Load data
   - Analyze and preprocess the dataset
   - Train the fraud detection model
   - Evaluate performance and visualize results

---

## License 💼

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contributions 🛠️

Contributions are welcome! Please submit a pull request or open an issue for suggestions or bug reports.

---

## Acknowledgments

- Kaggle for the dataset.
- Open-source libraries and contributors for tools used.
