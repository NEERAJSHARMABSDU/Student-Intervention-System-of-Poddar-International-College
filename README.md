# Student-Intervention-System-of-Poddar-International-College
Project: Student Intervention System  Investigate the factors that affect a student's performance . We will train and test several  supervised machine learning models on a given dataset to predict how likely a student is to pass. Finally we will selected the best model based on relative accuracy and efficiency.

Data The dataset used in this project is included as student-data.csv. 

This dataset has the following attributes: 

school : student's school (binary: "UnderGraduate" or "PostGraduate")
sex : student's sex (binary: "F" - female or "M" - male)
age : student's age (numeric: from 16 to 26)
address : student's home address type (binary: "U" - urban or "R" - rural) 
famsize : family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
Pstatus : parent's cohabitation status (binary: "T" - living together or "A" - apart)
Medu : mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education) 
Fedu : father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
Mjob : mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other") Fjob : father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other") Attendance : Lecture attend in sem (numeric: 1 - &lt;15 , 2 - 15 to 30 , 3 - 30 to 40 ,4 -40 to 45)
studytime : weekly study time (numeric: 1 - &lt;2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours) 
failures : number of past exam  failures (numeric: n if 1&lt;=n&lt;3, else 4) 
famsup : family educational support (binary: yes or no) paid : extra paid classes within the course subject  (binary: yes or no) activities : extra-curricular activities (binary: yes or no) higher : wants to take Post education (binary: yes or no) 
internet : Internet access at home (binary: yes or no) gf/bf : with in relationship (binary: yes or no) 
famrel : quality of family relationships (numeric: from 1 - very bad to 5 - excellent) 
Dalc : workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
Walc : weekend alcohol consumption (numeric: from 1 - very low to 5 - very high) 
health : current health status (numeric: from 1 - very bad to 5 - very good) 
passed : did the student pass the final exam (binary: yes or no)
