# Investigating a Medical Appointment Dataset (original data gotten from [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments))
## Introduction
In this project, I would be analyzing a medical appointment dataset consisting of about a 100,000 medical records in a Brazillian health sector that cut across different variables that make up the dataset. Some of these variables include: **Age, Gender, AppiontmentDay, ScheduledDay, Hypertension, No Show** etc. 
</br>The purpose of this investigation is to clean, explore and draw insights and conclusion from our data to understand what factor(s) determines if a patient shows up for their appointment.
## Question for analysis
### What factors affect/determine a patient showing up for an appointment?
- AppointmentDay?
- Gender?
- Hospital location?
- Health condition (Hypertensive, Diabetic)?
## Summary of Findings
After exploring and visualizing the data, most features that make up the data do not directly point to been reasons for patients showing up for their appointment. We can see that more females show up for their appointments; getting a reminder, having a health condition (hypertension or diabetes) does not determine that the parents show up, even being registered in the brazillian welfare system does not guarantee a show-up. In conclusion the data presented in this project is limited in ultimately determining the factors that affect patients showing up for their appointments.
## Key Insights for Presentation
- View the content on nbviewer:[Jupyter Notebook](http://nbviewer.org/github/BrownEyes01/Investigate-a-Dataset/blob/main/Project%20%281%29.ipynb) 
- Download the HTML file in the subdirectory and view content locally on any browser.
## Getting Started
> For testing and development purposes, these instructions will help you get a copy of the project up and running on your system.
### Prerequisites
- Installing Jupyter notebook, this can be gotten from the **Anaconda Navigator** or **Anaconda Prompt**.
- You would also need to install Python and some of it's libraries:
  - Pandas
  - Numpy
  - Matplotlib
  - Seaborn
 ### Installation
 The following shows how to get a development environment running
 Here are the installation steps:
 - Download the Anaconda [installer](https://www.anaconda.com/download/). Choose the Python 3.6 or higher version, and the appropriate 64/32-bit installer.
 - Refer to the installation instructions [here](https://docs.anaconda.com/anaconda/install/).
 - Verify the installation, as mentioned [here](https://docs.anaconda.com/anaconda/install/verify-install/)
 
 If you already have Anaconda installed, use the ```environment.yaml``` to create the exact environment I used during the project by typing the line below into the Anaconda terminal in the same folder where the environment file is saved on your computer
 ```
 conda env create -f environment.yaml
 ```
 OR If you're not using Conda, you can use pip to install dependencies with the requirements.txt file by typing this line into your terminal
 ```
 pip install -r requirements.txt
 ```
 ## Built With
 - [Anaconda](https://www.anaconda.com/)- Dependency Management
 - [Jupyter Notebook](https://jupyter.org/) - Data analysis documentation
 ## Authors
 - Frances Uzedu
 ## License
 - This project is licensed under the GNU License- see the [LICENSE](https://github.com/BrownEyes01/Investigate-a-Dataset/blob/main/LICENSE) for details.
 ## Acknowledgements
 - Udacity ALX-T Data Analyst Nanodegree
