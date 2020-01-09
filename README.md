# TaskReminder
This Task Reminder in assembly language will add tasks for next seven days in file from user  and on respective day the user will find task by entering date from that file which can be done on that day and set reminder for that tasks that has to be done on that day then this task reminder will remind user which subjects he has to be done on that day at which specific time.

**This consist of following menu in ASM:**

* Add Task
* Find Task
* Set Reminder
* Exit programme

## Add Task
In this part we will add next one week from user into the file along with date and "#" at the end of each day task to separate different tasks. It stores data in file into the following format:
```
10-2-2019,Maths,Engslish,Urdu#  10-3-2019,COAL,DSA,PSP#  10-4-2020,PPSD,CAL,PF#  10-5-2019,English,MATHS,BIO#  10-6-2019,ISl,PAK,URDU#  10-7-2019,DLD,DMATHS#  10-8-2019,COAL,DSA,COAL#  
```

## Find Task
In this section we will take date from user to do tasks for specific day and then this reminder search tasks by date and ouptput all the tasks which is to be done on that day
```
If user enter 10-4-2019
This will output
PPSD,CAL,PF
```
## Set Reminder
In this menu we will ask user to set reminder so taht this task reminder will output tasks at specific time which is to be completed
```
if user set reminder for 5 minutes then it will output after 5 minutes 
Complete the following task : PPSD,CAL,PF
```
## Exit programme 
if use want to exit then by pressing this option the programme will exit 
