# **Loan Eligibility Prediction**  

This project predicts loan eligibility using machine learning models based on applicant details such as income, credit history, and loan amount.  

## **Project Overview**  
- Uses **Random Forest** and **Logistic Regression** for prediction.  
- Handles class imbalance using **RandomOverSampler**.  
- Evaluates model performance using **accuracy** and **ROC-AUC**.  
- Provides visual insights through data visualization.  

## **Dataset Features**  
- **Applicant Details**: Gender, Marital Status, Income, Credit History.  
- **Loan Details**: Loan Amount, Loan Term, Loan Status.  

## **Technologies Used**  
- **Python**  
- **Google Colab**  
- **Machine Learning Libraries**: scikit-learn, pandas, NumPy  
- **Data Visualization**: Matplotlib, Seaborn  

## **How to Run the Project (Google Colab)**  
1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload the provided **Loan Eligibility Prediction.ipynb** notebook.  
3. Upload the dataset **loan_data.csv** in Colab’s file section.  
4. Run all cells in order.  
5. The model will train, evaluate, and display results.  

## **Results**  
- **Random Forest**: Higher accuracy but potential overfitting.  
- **Logistic Regression**: Lower accuracy, needs further tuning.  
- **Feature Importance**: Credit History, Loan Amount, and Applicant Income significantly impact loan approval.  

## **Future Work**  
- Improve model generalization and reduce overfitting.  
- Implement additional ML models (e.g., XGBoost, SVM).  
- Deploy as a web-based tool using Flask/Django + React.  
