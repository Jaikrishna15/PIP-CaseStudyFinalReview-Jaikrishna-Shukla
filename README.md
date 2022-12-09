[Read me .docx](https://github.com/Jaikrishna15/PIP-CaseStudyFinalReview-Jaikrishna-Shukla/files/10193729/Read.me.docx)
# PIP-CaseStudyFinalReview-Jaikrishna-Shukla
Updated repository for final PIP review

Springboard Project: 
Cat Checker – Elimination Classification
(Jaikrishna Shukla)


The client is a global company in the Pet Care and pet food space. The company owns a range of smart pet products aiming to improve the health of pets by monitoring the pet’s activities and generating a portfolio for the pet owners to consume.
The Smart Litter System is a smart cat litter system that is equipped with four load sensors capturing any load disturbance happening on the litter box. The device functions at 40 Hz frequency rate which means it records 40 samples per second. Multiple devices are used in the client facility to capture all activities in the device in the form of load signals on a day-to-day basis. The client facility is also equipped with cameras which capture photo feeds and video feeds that allows manual tagging of the various cat and human interaction events with the litter system.

The data provided is in such a form that there are 82 subfolders. Each subfolder has equal number of csv and json files. 
1. Event Load Sensor Data: Event named load sensor data containing timesteps and Load Sensor           values. This data is provided in the form of csv files. (13075 in number)
2. Tags Data: Event named label/tag data containing the information about the event such as cat name, event tags, free text etc (JSON File).  (13075 in number)
 Initially two dataframes are formed. One using all the csv files and other using all the json files. The granularity of the final dataframe has to be in such a way that one row represents one json and one csv file.

The cat interaction events are as shown below:
a.	Elimination
i.	Defecation 
ii.	Urination
b.	Non-Elimination

The objective of this project is to develop a solution approach to correctly classify the events as elimination or non-elimination and further classify the elimination events into urination and defecation.













	Instructions to run the jupyter notebook

•	The python code has been provided and split into parts like Data preparation, EDA, modelling etc. 
•	Prepared data has been saved to csv files and is read as per requirements.
•	The jupyter notebook will take nearly 1 hours to run completely.
•	Raw data can be download data from the google drive link.
https://drive.google.com/file/d/1bjWCFpS8L7z1b31XszuOhuH3-MUjO34c/view?usp=sharing 


