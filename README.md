# Pneumonia Detection

One of the most important aspects of healthcare, is a timely diagnosis of a disease, as it's easier to treat in early stages. This is not only appliable on cancer, but also in infections, along with other diseases.

Pneumonia is swelling or inflammation of the tissue in one or both lungs. It's usually caused by a bacterial infection, but it can also be caused by a virus. The symptoms of pneumonia can develop suddenly over 24 to 48 hours, or they may come on more slowly over several days. Common symptoms of pneumonia include cough, difficulty breathing, rapid heartbeat, high temperature, sweating, shivering and chest pain, among others [1]. This disease can lead to death, so a prompt diagnosis can increase the chance of fast recovering and survival of the individual.

This is why I created this project for the detection of presence of a pneumonia infection from chest X-ray images, taken from the Kaggle database [Chest X-Ray Images (Pneumonia) of Paul Mooney](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## Objective

Pneumonia is not easly identified in chest X-ray images, so the objective of this project is to create a model, that could be able to identify from images if a patient has pneumonia or not.

## Data

### Description

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

### Dataset

The dataset was obtained from the Kaggle dataset [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia), which comes from [Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification](https://data.mendeley.com/datasets/rscbjbr9sj/2) from Mendeley Data. According to the description of this dataset, data is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia or Normal). There are 5863 X-Ray images (JPEG) and 2 categories according to de diagnosis (Pneumonia or Normal).

## References

[1] NHS, “Pneumonia,” NHS choices. [Online]. Available: https://www.nhs.uk/conditions/pneumonia/. [Accessed: 20-Jan-2022].

[2] E. Byeon, “Exploratory data analysis ideas for image classification,” Medium, 11-Sep-2020. [Online]. Available: https://towardsdatascience.com/exploratory-data-analysis-ideas-for-image-classification-d3fc6bbfb2d2. [Accessed: 21-Jan-2022]. 
