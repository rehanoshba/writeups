BTLO –Bruteforce|writeup 
Scenario
Can you analyze logs from an attempted RDP bruteforce attack?
One of our system administrators identified a large number of Audit Failure events in the Windows Security Event log.
There are a number of different ways to approach the analysis of these logs! Consider the suggested tools, but there are many others out there!

1)	How many Audit Failure events are there? (Format: Count of Events)
 ans 31103

2)	What is the username of the local account that is being targeted? (Format: Username)

ans adminstrator

3) What is the failure reason related to the Audit Failure logs? (Format: String)
ans Unknown user name or bad password
 


4)What is the Windows Event ID associated with these logon failures? (Format: ID) 
ans 4625


5) What is the source IP conducting this attack? (Format: X.X.X.X)
ans  113.161.192.227

6) What country is this IP address associated with? (Format: Country) 
 Vietnam



7)What is the range of source ports that were used by the attacker to make these login requests? (LowestPort-HighestPort - Ex: 100-541)

 49162–65534
