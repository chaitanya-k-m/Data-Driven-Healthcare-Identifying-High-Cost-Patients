# Predicting Healthcare Costs: HMO Data Analysis & Machine Learning  

## **Project Overview**  
This project applies **data science and machine learning techniques** to analyze healthcare costs using data from a **Health Management Organization (HMO)**. The goal is to identify **key factors driving high medical expenses** and develop a **predictive model** to forecast individuals with high future healthcare costs. Additionally, the project provides **data-driven recommendations** to help reduce overall medical expenses.  

## **Project Goals**  
1. **Predict which individuals will have high healthcare costs** in the upcoming year using machine learning models.  
2. **Identify the primary factors contributing to high medical expenses**, such as **age, BMI, smoking habits, exercise frequency, and chronic conditions**.  
3. **Develop an interactive Shiny app** that enables real-time predictions based on user-input data.  
4. **Provide actionable recommendations** for cost reduction strategies based on analytical insights.  

## **Key Analysis & Findings**  
- **Exploratory Data Analysis (EDA)**:  
  - **Histograms & boxplots** visualize the distribution of age, BMI, and cost variables.  
  - **Correlation heatmaps** identify strong relationships between variables.  
  - **Geospatial analysis** highlights regional differences in healthcare costs.  

- **Predictive Modeling**:  
  - Implemented multiple models including **Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting**.  
  - Optimized models to maximize **sensitivity**, ensuring high-cost individuals are accurately identified.  
  - Used **cross-validation** to enhance model robustness.  

- **Shiny App Development**:  
  - **Interactive tool** for predicting whether a person will have high medical expenses.  
  - Uses **pre-trained models** to classify new test data.  
  - Displays **confusion matrix and sensitivity scores** for model evaluation.  

## **Methodology & Workflow**  
1. **Data Cleaning & Preprocessing**:  
   - Removed missing values and standardized categorical data.  
   - Created a **new ‘expensive’ classification label** based on cost thresholds.  

2. **Feature Engineering**:  
   - Derived new variables such as **BMI categories and smoking-exercise interaction**.  

3. **Machine Learning Model Training**:  
   - Split data into **training and test sets**.  
   - Tuned hyperparameters for better model performance.  

4. **Model Evaluation & Selection**:  
   - Used **confusion matrices and sensitivity scores** to compare models.  
   - Selected the **best-performing model** based on **predictive accuracy and sensitivity**.  

5. **Shiny App Deployment**:  
   - Built an interactive **web application** hosted on **shinyapps.io**.  
   - Allows users to input new data and obtain **real-time predictions**.  

## **Technology Stack**  
- **R (Tidyverse, Caret, Shiny, ggplot2)** – Data analysis, visualization, and machine learning.  
- **Shiny (shinyapps.io)** – Interactive web-based dashboard for real-time predictions.  
- **RMarkdown** – Report generation and documentation.  
- **Geospatial Mapping** – Analyzed location-based trends in healthcare costs.  

## **Project Deliverables**  
- **Exploratory Data Analysis Report (PDF)**
- **Machine Learning Code (R scripts)**
- **Predictive Model**
- **Shiny App**
- **Presentation Deck (PPTX)**  
