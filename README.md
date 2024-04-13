# DS3000 Foundations of Data Science - Group Project

## Overview

This project was developed as part of the DS3000 Foundations of Data Science coursework at Northeastern University. Our team utilized the unofficial 2018 election data from the MIT Election Data and Science Lab to apply data science techniques to 'real-world' datasets. The primary goal of this project was to identify the demographics most significantly affecting election outcomes. This involved training models to determine whether a county was a 'Swing' county, defined as having a 5% or less difference between Democratic and Republican votes. The most important features identified during model training were deemed the most significant demographics affecting election outcomes.

## Data Source

The data utilized in this project is the 2018 unofficial election data, provided by the MIT Election Data and Science Lab. The dataset encompasses a wide range of election data across various states and counties in the United States.

- **Data Repository:** [2018-elections-unofficial](https://github.com/MEDSL/2018-elections-unoffical/)

## Objectives

- **Primary Objective:** To determine which demographics are most influential in predicting the outcomes of elections.
- **Learning Outcomes:** Gain hands-on experience with complex, real-world data and apply multiple machine learning techniques to derive meaningful insights.

## Methodology

We employed several machine learning algorithms to analyze the data and achieve our objectives:

- **Random Forest (RF):** Used for its robustness and effectiveness in handling large data sets with numerous variables, providing insights into feature importance.
- **Support Vector Machines (SVC):** Applied to model complex relationships in high-dimensional spaces.
- **K-Nearest Neighbors (KNN):** Utilized to investigate the impact of locality and demographic similarity on election outcomes.

Each model was evaluated based on its accuracy and ability to highlight key demographic features.

## Requirements

This project requires Python 3.x and the following libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tqdm plotly statsmodels requests
```
## Results
Our results for this project can be seen in the [presentation board](temp).

## Team Members
- [Kai Webber](https://github.com/Waikebber)
- [Maximus Saenz](https://github.com/maxsaenz)
- [Micheal Baraty](https://github.com/mbaraty)
- [Nathan Parker](https://github.com/natejparker)
  
## Acknowledgments
We would like to thank the instructors and staff of the DS3000 course at Northeastern University for their guidance and support throughout this project. Special thanks to the MIT Election Data and Science Lab for providing the data used in this study.

## [Google Colab](https://colab.research.google.com/drive/12B2VmAJQPAJWfWBjommB6UT9odPZY7cz?usp=sharing)

