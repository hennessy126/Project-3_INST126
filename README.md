# Project-3_INST126
John Lloyde Rayela and Lorenzo Regala


In a professional working environment, almost all the software or digital activities are recorded using log files. 
For this project, we will be using log files that monitors date and time with the activitiy of each user corresponding to different system servers. 
There are a total of 50 users and the log files is generated over a one month period of May 2020. For the project, we are given the task to analyze the log file and generate reports. 
The different data that is recorded in the log file is date, time, activity, server, and user email. The task is to generate reports given the log file. 
The reports must mention the following insights: suspicious activities, irresponsible behavior, system glitches, and domain count. 

# Plan of Action
Functions - we gonna use this to define a function in the project when we write our codes
Strings - we gonna use this to format our codes
List - we gonna use this to put the log in a collection and change it whenever we want to
Dictionaries - we gonna use this to store data
Files - we gonna use this to access an external file just like the userlog.log
Variables - we gonna use this to assigned certain variables to specify information
Conditional statements - we gonna use this to have comparison between variables using operators


# Switching regulat clock to military time
The error we encounter was converting regular 24 hour time format into the military time format. The way we fixed it is tha we use the "if" function xif time >= "00:00:00" and time <= "05:00:00" and emailDict[email][day][time][0] == "login":

# Irresposible behavior count
We were getting invalid syntax error when we were writing the code for our irresponsible behavior because we didn't know if we have to use the print or if functions to do the count. The way we fixed it is that we were just missing the "return" functions to count the irresponsible behavior and that way our loop worked and runs the functions.

# Glitch Behavior Report
The glitch behavior report gave us a hard time because we didn't know what cause our code not run. We were missing a for loop for the time in mail. The way we fixed it is that we put: 
for time in emailDict[email][day]: 
  dayTimes.append(time).
