# 📊 Experiment 15: Data Normalization and Data Type Conversion

## 👩‍🎓 Student Details
- **Name:** Yashasavi Jain  
- **PRN:** 25070123127  
- **Batch:** B3  

---

## 🎯 Aim

The aim of this experiment is to understand the concepts of **data normalization** and **data type conversion**. The objective is to learn how to scale numerical data into a standard range and convert categorical data into numerical form for better analysis and machine learning model compatibility.

---

## 📘 Theory

Data preprocessing is a crucial step in data analysis and machine learning. It ensures that data is clean, consistent, and suitable for further processing. Two important preprocessing techniques are normalization and data type conversion.

---

### 🔹 Part A: Data Normalization

Data normalization is the process of scaling numerical values to a common range without distorting differences in the data. It improves the performance of algorithms and ensures fair comparison between variables.

#### 1. Min-Max Normalization
Min-Max normalization transforms data into a fixed range, typically between 0 and 1.

- Formula:  
  (Value - Minimum) / (Maximum - Minimum)
- Preserves the relationships among original data values.
- Sensitive to outliers.

#### 2. Normalization of Multiple Columns
Multiple numerical columns can be normalized simultaneously using the same Min-Max approach.

- Ensures uniform scaling across features.
- Useful in multivariate datasets.

#### 3. Z-Score Normalization (Standardization)
Z-score normalization transforms data based on mean and standard deviation.

- Formula:  
  (Value - Mean) / Standard Deviation
- Centers data around zero with unit variance.
- Useful when data follows a normal distribution.

#### 4. Decimal Scaling
Decimal scaling normalizes data by moving the decimal point.

- Formula:  
  Value / (10^j), where j is chosen such that max value < 1
- Simple and easy to apply.
- Less commonly used compared to other methods.

---

### 🔹 Part B: Data Type Conversion

Data type conversion involves transforming categorical or non-numeric data into numerical form so that it can be used in computations and machine learning models.

#### 1. Label Encoding
Label encoding assigns a unique integer to each category.

- Converts categorical labels into numeric values.
- Suitable for ordinal data.
- May introduce unintended ranking in nominal data.

#### 2. One-Hot Encoding
One-hot encoding creates separate binary columns for each category.

- Each category is represented as a column with values 0 or 1.
- Prevents misinterpretation of categorical hierarchy.
- Increases dimensionality of the dataset.

#### 3. Dummy Encoding
Dummy encoding is similar to one-hot encoding but drops one column to avoid redundancy.

- Helps prevent multicollinearity.
- Commonly used in regression models.

---

### 🔹 Importance of Data Preprocessing

- Ensures consistency in data
- Improves model accuracy and performance
- Reduces bias due to scale differences
- Enables efficient data analysis

---

## ✅ Conclusion

In this experiment, different techniques for data normalization and data type conversion were implemented and analyzed. Min-Max normalization, Z-score normalization, and decimal scaling were used to scale numerical data effectively. Additionally, categorical data was converted into numerical form using label encoding, one-hot encoding, and dummy encoding.

These preprocessing techniques play a vital role in preparing data for analysis and machine learning. Proper normalization ensures fair comparison across features, while encoding allows algorithms to process categorical information efficiently.
