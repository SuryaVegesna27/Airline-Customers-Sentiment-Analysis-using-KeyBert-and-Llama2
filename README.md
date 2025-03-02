# **Airline Customer Experience Analysis**  

## **Project Overview**  
This project analyzes airline customer experiences by leveraging **Natural Language Processing (NLP)** and **Machine Learning (ML)**. It extracts insights from customer reviews and numerical ratings to uncover patterns, detect sentiments, and identify critical factors affecting customer satisfaction or dissatisfaction.  

---

## **Purpose**  
With millions of online reviews, airlines need to understand passenger sentiments to improve their services. This project aims to:
- **Extract and analyze customer reviews** to identify major complaints and praises.
- **Perform sentiment analysis** to classify reviews as positive, negative, or neutral.
- **Implement topic modeling** to detect key themes such as food quality, staff behavior, and seating comfort.
- **Build a recommendation system** using machine learning models to predict customer satisfaction.  
- **Provide actionable insights** for airlines to enhance their services.  

---

## **Prerequisites**  
Ensure you have the following installed before running the project:  

- **Python** (≥ 3.7)  
- **Jupyter Notebook**  
- **Required Python Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `nltk`
  - `keyBERT`
  - `llama-index`
  - `openai` (for ChatGPT API usage)  

---

## **Installation and Setup**  

### **1. Clone the Repository**  
```sh
git clone https://github.com/yourusername/airline-customer-experience-analysis.git
cd airline-customer-experience-analysis
```

### **2. Set Up a Virtual Environment and Install Dependencies**  
```sh
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
pip install -r requirements.txt
```

### **3. Open Jupyter Notebook**  
```sh
jupyter notebook
```
Run the **`Customer_Reviews_Sentiment_Analysis.ipynb`** notebook to execute the analysis.  

---

## **Project Workflow**  

### **Step 1: Web Scraping Airline Reviews**  
- Uses `BeautifulSoup` and `requests` to scrape airline reviews from airlinequality.com.  
- Extracts:
  - **Airline name**
  - **Review title**
  - **Review text**
  - **Overall rating**
  - **Service ratings (e.g., cabin staff, inflight entertainment, seat comfort)**  
- Saves structured data into a CSV file for further analysis.  

### **Step 2: Data Cleaning & Preprocessing**  
- Handles missing values and incorrect data entries.  
- Tokenizes and normalizes review text using `nltk`.  
- Removes stopwords and applies **lemmatization** for better analysis.  

### **Step 3: Sentiment Analysis**  
- **Lexicon-Based Sentiment Analysis**:  
  - Uses `NLTK VADER` to classify reviews into **positive, negative, or neutral**.  
- **ChatGPT-3.5 Sentiment Categorization**:  
  - Uses OpenAI’s GPT model for advanced sentiment classification and topic extraction.  

### **Step 4: Topic Modeling**  
- **KeyBERT** extracts the main topics from reviews.  
- **LLama2** identifies patterns and clusters similar reviews.  
- Visualizes insights using `matplotlib` and `seaborn`.  

### **Step 5: Recommendation System (Machine Learning Model)**  
- Predicts whether a customer would **recommend an airline** based on their ratings and review sentiment.  
- Models Used:
  - **Logistic Regression**
  - **K-Nearest Neighbors (KNN)**
  - **Decision Trees**
  - **Random Forest**  
- Evaluates models using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**  

---

## **Results & Insights**  

### **Key Findings**  
- **Sentiment Analysis Results**:
  - **Negative reviews** often focus on **delays, baggage handling, and customer service.**  
  - **Positive reviews** highlight **in-flight experience, staff friendliness, and business class seating.**  
- **Topic Modeling Insights**:
  - Frequent topics include **WiFi connectivity, legroom space, and meal quality.**  
- **Machine Learning Model Performance**:
  - **Logistic Regression achieved the highest accuracy** for predicting customer recommendations.  
  - **Decision Trees** performed well in capturing nuanced sentiments.  

---

## **How to Contribute**  
Contributions are welcome! Follow these steps:  

1. **Fork the repository**  
2. **Create a feature branch**  
   ```sh
   git checkout -b feature-branch-name
   ```
3. **Make changes & commit them**  
   ```sh
   git commit -m "Add new feature/fix"
   ```
4. **Push changes**  
   ```sh
   git push origin feature-branch-name
   ```
5. **Create a pull request** on GitHub.  

---

## **License**  
This project is licensed under **MIT License** © 2024 [Surya Kiran Varma Vegesna]  

---

## **Contact**  
For queries or contributions, contact **Surya Kiran Varma Vegesna** at:  
📧 **Email**: surya@example.com  
🔗 **GitHub**: [yourusername](https://github.com/yourusername)  

---

### **Why This Update?**
✅ **Detailed structure** with a **purpose section** for clarity.  
✅ **Step-by-step explanation** of scraping, NLP, and ML workflow.  
✅ **Well-formatted GitHub-friendly layout.**  
✅ **Clear instructions for setup and contributions.**  

**You can copy-paste this directly into your `README.md` on GitHub. 🚀**

