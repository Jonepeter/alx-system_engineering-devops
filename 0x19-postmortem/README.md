### How to write postmortem
#### Summary
Between the hour of 15:45 and 16:35 on Dec 09, 2022, users encountered Syntax error when we write python script to crawl data from web pages. The event was triggered by code chunk testing at 15:45.

#### Leadup
Describe the sequence of events that led to the incident, for example, previous changes that introduced bugs that had not yet been detected.

EXAMPLE:
At {16:00} on {MM/DD/YY}, ({AMOUNT OF TIME BEFORE CUSTOMER IMPACT, e.g. 10 days before the incident in question}), a change was introduced to {PRODUCT OR SERVICE} in order to {THE CHANGES THAT LED TO THE INCIDENT}.

This change resulted in {DESCRIPTION OF THE IMPACT OF THE CHANGE}.

#### Fault
Describe how the change that was implemented didn’t work as expected. If available, attach screenshots of relevant data visualizations that illustrate the fault.

EXAMPLE:
{NUMBER} responses were sent in error to {XX%} of requests. This went on for {TIME PERIOD}.

#### Impact
Describe how the incident impacted internal and external users during the incident. Include how many support cases were raised.

EXAMPLE:
For {XXhrs XX minutes} between {XX:XX UTC and XX:XX UTC} on {MM/DD/YY}, {SUMMARY OF INCIDENT} our users experienced this incident.

This incident affected {XX} customers (X% OF {SYSTEM OR SERVICE} USERS), who experienced {DESCRIPTION OF SYMPTOMS}.

{XX NUMBER OF SUPPORT TICKETS AND XX NUMBER OF SOCIAL MEDIA POSTS} were submitted.

#### Detection
When did the team detect the incident? How did they know it was happening? How could we improve time-to-detection? Consider: How would we have cut that time by half?