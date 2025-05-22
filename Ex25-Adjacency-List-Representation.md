# Ex25 Adjacency List Representation
## DATE:
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm

1.Read the number of vertices and number of edges.

2.Read all edge pairs (source and destination) and store them.

3.Create a graph using the input edge list.

4.Print the adjacency list representation of the graph.

## Program:
```
/*
Developed by: Jwalamukhi S
RegisterNumber:  212223040079
*/
/*#include <stdio.h>
#include <stdlib.h>
 
// Define the maximum number of vertices in the graph
int N; 
 
// Data structure to store a graph object
struct Graph
{
    // An array of pointers to Node to represent an adjacency list
    struct Node* head[10];
};
 
// Data structure to store adjacency list nodes of the graph
struct Node
{
    int dest;
    struct Node* next;
};
 
// Data structure to store a graph edge
struct Edge {
    int src, dest;
   
} *edges[50];
*/
int main(void)
{  
int n,i;
scanf("%d",&N);
scanf("%d",&n);

struct Edge edges[n];
for(i=0;i<n;i++)
{
    scanf("%d ",&edges[i].src);
    scanf("%d ",&edges[i].dest);
    
    
}
struct Graph *graph=createGraph(edges,n);
printGraph(graph);
    
}


```

## Output:

![Screenshot 2025-05-22 142413](https://github.com/user-attachments/assets/cf25dfd9-a0c9-4e68-99c9-b7a37c0c54ae)


## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
