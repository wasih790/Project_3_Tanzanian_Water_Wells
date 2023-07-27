
# Tanzanian Water Well Functionality Prediction
This repository contains a project focused on predicting the functionality of water well pumps in Tanzania. The goal of this project is to determine whether a pump is functional or non-functional and provide insights to prioritize repairs and filtration efforts for the wells.

![5-Common-Well-and-Pump-Problems](https://github.com/wasih790/Project_3_Tanzanian_Water_Wells/assets/120667351/fc18cb67-9f6e-43fa-ab0c-0d0e212665ad)

# Dataset
The dataset used for this project consists of information on 59,000 water wells in Tanzania. Among these wells, 36,576 are functional pumps, while 22,824 are non-functional pumps. The dataset includes various attributes related to the wells, such as water quality, installation details, and location-specific information, etc. The dataset used for analysis is stored in the file named Taz_Water.csv, located in the Data Wrangling directory.

![Screenshot 2023-07-27 at 9 58 32 AM](https://github.com/wasih790/Project_3_Tanzanian_Water_Wells/assets/120667351/dd0b7a40-1cc4-43ba-b0cb-e8a83bb55980)

# Analysis
The analysis focused on understanding the relationships between water well functionality and water quality attributes. The following insights were discovered:

- Out of the 36,576 functional pumps, 3,900 wells were found to have undrinkable water.
- Among the 22,824 non-functional pumps, 18,000 wells had drinkable water.

![Screenshot 2023-07-27 at 10 00 10 AM](https://github.com/wasih790/Project_3_Tanzanian_Water_Wells/assets/120667351/62f69227-3f6d-4b5e-8017-2dfa8c343b79)

# Fundraising and Repairs
Based on the analysis findings, the following recommendations are made regarding fundraising, repairs, and filtration efforts for the water wells:

1. Fundraising: Danida (Danish International Development Agency) is recommended as a potential source for raising funds due to its effectiveness and reliability.

2. Repairs: Prioritize repairs for functioning wells that require filters to yield safe drinking water. This strategy is recommended as it presents a smaller-scale project with significant impact potential.

3. Installer: Engage DWE (Department of Water and Energy) as the best installer for pumps, given their track record of installing 11,000 functional pumps. This choice ensures long-lasting and reliable installations.

4. Targeted Efforts: Concentrate repair and filtration efforts on regions with high population densities. This approach maximizes the positive impact on the most significant number of people.

# Model Development
For predicting water well functionality, three different models were developed and evaluated using accuracy and AUC score as performance metrics. Each model was fine-tuned to enhance its predictive capabilities. The models used in this project are as follows:

1. Logistic Regression: A logistic regression model was built to predict the functionality of water wells.

2. Hyper-Tuned Logistic Regression: The logistic regression model was further optimized by hyperparameter tuning to improve its performance.

3. Random Forest: A random forest model was employed to predict water well functionality, leveraging ensemble learning techniques.

4. Hyper-Tuned Random Forest: The random forest model was fine-tuned using hyperparameter optimization to maximize its accuracy and AUC score.

5. XG Boosted: An XG Boosted model was utilized to predict water well functionality, harnessing the power of gradient boosting algorithms.

6. Hyper-Tuned XG Boosted: The XG Boosted model was refined through hyperparameter tuning to achieve superior accuracy and AUC score.

# Best Model Performance
Among the six models developed, the hyper-tuned random forest model emerged as the best performer, delivering an accuracy of 85% and an AUC score of 91%. These metrics indicate that the model achieves a high level of accuracy in predicting water well functionality.

![Screenshot 2023-07-27 at 9 59 18 AM](https://github.com/wasih790/Project_3_Tanzanian_Water_Wells/assets/120667351/79f38382-5719-40a0-8442-d6c655689a35)

# Repository Structure
The repository has the following structure:

- Data Wrangling: This directory contains the dataset file (Taz_Water.csv) used for model training, evaluation, and exploratory data analysis.
- Simple Model: This directory contains Jupyter notebooks used for logistic regression model development.
- Complex Model: This directory contains the trained models Random Forest and XG Boosted and any necessary files related to the models.
- README.MD: This file provides an overview of the project, instructions, and other relevant information.
- Presentation: The file provides a pdf overview of the project and the analysis. 
- Visualization: This directory contains Tableau visualizations for the water well data. You can access the interactive visualizations using the following link: Tanzania Water Wells Tableau Visualizations
(https://public.tableau.com/app/profile/mohamed.katherhassan/viz/TanzaniaWaterWells_All/WaterWells)

# Original Data
- The Original data can be found on this link https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/
