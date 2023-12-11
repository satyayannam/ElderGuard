
# ElderGuard - Early Fall Detection for Elderly People using Machine Learning

ElderGuard is an innovative open-source project designed to enhance the safety of elderly individuals by predicting and detecting falls at an early stage using machine learning techniques. Falls among the elderly can have severe consequences, and timely intervention is crucial to mitigate potential risks. This project leverages machine learning algorithms to analyze sensor data and promptly identify fall patterns.



## Datasets
The data present in the `train` and the `test` datasets are based on the real-time notings of the sensors. This includes data from wearable sensors such as accelerometers, gyroscopes, and magnetometers, as well as environmental data such as temperature and humidity. The data should be collected from diverse subjects and activities to ensure the system can generalize to different scenarios.

In order to better accurately forecast the fall in elderly people, we used 14 variables.
These 14 attributes include:
1. Age  - age in years
2. sex  -  sex (1 = male; 0 = female)
3. cp   - chest pain type:\
    --Value 1: typical angina\
    --Value 2: atypical angina\
    --Value 3: non-anginal pain\
    --Value 4: asymptomatic

4. trestbps - resting blood pressure (in mm Hg on admission to the hospital)
5. chol - serum cholestoral in mg/dl
6. fbs  - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg  - resting electrocardiographic results\
    --Value 0: normal\
    -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05mV)
    -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

8. thalach  -  maximum heart rate achieved
9. exang    - exercise induced angina (1 = yes; 0 = no)
10. oldpeak -  ST depression induced by exercise relative to rest
11. slope   - the slope of the peak exercise ST segment\
    -- Value 1: upsloping\
    -- Value 2: flat\
    -- Value 3: down sloping
12. ca - number of major vessels (0-3) colored by flourosopy
13. thal    - 3 = normal; 6 = fixed defect; 7 = reversable defect
14. target (the predicted attribute)

Here the `train` dataset consists of the train data and the `test` dataset consists of the test data.
The main program is available in the `Elderly Fall DL101.ipynb` file. and the link to the file is below:
https://github.com/satyayannam/ElderGuard/blob/c46f4f2a6d7c37c40abe7876fb9f74aca80461f2/Elderly%20Fall%20DL101.ipynb
## Results
The results while the project is in testing phase are as follows:
![image](https://github.com/satyayannam/ElderGuard/assets/71513870/7f3c42d7-19af-4066-9c49-806c29e86f24)

Note: try changing the train dataset inorder to train the model more accurately.
## Conclusion
The physical, cognitive, and sensory functions of individuals are directly impacted by old age, leading to difficulties in performing regular activities of daily living (ADLs). Consequently, the risk of falls increases, posing potentially fatal consequences. Therefore, there is a need to develop fall detection and prevention systems to mitigate the impact of falls. This research paper provides an overview of the latest machine learning (ML)-based systems for fall detection and prevention. It analyzes these systems based on various parameters, including participant age, dataset used, ML algorithms employed, types of sensors utilized, 
and sensor placement for specific tasks. The analysis reveals that support vector machines (SVMs) and wearable devices are commonly employed in fall detection and prevention applications. However, it is noteworthy that most studies have been conducted in controlled environments with adult participants, limiting the generalizability of their findings. The paper also visualizes the learning outcomes of ML algorithms and their performance metrics in conjunction with different types of wearables. Lastly, the paper identifies crucial future research directions, such as energy efficiency, sensor fusion, context awareness, and wearable design, to further advance the field of fall detection and prevention.
