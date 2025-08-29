# Salma Bhar Portfolio
## 1. Introduction
Hello! My name is Salma Bhar (she/her). I am an international student from Tunisia and a senior pursuing a B.A. in Computer Science and Minors in Mathematics and Astronomy (because it's fun) at Case Western Reserve University, Cleveland OH. I also studied abroad at Universidad Carlos III in Madrid, Spain and I am a graduate of UWC ISAK Japan which is part of the United World Colleges movement.

This is a repository to showcase skills, share projects and track my progress in Data Science and AI/ML related topics. I am aiming to start exploring the application of Computer Science in research projects.

My LinkedIn: https://www.linkedin.com/in/salmabhar/

## Table of Contents
1. Introduction
2. Machine Learning Projects
    - Machine Learning Approach to Predicting Countries' Happiness Index
    - Detecting Objects in Autonomous Driving
    - Algorithmic Justice League Equitable AI for Dermatology
    - Quantum Reinforcement Learning for Multi-Armed Bandit and Control Tasks
3. Data Science in Research Projects
    - A Data-Driven Approach to Enhancing Solar Cell Longevity and Efficiency
4. Software Engineering
    - Snack Overflow

## 2. Machine Learning Projects
### Machine Learning Approach to Predicting Countries' Happiness Index
**Description:** This project aims to predict the happiness index, also known as the Life Ladder score, of countries using data from the World Happiness Report. The dataset includes variables such as GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, perceptions of corruption, and several other factors. I experimented with additional models such as Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor. Then, I performed hyperparameter tuning using cross-validation to find the best set of hyperparameters. Additionally, I conducted feature selection and engineering to identify and include relevant features that improved model performance. Finally, I analyzed residuals and iterated on model improvements.

**Skills:** Data Preprocessing, Exploratory Data Analysis (EDA), Feature Engineering, Regression Analysis, Model Selection, Hyperparameter Tuning, Model Evaluation, Data Visualization, Decision Trees, Random Forest, Gradient Boosting

**Technology:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.

**Results:** The best-performing model was a Gradient Boosting Regressor, which achieved the following metrics:
  - Mean Absolute Error (MAE): 0.2119
  - Mean Squared Error (MSE): 0.0860
  - R-squared (R^2): 0.7912
The model successfully identified key features contributing to the happiness index, providing valuable insights into factors influencing national happiness.

**Code:** [Jupiter Notebook File](https://github.com/Salma-Bhar-CWRU/Salma-Bhar-Portfolio/blob/main/PredictingHappinessIndexUsingML.ipynb)

### Detecting Objects in Autonomous Driving
**Description:** This project with Latitude AI aims to developed a 3D object detection system for autonomous driving. We utilized Detectron2 and DepthAnything to process over 34,000 samples from the nuScenes dataset. We implemented a method enhancing 2D detections with depth to approximate a 3D scene understanding. Delivered a comprehensive project report and a functional model for self-driving car safety. This project advanced vehicle safety and autonomy by leveraging machine learning and data science.

**Skills:** Team Work, Project Management, Depth estimation, Data Visualizaion, Data processing. 

**Technology:** Python,nuScenes, Detectron2, DepthAnything, Matplotlib, Numpy, Scipy.

**Potential Next Steps:**
  - Expanding 3D detection on more categories (pedestrians, buses, traffic lights, etc…)
  - If enough computational resources are available, revisit our initial approach i.e. a FastBEV-based approach 
  - Expanding the method on multiple cameras instead of a single camera

**Code:** Project Github repo can be found [here.](https://github.com/natwoshoes/ObjectDetectionModel_LatitudeAI)

### Algorithmic Justice League Equitable AI for Dermatology
**Description:** Built inclusive ML models for dermatology image classification as part of the Break Through Tech AI program and the Algorithmic Justice League x Kaggle Challenge. Aimed to improve diagnosis accuracy across diverse skin tones. </br>
 
**Project Highlights:** </br>
- Selected EfficientNetB3 as final model with ~94% test accuracy and macro F1 of 0.96.
- Addressed algorithmic fairness using stratified validation and data balancing techniques.
- Collaborated on CNN, ViT, and ResNet architectures to benchmark model performance.
  
**Skills:** Deep Learning, Fairness in AI, Vision Transformers, EDA </br>
**Tech:** Python, TensorFlow, Keras, EfficientNet, ResNet, Kaggle </br>

**Code:** Project Poster can be found [here](https://github.com/AJL-Team-Selenium/VIR-Team-Selenium)

### Quantum Reinforcement Learning for Multi-Armed Bandit and Control Tasks
**Description:** This project explores Quantum Reinforcement Learning (QRL) by applying quantum variational circuits to the Multi-Armed Bandit (MAB) problem and extending to full reinforcement learning tasks such as CartPole and LunarLander. The goal was to investigate whether quantum methods can improve exploration efficiency, reduce trainable parameters, and achieve more stable convergence compared to classical reinforcement learning (RL). </br>
 
**Project Highlights:** </br>
- Implemented ε-greedy classical RL for baseline performance on MAB.
- Designed Variational Quantum Circuit (VQC) agents (4–8 qubits) for CartPole and LunarLander.
- Compared VQC-DQN (quantum policy + classical updates) and Hybrid A2C (quantum actor + classical critic) frameworks.
- Demonstrated that QRL reduced trainable parameters by up to 90% while maintaining comparable performance to classical RL.
- Highlighted interdisciplinary impacts in physics (entropy reduction via superposition), engineering (decision-making under uncertainty), and computer science (compact policy representations).
  
**Skills:** Quantum Computing, Reinforcement Learning, Variational Quantum Circuits (VQC), Qiskit, Classical vs Quantum RL, Data Analysis, Interdisciplinary Research </br>
**Tech:** Python, Qiskit, NumPy, SciPy, Matplotlib </br>

**Results:** 
- Classical RL (ε-greedy): reliable convergence, but slower and parameter-heavy.
- QRL: fewer tunable parameters, stable convergence trends, parameter-efficient but with simulation overhead.
- Showed strong promise for data-efficient decision-making despite current hardware limitations.

**Code:** Project Github repo can be found [here](https://github.com/Salma-Bhar-CWRU/Portfolio/blob/main/QCID%20386%20Final%20Poster.pptx.pdf)

## 3. Data Analysis in Research Projects
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

## 4. Software Engineering
### Snack Overflow
**Description:** A full-stack snack management system for workplaces, where employees can order, upvote, and track snacks, while admins monitor inventory and employee trends. Features include authentication, snack ordering limits, inventory tracking, and real-time statistics. </br>
 
**Project Highlights:** </br>
- Built using React (frontend) and Node.js/Express with MySQL (backend).
- Daily snack limit system, profile dashboards, and a dynamic role-based sidebar.
- Real-time inventory updates and smart snack control based on availability.
  
**Skills:** Full-Stack Dev, REST APIs, Authentication, Role-based UI </br>
**Tech:** React, Node.js, Express, MySQL, JavaScript, HTML/CSS </br>

**Code:** Project Github repo can be found [here](https://github.com/Salma-Bhar-CWRU/Snack-Overflow/tree/main)
