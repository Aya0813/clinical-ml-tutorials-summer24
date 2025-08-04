# Clinical Machine Learning Tutorials: Summer 2024

This repository documents two workshops I led in July 2024 at Zurich, Switzerland, on using Machine Learning to uncover biases in clinical data, with a focus on hidden hypoxemia and pulse oximeter accuracy.

This repository documents two workshops I led in July 2024 at Zurich, Switzerland, on using Machine Learning to uncover biases in clinical data, with a focus on hidden hypoxemia and pulse oximeter accuracy. The primary tutorial took around six months to develop under the guidance of [Prof. Leo Anthony Celi](https://imes.mit.edu/people/celi-leo) and with the support of members of his lab at MIT Critical Data, notably [Dr. Takeshi Tohyama](https://www.linkedin.com/in/takeshi-tohyama-167721265/) and [João Matos](https://www.linkedin.com/in/joao-mat0s/). 


## 📍 Overview

### 1. Bumblekite Machine Learning Summer School in Health, Care, and Biosciences
- **Location**: ETH Zurich
- **Date**: July 2nd, 2024 (as part of the summer school held from June 30th to July 6th, 2024).
- **Website**: [Bumblekite Summer School 2024](https://www.bumblekite.co/summer-school-24/#schedule)
- **Audience**: 60+ participants, primarily graduate students from diverse academic and professional backgrounds, including Machine Learning (ML), statistics, mathematics, and biology, representing both academia and industry.
- **Format**: I led the hands-on tutorial session on the first day of the summer school, which lasted 3 hours+. The summer school itself featured daily lecture series and applied tutorials (see official schedule in the website). My tutorial was delivered under the guidance and in the presence of [Prof. Leo Anthony Celi](https://imes.mit.edu/people/celi-leo) (Senior Research Scientist (MIT); Associate Professor of Medicine (Harvard)). 
- **Materials**: [ETH-Zurich-Tutorial/](./ETH-Zurich-Tutorial)

### 2. Balgrist University Hospital Datathon
- **Location**: Balgrist University Hospital
- **Date**: July 6th, 2024
- **Audience**: Open to the public, with a total attendance of around 60 participants, including seasoned professionals and students from across Europe and beyond. Many attendees had advanced backgrounds in biology, clinical medicine, or pharmacy, with a mix of career stages and expertise levels. Participants were distributed into smaller working groups, and I directly taught a group of around 10–15 people during the workshop, while also supporting other groups as needed in my role as one of the organizers. 
- **Format**: This was a nearly full-day datathon organized in collaboration with some Bumblekite ML summer school organizers and several members of [MIT Critical Data](https://criticaldata.mit.edu/#community) as part of one of the many global datathons led by Prof. Leo Anthony Celi. I was one of the datathon organizers and also took part in the opening remarks. During the datathon, I led a 2-hour hands-on workshop, which was a condensed and simplified version of the Bumblekite tutorial, tailored for an audience with limited to no prior experience in Python or ML.
- **Materials**: [Balgrist-Datathon/](./Balgrist-Datathon)

## 🩺 Tutorial Content Overview
- Investigated the prevalence and clinical impact of hidden hypoxemia across racial groups using large-scale EHR data.
- Preprocessed the [BOLD](https://www.nature.com/articles/s41597-024-03225-z#Sec23) dataset, composed of approximately 50,000 ICU patient records from MIMIC-III, MIMIC-IV, and eICU-CRD databases.
- Developed and evaluated Machine Learning models to quantify bias in pulse oximetry-based oxygen saturation measurements and their effect on mortality prediction.
- Conducted group-wise performance analysis and implemented fairness-aware evaluation metrics to assess model behavior across demographic subgroups.

## 🧠 Inspiration
This series draws from past MIT & Brown critical datathons.

--- 


