# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
def gauss_elimination(arr,n):
    for i in range(n):
        for j in range(i+1,n):
            ratio=arr[j][i]/arr[i][i]
            for k in range(n+1):
                arr[j][k]-=ratio*arr[i][k]
    x=[0]*n 
    for i in range(n-1,-1,-1):
        x[i]=arr[i][n]
        for j in range(i+1,n):
            x[i]-=arr[i][j]*x[j]
        x[i]/=arr[i][i]
    return x
data=[]
n=int(input())
values=[float(input()) for _ in range(n*(n+1))]
idx=0
for i in range(n):
    row=[]
    for j in range(n+1):
        row.append(values[idx])
        idx+=1
    data.append(row)
result=gauss_elimination(data,n)
for i in range(n):
    print(f'X{i} = {result[i]:.2f}',end=' ')
Program to find the solution of a matrix using Gaussian Elimination.
Developed by: JONATHAN SAMRAJ A
RegisterNumber: 212225040160
*/
```

## Output:


## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

