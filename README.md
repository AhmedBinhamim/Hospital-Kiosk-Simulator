# Hospital-Kiosk-Simulator
In this project we created a program to simulate the kiosks serving patients in a hospital

The program displays a welcome message to the user and promotes him to enter the 
number of patients to simulate in the system then promotes the user to input the type of 
random number generator from a list of two choices displayed which are linear congruential 
generator and random variate generator for uniform distribution. 

Based on the user choice of 
random generator he is promoted to enter the required data. Then the user is promoted to 
enter what type of line rule to be used to distribute patients over the kiosks. The user can 
select between sequential in which the patients will be going to kiosk 1 and 2 in sequential 
manner or idle in which the patients will be sent to the idle kiosk and if both kiosks are idle 
then patient is sent to kiosk 1. 

The system then takes these inputs from the user and the 
generated service time and interarrival time of the customers and then process the results to 
simulate the kiosks and display the results in table format plus the system log which shows 
when did each customer arrive, got serviced and leave the system.

The program has fixed number of kiosks which is set to 3 in which the first two 
kiosks are for normal aged patients and kiosk 3 is for patients aged 60 or above. The age of 
the patients is randomly generated for the number of patients provided. Kiosk 1 and 2 follow 
the rules set for patients distribution over the kiosks while kiosk 3 does not, because kiosk 3 
should service all the patients who are aged 60 or above only.
