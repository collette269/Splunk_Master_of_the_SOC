Defend the SOC

Load Apache Attack Logs into Splunk. Analyze.

REPORTS:

A report that shows a table of the different HTTP methods (GET, POST, HEAD, etc).

A report that shows the top 10 domains that referred to VSI's website.

A report that shows the count of the HTTP response codes. 

Apache Report Comparison

Apache REPORT Comparison				

![image](https://user-images.githubusercontent.com/88781846/148950172-a56bd59e-9403-440b-93d4-491cd0f88331.png)

![Apa 2 Log Report 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Log%20Report%201.PNG)

ALERTS:

Determine a baseline and threshold for hourly activity from a country other than the United States.

The ALERT for more than... 200 per hour

![Apa 2 Alert 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Alert%201.PNG)

Determine an appropriate baseline and threshold for hourly count of the HTTP POST method.

The ALERT for more than ... 20 per hour

![Apa 2 Alert 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Alert%202.PNG)

VISUALIZATIONSS:

A line chart that displays the different HTTP methods field over time.
A geographical map showing the location based on the clientip field.

High Activity to Note: ...

![Apa 2 Log Visualization 1](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Visualization%201.PNG)

A bar, column, or pie chart that displays the number of different URIs.
A bar, column, or pie chart that displays the counts of the top 10 countries.
...

![Apa 2 Log Visualization 2](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Visualization%202.PNG)

A statistical chart that illustrates the count of different user agents.
One single value visualization of your choice: radial gauge, marker gauge, etc.
...
![Apa 2 Log Visualization 3](https://github.com/collette269/Splunk_Master_of_the_SOC/blob/main/Apache/Apa%202%20Visualization%203.PNG)

Total activity...  

CONCLUSION: 
