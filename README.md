# POLICE SHOOTING IN THE UNITED STATES OF AMERICA


## 1. Introduction
Matthew Hoffman, a 32-year-old white man was fatally shot on Sunday, 4th of January 2015 at approximately 5:20 p.m. Hoffman was described to have entered the restricted area of the Mission Station parking lot where three police sergeants were on their way to get coffee. At first, he appeared to comply when the sergeants told Hoffman to exit the lot. While officers got into their patrol car, Hoffman remained in the same spot for some time. Concerned, the officer got out of their vehicle, and told Hoffman to exit, at which point he backed away towards Valencia Street with his hands in his pockets, "staring at the officers."
<br>
When Hoffman lifted up his sweatshirt to display what was later revealed to be an airsoft pistol - with legally mandated orange markings blacked out - and pointed it at the officers, two of them fired five rounds each at Hoffman. Three bullets landed in his forearm, leg, and upper body. He died from his wounds later that night at San Francisco General Hospital.
<br>
In the recent killings, a hot topic came into being, "Racism". The case of Mathew Hoffman is just one of thousands of police shooting incidents that happen yearly. This case is worth looking into to understand the cause and possible solutions.
<br><br>
### 1.1 Dataset
The police shooting dataset is obtained from the [Kaggle website](https://www.kaggle.com/datasets/ahsen1330/us-police-shootings). The dataset consists of four thousand, eight hundred and ninety-five (4895) rows and fifteen 15 columns collected between 2015 and 2020.<br>

### 1.2 System Setup
List of all required Python libraries
- jovian
- os
- Opendatasets
- NumPy
- Pandas
- Matplotlib
- Seaborn

## 2. Data Preparation and Cleaning
Import the necessary libraries that will be used for this project
Download and read the dataset into a dataframe
Clean and convert dataset for analysis
<br>
### 2.1 Import the Dataset and Preview
The raw data comes with a lot of redundant columns that we do not need for this exploratory data analysis. In this section, we clean the rough dataset to get a DataFrame structure below.

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/795ea7d9-620a-4218-85d5-5b4b9f6d8325) 
<br>The dataframe containing the first five rows of the dataset
<br>
The dataframe containing the first five rows of the dataset contains a record of four thousand, eight hundred and ninety-five (4895) police shooting victims which were collected between the 2nd of January 2015 and the 15th of June 2020. This comprises four thousand, six hundred and seventy-three (4673) males and two hundred and twenty-two (222) females.<br>

## 3. Exploration
There are endless questions to ask from this dataset. However, we will be asking the following questions to gain some insights;<br>

### 3.1 Questions
1. How many men and women have been victims of police shootings?
2. What race has the highest number of police shooting victims?
3. Which city has the highest case of police shootings?
4. How many shooting victims were diagnosed with mental illness
5. What is the age range with the highest number of victims?
6. How many victims were violent?
7. How many victims were attacked with a weapon and which weapon was mostly used by victims?
8. What days have the most cases of police shootings?
9. How many victims didn't flee before being shot by the police?
10. How many victims in question 9 above were not armed?
11. How many victims were tasered before or after being shot? Were all tasered victims violent?
12. How many cases had active body cam?

### 3.2 Answers

#### 1. How many men and women have been victims of police shootings?


The total count of female and male shooting victims is 222 and 4673 respectively
<br>gender
<br> Female  |   222
<br> Male    | 4673 

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/293a3c13-df3f-42b9-8dc8-1f508dc85740)


#### 2. What race has the highest number of police shooting victims?

<br>
The race with the highest number of shooting victims is White race,  with a 
total of 2476 victims
<br>race
<br>White       2476
<br>Black       1298
<br>Hispanic     902
<br>Asian         93
<br>Native        78
<br>Other         48
<br>

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/70b60fd8-83aa-45f6-afad-5a6f0dfeaabc)


<br>

