# Alzheimers-Research
## ACSEF RESEARCH PROJECT 

### ABSTRACT:

The objective of this research was to develop a model to accurately diagnose a patient with Alzheimer's Disease and predict their future cognitive state without using expensive data such as MRI and PET. Instead, using easily accessible and inexpensive data, which don't require visits to the hospital. For developing the classification and prediction of change in Mini-mental state examination (an indicator of dementia) models, I preprocessed clinical data from 2162 patients that were obtained from the Alzheimer's Disease Neuroimaging Initiative (ADNI). After preprocessing the data, I implemented several machine learning models, such as Naive Bayes, SVM, Neural Networks, Logistic Regression, and more. After fitting the models on the training set, I tested the classification models for classification accuracy and AUC on testing data of 130 patients. I, also, tested the regression models with classification accuracy and MAE on testing data of 154 patients. From the several machine learning algorithms, I selected the Gaussian Naive Bayes algorithm (95% classification accuracy of AD and 0.9 AUC) and the Elastic Net regression model (82% classification accuracy of change in MMSE with a MOE of 1 and 1.01 MAE). This project accurately developed machine learning models that can diagnose a patient with AD and predict the change in their MMSE score using data obtained without going to the hospital. This model can be used instead of paying thousands of dollars for health testing and can extend to low-income or rural areas where brain scans and advanced testing are not a feasible option. 

### Project Motivation: 

Alzheimer’s disease (AD) is a progressive neurodegenerative disease, as well as the most common form of dementia, that is often characterized by memory and cognitive impairment, which negatively affects behavior, speech, and the motor system. In the United states alone, there are approximately 5.8 million senior citizens with Alzheimer’s disease, a number predicted to double in the next 30 years. Mild Cognitive impairment (MCI) is a noticeable condition that affects an individual’s thinking ability, and those with MCI are more susceptible to developing Alzheimer’s Disease. However, the cause of Alzheimer’s Disease is not fully understood and there is no medication to stop its progression. 99.6% of clinical trials—to treat AD—result in failure as AD cannot be easily detected in its early stages, and when AD and dementia are discovered it's often too late. 

A model that can accurately and inexpensively predict someone's future condition will help immensly for aiding in healthcare and clinical trials. Healthcare costs are often too high for most people to recieve MRI tests, and often in rural communities, one has to travel for days or even weeks to go to their closest hospital. Thus, my project's aim is to predict the future MMSE (indicator of dementia) score of patients and if a patient has AD using markers that can easily be aqcuired. 

### Data:

The training data (for predicting MMSE scores) consist of individuals participating in the Alzheimer’s Disease Neuroimaging Initiative (ADNI), which is a longitudinal multicenter study established in 2004 with the goal of detecting AD at an early stage, tracking disease progression through biomarkers, supporting advances in AD intervention, prevention and treatment, and providing a resource for AD research. The study has grown to >1600 participants with mild cognitive impairment (MCI),ranging from Early MCI (EMCI) to Late MCI (LMCI), Alzheimer's Disease (AD) and elderly, cognitively normal (CN) control subjects that have been recruited over three phases ADNI 1, ADNI GO and ADNI 2.

![Screen Shot 2021-03-03 at 9 48 19 AM](https://user-images.githubusercontent.com/40369092/109848967-b0556800-7c05-11eb-8cf5-c04d31604836.png)



![Screen Shot 2021-03-03 at 9 48 02 AM](https://user-images.githubusercontent.com/40369092/109849020-bfd4b100-7c05-11eb-9dd6-038387bd74a1.png)


### Research Plan:

![Screen Shot 2021-03-03 at 11 34 23 AM](https://user-images.githubusercontent.com/40369092/109861756-80619100-7c14-11eb-95d3-4860058ddfac.png)



### Results: 

##### Check the 2 jupyter notebooks to see the results – PredictingChangeinMMSE.ipynb and ADCLASSIFICATION.ipynb
#### MMSE Prediction: 

Here is the google form that takes your information to predict your MMSE score: [MMSE PREDICTION](https://docs.google.com/forms/d/e/1FAIpQLSfKuRvqtKkMWoycQKUdDfc7HM-Ni73XON573PxgY9RiNIYidw/viewform?vc=0&c=0&w=1&flr=0). You will recieve an email with your result after filling out this google form. The data in this form must be inputed specifically, as asked, to recieve the correct information. 

#### State Prediction: 

Here is the google form that takes your information to classify if you have Alzheimer's Disease:[AD](https://docs.google.com/forms/d/e/1FAIpQLSfLWFJnlK_CEyLQCRE6zJuar-JtuS5RgC0knfOJ4dUdXhb_uQ/viewform). You will recieve an email with your results after filling out this google form. The data in this form must be inputed specifically, as asked, to recieve the correct information.


