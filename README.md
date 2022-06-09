
![medical picture](https://media.istockphoto.com/photos/doctor-or-physician-writing-diagnosis-and-giving-a-medical-to-male-picture-id1190794708?k=20&m=1190794708&s=612x612&w=0&h=5LPA6yeThxkKO_05LqYfAK-8HA8rG8gDrrjOzRW3Mhw=)


# No_show Medical Appointment. 
# Overview

This dataset is about the appointment of patients, whether they showed up or not. The dataset entails information from 100k medical appointments in Brazil. 

## Dataset information
The dataset contains 14 columns and 110527 rows
Column Description:
* Patientid: Identification of a patient. 
* AppointmentID: Identification of each appointment. 
* Gender: Male or Female. Female is the greater proportion, woman takes way more care of they health in comparison to man. 
* ScheduledDay: The day of the actual appointment, when they have to visit the doctor.
* AppointmentDay: The day someone called or registered the appointment, this is before appointment. 
* Age: How old is the patient. 
* Neighbourhood: Where the appointment takes place. 
* Scholarship: Indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. 
* Hypertension: True or False. 
* Diabetes: True or False. 
* Alcoholism: True or False. 
* Handicap: True or False SMS_received: 1 or more messages sent to the patient. 
* No-show: True or False.

## Project Content
The project entails data wrangling and exploratory data analysis of No-show appointments. Various columns were used to make inferences of No-show appointment column(the most important) to know if patients' appointments were affected by other reasons like diseases, neighborhood or age.

## Question(s) for Analysis
* What is the gender distribution of patients?
* Does gender have an effect in show up? 
* Does the age of the gender have an effect in show up?
* Does having a scholarship affect the number of show up for an appointment? 
* Do the diseases affect whether a patient shows up or not?

## Conclusion
In conclusion. From the exploratory analysis the results were: 
* The variable, Gender which consists of females and males has been visualized with a bar chart and the outcome was that female patients were more likely to attend an appointment than males in the dataset. 
* Gender column was plotted using count plot to find a relationship between No-show column and gender to know the percentage of what gender showed up and didn't. Females had a higher percentage of showing up and a higher percentage of those who didn't show up than males. 
* Although younger patients didn't turn up for an appointment. There was the proximity of both ages above 50 and below 50 showing up for their appointment. 
* Scholarship didn't affect the showing up of patients. The visualization showed that both those with or without scholarships went for their appointment. 
* The diseases of patients influenced patients showing up for an appointment. patients with no disease barely showed up.

## Limitation
No clear correlation of scholarship and No-show in the dataset



## Acknowledgements

 - Data Source: [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments/code)
 - Picture: [Istockphoto](https://media.istockphoto.com/photos/doctor-or-physician-writing-diagnosis-and-giving-a-medical-to-male-picture-id1190794708?k=20&m=1190794708&s=612x612&w=0&h=5LPA6yeThxkKO_05LqYfAK-8HA8rG8gDrrjOzRW3Mhw=)
 
