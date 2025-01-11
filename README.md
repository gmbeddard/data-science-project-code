### EM255 Intro to Data Science Final Project: An Analysis on Endometriosis in South Asian Women

#### Project Overview
As a part of our work for our women's health-focused startup, Saha, we developed a model investigating the factors influencing endometriosis in South Asian women. We focused on symptoms such as infertility, menstrual irregularities, blood pressure, and depression. The study also examines socioeconomic impacts on healthcare access in the U.S., particularly regarding the diagnosis and treatment of endometriosis. Using the National Health and Nutrition Examination Survey (NHANES) dataset (2005-2006 cycle), the project employs data science and machine learning techniques to explore patterns, build predictive models, and derive actionable insights.

#### Features
- **Data Cleaning and Preparation**: Integrated data from reproductive health, demographics, depression, and blood pressure datasets, focusing on critical variables such as diagnosis, age, and socioeconomic indicators.
- **Data Visualization**: Created visualizations like box plots, pie charts, heatmaps, and point plots to analyze trends across variables such as race, income, and menstrual irregularity.
- **Predictive Modeling**:
  - Logistic Regression, Decision Tree Classification, and Naive Bayes models were implemented.
  - Naive Bayes achieved the best performance, with 80% accuracy and better balance between true positives and negatives.
- **Ethical Considerations**: Addressed issues of algorithmic bias, data security, and potential misuse of findings, emphasizing inclusivity and fairness in healthcare applications.

#### Results and Insights
- **Key Factors**: Features such as age, days since the last period, and socioeconomic status significantly impact diagnosis likelihood.
- **Findings**:
  - Higher income levels correlate with earlier and more consistent diagnoses.
  - Non-Hispanic white women are diagnosed more frequently, likely reflecting healthcare access disparities.
  - Irregular menstrual cycles are strongly associated with endometriosis.

#### Future Directions
- Integrate updated NHANES data and broaden demographic representation to include underserved groups.
- Enhance predictive models by refining features and testing advanced algorithms, since our initial models were not great.
- Expand focus to global populations, particularly South Asian women, for a more inclusive study.

#### Repository Content
- **Code**: Scripts for data cleaning, visualization, and model building are in the `src` folder.
- **Datasets**: Processed data files and links to raw NHANES datasets.
- **Google Collab Link**: We worked primarily on Google Collab and detailed our step-by-step process there. Here is the link: https://colab.research.google.com/drive/1wN9cWJCsdpCtSKAjW27ydoC0j2d6-7zk?usp=sharing.

#### Authors
Gabby Beddard, Camille Gimilaro

Thanks for reading :D
