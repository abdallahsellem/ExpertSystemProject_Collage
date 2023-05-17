# Introduction

**Problem**: Detect if a Person is Exposed to Heart Disease

**Source**: The dataset is publically available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. 
## Attributes:

#### Demographic:

**gender**: male or female(Nominal)
**Age**: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
Education: no further information provided
Behavioral:

**Current Smoker**: whether or not the patient is a current smoker (Nominal)
**Cigs Per Day**: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

#### Information on medical history:
**BP Meds**: whether or not the patient was on blood pressure medication (Nominal)
**Prevalent Stroke**: whether or not the patient had previously had a stroke (Nominal)
**Prevalent Hyp**: whether or not the patient was hypertensive (Nominal)
**Diabetes**: whether or not the patient had diabetes (Nominal)

#### Information on current medical condition:
**Tot Chol**: total cholesterol level (Continuous)
**Sys BP**: systolic blood pressure (Continuous)
**Dia BP**: diastolic blood pressure (Continuous)
**BMI**: Body Mass Index (Continuous)
**Heart Rate**: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
**Glucose**: glucose level (Continuous)
Target variable to predict:
**10 year risk of coronary heart disease (CHD)** - (binary: “1”, means “Yes”, “0” means “No”)


## Algorithms :

1. **Logistic Regression** 
2. **K-Nearest Neighbor (KNN)**
3. **Support Victor Machine (SVM)**
