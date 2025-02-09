# 1450. Number of Students Doing Homework at a Given Time Solutions

| Solver    | Solution                                                                                                      | Language |
|-----------|---------------------------------------------------------------------------------------------------------------|----------|
| ahmed reda| <br>public int BusyStudent(int[] startTime, int[] endTime, int queryTime) {<br>    int len = startTime.Length;<br>    int count = 0;<br><br>    for(int i = 0; i < len; i++)<br>    {<br>        if(queryTime >= startTime[i] && queryTime <= endTime[i])<br>        {<br>            count++;<br>        }<br>    }<br>    return count;<br>} | C#       |




**_[Back To Problem List](../../problem-solving/README.md#problem-of-the-day)_**
