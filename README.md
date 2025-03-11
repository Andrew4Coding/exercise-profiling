Name    : Andrew Devito Aryo

NPM     : 2306152494

Class    : Adpro-A

# Week 5: Java Profiling
## Test Results (Via GUI)
### /all-student-name 
**View Results Tree**
![alt text](image.png)

**View Results Table**
![alt text](image-1.png)

**Summary Report**
![alt text](image-2.png)

**Graph Results**
![alt text](image-3.png)

### /highest-gpa
**View Results Tree**
![alt text](image-4.png)

**View Results Table**
![alt text](image-5.png)

**Summary Report**
![alt text](image-6.png)


**Graph Results**
![alt text](image-7.png)

## Test Results (Via CLI)
### /all-student-name
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741660686735,7438,all student name request,200,,Thread Group 1-5,text,true,,312447,132,10,10,http://localhost:8080/all-student-name,7424,0,2
1741660686431,7742,all student name request,200,,Thread Group 1-2,text,true,,312447,132,10,10,http://localhost:8080/all-student-name,7732,0,20
1741660687027,7146,all student name request,200,,Thread Group 1-8,text,true,,312447,132,10,10,http://localhost:8080/all-student-name,7143,0,1
1741660686530,7643,all student name request,200,,Thread Group 1-3,text,true,,312447,132,10,10,http://localhost:8080/all-student-name,7629,0,2
1741660687127,7046,all student name request,200,,Thread Group 1-9,text,true,,312447,132,10,10,http://localhost:8080/all-student-name,7032,0,1
1741660686628,7545,all student name request,200,,Thread Group 1-4,text,true,,312447,132,10,10,http://localhost:8080/all-student-name,7532,0,1
1741660686828,7352,all student name request,200,,Thread Group 1-6,text,true,,312447,132,4,4,http://localhost:8080/all-student-name,7350,0,1
1741660686430,7763,all student name request,200,,Thread Group 1-1,text,true,,312447,132,3,3,http://localhost:8080/all-student-name,7761,0,21
1741660687227,6967,all student name request,200,,Thread Group 1-10,text,true,,312447,132,2,2,http://localhost:8080/all-student-name,6966,0,1
1741660686928,7284,all student name request,200,,Thread Group 1-7,text,true,,312447,132,1,1,http://localhost:8080/all-student-name,7281,0,1

```

### /highest-gpa
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741660833815,131,highest gpa request,200,,Thread Group 1-1,text,true,,275,127,3,3,http://localhost:8080/highest-gpa,127,0,30
1741660833815,131,highest gpa request,200,,Thread Group 1-2,text,true,,275,127,3,3,http://localhost:8080/highest-gpa,128,0,30
1741660833906,87,highest gpa request,200,,Thread Group 1-3,text,true,,275,127,1,1,http://localhost:8080/highest-gpa,87,0,0
1741660834007,83,highest gpa request,200,,Thread Group 1-4,text,true,,275,127,1,1,http://localhost:8080/highest-gpa,83,0,1
1741660834105,95,highest gpa request,200,,Thread Group 1-5,text,true,,275,127,1,1,http://localhost:8080/highest-gpa,95,0,1
1741660834206,135,highest gpa request,200,,Thread Group 1-6,text,true,,275,127,2,2,http://localhost:8080/highest-gpa,134,0,1
1741660834311,94,highest gpa request,200,,Thread Group 1-7,text,true,,275,127,1,1,http://localhost:8080/highest-gpa,94,0,1
1741660834409,85,highest gpa request,200,,Thread Group 1-8,text,true,,275,127,1,1,http://localhost:8080/highest-gpa,85,0,1
1741660834520,82,highest gpa request,200,,Thread Group 1-9,text,true,,275,127,1,1,http://localhost:8080/highest-gpa,82,0,1
1741660834611,104,highest gpa request,200,,Thread Group 1-10,text,true,,275,127,1,1,http://localhost:8080/highest-gpa,104,0,0
```
