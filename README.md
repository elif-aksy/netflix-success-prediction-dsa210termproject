 Netflix Success Prediction

##  Project Overview
This project aims to analyze and predict the success of Netflix movies and TV shows using data science and machine learning techniques. The goal is to identify which factors influence content success and build models to predict IMDb ratings.

---

##  Objectives
- Analyze Netflix content data (movies & TV shows)
- Identify factors affecting success (genre, country, year, etc.)
- Perform exploratory data analysis (EDA)
- Conduct statistical hypothesis testing
- Build machine learning models to predict IMDb ratings

---

##  Datasets

### 1. Netflix Titles Dataset
- Source: Kaggle
- Features:
  - Title
  - Type (Movie / TV Show)
  - Genre
  - Release Year
  - Country
  - Duration

### 2. IMDb Ratings Dataset
- Source: Kaggle
- Features:
  - IMDb Rating
  - Vote Count

###  Data Enrichment
The datasets are merged based on title names to enrich the Netflix dataset with rating information.

---

##  Project Pipeline

1. Data Collection  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Hypothesis Testing  
5. Feature Engineering  
6. Machine Learning Models  
7. Evaluation & Interpretation  

---

##  Machine Learning Models
- Linear Regression  
- Decision Tree  
- Random Forest  

---

##  Evaluation Metrics
- Mean Squared Error (MSE)  
- R² Score  

---

##  Project Structure

```
netflix-success-prediction/
│
├── data/              # Raw and processed datasets
├── notebooks/         # Jupyter notebooks (EDA, ML)
├── src/               # Python scripts (optional)
├── results/           # Figures and outputs
├── requirements.txt   # Dependencies
└── README.md
```

---

##  How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/netflix-success-prediction.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run notebooks:
```bash
jupyter notebook
```
---

##  Author
- Elif Aksoy

##  License
This project is for academic purposes (DSA 210).
