### README

## Airline Customer Experience Analysis

### Description
This project analyzes airline customer experiences by leveraging both textual reviews and numerical ratings to discern patterns, sentiments, and critical factors contributing to customer satisfaction or dissatisfaction. The project involves advanced natural language processing (NLP) techniques and machine learning models to provide comprehensive insights into airline services and develop a recommendation system.

### Prerequisites
Before you begin, ensure you have met the following requirements:
- **Python 3.7** or higher installed
- **Jupyter Notebook**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Scikit-learn**, **NLTK**, **KeyBERT**, **LLama2**, **ChatGPT 3.5 Turbo** libraries installed

### Installation and Setup
To install and set up the project, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/airline-customer-experience-analysis.git
   cd airline-customer-experience-analysis
   ```

2. **Set up the Python Environment:**
   Create a virtual environment and install the required libraries:
   ```sh
   python -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook:**
   Open and run `Customer_Reviews_Sentiment_Analysis.ipynb` in Jupyter.

### Using the Project
Once the Jupyter Notebook is open, you can run the cells to execute the following steps:

1. **Textual Analysis:**
   - Preprocess and clean text reviews.
   - Perform topic modeling using KeyBERT and LLama2.
   - Use ChatGPT 3.5 Turbo to categorize topics and perform sentiment analysis using NLTK.

2. **Numerical Analysis:**
   - Develop a recommendation system using machine learning models such as Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, and Random Forest.
   - Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

### Key Findings
- **Textual Analysis Results:** Identified key topics and sentiments associated with airline services such as food and beverage, wifi connectivity, and cabin services.
- **Recommendation System Results:** Demonstrated high accuracy and F1-scores across multiple machine learning models, with Logistic Regression achieving the highest performance.

### Results Analysis and Interpretation
- **Topic Modeling:** Provided insights into customer opinions on specific airline services.
- **Sentiment Analysis:** Revealed customer sentiment trends, highlighting areas for improvement and strengths.
- **Recommendation System:** Showcased the effectiveness of machine learning models in predicting customer recommendations based on numerical ratings.

### Contributing to the Project
To contribute, follow these steps:
1. **Fork the repository.**
2. **Create a branch:**
   ```sh
   git checkout -b <branch_name>
   ```
3. **Make your changes and commit them:**
   ```sh
   git commit -m '<commit_message>'
   ```
4. **Push to the original branch:**
   ```sh
   git push origin <project_name>/<location>
   ```
5. **Create a pull request.**

### License
This project is licensed under the @2023 Surya Kiran Varma Vegesna.

### Contact
If you have any questions or want to contribute, please email us at surya@example.com.
