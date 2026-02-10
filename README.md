# Fashion Forward Forecasting – Product Recommendation Prediction
## Motivation
Customer reviews are a critical source of insight for online fashion retailers, as they reflect customer satisfaction, product quality, and overall shopping experience. However, not all customers explicitly indicate whether they would recommend a product, even though they provide valuable feedback in the review text.

The motivation of this project is to leverage existing labeled reviews to build a predictive model capable of determining whether a customer would recommend a product based on review text, customer age, and product category information. Automating this process can help retailers better understand customer sentiment, identify trends, and support data-driven business decisions.

## Dataset
This project uses the Women’s Clothing E-Commerce Reviews dataset, which contains customer reviews along with demographic information, product categories, and a binary indicator specifying whether the product was recommended.

The dataset includes a mix of:
- Text data (customer review text)
- Numerical data (customer age)
- Categorical data (division, department, and class name)

## Software Dependencies
The project was developed using Python and the following main libraries:
- Python 3.x
- pandas
- numpy
- scikit-learn
- spaCy

All analysis, preprocessing, and modeling are performed in a Jupyter Notebook.

## File Descriptions
- notebook.ipynb: Main Jupyter notebook containing data exploration, pipeline construction, model training, and hyperparameter tuning.
- README.md: Project documentation and overview.
- reviews.csv: Raw dataset used for the analysis.

## How to Interact with This Project
1. Clone the repository
2. Install the required Python libraries
3. Open the Jupyter notebook
4. Run the notebook cells sequentially to reproduce the analysis and results

## Results Summary
This project demonstrates that customer recommendation behavior can be effectively predicted using a combination of review text and structured customer and product information.

A machine learning pipeline was developed using spaCy-based text preprocessing, TF-IDF feature extraction, and Logistic Regression. Hyperparameter tuning with cross-validation improved model performance compared to the baseline model.

## Key findings include:
- Review text provides strong predictive signal for recommendation behavior.
- Structured features such as age and product category enhance model performance when combined with text data.
- An end-to-end pipeline approach ensures reproducibility and prevents data leakage.

Overall, the results show that integrated text and structured data pipelines can support better understanding of customer sentiment in online retail environments.

## Licensing
This project is provided for educational purposes only. The dataset is publicly available and subject to its original usage guidelines.

## Authors
Aina Lluís Huelmo

## Acknowledgments
- Udacity Data Scientist Nanodegree program for project guidance
- Dataset providers for making the data publicly available

