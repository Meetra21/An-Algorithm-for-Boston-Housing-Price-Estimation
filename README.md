# An Algorithm for Boston Housing Price Estimation  

This project implements a **Deep Neural Network (DNN)** to predict housing prices using the classic **Boston Housing Prices Dataset**. The goal is to accurately estimate the **median value of owner-occupied homes (in $1000s)** based on various socioeconomic and housing-related features.  

---

## 🎯 Project Goal  

- Build a **regression model** using Deep Learning to estimate housing prices.  
- Evaluate performance of the model against traditional benchmarks.  
- Provide insights into the **importance of housing features** influencing price.  

---

## 📂 Dataset  

- **Name**: Boston Housing Prices Dataset  
- **Source**: UCI Machine Learning Repository / Scikit-learn built-in dataset  
- **Samples**: 506 instances  
- **Features**: 13 numerical attributes including:  

| Feature | Description |
|---------|-------------|
| CRIM    | Per capita crime rate by town |
| ZN      | Proportion of residential land zoned for lots over 25,000 sq.ft. |
| INDUS   | Proportion of non-retail business acres per town |
| CHAS    | Charles River dummy variable (1 if tract bounds river, 0 otherwise) |
| NOX     | Nitric oxide concentration (parts per 10 million) |
| RM      | Average number of rooms per dwelling |
| AGE     | Proportion of owner-occupied units built prior to 1940 |
| DIS     | Weighted distances to Boston employment centers |
| RAD     | Index of accessibility to radial highways |
| TAX     | Full-value property-tax rate per $10,000 |
| PTRATIO | Pupil-teacher ratio by town |
| B       | 1000(Bk - 0.63)^2 where Bk is proportion of Black residents by town |
| LSTAT   | % lower status of the population |
| MEDV    | Median value of owner-occupied homes in $1000s (target variable) |

---

## 🧭 Workflow  

### 1. Data Preprocessing  
- Normalization of feature values  
- Train-test split (e.g., 80%-20%)  
- Handling outliers and scaling  

### 2. Deep Neural Network Model  
- Framework: TensorFlow / Keras  
- Architecture:  
  - Input layer (13 features)  
  - Multiple dense hidden layers with ReLU activation  
  - Dropout for regularization  
  - Output layer: Single neuron (linear activation for regression)  
- Optimizer: Adam  
- Loss function: Mean Squared Error (MSE)  



---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/An-Algorithm-for-Boston-Housing-Price-Estimation.git
   cd An-Algorithm-for-Boston-Housing-Price-Estimation
