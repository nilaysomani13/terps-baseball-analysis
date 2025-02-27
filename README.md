# terps-baseball-analysis

## 📖 Overview  
This project focuses on analyzing historical baseball data for the UMD Terps Baseball Team using Python. Our objective was to develop predictive models to forecast game outcomes for the 2024 season based on past performance, location, and opponent.  

## 🛠 Tools and Technologies Used  
- Programming Language: Python  
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- Development Environment: Google Colab  

## 🔍 Machine Learning Models & Techniques  
- **Linear Regression:** Used to identify patterns between variables like location, opponent, and historical game outcomes.  
- **Logistic Regression:** Used to classify results into Win/Loss as a binary classification problem.  
- **Model Evaluation:** Evaluated models using RMSE (Root Mean Squared Error), Confusion Matrix, Accuracy, and Recall.  

## 🔄 Data Preprocessing  
- Segregated game records based on wins/losses and home/away statistics.  
- Extracted relevant features such as year from game records and historical opponent performance.  
- Downloaded and cleaned 2024 season schedule from [UMTerps Baseball](https://umterps.com/sports/baseball/schedule) for model testing.  

## 🔮 Predictive Modeling for 2024  
- **Historical Data Utilization:** Trained models using past baseball data to forecast performance in different locations.  
- **Feature Selection & Development:** Insights from exploratory data analysis informed model development.  
- **Model Validation:** Evaluated reliability and accuracy of predictions for the 2024 season.  

## 🔬 Research Conducted  
1. **2024 Baseball Schedule Dataset** – Sourced from UMTerps and converted from PDF format for analysis.  
2. **Model Selection** – Explored different regression models through literature, course modules, and past research to identify the best fit for our dataset.  

## 🚧 Challenges Faced  
- **Dataset Selection:** Whether to use existing historical data or work solely with the new 2024 dataset.  
- **Data Size & Context:** Lack of player performance details made it challenging to explain performance changes (e.g., new players, injuries).  
- **Model Selection:** Choosing the most suitable model required experimentation and domain knowledge.  
- **Handling Draws:** Only one recorded draw in 24 years posed a challenge for meaningful classification.  

## 🎯 Accomplishments  
### 📊 Data Preparation  
- Preprocessed dataset, handled outliers, and ensured data quality.  

### 📈 Exploratory Data Analysis (EDA)  
- Analyzed feature importance, win/loss trends, and performance by location.  
- Identified key influencing factors like team strengths, past results, and game locations.  

### 🔍 Feature Engineering  
- Created new features such as home/away statistics and team performance metrics.  
- Optimized feature selection to enhance model accuracy.  

### 🤖 Model Development  
- Built **Linear Regression** and **Logistic Regression** models.  
- Trained models on historical data (1999-2023) to predict 2024 outcomes.  

### 📑 Documentation & Reporting  
- Documented all preprocessing steps, model selection rationale, evaluation results, and key insights.  
- Created **visualizations** and reports for better stakeholder understanding.  

## 🛠 Model Testing & Evaluation  
- **Predicting 2024 Season Outcomes:** Trained models used **historical data** to predict outcomes, which were compared against real 2024 results.  
- **Testing on 1999-2023 Data:** Evaluated model accuracy using training data by analyzing **accuracy, confusion matrix, and RMSE**.  

## 🤝 Team Contributions  
| Team Member      | Contribution |
|----------------|--------------|
| **Shashank Bisht** | Led project presentation. |
| **Dhruvin Shah** | Focused on model development and evaluation. |
| **Nilay Somani** | Data processing, cleaning, and project documentation. |
| **Anudeep Koneru** | Conducted EDA and defined mission objectives. |

**💡 Note:** All team members collaborated across different aspects as needed.  

## 📚 Key Learnings  
- **Predictive Analytics in Sports:**  
  - Applied data-driven insights to sports performance analysis.  
  - Learned how **baseball statistics** are reported and interpreted.  
- **Collaboration & Communication:**  
  - Importance of knowledge sharing and leveraging past projects for efficiency.  
- **Continuous Learning:**  
  - Recognized the **iterative nature of data analytics**, requiring refinement of models based on new insights.  

## 🚀 Future Work & Recommendations  
- **Enhance Data Sources:** Include **player statistics, injury reports, and team rosters** to improve prediction accuracy.  
- **Advanced ML Models:** Explore **Random Forest, XGBoost, or Deep Learning** models for better performance.  
- **Real-Time Data Integration:** Implement an API to fetch live game statistics for ongoing evaluation.  

## 📬 Contact  
For any questions or collaboration opportunities, feel free to reach out!  
📧 **Email:** nsomani@umd.edu
🔗 **LinkedIn:** https://www.linkedin.com/in/nilaysomaniconnect/

---

## 🚀 Get Started (Run the Project)  
To run this project locally, follow these steps:  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/nilaysomani13/terps-baseball-analysis.git
cd terps-baseball-analysis

2️⃣ Install dependencies:
pip install -r requirements.txt

3️⃣ Run the analysis:
python project_0504_06_umterpsbaseball_analysis.py
