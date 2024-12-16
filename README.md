# Credit Worthiness 

The analysis aimed to determine the probablity of a loan defaulting due to factors collected in the data. The team secured data from Kaggle, cleaned the dataset, built a regression model and created an interactive (HTML) user interface (UI) to get predictions.  The HTML page allowed users to see the predictions of the model. The evaluation had limitations due to limitations within the data. This report outlines the limitations of the data and an overview of the analysis. A

## Overview

The analysis is organized into the following sections located in the Credit Worthiness folder:

- ****Data (Credit Worthinees Clean File.ipynb)** **
  - Reviewed the dataset.
  - Processed and cleaned data.


- **Machine Learning Model (Analyze CSV.ipynb)**
  - Regression model used to predict loan defaults.
  - Evaluation metrics such as accuracy and R-squared.
  - Insights derived from the model.

- **HTML Page (HTML_Code.html)**

  - Interactive UI to generate loan default predictions

- **Conclusion**
  - Summary of findings and insights.
  - Identified limitations in the dataset.
  - Recommendations for improving the analysis in the future.

---

## Data

After cleaning the data, the team reviewed the relationship between certain data factors and the loan status. The review is documented below. 

<br>
After cleaning the data, the team reviewed the relationship between certain data factors and the loan status. The review is documented below.
<br>
<img width="866" alt="Screenshot 2024-12-14 at 7 26 39 PM" src="https://github.com/user-attachments/assets/79c6aec0-23bf-4b96-a818-8334edaab02b" />

<br>
First the team reviewed the average personal income by home ownership type. People with a mortgage held the highest income, whereas those who rent had the lowest average.
<br>
<img width="868" alt="Screenshot 2024-12-14 at 7 27 17 PM" src="https://github.com/user-attachments/assets/a939ad31-510b-49f4-a60b-42ab1c0d68b6" />

<br>
Medical loans had the highest number of defaults followed by debt consolidation loans.  
<br>
<img width="582" alt="Screenshot 2024-12-14 at 7 27 33 PM" src="https://github.com/user-attachments/assets/0967a9bf-e032-4f01-a369-98ad1efc664e" />

<br>
In addition to having the lowest income, renters had the highest number of loan defaults. 
<br>
<img width="586" alt="Screenshot 2024-12-14 at 7 27 50 PM" src="https://github.com/user-attachments/assets/f9469afe-66dc-4cfd-b689-2b8635000ef4" />


## Model
<br> 
The data had limitations as indicated by the 0.21 R squared. Additional data points such as debt-to-income ratio is needed to better predict loan defaults. The report below indicates that the model does a good job of predicting non-default accounts, however it performs poorly on default accounts.

Results:
- Accuracy: 82%
- Precision: 80%
- Recall: 75%
- F1-Score: 77%
- R-Squared: 0.21

## HTML Page


<img width="647" alt="Screenshot 2024-12-14 at 6 25 48 PM" src="https://github.com/user-attachments/assets/22097f76-e577-4237-9dcd-ba5897f6a04a" />

## Conclusion



