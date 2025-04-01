# **Predicting Business Scale of IKM in Surabaya Using Machine Learning**  

## **Project Description**  
This project focuses on predicting the **business scale of small and medium industries (IKM) in Surabaya** using **machine learning classification models**. The business scale is categorized into **Micro, Small, Medium, and Large enterprises**. The dataset is analyzed and classified using three machine learning models to determine the most accurate prediction model.  
![Image](https://github.com/user-attachments/assets/9dc84918-a0dc-4585-9c42-c0b26b70c3d4)

## **Dataset**  
The dataset consists of **Surabaya's IKM data**, which includes:  
- **Business Scale**: Micro, Small, Medium, Large  
- **Industry Category**  
- **Risk Level**  
- **Number of Employees**  
- **Investment Amount**  
- **Industry Size**  
- **Number of Businesses**  
- **etc**
  
## **Methodology**  
### **1. Data Preprocessing**  
- Handling missing values and data cleaning  
- Feature selection and transformation  

### **2. Classification Models Used**  
Three classification models were implemented:  
1. **Naïve Bayes** – Accuracy: **95.5%** (Best Model)  
2. **Random Forest** – Accuracy: **95.4%**  
3. **Decision Tree** – Accuracy: **94.6%**  

### **3. Model Evaluation**  
- **Accuracy, Precision, Recall, and F1-Score** were used to compare model performance.  
- **Naïve Bayes achieved the highest accuracy (95.5%)**, making it the best-performing model.  

## **Key Insights**  
- **Micro businesses dominate** the IKM landscape in Surabaya.  
- **Investment and number of employees significantly impact business scale classification.**  
- **Naïve Bayes performs best**, likely due to the probabilistic nature of business characteristics.  

Correlation Feature
![Image](https://github.com/user-attachments/assets/45b02e6a-8e65-476f-a392-3efc294f1e3a)


Results 

![Image](https://github.com/user-attachments/assets/3bc37068-e90a-4474-b49f-052d9c704b11)

## **Technologies Used**  
- **Python**: Scikit-learn, Pandas, NumPy  
- **Machine Learning**: Naïve Bayes, Random Forest, Decision Tree  
- **Visualization**: Matplotlib, Seaborn  

## **How to Use**  
1. Clone this repository.  
2. Install dependencies using `pip install -r requirements.txt`.  
3. Run `predict_business_scale.py` to classify businesses based on input features.  
4. View results and insights from the `business_scale_analysis.ipynb` notebook.  

## **Conclusion**  
This project successfully predicts **business scale classifications** for IKM in Surabaya, with **Naïve Bayes achieving the highest accuracy (95.5%)**. The model can help policymakers and business owners better understand the **growth potential and risk factors** of IKM businesses.  
