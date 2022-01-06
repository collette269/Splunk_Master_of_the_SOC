WINDOWS SERVER LOGS 

Load logs into Splunk. Analyze data. Develop baseline. Create reports, alerts and dashboards.

REPORTS:
1.	A report with a table of signatures and associated SignatureID. 

2.	A report that provides the count and percent of the severity.

3.	A report that provides a comparison between the success and failure of Windows activities.

![Win 1 Log Report](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Log%20Reports.png)
![Win 1 Log Report Cont](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Log%20Reports%20Cont.png)

ALERTS:
1.	Determine a baseline and threshold for hourly level of failed Windows activity.

Status=failure

BASELINE over 8   

![Win 1 Alert 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Alert%201.PNG)

2.	Determine a baseline and threshold for hourly count of the signature: an account was successfully logged on.   

Signature=”An account was successfully logged on”

BASELINE over 45

![Win 1 Alert 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Alert%202.PNG)

3.	Determine a baseline and threshold for hourly count of the signature: a user account was deleted. 

Signature-“a user account was deleted”

BASELINE over 25

![Win 1 Alert 3](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Alert%203.PNG)

DASHBOARDS: 
1.	A line chart that displays the different signature field values over time.

2.	A line chart that displays the different user field values over time.

![Win 1 Log Visualization 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Log%20Visualization%201.png)

3.	A pie chart that illustrates the count of different signatures.

![Win 1 Log Visualization 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Log%20Visualization%202.png)

4.	A pie chart that illustrates the count of different users.

5.	A statistical chart that illustrates the count of different users.

![Win 1 Log Visualization 3](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Log%20Visualization%203.png)

6.	A radial gauge that illustrates total level of activity

![Win 1 Log Visualization 4](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Windows/Win%201%20Log%20Visualization%204.png)
