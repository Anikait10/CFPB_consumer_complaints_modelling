
# CFPB Consumer Complaints Modelling

This project analyzes consumer complaints data from the Consumer Financial Protection Bureau (CFPB) and builds a model to predict and categorize complaints. The dataset includes various details about the complaints, including the company, state, product, issue, and the company's response.

## Project Structure

- **Data Loading and Cleaning**: Initial steps to load the data, handle missing values, and preprocess it for analysis.
- **Exploratory Data Analysis (EDA)**: Summarizing and visualizing the data to understand the distribution and key characteristics of the complaints.
- **Modelling**: Building and evaluating machine learning models to predict the categories of complaints and optimize the cost associated with misclassification.

## Notable Sections

1. **Data Import and Preparation**
    - Loading the dataset.
    - Data cleaning and preprocessing steps.

2. **Exploratory Data Analysis (EDA)**
    - Distribution of complaints by product and company.
    - Analysis of complaint trends over time.
    - Visualizations of complaint categories and resolutions.

3. **Modelling**
    - Splitting the data into training and testing sets.
    - Training various machine learning models (e.g., Logistic Regression, Random Forest).
    - Evaluating model performance using metrics such as accuracy and ROC-AUC.
    - Implementing cost optimization for model predictions.

## Dependencies

- Python 3.10
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Anikait10/CFPB_consumer_complaints_modelling.git
```

2. Navigate to the project directory:

```bash
cd cfpb-consumer-complaints-modelling
```

3. Open the Jupyter notebook:

```bash
jupyter notebook CFPB_consumer_complaints_modelling.ipynb
```

4. Run the cells sequentially to reproduce the analysis.

## Results

- The notebook provides insights into the most common types of complaints and their distribution across various dimensions.
- The machine learning models predict complaint categories with reasonable accuracy.
- Cost optimization techniques are applied to minimize the financial impact of misclassification.

## Conclusion

This analysis of CFPB consumer complaints offers valuable insights into consumer issues and helps in developing predictive models to categorize complaints. The cost optimization approach enhances the practical utility of the model by reducing the potential financial impact of incorrect predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
