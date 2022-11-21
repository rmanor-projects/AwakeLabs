# Awake Labs - Take Home Challenge: Predicting the Likelihood of a Patient Getting a Heart Attack
--------------------------------------------------------------------------------------------------

## Overview
------------

In this project I was given a publicaly avaialble dataset that included 14 patient's attributes / features of demographic and medical data as well as a Target variable called output (namely a class attribute):

### Data IN:

## Demographic Data:

1. Age, 
2. Sex,

## Medical data:


3. cp (chest pain: 0 = Typical Angina, 1 = Atypical Angina, 2 = Non-anginal Pain, 3 = Asymptomatic), 
4. trtbps (resting blood pressure, mmHg), 
5. chol (Cholestoral mg/dl), 
6. fbs (fasting blood sugar > 120 mg/dl 1 Yes, 0 No),
7. restecg (Resting ECG results, 0 = Normal, 1 = ST-T wave normality, 2 = Left ventricular hypertrophy),
8.thalachh (Maximum heart rate achieved),
9. oldpeak (Previous peak),
10. slp (Slope),
11. caa (Number of major vessels),
12. thall (Thalium Stress Test result),
13. exng (Exercise induced angina 1 = Yes, 0 = No),
14. o2Saturation (Blood oxygen saturation in %)

### Application:

1. Objective: A ML model that given the 14 attributes above could predict if a patient is presenting with a hearth attack or not. 

2. Tool used: JupyterLab. 

        In principle, JupyterLab is an R&D tool and not a tool for deployment. That said, for the purpose of writing and presenting this Home Challenge I thought this would be a good tool to present my thinking process in general, and this analysis. The benefit of using JupyterLab is that one could easily write code, provide annotation as well as present EDA and Results in a graphical format all in one place. In addition, it is an open-source tool and the final application developed could easily be exported as a model file to other platform at scale like Google could and AWS.    
        
        The approach I chose is to test different models and compare them before choosing the most appropriate one. The main challenge was that the dataset given was limited in term of its size (number of data / patients). Hence, the chosen model lacks the sensitivity I would have liked to achieve. In a real-world scenario, I would have recommended acquiring more data before re-estimating the model and its success metric.  
        
### How to Install and Run the Project - local installtion:

1. Install Anaconda following the steps in the link provided and according to your operation system: https://docs.anaconda.com/anaconda/install/
2. I used Anaconda on Windows.
3. After installation completed, open ANACONDA.NAVIGATOR and choose JupyterLab.
4. On GitHab: Download the JupyterLab file provided on this page to your local computer. 
5. Using JupyterLab, nevigate to the location of your JupyterLab file on your computer. This should also be your working directory. 
6. I worked with:   Python 3.9.12 and sklearn version 1.0.2
7. If you are not familiar working with JupyterLab please refer to the following link for a detailed step-by-step instructions: https://jupyterlab.readthedocs.io/en/stable/user/interface.html



