# no-show-appointments

![Contributors](https://img.shields.io/github/contributors/walidsi/no-show-appointments?style=plastic)
![Forks](https://img.shields.io/github/forks/walidsi/no-show-appointments)
![Downloads](https://img.shields.io/github/downloads/walidsi/no-show-appointments/total)
![Stars](https://img.shields.io/github/stars/walidsi/no-show-appointments)
![Licence](https://img.shields.io/github/license/walidsi/no-show-appointments)
![Issues](https://img.shields.io/github/issues/walidsi/no-show-appointments)

### Goal
In this project we will be analyzing the No-Show Appointments dataset. The dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointments. A number of characteristics about the patient are included in each row and we need to find out the factors that are important in predicting whether a patient shows-up for the appointment or not.

We seek answers to the following questions:
- Which gender is more committed to showing up for their appointments?
- Are older people more likely to miss/attend their appointments?
- Does scholarship (social welfare membership status) affect patient no-show?
- Are handicapped patients more likey to miss their appointments?
- Are there more no-show on certain days of the week?
- If a patient recevies a reminder SMS, is she/he more likely to attend the apointment?
- Does alochol problems affect patient attendance of their appointments?
- Do patients with chronic diseases (diabetes and hypertension) tend to miss appointments more or less than other patients?
- Which neighbourhoods have higher no-show proportions? and which have the lowest?

### Dataset
The dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up
for their appointment. A number of characteristics about the patient are included in each row.
- ‘ScheduledDay’ tells us on what day the patient set up their appointment.
- ‘Neighborhood’ indicates the location of the hospital.
- ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- Whether the patient has diabetes / hypertension or not, is hadicapped or not, alcholic or not.
- Demographics information about the patient like age, gender and living neigborhood. 
- Note: be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

### Process

### Summary of Findings
Our analysis revealed the following tentative findings:
- The proportion of female patiends who missed their appointments is approximately equal to the proportion of male patients who did not show up.
- Patients in older age groups tends to miss their appointments less than patients in younger groups.
- Patients enrolled in the scholarship welfare program miss their appointments more than patients who are not enrolled in the scholarship program.
- Handicapped patients tend to miss their appointments more than not Handicapped patients.
- There are more no-shows on Fridays and Saturdays than the rest of the weekdays.
- On average, patients who receive SMS reminder miss heir appointments more than patients who did not get an SMS reminder.
- Female patients with alcoholism probllem tend to miss their appointments more than male patients with the same problem.
- Patients with chronic diseases like diabetes and hypertension are more punctual and miss their appointments less than pat without chronic diseases.
- No-show differs from one neighbourhood to another. After excludiing the two outliers, we can see that the heighest no-show neighbourhood is SANTOS DUMONT with around 29% no-show while the neighbourhood with lowest no-show is ILHA DO BOI with no-show of around 8%.


### Install
This project requires **Python 3.x** and the following Python libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Code
Code is provided in the `No_Show_Appointments_Analysis.ipynb` notebook file.

### Run
In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook No_Show_Appointments_Analysis.ipynb
```  
or
```bash
jupyter notebook No_Show_Appointments_Analysis.ipynb
```

This will open the iPython Notebook software and project file in your browser.
