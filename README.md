# Splunk_Master_of_the_SOC

Unit 19 Activity 

Rice University, Boot Camp Certificate Program, Cyber Security

Data provided by Trilogy Education Services, a 2U, Inc. brand.

As a SOC analyst for "Virtual Space Industries (VSI)" you will use Splunk to review logs to create a baseline for normal operational proceedure and create reports, alerts and dashboards to monitor activity. 

There has been rumors the competitor, JobeCorp, may be launching an attack against the system and web applications. As a SOC analyst, you will monitor the logs to determine if an attack has occured and provide analysis of results. 

WINDOWS SERVER LOGS 

Load logs into Splunk. Analyze data. Develop baseline. Create reports, alerts and dashboards.

REPORTS:
1.	A report with a table of signatures and associated SignatureID. 
table signature signature_id | dedup signature

2.	A report that provides the count and percent of the severity.
Top severity

3.	A report that provides a comparison between the success and failure of Windows activities.
Stats count by status

ALERTS:
1.	Determine a baseline and threshold for hourly level of failed Windows activity.
Status=failure
BASELINE over 8   

2.	Determine a baseline and threshold for hourly count of the signature: an account was successfully logged on.   
Signature=”An account was successfully logged on”
BASELINE over 45

3.	Determine a baseline and threshold for hourly count of the signature: a user account was deleted. 
Signature-“a user account was deleted”
BASELINE over 25

DASHBOARDS: 
1.	A line chart that displays the different signature field values over time.
timechart span=1h count by signature

2.	A line chart that displays the different user field values over time.
timechart count by user

3.	A pie chart that illustrates the count of different signatures.
top signature

4.	A pie chart that illustrates the count of different users.
top user

5.	A statistical chart that illustrates the count of different users.
top user

6.	A radial gauge that illustrates total level of activity
stats count as total
