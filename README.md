# Practical_3
Introduction

Diabetes affects millions of people around the world. It strains not only the healthcare sector but also the wider global economy due, for example, sick days. Thus, there is a need to minimise expenditure where possible. One such means is to automate the process of detecting diabetic patients, where according to the NHS, 3% of adults remain undiagnosed with diabetes.

The given dataset is record of different age groups, either diabetic or non diabetic, their blood glucose level reading with superficial body features like body temperature, heart rate, blood pressure etc. Using calibrated wearable devices and apparatus, various age groups recorded their readings. A total of 16,969 patients and 10 features are contained in that dataset.

In this report, I will detail the use of a machine learning (ML) pipeline for predicting whether a patient was diabetic or not using the superficial features and glucose levels.

Methodology

The ideal methodology will be as detailed and as easy to follow as possible. Think of it like writing a recipe for a meal. When it comes to AI, it is best practice to report the version number of the software used (e.g., Python v.3.7.6) and the computer specs/colab specs.

The data was obtained from the IEEE DataPort. The digital object identifier (DOI) is https://dx.doi.org/10.21227/c4pp-6347

All coding was performed using Python version (3.7.6)

Results

![301653517-d64f4924-1f3c-4555-8b50-56f845fdd5c9](https://github.com/Umar190/Practical_3/assets/159279907/239b0482-6522-4fbd-ba3e-20dfafdf6790)

From the 9 features, the data appeared to be well distributed

![301654458-069ee2bc-e140-4f4f-ba04-35d5df82487c](https://github.com/Umar190/Practical_3/assets/159279907/de5f8e5e-d327-4cb3-9c97-84b01df98510)

Model Training & Evaluation
I trained 4 different learners were there accuracy, f1 score and matthews coefficient correlation (MCC) were:

| Model	Accuracy |             | Accuracy (%) |   	| F1 (%) | 	| MCC |
| ---------------|-------------|-----|------|--------|--|-----|
| Random Forest |	             | 100	|   | 90 |	     | 0.90 |
| Neural Net |    	           | 99	|   | 60 |	     | 0.65 |
| Logistic Regression |       |	99 |   |	56	|    |  0.62 |
| Decision Tree |             |	99	|  |  87 |	   |   0.87 |

The results show that despite the imbalance, all four models were able to accurately predict the patients clinical condition. The high MCC score confirmed that the models were performing much better than random guessing. I then removed the feature 'Blood Glucose Level' and discovered...

Discussion & Conclusion

Machine learning (ML) has proven to be highly effective in predicting whether a patient is diabetic. 





