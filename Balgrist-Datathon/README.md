# Welcome to the Balgrist-University-Hospital-Datathon-2024!

## Understanding the Problem
Pulse oximeters are medical devices used to measure the level of oxygen in the blood without needing a blood sample. The most accurate method, however, requires taking a blood sample to measure oxygen levels directly. Pulse oximeters currently available are less accurate in people with darker skin tones. These pulse oximetry inaccuracies can fail to detect episodes of hidden hypoxemia, i.e., low SaO2 with high SpO2. Hidden hypoxemias can result in less treatment and increased mortality. Yet flawed, pulse oximeters remain ubiquitously used because of their ease of use; debiasing the underlying algorithms could alleviate the downstream repercussions of hidden hypoxemia.

## Dataset
BOLD is a new comprehensive dataset that aims to underscore the importance of addressing biases in pulse oximetry accuracy, which disproportionately affect darker-skinned patients. The dataset was created by harmonizing three Electronic Health Record databases (MIMIC-III, MIMIC-IV, eICU-CRD) comprising Intensive Care Unit stays of US patients. You can find more details about the dataset in the [BOLD paper](https://www.nature.com/articles/s41597-024-03225-z#Sec23).

## Main Paper
The tutorial is built upon the paper titled "Analysis of Discrepancies Between Pulse Oximetry and Arterial Oxygen Saturation Measurements by Race and Ethnicity and Association With Organ Dysfunction and Mortality" published in JAMA Network Open. This paper investigates discrepancies between pulse oximetry (SpO2) and arterial oxygen saturation (SaO2) measurements, examining the impact of these discrepancies on clinical outcomes across different racial and ethnic groups.

## Objective of the Tutorial
The objective of this tutorial is to provide a comprehensive guide on how to analyze and address biases in healthcare data, with a specific focus on hidden hypoxemia and its impact on in-hospital mortality predictions. Through a series of structured steps, including exploratory data analysis, data preprocessing, train-test splitting, and model evaluation, participants will learn how to:
1. Detect and understand hidden patterns and biases in healthcare datasets.
2. Preprocess data effectively to ensure robust and reliable model performance.
3. Evaluate the influence of hidden hypoxemia on patient outcomes using statistical and machine learning techniques.
4. Assess and compare the performance of different models across various racial groups to highlight the importance of careful feature selection and bias mitigation in clinical predictions.

## Key Variables to Keep in Mind
1. **Pulse Oximetry (SpO2)**: This is a [non-invasive] method used to measure the oxygen level (oxygen saturation) in the blood. It is usually done using a device clipped onto a finger, toe, or earlobe. Normal SpO2 levels range from 95% to 100%, indicating sufficient oxygen in the blood. Levels below 95% can indicate hypoxemia, with severe hypoxemia occurring below 85%.
2. **Arterial Oxygen Saturation (SaO2)**: This is an [invasive] measurement of oxygen saturation directly from the blood using an arterial blood gas (ABG) test. It is more accurate than pulse oximetry but requires drawing blood from an artery. SaO2 provides a direct measurement of oxygen levels in the blood and is used to confirm the accuracy of SpO2 readings, especially in cases of suspected hypoxemia.
3. **ABG**: Arterial Blood Gas
4. **Hypoxemia**: This refers to low levels of oxygen in the blood. It can be dangerous and requires medical attention.
5. **Hidden Hypoxemia**: This occurs when a patient's pulse oximetry reading (SpO2) suggests they have normal oxygen levels, but their arterial oxygen saturation (SaO2) shows they actually have low oxygen levels. (i.e., SpO2 ≥ 88% but SaO2 < 88%).
6. **Organ Dysfunction**: This refers to the impaired function of organs (like the heart, lungs, liver, or kidneys) often assessed using specific scores like the Sequential Organ Failure Assessment (SOFA) score.
7. **In-hospital Mortality**: This means death occurring during a hospital stay.
8. **Sequential Organ Failure Assessment (SOFA) Score**: A scoring system used to track a patient's status during their stay in an intensive care unit (ICU). Higher scores indicate more severe organ dysfunction.
9. **Electronic Health Record (EHR)**: Digital version of patients' paper charts. They contain the medical and treatment history of patients.

## Schedule
* **Hour 1** - Exploratory Data Analysis (EDA) of the BOLD dataset.
* **Hour 2** - Build a mortality prediction model using the BOLD dataset.

## Programme
**09:00 - 09:15** Opening Remarks by Sebastiano Caprara (15 min)

**09:15 - 11:30** Hands-on workshop on discovering data biases in clinical data by Aya El Mir
During the workshop, you will be working on the BOLD dataset.

**11:30 - 12:30** Visit to OR-X and lunch break

**12:30 - 14:30** HASTE Policy Camp
During the policy camp, you will be discussing cases in a small group, trying to understand the worst possible outcome and how to prevent it by establishing safeguards.

**14:30 - 15:00** Reflections and closing remarks (30 min)

## Location
The datathon will take place at the Auditorium at Balgrist University Hospital, located at Forchstrasse 340, 8008 Zürich.

## Note
A lot of the content in this tutorial was inspired by these previous datathons: MIT Critical Datathon 2023 and Brown University Datathon 2024.

Happy coding!
