Defend the SOC

Load Apache Attack Logs into Splunk. Analyze.

REPORTS:

The second set of log activity changed significantly from the normal operation proceedure logs. The GET activity decreased by 84% or 16,545 events, the POST activity increased by 525% or 1,112 events and the HEAD activity decreased by 82% or 69 events. 

Apache Report Comparison

Apache REPORT Comparison				

![image](https://user-images.githubusercontent.com/88781846/148950172-a56bd59e-9403-440b-93d4-491cd0f88331.png)

![Apa 2 Log Report 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Log%20Report%201.PNG)

ALERTS:

Hourly activity from a country other than the United States.

The ALERT for more than 200 events per hour from a non-United States county would have been triggered at 9pm on March 25th to email the SOC team. There were 935 events from 8-9pm. 

![Apa 2 Alert 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Alert%201.PNG)

Hourly activity count of HTTP POST events. 

The ALERT for more than 20 HTTP POST events per hour would have been triggered at 9pm on March 25th to email the SOC team. There were 1296 events from 8-9pm. 

![Apa 2 Alert 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Alert%202.PNG)

VISUALIZATIONSS:

A line chart that displays the different HTTP methods field over time.
A geographical map showing the location based on the clientip field.

High Activity to Note: 
 
GET activity increased to 729 at 6pm.

POST activity increased to 1,296 at 8pm.

![Apa 2 Log Visualization 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Visualization%201.PNG)

VSI Account Logon 44 % activity
United States Client Country activity 53%
Ukraine Client Country Activity 23%

![Apa 2 Log Visualization 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Visualization%202.PNG)

Mozilla/4.0 InfoPath.1 useragents 29%
Chef Client/10.18.2 http://opscode.com useragents 14%
Total events decreased from 20,000 to 4,497.  

![Apa 2 Log Visualization 3](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Visualization%203.PNG)

CONCLUSION: 
