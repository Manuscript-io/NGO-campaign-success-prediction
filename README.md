# NGO-campaign-success-prediction
### Overview

This project predicts whether an NGO fundraising campaign will be successful using Machine Learning. The model is trained on the Donors Choose dataset containing over 100,000 real-world fundraising projects.

The objective is to demonstrate how NGOs such as NayePankh Foundation can use data-driven decision-making to improve campaign planning and fundraising outcomes.

### Dataset
This project uses the DonorsChoose Dataset, which contains over 100,000 real-world fundraising projects and their approval outcomes.

Due to GitHub file size limitations, the dataset is not included in this repository.

Dataset Source: https://www.kaggle.com/datasets/arunasivapragasam/donors-choose

To run this project locally:

1. Download the dataset from Kaggle.
2. Place Preprocessed_DonorsChoose_dataset.csv in the project directory.
3. Run the Jupyter Notebook.

The dataset is used solely for educational and research purposes.

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- XGBoost

### Machine Learning Models
#### Logistic Regression
- Baseline classification model.

#### Random Forest
- Used to capture nonlinear relationships and determine feature importance.

#### XGBoost
- Advanced ensemble model used to achieve the highest prediction performance.

### Key Findings
- Project cost significantly affects approval probability.
- Teacher experience influences campaign success.
- Ensemble models outperform linear models.
- XGBoost achieved the best performance.

#### This model can help NGOs:

- Predict campaign success before launch
- Optimize fundraising strategies
- Allocate resources more effectively
- Improve overall campaign outcomes
