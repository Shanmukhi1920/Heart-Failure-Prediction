## Predicting Heart Failure

## Context

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

## Attribute Information:

* Age: age of the patient [years]

* Sex: sex of the patient [M: Male, F: Female]

* ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]

* RestingBP: resting blood pressure [mm Hg]

* Cholesterol: serum cholesterol [mm/dl]

* FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]

* RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]

* MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]

* ExerciseAngina: exercise-induced angina [Y: Yes, N: No]

* Oldpeak: oldpeak = ST [Numeric value measured in depression]

* ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

* HeartDisease: output class [1: heart disease, 0: Normal]


## Insights

* Out of 918 observations, 508 individuals are prone to heart diseases, with only 50 of them being women, indicating a higher susceptibility of men to heart diseases.

* Approximately 65% of the people in the dataset have a fasting blood sugar value below 120 mg/dl (indicated by '0').

* Among those experiencing chest pain, 54% have an asymptomatic type, with 84% of them being male, followed by 22% with non-anginal pain, 18% with atypical angina pain, and 6% with typical angina pain.

* Within the group of 508 individuals with heart disease, 77% of them have asymptomatic chest pain.

* On average, females tend to have higher levels of cholesterol and maximum heart rate compared to males.

* A total of 690 observations in the dataset fall within three standard deviations.

* The K-means clustering algorithm generated three clusters, with sample sizes of 109, 227, and 354, respectively.

* SVM has training accuracy of 85.7% with C value tuned to 10e-03 while Kknn has 86.6% with kmax=8, rectangle kernel and p set to Manhattan distance.

* Testing accuracy of svm is 85% and False positives are only 4.

* The model has a precision of 79.2% and recall of 93.8%.

* Area under ROC Curve is 86.3%.




