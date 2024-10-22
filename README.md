# Air Quality Index Detection Project
--------------------------------------------
Team Leader - Gaurav Sharma     
Year- Third Year     
Branch - Electronics and Computer Science    
Roll No.-48
--------------------------------------------
Team Member - Rithvika Sapalya     
Year- Third Year     
Branch - Electronics and Computer Science       
Roll No.-46
--------------------------------------------
Team Member - Amar Singh       
Year- Third Year      
Branch - Electronics and Computer Science      
Roll No.-54
--------------------------------------------
Hello everyone ,
We are a group of three students preparing a project for an Machine Learning Innovation Challenge.
# The problem statement that we are working on states that we have to explore building models to predict air quality index based on existing parameters like CO, Ozone, PM2.5 and analyze the impact of weather conditions on air quality in different regions.
Air pollution is a significant environmental issue affecting public health worldwide. Various pollutants, such as Carbon Monoxide (CO), Ozone (O3), and Particulate Matter (PM2.5), contribute to the deterioration of air quality. Understanding the relationship between these pollutants and weather conditions can help in predicting air quality and implementing effective mitigation strategies.
# Introduction to our Dataset 
The dataset was provided to us by the organising team it contains the mixture of both numeric and string values in it. It has total 26,705 rows and 41 columns. Our dataset consists of the value of carbon monoxide,ozone and PM2.5 based on different regions and location names.Also our data consists of weather details along with wind direction, pressure, temperature, and visibility.
# Information about Data Split
We have splitted the data into training and test data set so that it will be easy to fit the dataset into our model so that the accuracy we obtain is up to the mark.    
Also we used two parameters to split the dataset.    
1.test_size=0.2:     
This parameter specifies the proportion of the dataset that should be allocated to the testing set.     
In this case, test_size=0.2 means that 20% of the data will be reserved for testing, while the remaining 80% will be used for training the model.     
The choice of this ratio depends on factors like the size of the dataset and the desired trade-off between the size of the training set and the size of the testing set.     
2.random_state=42:     
The random_state parameter is used to seed the random number generator during the data splitting process.        
Setting random_state to a specific value, such as 42 in this case, ensures reproducibility. If you use the same seed in different runs, you will get the same split each time, which is crucial for consistency in model evaluation and comparison.      
The actual value (e.g., 42) is arbitrary and chosen for its convention, but any fixed integer can be used.   
![image](https://github.com/Gauravv08/Think-ML/assets/99554330/c8bd01c0-e798-4f42-bbf6-545d7d242410)
# Approach
The approach began with loading the air quality dataset, encompassing features like CO, O3, PM2.5, and weather conditions, as well as the target variable (AQI). To facilitate model interpretation, categorical data, such as regions, were encoded into numerical values. Subsequently, Seaborn was employed for data visualization, allowing for the exploration of relationships between various features and the AQI. Following visualization, the dataset was split into training and testing sets, with 80% allocated for training and 20% for testing, utilizing a random seed for reproducibility. Finally, a Random Forest Classifier was chosen as the predictive model, fitting it to the training data. The model's performance was evaluated on the testing set to gauge accuracy. This systematic approach aimed to leverage machine learning techniques for predicting AQI while considering the impact of weather conditions.
We also did the project on a application provided by Altair named Rapid Miner. 
This is the screenshot of the model
![Screenshot 2024-02-11 191406](https://github.com/Gauravv08/Think-ML/assets/99554330/1df7dfb8-58fe-43ad-8688-6d3fd15a2f4b)
## Coding Approach
![image](https://github.com/Gauravv08/Think-ML/assets/99554330/303cd0a6-85a5-4228-8601-b7a16eb819bd)
# Result
The predictive model exhibited promising results in forecasting Air Quality Index (AQI) based on the selected features such as CO, O3, PM2.5, and weather conditions. The model's effectiveness was assessed through various metrics, providing insights into its predictive capabilities.
## Graphical Comparision Between Parameters
![Screenshot 2024-02-11 121409](https://github.com/Gauravv08/Think-ML/assets/99554330/d9e0a2df-10c6-4aea-8a75-af402ecb6509)
## Graphical Comparision Between Models
![Screenshot 2024-02-11 121312](https://github.com/Gauravv08/Think-ML/assets/99554330/fe0fbfa6-702c-4490-b03b-5f4066b9b051)
## Comparision Chart
![Screenshot 2024-02-11 121245](https://github.com/Gauravv08/Think-ML/assets/99554330/7b54c30f-760d-4766-92c7-e7c8e74d4576)
## Predictions
![predictions](https://github.com/Gauravv08/Think-ML/assets/99554330/675857e5-1316-414e-812a-1e9f23f6d974)
## Optimal Parameters
![optimal parameters](https://github.com/Gauravv08/Think-ML/assets/99554330/e7a9241b-71c0-432b-8395-cac9a4836372)
## Lift Chart
![lift chart](https://github.com/Gauravv08/Think-ML/assets/99554330/339f8b3a-8901-4093-8c2c-d7407fc9be6f)
## Correlations
![correlations](https://github.com/Gauravv08/Think-ML/assets/99554330/2cba2136-eca2-4ed5-8251-4853b7413429)
## Confusion Matrix
![confusion matrix](https://github.com/Gauravv08/Think-ML/assets/99554330/1f678d5b-4b4b-4bae-8017-c2cae7378aef)
## Output
![image](https://github.com/Gauravv08/Think-ML/assets/99554330/918e8939-d006-471f-8885-c483e0163674)
## Coding Result
![image](https://github.com/Gauravv08/Think-ML/assets/99554330/f6ab4dac-ab30-4b4e-a3b3-681544c870e7)            
**Further results are available in the code preview section.**
# Dependencies
The project's success relies on the availability and quality of air quality and weather data. Dependencies also include the proper functioning of machine learning libraries, such as scikit-learn and Seaborn, for data manipulation, visualization, and modeling.
# Performance , Accuracy and F1 Score
## Performance
![performance](https://github.com/Gauravv08/Think-ML/assets/99554330/f9d2aa8a-11f9-433d-b3f4-8ebbc09a1ba3)
## Accuracy and F1 Score
![image](https://github.com/Gauravv08/Think-ML/assets/99554330/5aafa1d6-dd0c-4e7f-87df-781705ac8a9f)
![image](https://github.com/Gauravv08/Think-ML/assets/99554330/230f24a7-d819-484f-9229-9d8ffd7fe779)
# Novelty Factor
The novelty factor was explored by assessing the model's adaptability to new data and environmental conditions. This involved validation on unseen data and consideration of the model's robustness in predicting AQI in diverse scenarios.
![image](https://github.com/Gauravv08/Think-ML/assets/99554330/3a6e696c-619c-4c62-8049-404edc694af4)
# Video Of Code and the Model
https://github.com/Gauravv08/Think-ML/assets/99554330/3f9d7afe-1406-4b2e-b51b-8ef368dbdb3c
# References
The project drew upon relevant literature, research papers, and online resources for methodologies, data preprocessing techniques, and validation approaches.    
Altair website was the main source of reference for us as it helped me to easily understnad the application along with model interpretations.




