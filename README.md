# Capstone Project: Predicting Students' Outcomes with Classification

### Project Objective

This project aims to build a model that will confidently predict those students who are at risk of withdrawing or failing a particular subject. The data comes from the Open University, which is the biggest university in the UK for undergraduate degrees with currently almost 170 000 students. Most students at Open University study off-campus and the virtual learning environment (VLE) provides the main connection between the student and the institution. Due to the lack of the traditional campus presence of students, there is a risk of disconnection between the two, which could lead to a lack of supports of students who might be struggling with the workload.

This model could be used by the university to identify the students who need more support and prevent them from failing or withdrawing from the course.

### About the Dataset

* The data contains information from the Open University Virtual Learning Environment(VLE) which off-campus students use for accessing the course content, forum discussions, sending assessments and checking out assignment marks.

* It consists of 7 selected courses (=modules) from 4 different semesters (=presentations).

* The dataset includes student demographics such as location, age group, disability, education level and gender.

### Notebook Contents
1) Obtaining data + Joining Tables
* studentInfo table
* looking at final results distribution
* studentVle table
* aggregating data and joining tables (studentInfo + studentVle)
* studentAssessment table
* joining the table with Assessments info (studentInfo + studentVle + studentAssessments)

2) Data Exploration

Exploring the relationships between the final outcome and the following:

* number of clicks in VLE
* average grade from assignments
* disability
* IMB score - deprivation index

3) Preparing Variables for Modelling

* creating dummy variables
* splitting data into training (85%), validation (10%) and test (5%) sets
* tackling class imbalance by SMOTE resampling

4) Building the Models

* Model 1 - Random Forest
* Model 2 - Random Forest with grid-search
* Model 3 - XGBoost
* Model 4 - LightGBM

5) Examining the Best Model and Conclusion

* final model testing
* main findings
* future work

