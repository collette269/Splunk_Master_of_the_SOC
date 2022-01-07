Defend the SOC

Load Windows Attack Logs into Splunk. Analyze.

REPORTS:

The second set of log activity changed significantly from the normal operation proceedure logs. The failed attempts at loggin decreased by half, the successful loggin increased and the number of high severity risk events increased by 70%.  

![image](https://user-images.githubusercontent.com/88781846/148576484-5fe75529-a989-442c-8bf7-38389afb4d88.png)

![Win 2 Log Reports](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Log%20Reports.png)
![Win 2 Log Reports Cont ](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Log%20Reports%20Cont.png)

ALERTS:

Failed Windows Activity

The ALERT for more than 8 failed loggins in one hour would have emailed the SOC team to investigate at 9am. 

![Win 2 Alert 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Alert%201.PNG)

The ALERT for more than 45 successful loggins in one hour would have email the SOC team to investigate at noon. 

![Win 2 Alert 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Alert%202.PNG)

The ALERT for more than 25 deleted accounts in one hour was not triggered as requirements were not met.

![Win 2 Alert 3](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Alert%203.PNG)

DASHBOARDS:

High Activity to Note:

Midnight to 3am user account was locked out.

8am to 11am attempts to reset a password.

10am -1pm account was successfully logged on.


1:40am to 2:40am User A very active.

9:10am to 11am. User K very active.

10:40am to 11:20am User J more active.

![Win 2 Log Visualization 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Log%20Visualization%201.png)

40% of all signatures was an attempt was made to reset a password.

34% a user account was locked out.

![Win 2 Log Visualization 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Log%20Visualization%202.png)

36% or 1,878 User A total activity 

40% or 2,118 User K total activity

![Win 2 Log Visualization 3](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Log%20Visualization%203.png)

Total activity almost in the high range.  

![Win 2 Log Visualization 4](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Log%20Visualization%204.png)

CONCLUSION: This was a brute force attack that started March 25th at midnight. The attackers were able to gain access to User A, User K and User J. The SOC team was emailed at 9am and noon. 

I recommend adding an alert for the users locked out in an hour. In the attack, an alert would have been sent at 2am and again at 3am, providing more time for the SOC analyst team to review and react. 

![Win 2 Alert 4](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%202%20Alert%204.PNG)

