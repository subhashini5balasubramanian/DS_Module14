# Ex10 Applications of Queue – FCFS

## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. Start with process, burst time, and waiting time arrays.
2. Loopthrough each process from i= 0 to n-1.
3. Compute tat[i] = burst_time[i] + wait_time[i].
4. End the algorithm.
## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: SUBHASHINI.B 
RegisterNumber: 212223040211
*/

int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
// calculating turnaround time byadding
// burst_time[i] + wait_time[i] int i;
for ( i = 0; i < n ; i++)
tat[i] = burst_time[i] + wait_time[i]; return 0;
}
```

## Output:
![Screenshot 2025-04-29 100154](https://github.com/user-attachments/assets/1b63c6ad-f382-48bc-b8df-e58c78cf0cf6)



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
