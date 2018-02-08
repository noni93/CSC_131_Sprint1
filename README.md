# **Lakhwinder pal Singh**

#### Assignment 2 Individual Project - Sprint 1 (Design and Coding)  
###### Feb 4, 2018
___

#### Design of my Program
When i started this program there were different ways i could have taken, but the approach i took seemed easy and simple, but the implementation was hard. Help was taken from internet, websites such as stackoverflow.com.  Link is provided in the comments 

The program performs various tasks such as  
java TM start <task name> Logs the start time of a task with name <task name>  
java TM stop <task name>	Logs the stop time of a task with name <task name>  
java TM describe <task name> <description>	Logs the description of the task with name <task name>  
java TM summary <task name>	Provides a report of the activity and total time spent working on task with name <task name>  
java TM summary 	Provides a report of the activity and total time spent working on ALL tasks

I created two classes, one for the user input, writing to the file, selecting between the different functions based on the arguments provided by the user.  
An if conditions were applied to check the length of argument, and according to the length certain function calls were made. for argument length of 2, switch statement came in handy to differentiate and go forward.  
Second class contributed in reading from file to linked list, sorting the linked list, time spent on certain task, and other condition for start, stop, and describe functions  of previous class. Summary task function was created to compare elements of a linked list. It gets first element, converts to string and in another for loop compared with other elements. If other elements have same task name with start and stop time it calls another function to get the difference between those two times. and deletes these elements from the list so it will be easier for the function as it wont have to go through the elements over again. 

#### Concerns 
one of the issues is that the program sometimes doesn't allow user to stop a task. It is random, but not that big of concern.  
Other issue is that there are some function calls within the function call. It might be issue for time complexity.   
Another issue is that if user enters multiple descriptions for one task, the program generates multiple instance of that task with all  of the descriptions provided. And if user stops the task, only one of those instances gets the stop time, others remain still running. 

#### conclusion
the program performs all the tasks those were assigned in the assignment. Certain overlap of the logic created confusion, and resulted in some error. But with the time provided the program meets the specification requirements for the user, and budget was kept in mind. 


  


