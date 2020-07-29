# OSIC Pulmonary Fibrosis Progression (On-going Kaggle Competion)
## Predict lung function decline
## Current Rank: 12th

### CT Scan of patient 
                               ![ezgif com-crop](https://user-images.githubusercontent.com/39052765/88742777-b01d5780-d160-11ea-8446-43d69eb3618d.gif)

## Motivation:
Imagine one day, your breathing became consistently labored and shallow. Months later you were finally diagnosed with pulmonary fibrosis, a disorder with no known cause and 
no known cure, created by scarring of the lungs. If that happened to you, you would want to know your prognosis(a forecast of the likely outcome of a situation). That’s where a 
troubling disease becomes frightening for the patient: outcomes can range from long-term stability to rapid deterioration, but doctors aren’t easily able to tell where an 
individual may fall on that spectrum. My help, and data science, may be able to aid in this prediction, which would dramatically help both patients and clinicians.

Current methods make fibrotic lung diseases difficult to treat, even with access to a chest CT scan. In addition, the wide range of varied prognoses create issues organizing 
clinical trials. Finally, patients suffer extreme anxiety—in addition to fibrosis-related symptoms—from the disease’s opaque path of progression. Open Source Imaging Consortium 
(OSIC) is a not-for-profit, co-operative effort between academia, industry and philanthropy. The group enables rapid advances in the fight against Idiopathic Pulmonary 
Fibrosis (IPF), fibrosing interstitial lung diseases (ILDs), and other respiratory diseases, including emphysematous conditions. Its mission is to bring together radiologists, 
clinicians and computational scientists from around the world to improve imaging-based treatments.

## objective
In this competition, we’ll predict a patient’s severity of decline in lung function based on a CT scan of their lungs. We’ll determine lung function based on output from a 
spirometer, which measures the volume of air inhaled and exhaled. The challenge is to use machine learning techniques to make a prediction with the image, metadata, 
and baseline FVC as input.If successful, patients and their families would better understand their prognosis when they are first diagnosed with this incurable lung disease. 
Improved severity detection would also positively impact treatment trial design and accelerate the clinical development of novel treatments.

## What is Pulmonary Fibrosis??
The word “pulmonary” means lung and the word “fibrosis” means scar tissue— similar to scars that you may have on your skin from an old injury or surgery. So, in its simplest 
sense, pulmonary fibrosis (PF) means scarring in the lungs. Over time, the scar tissue can destroy the normal lung and make it hard for oxygen to get into your blood.

[![normal-and-impaired-gas-exchange](https://user-images.githubusercontent.com/39052765/88479760-1e9ac380-cf6f-11ea-9101-2bc73422b3bb.png)](url)

## Treatment Options
As given in the description, current methods make fibrotic lung diseases difficult to treat, even with access to a chest CT scan. In addition, the wide range of varied prognoses
create issues organizing clinical trials.

## So what do you mean by Prognosis?
Prognosis is a medical term for predicting the likely or expected development of a disease, including whether the signs and symptoms will improve or worsen (and how quickly) or
remain stable over time; expectations of quality of life, such as the ability to carry out daily activities; the potential for complications and associated health issues; and the likelihood of survival (including life expectancy).

## Reference: https://www.pulmonaryfibrosis.org/life-with-pf/about-pf

# About the Competition
## What do you need to do?
In this competition, you’ll predict a patient’s severity of decline in lung function based on a CT scan of their lungs. You’ll determine lung function based on output from a
spirometer, which measures the volume of air inhaled and exhaled. The challenge is to use machine learning techniques to make a prediction with the image, metadata, and baseline FVC as input.

## Submission
The test set consists of Three_Patient_Week(s) per patient. You need to predict the Forced vital capacity(FVC) i.e. volume of air exhaled and the confidence value in your prediction.

## Your Evaluation Metric
For each true FVC measurement, you will predict both an FVC and a confidence measure (standard deviation σ). The metric is computed as:
![scores](https://user-images.githubusercontent.com/39052765/88480298-e5fce900-cf72-11ea-8d78-bcf5cbd03c19.jpg)


