# Bank Marketing Campaign Analysis

## Summary of Findings
This project analyzes the effectiveness of direct marketing campaigns by a Portuguese banking institution. The goal is to predict whether a client will subscribe to a term deposit based on various features. The analysis highlights key factors such as age, job title, and previous campaign outcomes that influence subscription rates.

## Project Organization
- A README file with a summary of findings and link to the notebook
- A Jupyter notebook with headings and text appropriately formatted
- No unnecessary files
- Directories and files have appropriate names and locations

## Project Structure
- `data/`: Contains the dataset files.
  - `bank-additional-full.csv`: The dataset used for analysis.
- `notebook/`: Jupyter notebook with the analysis.
  - `Bank_Marketing_Campaign_Analysis.ipynb`: Jupyter notebook containing the data analysis, visualizations, and modeling.
- `README.md`: This file.

## Syntax and Code Quality
- Libraries are imported and aliased correctly
- Code does not contain errors
- No long strings of code output
- Demonstrates competency with pandas and seaborn
- Comments are used appropriately to explain code
- Variables are sensible

## Visualizations
- Appropriate plots for categorical and continuous variables are utilized
- Plots contain human-readable labels
- Plots contain descriptive titles
- Axes are legible
- Subplots are used when appropriate
- Plots are scaled appropriately for readability

## Modeling
- Use of four classifier models (kNN, Decision Trees, Logistic Regression, and SVM)
- Clear identification of evaluation metrics
- Appropriate interpretation of evaluation metrics
- Clear rationale for use of the evaluation metrics
- Appropriate comparison of the four models

### Model Performance
| Model               | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---------------------|----------|-----------|--------|----------|---------|
| k-Nearest Neighbors | 0.891559 | 0.535871  | 0.263499 | 0.353282 | 0.716913 |
| Decision Tree       | 0.837501 | 0.308833  | 0.359971 | 0.332447 | 0.631103 |
| Logistic Regression | 0.900785 | 0.665314  | 0.236141 | 0.348565 | 0.784794 |
| SVM                 | 0.899490 | 0.661538  | 0.216703 | 0.326464 | 0.711070 |


## Findings
- Clearly stated business understanding of the problem
- Clean and organized notebook with data cleaning
- Correct and concise interpretation of descriptive and inferential statistics
- Clearly stated findings in their own section with actionable items highlighted in appropriate language for a non-technical audience
- Next steps and recommendations

### Key Insights
- **Age**: Older clients are more likely to subscribe.
- **Job**: Certain job titles (e.g., retired) show a higher subscription rate.
- **Campaign**: The number of contacts performed during this campaign has an impact on the subscription rate.
- **Previous Outcome**: The outcome of the previous marketing campaign (if any) is a strong indicator of the current campaign's success.

### Recommendations
- **Targeted Campaigns**: Focus on clients with job titles and ages that show higher subscription rates.
- **Follow-Up Strategy**: Implement a follow-up strategy based on the outcome of previous campaigns.
- **Contact Frequency**: Optimize the number of contacts to balance effectiveness and client satisfaction.

### Next Steps
- **Feature Enhancement**: Explore additional features that could improve model accuracy.
- **Model Optimization**: Fine-tune the models using hyperparameter optimization.
- **Deployment**: Develop a system to integrate the model predictions into the marketing strategy.

## Link to Notebook
[Bank Marketing Campaign Analysis Notebook](Bank_Marketing_Campaign_Analysis.ipynb)