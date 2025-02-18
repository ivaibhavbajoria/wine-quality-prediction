**README.txt**

---

**Wine Quality Prediction with Machine Learning**  
This project aims to predict wine quality (on a scale of 3–9) using physicochemical features. It employs machine learning algorithms to classify wine quality and evaluate model performance.

---

### **Dataset**  
**Source**: `winequality.csv`  
**Features**:  
- `type`: Red or white wine (encoded as integers).  
- 11 physicochemical attributes: Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol.  
- **Target**: `quality` (integer score).  

**Size**: 6,497 samples, 13 columns.  

---

### **Dependencies**  
- Python 3.7+  
- Libraries:  
  ```bash
  pandas, numpy, matplotlib, seaborn  
  scikit-learn, xgboost  
  ```

---

### **Installation**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/[username]/wine-quality-prediction.git  
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```

---

### **Usage**  
1. **Upload Dataset**:  
   - Place `winequality.csv` in the project directory or update the file path in the notebook.  
   - If using Google Colab, mount Google Drive and adjust the path accordingly.  

2. **Run Jupyter Notebook**:  
   - Execute cells sequentially to:  
     - Load and preprocess data.  
     - Train and evaluate models (Random Forest, Logistic Regression, XGBoost, SVM).  
     - Generate visualizations (histograms, confusion matrices).  

---

### **Data Preprocessing**  
1. **Handle Missing Values**: Fill NaN entries with column means.  
2. **Encode Categorical Data**: Convert `type` (red/white) to numerical values.  
3. **Feature Scaling**: Standardize features using `StandardScaler`.  
4. **Train-Test Split**: 80% training, 20% testing.  

---

### **Models**  
- **Random Forest Classifier**  
- **Logistic Regression**  
- **XGBoost Classifier**  
- **Support Vector Machine (SVM)**  

---

### **Results**  
**Best Model**: Random Forest achieved the highest accuracy (~85%).  
**Evaluation Metrics**:  
- Accuracy  
- Classification Report (precision, recall, F1-score)  
- Confusion Matrix  

---

### **Visualization**  
- Histograms for feature distributions.  
- Confusion matrices for model performance comparison.  

---

### **License**  
MIT License. See `LICENSE` for details.  

---

