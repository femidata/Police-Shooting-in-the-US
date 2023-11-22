# Police-Shooting-in-the-US


1. Introduction
Matthew Hoffman, a 32-year-old white man was fatally shot on Sunday, 4th of January 2015 at approximately 5:20 p.m. Hoffman was described to have entered the restricted area of the Mission Station parking lot where three police sergeants were on their way to get coffee. At first, he appeared to comply when the sergeants told Hoffman to exit the lot. While officers got into their patrol car, Hoffman remained in the same spot for some time. Concerned, the officer got out of their vehicle, and told Hoffman to exit, at which point he backed away towards Valencia Street with his hands in his pockets, "staring at the officers."
When Hoffman lifted up his sweatshirt to display what was later revealed to be an airsoft pistol - with legally mandated orange markings blacked out - and pointed it at the officers, two of them fired five rounds each at Hoffman. Three bullets landed in his forearm, leg, and upper body. He died from his wounds later that night at San Francisco General Hospital.
In the recent killings, a hot topic came into being, "Racism". The case of Mathew Hoffman is just one of thousands of police shooting incidents that happen yearly. This case is worth looking into to understand the cause and possible solutions.

*1.1 Dataset*
The police shooting dataset is obtained from the Kaggle website. The dataset consists of four thousand, eight hundred and ninety-five (4895) rows and fifteen 15 columns collected between 2015 and 2020.

*1.2 System Setup*
List of all required Python libraries
jovian
os
Opendatasets
NumPy
Pandas
Matplotlib
Seaborn

# *2. Data Preparation and Cleaning*
Import the necessary libraries that will be used for this project
Download and read the dataset into a dataframe
Clean and convert dataset for analysis

2.1 Import the Dataset and Preview
The raw data comes with a lot of redundant columns that we do not need for this exploratory data analysis. In this section, we clean the rough dataset to get a DataFrame structure below.
The dataframe containing the first five rows of the datasetThe dataset contains a record of four thousand, eight hundred and ninety-five (4895) police shooting victims which was collected between the 2nd of January 2015 and the 15th of June 2020. This comprises four thousand, six hundred and seventy-three (4673) males and two hundred and twenty-two (222) females.
3. Exploration
There are endless questions to ask from this dataset. However, we will be asking the following questions to gain some insights;
3.1 Questions
How many men and women have been victims of police shootings?
What race has the highest number of police shooting victims?
Which city has the highest case of police shootings?
How many shooting victims were diagnosed with mental illness
What is the age range with the highest number of victims?
How many victims were violent?
How many were victims attacked with a weapon and which weapon was mostly used by victims?
What days have the most cases of police shootings?
How many victims didn't flee before being shot by the police?
How many of the victims in question 9 above were not armed?
How many victims were tasered before or after being shot? Were all tasered victims violent?
How many cases had active body cam?

3.2 Answers
How many men and women have been victims of police shootings?

The total count of female and male shooting victims are 222 and 4673 respectively
gender
Female     222
Male      4673
2. What race has the highest number of police shooting victims?
The race with the highest number of shooting victims is White race,  with a 
total of 2476 victims
race
White       2476
Black       1298
Hispanic     902
Asian         93
Native        78
Other         48
3. Which city has the highest case of police shootings?
state_full
California        701
Texas             426
Florida           324
Arizona           222
Colorado          168
Georgia           161
Oklahoma          151
North Carolina    148
Ohio              146
Washington        126
Tennessee         125
Missouri          124
Louisiana         102
Illinois           99
Pennsylvania       95
Alabama            95
New Mexico         93
Virginia           92
Indiana            91
New York           90
4. How many shooting victims were diagnosed with mental illness?
signs_of_mental_illness
False    3792
True     1103
signs_of_mental_illness False True
gender  
Female                  153    69
Male                    3639   1034
Signs of mental illness by gender5. What is the age range with the highest number of victims?
age
37    222
25    176
31    174
27    165
33    164
     ... 
81      1
78      1
12      1
13      1
91      1
6. How many victims were violent?
threat_level
attack          3160
other           1528
undetermined     207
The threat level of victims7. How many victims were attacked with a weapon and which weapon was mostly used by victims?
Weapons used by victims8. What days have the most cases of police shootings?
date
2019-12-31    100
2015-07-31    100
2018-03-31     99
2017-02-28     97
2018-01-31     96
             ... 
2020-04-30     58
2019-08-31     57
2018-09-30     50
2017-12-31     39
2020-06-30     22
9. How many victims didn't flee before being shot by the police?
flee
Car             820
Foot            642
Not fleeing    3073
Other           360
Fleeing Victims10. How many victims in question 9 above were not armed?
Unarmed and not fleeing 187
11. How many victims were tasered before or after being shot? Were all tasered victims violent?
Total count of victims tasered   248
Out[63]:
Threat level of tasered victims

threat_level
attack          125
other           118
undetermined      5
12. How many cases had active body cam?
4. Conclusion
Police shooting in the United States remains a very serious issue that should be taken very seriously considering that a total of four thousand, eight hundred and ninety-five (4,895), comprising of four thousand, six hundred and seventy-three (4,673) male and two hundred and twenty-two (222) female were shot in five (5) years.
From the analysis in this project, it can be seen most of these shootings recorded were a result of agitation on the side of the police officers probably as a result of weapons pulled by victims or being attacked due to aggressiveness or a mental disorder. However, these claims can't be ascertained as the majority of the police officers didn't have a body cam on at the time of these incidents.
Contrary to the belief that police brutality in the United States is racially motivated, this project has shown that more white people were shot
Finally, I believe general gun violence in the United States will be reduced to a minimum if a gun control law is put in place. Also, citizens will save their lives if they can avoid moves that will agitate police officers when confronted.