#### 3. Which city has the highest case of police shootings?
<br>state_full
<br>California        701
<br>Texas             426
<br>Florida           324
<br>Arizona           222
<br>Colorado          168
<br>Georgia           161
<br>Oklahoma          151
<br>North Carolina    148
<br>Ohio              146
<br>Washington        126
<br>Tennessee         125
<br>Missouri          124
<br>Louisiana         102
<br>Illinois           99
<br>Pennsylvania       95
<br>Alabama            95
<br>New Mexico         93
<br>Virginia           92
<br>Indiana            91
<br>New York           90
<br>

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/35fef28b-89ec-4d51-8f8a-d110a28a8032)

#### 4. How many shooting victims were diagnosed with mental illness?

<br>signs_of_mental_illness
<br>False    3792
<br>True     1103
<br>

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/85f88e6b-849a-4799-b63d-4c86fbdfb19c)


<br>signs_of_mental_illness False True
<br>gender  
<br>Female                  153    69
<br>Male                    3639   1034

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/d736201d-0cd0-4965-ae5d-c559c718b3c2)


<br>Signs of mental illness by gender

#### 5. What is the age range with the highest number of victims?
<br>age
<br>37    222
<br>25    176
<br>31    174
<br>27    165
<br>33    164
<br>     ... 
<br>81      1
<br>78      1
<br>12      1
<br>13      1
<br>91      1

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/4ce5eea1-775a-456e-ad5c-5b2b6c6e8f98)


#### 6. How many victims were violent?
<br>threat_level
<br>attack          3160
<br>other           1528
<br>undetermined     207

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/8b7b9b54-cedb-487b-b341-f01af9a87e29)


<br>The threat level of victims

#### 7. How many victims were attacked with a weapon and which weapon was mostly used by victims?

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/e9fe4f2f-ae9a-4daf-a351-e6a606bce2fd)

<br>Weapons used by victims

#### 8. What days have the most cases of police shootings?
<br>date
<br>2019-12-31    100
<br>2015-07-31    100
<br>2018-03-31     99
<br>2017-02-28     97
<br>2018-01-31     96
<br>             ... 
<br>2020-04-30     58
<br>2019-08-31     57
<br>2018-09-30     50
<br>2017-12-31     39
<br>2020-06-30     22

![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/e6a2e522-bbc3-41bf-9e91-3b3b061584f0)



#### 9. How many victims didn't flee before being shot by the police?
<br>flee
<br>Car             820
<br>Foot            642
<br>Not fleeing    3073
<br>Other           360


![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/7c461a99-7e53-4dc4-a725-6fd03b10cc90)

<br>Fleeing Victims

#### 10. How many victims in question 9 above were not armed?
<br>Unarmed and not fleeing 187<br>
#### 11. How many victims were tasered before or after being shot? Were all tasered victims violent?
<br>Total count of victims tasered   248<br>
<br>Out[63]:
<br><br>Threat level of tasered victims

<br>threat_level
<br>attack          125
<br>other           118
<br>undetermined      5<br>


#### 12. How many cases had active body cam?
![image](https://github.com/femidata/Police-Shooting-in-the-US/assets/54317999/5fe3d0cb-04ad-46de-a88b-c7e1ab2424d4)





## 4. Conclusion
Police shooting in the United States remains a very serious issue that should be taken very seriously considering that a total of four thousand, eight hundred and ninety-five (4,895), comprising of four thousand, six hundred and seventy-three (4,673) male and two hundred and twenty-two (222) female were shot in five (5) years.
From the analysis in this project, it can be seen most of these shootings recorded were a result of agitation on the side of the police officers probably as a result of weapons pulled by victims or being attacked due to aggressiveness or a mental disorder. However, these claims can't be ascertained as the majority of the police officers didn't have a body cam on at the time of these incidents.
Contrary to the belief that police brutality in the United States is racially motivated, this project has shown that more white people were shot
Finally, I believe general gun violence in the United States will be reduced to a minimum if a gun control law is put in place. Also, citizens will save their lives if they can avoid moves that will agitate police officers when confronted.

Check the notebook [here](https://github.com/femidata/Police-Shooting-in-the-US/blob/main/Shooting%20in%20the%20US.ipynb)
