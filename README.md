# iog-dba-mysqlpatching-service

Name: MySQL database patching
Overview: Support Monthly MySQL database patching on Linux server patching window. 
Team: 14 members
End User: All product team and customers. 

SLI (Indicator)	SLO (Goal)	SLA (Communicated to Users)
Time to Prepare Patching - Time team prepare patching and send to DBAs review. Gather user request. Team send patching list modification to Linux team, and update the ISIT change ticket.	80% within 1day before patching
20% within 2day before patching	80% with 1day to finalize the patching list 
Time to complete patching – Time takes for team to complete patching	80% completed within 2hrs
20% completed 3hrs or more	80% completed within 2hrs
20% completed 3hrs or more
Accuracy of VIP operation - Before and after patching team operates vip properly	98% F5vip flipped before patching and flipped back to the correct server post patching	98% f5 vip operation performed as expected.

Accuracy of Patching – Team ensures the correct patching applied to the schedule server on specific phase	98% servers successfully patching with the right version	98% servers successfully patching with the right version
Life Cycle Patching Order – Team ensures non-prod database is patched first before prod database is patched	99% non-prod servers are patched before prod servers	99% non-prod servers are patched before prod servers
Accuracy of Monitoring – Team turns on monitoring, turns off patching flag on server, sends update on remaining server issues  	99% normal operation post patching	99% normal operation post patching

