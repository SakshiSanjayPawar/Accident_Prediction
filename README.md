#  Accident Prone Hotspots Prediction 
 
 
1. Project by:     
Gayatri Panse 
 Sakshi Pawar

2.Problem statement:  To predict accident-prone areas utilizing a comprehensive dataset comprising of 
geographical coordinates, weather conditions, road surface conditions, and other factors using Supervised 
Learning Algorithms namely Logistic Regression and Decision Tree.

3. Introduction: 
• Background: 
With the escalating rates of road accidents, there's an urgent need for advanced predictive 
analytics to proactively address road safety concerns. 
• Approach: 
This project harnesses the potential of machine learning algorithms, specifically Logistic 
Regression and Decision Tree Classifier models, to analyze historical accident data 
comprehensively. 
• Scope: 
Utilizing a supervised learning approach, we leverage a meticulously curated dataset 
containing detailed accident records. By employing these sophisticated techniques, we 
aim to identify underlying patterns and correlations contributing to accidents, facilitating 
targeted preventive measures and optimizing traffic management strategies to enhance 
overall road safety 
 
4. Tool used:  
• Google Colab 
• VS code 
 
5. Libraries Used: 
• Pandas,  
• Numpy 
• Matplotlib, 
• Sklearn(Scikit learn),  
• Gmplot

 
6.Languages: Python, HTML 

7. Dataset Information: 
Data Source: The dataset comprises historical accident records stored in CSV format. 
 
Key Features: 
 
• Index: Unique identifier for each record. 
 
• Latitude: Geographical latitude of the accident location. 
 
• Longitude:  Geographical longitude of the accident location. 
 
• Severity: Numerical scale indicating the severity of the accident. 
 
• No_of_casualties:  Number of casualties resulting from the accident. 
 
• Speed:  Speed of the vehicle involved at the time of the accident (in km/h). 
 
• Weather: Numerical code representing the weather conditions at the time of the accident,  
• with codes:- 1= Clear, 2=Fog,3= Rainy 
 
• Road_surface:  Numerical code indicating the type of road surface,  
• encoded as:   1=Concrete,2= Gravel,3= Bituminous 
 
• Alcohol: Binary indicator (0 or 1) where 1 indicates the presence of alcohol involvement in the 
accident and 0 indicates no alcohol involvement. 
 
• Gradient: Binary indicator (0 or 1) where 1 suggests a significant road gradient at the accident site 
and 0 indicates a flat road. 
 
• Intersection: Binary indicator (0 or 1) where 1 signifies the accident occurred at or near an 
intersection, and 0 indicates it did not. 
 
Each record in the dataset represents an accident occurrence, with features describing the conditions 
under which the accident occurred. These data will train our Logistic Regression and Decision Tree 
models to predict accident-prone areas based on given features. 
 
Categorization of road surface and weather conditions into numerical codes structures the dataset, easing 
modelling. Binary indicators for alcohol, gradient, and intersection simplify analysis of their impact on 
accidents, aiding accurate prediction of high-risk areas and analysis of various factors' influence on road 
safety. 

 
8. Methodology: 
1. Data Preparation: 
• Cleaning, transforming, and splitting the dataset into training (80%) and testing (20%) 
sets. 
2. Models Used: 
• Logistic Regression: Estimates the probability of an area being accident-prone. 
• Decision Tree Classifier: Classifies areas based on the probability of accidents. 
3. Unique Features: 
• Logistic Regression: Provides probabilities, offering a straightforward interpretation of 
risk levels. 
• Decision Trees: Offer a visual interpretation of decision-making processes, which is 
intuitive and easy to explain to non-technical stakeholders. 
 
 
 

9.Prediction plots on Google Map 
• Data representation in Google maps on the basis of Severity parameter 
 
 • Logistic Regression: 
1. Plotting Predictions on Google Maps 
 
 
2. Plotting Accurate Predictions 
TP, TN: Red Circles 
FP, FN: Yellow Circles 
 
 
 
• Decision Tree: 
1. Plotting Predictions on Google Maps 
 
 
2. Plotting Accurate Predictions 
TP, TN: Red Circles 
FP, FN: Yellow Circles 
 
10. Drive Link for entire project: 
https://drive.google.com/drive/folders/16pBem8AHSjnl1XOAOb8PiNsMABQc0cSR?usp=shari
 ng 
 
9.Conclusion:  
1. Summary: 
The Decision Tree model has exhibited superior performance compared to Logistic 
Regression in predicting accident-prone areas using the provided dataset. 
2. Implications: 
The effective prediction facilitated by the Decision Tree model enables proactive safety 
measures, which have the potential to significantly reduce accident rates in identified high
risk areas. 
 
3. Performance Metrics: 
• Logistic Regression: Achieved 52% accuracy on the testing set. 
• Decision Tree: Achieved 60% accuracy on the testing set. 
4. Visuals: 
• Mapping accident-prone areas using latitude and longitude has visually highlighted 
high-risk zones, aiding in the identification of areas requiring targeted safety measures. 
5. Model Comparison: 
• Decision Trees have demonstrated superior performance and provided clearer criteria 
for classifications. This makes them preferable for understanding complex decision 
boundaries in geographical data, thereby enhancing the effectiveness of accident 
prediction and prevention strategies. 
 
 
 
10.Future Scope: 
1. Model Improvement:     
Explore more sophisticated models like Random Forests and Gradient Boosting Machines 
to further enhance predictive accuracy and robustness. 
2. Data Enrichment: 
Integrate more detailed traffic flow data and real-time weather updates to provide a more 
comprehensive understanding of the factors influencing accident occurrences. 
3. Real-Time Application: 
• Develop a real-time prediction system capable of alerting drivers and traffic 
management systems about potential risks in high-risk areas. 
• Integration with Google Maps: Enhance the utility of the prediction system by 
integrating it with Google Maps, providing real-time accident-prone area alerts to 
drivers during navigation. 
