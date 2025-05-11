# Ex21 Representation of Graph
## DATE:
## AIM:
To write a C program to display the adjacency matrix of the given graph by supplying the edges and the number of vertices.

## Algorithm
```
1. Start 
2. Read the value of V (number of vertices). 
3. Declare an adjacency matrix adjMatrix[V][V]. 
4. Initialize the matrix to 0 using the init function. 
5. Calculate the maximum number of edges me as n * (n - 1) / 2. 
6. For each edge, read e1 and e2, add the edge to the adjacency matrix, and stop if e1 == -1 
&& e2 == -1. 
7. Print the adjacency matrix. 
8. End 
```
## Program:
```
/*
Program to display the adjacency matrix of the given graph
Developed by: Saranya S
RegisterNumber:  212223110044
*/
```
```
/*#include<stdio.h>
int V;

//init matrix to 0
void init(int arr[][V])
{
    int i,j;
    for(i = 0; i < V; i++)
        for(j = 0; j < V; j++)
            arr[i][j] = 0;
}
*/
void printAdjMatrix(int arr[][V])
{
     int i, j;
      //type your code here...
      for(i=0;i<V;i++)
      {
          for(j=0;j<V;j++)
          {
              printf("%d ",arr[i][j]);
          }
          printf("\n");
      }
}
```

## Output:
![image](https://github.com/user-attachments/assets/d3a558ba-259f-4eb5-bdc1-b93f030e7f81)

## Result:
Thus, the C program to print the adjacency matrix of the given graph is implemented successfully.
