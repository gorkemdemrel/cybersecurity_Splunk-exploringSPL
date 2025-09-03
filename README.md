Splunk is a powerful SIEM solution that provides the ability to search and explore machine data. Search Processing Language (SPL) is used to make the search more effective. It comprises various functions and commands used together to form complex yet effective search queries to get optimized results.

This room will dive deep into some key fundamentals of searching capability, like chaining SPL queries to construct simple to complex queries.

Learning Objectives

This room will teach the following topics:

What are Search processing Language?
How to apply filters to narrow down results.
Using transformational commands.
Changing the order of the results.

Questions:
What is the name of the host in the Data Summary tab?
In the search History, what is the 7th search query in the list? (excluding your searches from today)
In the left field panel, which Source IP has recorded max events?
How many events are returned when we apply the time filter to display events on 04/15/2022 and Time from 08:05 AM to 08:06 AM?
How many Events are returned when searching for Event ID 1 AND User as *James*?
How many events are observed with Destination IP 172.18.39.6 AND destination Port 135?
What is the Source IP with highest count returned with this Search query?
Search Query: index=windowslogs  Hostname="Salena.Adam" DestinationIp="172.18.38.5"
In the index windowslogs, search for all the events that contain the term cyber how many events returned?
Now search for the term cyber*, how many events are returned?
What is the third EventID returned against this search query?
Search Query: index=windowslogs | table _time EventID Hostname SourceName | reverse 
Use the dedup command against the Hostname field before the reverse command in the query mentioned in Question 1. What is the first username returned in the Hostname field?
Using the Reverse command with the search query index=windowslogs | table _time EventID Hostname SourceName - what is the HostName that comes on top?
What is the last EventID returned when the query in question 1 is updated with the tail command?
Sort the above query against the SourceName. What is the top SourceName returned?
List the top 8 Image processes using the top command -  what is the total count of the 6th Image?
Using the rare command, identify the user with the least number of activities captured?
Create a pie-chart using the chart command - what is the count for the conhost.exe process?





