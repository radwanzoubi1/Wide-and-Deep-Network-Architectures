# Wide and Deep Network Architectures for Autism Risk Prediction

This project implements Wide and Deep Networks to analyze the Autism Screening Data for Toddlers. The primary goal is to predict the likelihood of autism based on demographic and behavioral features using advanced deep learning techniques. The project explores feature embeddings, cross-product transformations, and hyperparameter tuning to optimize predictive accuracy.

---

## About the Dataset

### Domain:
- **Autism Screening**: Early detection of autism risk in toddlers to enable timely intervention and support.
- **Purpose**: Leveraging data-driven insights to improve the accuracy of autism screening tools.

### Dataset Overview:
- **Data Type**: Tabular data with categorical and numeric variables.
- **Task**: Binary classification to predict autism risk.
- **Attributes**:
  - **Features**: Includes demographic details, behavioral scores, and family history indicators.
  - **Target Variable**: Autism risk status (Yes/No).

### Data Source:
- Autism Screening Data for Toddlers: https://www.kaggle.com/datasets/fabdelja/autism-screening-for-toddlers

---

## Project Objectives

1. **Wide and Deep Network Implementation**:
   - Created using TensorFlow and Keras to process mixed data types.
   - Incorporates embedding layers for categorical data and cross-product feature transformations.

2. **Model Evaluation and Tuning**:
   - Tested multiple architectures with varying deep branch depths.
   - Tuned hyperparameters such as learning rate, activation functions, and regularization techniques.

3. **Comparative Analysis**:
   - Compared the performance of Wide and Deep Networks against simpler models like a standard Multi-Layer Perceptron (MLP).
   - Evaluated models using advanced metrics like AUC-ROC and precision-recall curves.

4. **Visualization**:
   - Produced plots to illustrate training and validation performance, feature embeddings, and data clusters.

---

## Key Questions Explored

1. **What features contribute most to autism risk prediction?**
   - Explored using feature embeddings and cross-product analysis.

2. **How does model depth affect generalization?**
   - Analyzed through experiments with deep branch layers and statistical comparisons.

3. **What architecture provides the best performance for this dataset?**
   - Determined through cross-validation and metric-based evaluations.

---

### Data Preprocessing:
1. **Encoding**: Applied one-hot and embedding representations for categorical variables.
2. **Scaling**: Standardized numerical features for consistent model input.
3. **Splitting**: Used stratified cross-validation to ensure balanced class distribution in training and testing sets.

---

## Results

1. **Wide and Deep Models**:
   - Demonstrated superior predictive accuracy compared to baseline models.
   - Effectively handled complex feature interactions through embeddings.

2. **Comparative Analysis**:
   - Highlighted the importance of model architecture in achieving high generalization performance.
   - Showed that Wide and Deep Networks outperform MLP in terms of AUC-ROC and recall.

---

## Tools and Libraries Used

- **Python**: Programming language.
- **Jupyter Notebook**: Interactive environment for reproducibility.
- **TensorFlow/Keras**: Deep learning framework.
- **NumPy**: For numerical operations.
- **Pandas**: For data manipulation.
- **Matplotlib/Seaborn**: For data visualization.

---

## Project Structure

```plaintext
.
├── Wide-and-Deep-Networks.ipynb        # Main Jupyter Notebook
├── README.md                          # Project documentation
```

---

## How to Run

### 1. Clone the Repository:
```bash
git clone https://github.com/radwanzoubi1/Wide-and-Deep-Network-Architectures.git
cd Wide-and-Deep-Network-Architectures
```

### 2. Install Dependencies:
```bash
pip install numpy pandas matplotlib seaborn tensorflow
```

### 3. Run the Notebook:
- **Open Jupyter Notebook**:
```bash
jupyter notebook Wide-and-Deep-Networks.ipynb
```
- Run all cells to reproduce the analysis.


