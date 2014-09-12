PopCheck
========

> A repopulating checklist app: I would like a checklist to be continuously auto-generated. I'm mostly thinking about household chores and errands. The main idea is that each chore has a different repeating frequency. If I don't get to it, I want it to stick around on the list. 


I imagine a universe with three types of tasks:

1. One-offs: e.g. Get tix for Fri.  
   These have an optional expiration date: if it's after Fri, its off the list, regardless of whether I got the tickets
2. Repeaters, that are date independent. e.g. change the sheets every 5 days.  
   The 5day interval always starts from last completed task, regardless of whether previous interval was 5 or 8 days.
3. Calendar specific repeaters: take out trash every Wed night.  
   It expires every wed night, and reappears next week, regardless of whether it was taken care of

{TaskID, TaskString, Date/repeater structure}

Two views: 
1. The checklist, which self generates from the set of tasks.
2. Task Editor
