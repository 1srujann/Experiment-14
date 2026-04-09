# Experiment 14: Data Normalization and Data Conversion

---

## Title

Data Normalization and Encoding Techniques Using Pandas and Scikit-learn

---

## Aim

To study and implement various data normalization and data conversion techniques using Python libraries such as Pandas and Scikit-learn.

---

## Objectives

- To understand different normalization techniques  
- To apply Min-Max, Z-score, and Decimal scaling methods  
- To convert categorical data into numerical form  
- To perform encoding using Label Encoding, One-Hot Encoding, and Dummy Encoding  
- To prepare datasets for analysis and machine learning  

---

## Theory

Data normalization is a preprocessing technique used to scale numerical values into a standard range. It ensures that features with different units or magnitudes contribute equally during analysis.

Common normalization techniques include:

- **Min-Max Normalization:** Scales values between 0 and 1  
- **Z-score Normalization:** Standardizes values based on mean and standard deviation  
- **Decimal Scaling:** Reduces values by dividing by a power of 10  

Data conversion involves transforming categorical data into numerical format, which is essential for analysis and machine learning models.

Encoding techniques include:

- **Label Encoding:** Assigns numeric labels to categories  
- **One-Hot Encoding:** Converts categories into binary columns  
- **Dummy Encoding:** Similar to one-hot encoding but avoids redundancy  

---

## Datasets Used

- **Amazon Products Dataset**
  - Columns: Price, Rating, Reviews, Units_Sold  
  - Used for normalization techniques  

- **Student Dataset**
  - Columns: Gender, Department, CGPA, Attendance, Salary, etc.  
  - Used for encoding and data conversion  

- **Custom Sales Dataset**
  - Includes Product, Price, Units Sold, Discount  
  - Used to demonstrate normalization methods  

---

## Problem Statements

### 1. Min-Max Normalization

Apply Min-Max normalization on numerical columns such as:
- Price  
- Units_Sold  
- Reviews  

---

### 2. Z-score Normalization

Standardize the `Units_Sold` column using mean and standard deviation.

---

### 3. Decimal Scaling

Scale the `Price` column by dividing it with an appropriate factor.

---

### 4. Categorical Data Conversion

Convert categorical variables such as:
- Customer_Gender  
- Product_Category  
- City  

into numerical format.

---

### 5. Encoding Techniques

Implement different encoding methods:

- **Label Encoding** for Gender  
- **One-Hot Encoding** for Product Category and Attendance  
- **Dummy Encoding** for Payment Method and Salary  

---

## Conclusion

Thus, data normalization and data conversion techniques were successfully implemented using Pandas and Scikit-learn. The experiment involved working with multiple datasets such as Amazon Products, Student Dataset, and a custom dataset, providing practical understanding of scaling numerical data and converting categorical data into machine-readable format.
