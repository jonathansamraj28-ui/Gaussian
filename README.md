# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Input matrix dimensions and initialize augmented matrix and solution vector.

2.Populate the augmented matrix with user inputs.

3.Perform Gaussian elimination to reduce the matrix to upper triangular form, ensuring no division by zero.

4.Back substitute to compute solution values for the variables.

5.Print the solution vector formatted to two decimal places.

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
<img width="827" height="588" alt="Screenshot 2025-10-17 004352" src="https://github.com/user-attachments/assets/38339bfd-850f-40b3-8986-7f162dc47a80" />


## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

