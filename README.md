# Travel Survey Analysis - AIML Project

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?style=flat-square&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-green?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Industry](https://img.shields.io/badge/Industry-Travel%20%26%20Transportation-blue?style=flat-square&logo=airplane&logoColor=white)
![Project Type](https://img.shields.io/badge/Project-Customer%20Analytics-purple?style=flat-square&logo=chart-line&logoColor=white)

A machine learning project focused on predicting customer satisfaction (Overall Experience) based on travel survey data and passenger demographics.

## 🎓 Academic Context

This project was developed as part of the **MIT Professional Education Program - Applied AI and Data Science Program**.

**Program Details:**
- **Institution**: Massachusetts Institute of Technology (MIT)
- **Program**: Applied AI and Data Science Program
- **Focus**: Practical application of machine learning and data science techniques
- **Website**: [MIT Online Data Science Program](https://professional-education-gl.mit.edu/mit-online-data-science-program)

The project demonstrates real-world application of data science methodologies, following industry best practices and academic rigor expected in MIT's professional education curriculum.

## 🏷️ Keywords & Topics

**Primary Keywords**: Data Science • Machine Learning • Customer Satisfaction • Python • Travel Industry Analysis  
**Technical Stack**: Pandas • Scikit-Learn • Statistical Analysis • Data Visualization • Classification Models • Feature Engineering  
**Business Focus**: Customer Experience • Service Quality Analysis • Travel Analytics • Satisfaction Prediction • Customer Insights  
**Industry**: Transportation • Travel Services • Passenger Experience • Service Quality • Customer Relationship Management  

**Project Type**: Customer Analytics & Machine Learning | Industry: Travel & Transportation | Focus: Customer Satisfaction & Service Quality

---

## Dataset Overview

This project contains travel survey data split into training and testing sets, with the goal of predicting customer satisfaction based on various service quality metrics and travel characteristics.

**📋 For detailed methodology, requirements, and best practices, see [PROJECT_DESCRIPTION.md](PROJECT_DESCRIPTION.md)**

### Files Structure

```
├── .gitignore                   # Git ignore file for system files and artifacts
├── Data_Dictionary.xlsx         # Data dictionary with variable descriptions
├── LICENSE                      # MIT License file
├── PROJECT_DESCRIPTION.md       # Comprehensive project description, methodology, and requirements
├── README.md                    # Project overview and getting started guide
├── requirements.txt             # Python dependencies and package versions
├── Submission_1.csv             # Sample submission format
├── Surveydata_train.csv         # Training survey responses (with target variable)
├── Surveydata_test.csv          # Test survey responses (without target variable)
├── Traveldata_train.csv         # Training travel demographics and details
├── Traveldata_test.csv          # Test travel demographics and details
└── travel_survey_analysis.ipynb # Complete ML pipeline and analysis notebook
```

---

## Dataset Features

### Survey Data Features
- **Service Quality Metrics**: Seat Comfort, Catering, Platform Location, Onboard WiFi Service, Onboard Entertainment, Online Support, Ease of Online Booking, Onboard Service, Legroom, Baggage Handling, Check-in Service, Cleanliness, Online Boarding
- **Seat Class**: Green Car, Ordinary
- **Arrival Time Convenience**: Rating of arrival time convenience

### Travel Data Features
- **Demographics**: Gender, Age, Customer Type (Loyal/Disloyal Customer)
- **Travel Details**: Type of Travel (Business/Personal), Travel Class (Business/Eco), Travel Distance
- **Delay Information**: Departure Delay in Minutes, Arrival Delay in Minutes

### Target Variable
- **Overall_Experience**: Binary classification (0 = Dissatisfied, 1 = Satisfied)

---

## Getting Started

1. **Data Exploration**: Start by examining the training datasets to understand feature distributions and relationships
2. **Data Preprocessing**: Handle missing values, encode categorical variables, and merge survey and travel data
3. **Feature Engineering**: Create new features from existing ones if needed
4. **Model Development**: Build and evaluate classification models
5. **Prediction**: Generate predictions for the test set in the submission format

---

## Submission Format

The final predictions should be submitted in CSV format with columns:
- `ID`: Passenger identifier
- `Overall_Experience`: Predicted satisfaction (0 or 1)

---

## Data Quality Notes

- Some missing values are present in the datasets (empty cells)
- Survey responses use categorical ratings (Poor, Needs Improvement, Acceptable, Good, Excellent)
- Travel data includes both categorical and numerical features
- Test and training sets have different ID ranges (988xxxxx for training, 999xxxxx for testing)

---

## Quick Start

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/sandesha21/travel-survey-analysis-AIML-project
   cd travel-survey-analysis-AIML-project
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

### Running the Analysis
1. Open `travel_survey_analysis.ipynb` in Jupyter
2. Run all cells sequentially
3. The notebook will generate `final_submission.csv` with predictions

---

## Next Steps

1. Perform exploratory data analysis (EDA)
2. Implement data preprocessing pipeline
3. Train classification models (Logistic Regression, Random Forest, XGBoost, etc.)
4. Evaluate model performance using appropriate metrics
5. Generate final predictions for submission

---

## � Results & Performance

The project implements multiple machine learning models:
- **Logistic Regression** (baseline)
- **Random Forest** 
- **Gradient Boosting**
- **Support Vector Machine**

Key evaluation metrics:
- Accuracy
- AUC-ROC Score
- Precision & Recall
- Feature Importance Analysis

---

## 🔍 Key Insights

- **Service Quality Impact**: Identifies which service aspects most influence satisfaction
- **Customer Segmentation**: Analyzes satisfaction patterns across different traveler types
- **Delay Analysis**: Quantifies the impact of delays on customer experience
- **Actionable Recommendations**: Provides data-driven suggestions for service improvements

---

## 👨‍💻 Author  
**Sandesh S. Badwaik**  
*Applied Data Scientist & Machine Learning Engineer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sbadwaik/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sandesha21)

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

--- 

🌟 **If you found this project helpful, please give it a ⭐!**