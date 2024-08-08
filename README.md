# Salma Bhar Portfolio
## 1. Introduction
Hello! My name is Salma Bhar (she/her). I am an international student from Tunisia and a third-year pursuing a B.S. in Computer Science with an AI concentration and a Minor in Astronomy at Case Western Reserve University, Cleveland OH. 

I also studied abroad at Universidad Carlos III in Madrid, Spain and I am a graduate of UWC ISAK Japan which is part of the United World Colleges movement.

I am exploring experiences in AI/ML, Data Analysis, and Technical Product Management.

This is a repository to showcase skills, share projects and track my progress in Data Science and AI/ML related topics.

## Table of Contents
1. Introduction
2. Machine Learning Projects
    - Machine Learning Approach to Predicting Countries' Happiness Index
3. Data Analysis in Interdisciplinary Research Projects
    - Accelerated Degradation in Advanced Photovoltaic Cells: A Data-Driven Approach to Enhancing Solar Cell Longevity and Efficiency

## 2. Machine Learning Projects
### Machine Learning Approach to Predicting Countries' Happiness Index
**Goal:** To develop a machine learning model that accurately predicts the happiness index of countries based on various socio-economic and political factors.

**Description:** This project aims to predict the happiness index, also known as the Life Ladder score, of countries using data from the World Happiness Report. The dataset includes variables such as GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, perceptions of corruption, and several other factors. I experimented with additional models such as Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor. Then, I performed hyperparameter tuning using cross-validation to find the best set of hyperparameters. Additionally, I conducted feature selection and engineering to identify and include relevant features that improved model performance. Finally, I analyzed residuals and iterated on model improvements.

**Skills:** Data Preprocessing, Exploratory Data Analysis (EDA), Feature Engineering, Regression Analysis, Model Selection, Hyperparameter Tuning, Model Evaluation, Data Visualization, Decision Trees, Random Forest, Gradient Boosting

**Technology:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.

**Results:** The best-performing model was a Gradient Boosting Regressor, which achieved the following metrics:
  - Mean Absolute Error (MAE): 0.2119
  - Mean Squared Error (MSE): 0.0860
  - R-squared (R^2): 0.7912
The model successfully identified key features contributing to the happiness index, providing valuable insights into factors influencing national happiness.

**Code:** [Jupiter Notebook File](https://github.com/Salma-Bhar-CWRU/Salma-Bhar-Portfolio/blob/main/PredictingHappinessIndexUsingML.ipynb)

## 3. Data Analysis in Interdisciplinary Research Projects
### Accelerated Degradation in Advanced Photovoltaic Cells: A Data-Driven Approach to Enhancing Solar Cell Longevity and Efficiency

**Undergraduate Researchers:** <br>
Salma Bhar, B.S. Computer Science, CWRU <br>
Marina Kamperai, B.S. Chemical Engineering. CWRU <br>
Shahib Prokhor, B.S. Biomedical Engineering, CWRU <br>
<br>
**Project Mentor:** Dr. Ina Martin, Materials Science and Engineering, CWRU <br>
<br>
**Partners and project members:** <br>
Dr. Laura Bruckman, Materials Science and Engineering, CWRU <br>
Mirra Rasmussen, Graduate Student, Materials Science and Engineering, CWRU <br>
Mariana Bertoni,  Arizona State University <br>
Kristopher O. Davis, University of Central Florida <br>

**Abstract:** Advanced crystalline silicon photovoltaic (PV) cell architectures such as silicon heterojunction cells (SHJ) mitigate energy conversion losses present in traditional architectures. However, the use of new materials and processes introduces the potential for new failure modes. The objective of this project is to apply different accelerated aging exposures with combined stressors including light, temperature, to different cell architectures; currently, this includes PERC, PERT and, SHJ architectures. In the near future, tunnel-oxide passivated contact (TOPCon) cells will also be included. We will focus on identifying degradation modes due to variations in the surface layers, including the Si passivation materials, and screen printed contacts, both known sources of solar cell degradation. The research methodology includes an initial performance assessment of the PV cells, exposure to accelerated aging conditions, and subsequent periodic re-characterization. The changes in devices are measured through key performance parameters, such as Current-Voltage characterization (I-V), Suns Voltage (Suns-Voc), and Quantum Efficiency (QE), are measured and recorded. To analyze and visualize the degradation data, we employ the R programming language and associated packages, including ggplot, dplyr, and tidyverse. These tools help extract valuable features from the I-V, QE, and Suns-Voc data, allowing us to gain a comprehensive understanding of the degradation effects on each type of solar cell and the underlying mechanisms. The data-driven models concluded from this research project will contribute to better insights about the performance of photovoltaic cells. In other words, we can conclude better ways to predict the lifetime of solar cells, and ultimately contribute to improved design. The conclusions from this research could also be applied to larger areas in the field of photovoltaic cells and contribute to more sustainable practices in energy production. 


**Skills:** data cleaning, data management, data visualization, data analysis & modeling, interdisciplinary knowledge

**Technology:** R, dplyr, tidyverse, ggplot2, RStudio, High Performance Computing (HPC), Git, Jira

**Presentations:** Sponsored by CWRU to present at the SUNY Buffalo Undergraduate Research Conference in July 2023. Presented a poster as a team at the Fall 2023 intersections at CWRU.

**Poster:** [Fall 2023 Intersections Poster](https://github.com/Salma-Bhar-CWRU/Salma-Bhar-Portfolio/blob/main/Intersections%20December%202023%20-%20Salma%20Bhar%20Marina%20Kamperai%20Shahib%20Prokhor.pdf)
