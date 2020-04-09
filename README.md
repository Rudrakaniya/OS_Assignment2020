# What is this?
This repository is made for the assignment of CSE316 (Operating Systems) as a part of CA3, for 4th Semester.
The problems statement which was assigned:
- Reena’s operating system uses an algorithm for deadlock avoidance to manage the
allocation of resources say three namely A, B, and C to three processes P0, P1, and P2. Consider
the following scenario as reference .user must enter the current state of system as given in this
example :

* Suppose P0 has 0,0,1 instances <space> , P1 is having 3,2,0 instances and P2 occupies 2,1,1 instances of
A,B,C resource respectively.
Also the maximum number of instances required for P0 is 8,4,3 and for p1 is 6,2,0 and finally for
P2 there are 3,3,3 instances of resources A,B,C respectively. There are 3 instances of resource A,
2 instances of resource B and 2 instances of resource C available. Write a program to check
whether Reena’s operating system is in a safe state or not in the following independent requests
for additional resources in the
current state:
1. Request1: P0 requests 0 instances of A and 0 instances of B and 2 instances of C.
2. Request2: P1 requests for 2 instances of A, 0 instances of B and 0 instances of C.
* All the request must be given by user as input.
  
  
### Banker’s Algorithm
  Banker’s Algorithm is a deadlock avoidance strategy.It is called so because it is used in banking systems to decide whether a loan can be granted or not.
  
  
### Solution
To comiple the file you can use the command:
```bash
g++ safeStateOS.cpp
```
And then run the executable file by using this command:
```bash
./a.out
```

#### ScreenShot
![](https://i.imgur.com/aaNZANS.png)

provide all the asked input and you will have your answer.

Previously worked at: -
https://github.com/Rudrakaniya/gtk/blob/master/OS_Safe_State.c%2B%2B

