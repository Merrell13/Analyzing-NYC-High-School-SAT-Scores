# Analyzing-NYC-High-School-SAT-Scores
The correlation between SAT scores in NYC high schools and various demographics such as race, gender and income.

The SAT, or Scholastic Aptitude Test, is an exam that U.S. high school students take before applying to college. Colleges take the test scores into account when deciding who to admit, so it's fairly important to perform well on it.

The test consists of three sections, each of which has 800 possible points. The combined score is out of 2,400 possible points (while this number has changed a few times, the data set for our project is based on 2,400 total points). Organizations often rank high schools by their average SAT scores. The scores are also considered a measure of overall school district quality.

In this project I am going to investigate the correlation between SAT scores in NYC high schools and various demographics such as race, gender and income.

All of the data sets used in this project have been taken from https://data.cityofnewyork.us/.

Here are the details all of the data sets I'll be using:

SAT scores by school - SAT scores for each high school in New York City https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4

School attendance - Attendance information for each school in New York City https://data.cityofnewyork.us/Education/2010-2011-School-Attendance-and-Enrollment-Statist/7z8d-msnt

Class size - Information on class size for each school https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3

AP test results - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject) https://data.cityofnewyork.us/Education/AP-College-Board-2010-School-Level-Results/itfs-ms3e

Graduation outcomes - The percentage of students who graduated, and other outcome information https://data.cityofnewyork.us/Education/Graduation-Outcomes-Classes-Of-2005-2010-School-Le/vh2h-md7a

Demographics - Demographic information for each school https://data.cityofnewyork.us/Education/School-Demographics-and-Accountability-Snapshot-20/ihfw-zy9j

School survey - Surveys of parents, teachers, and students at each school https://data.cityofnewyork.us/Education/NYC-School-Survey-2011/mnz3-dyi8

Basic research into New York, SAT's and the data has led to the following information:

Only high school students take the SAT, so I'llfocus on high schools.
New York City is made up of five boroughs, which are essentially distinct regions.
New York City schools fall within several different school districts, each of which can contains dozens of schools.
Our data sets include several different types of schools. We'll need to clean them so that we can focus on high schools only.
Each school in New York City has a unique code called a DBN, or district borough number.
Aggregating data by district will allow us to use the district mapping data to plot district-by-district differences.
