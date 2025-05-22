# Ex22 Breadth First Graph
## DATE:
## AIM:
To write a printQueue C function of the given graph that is to be traversed in the breadth first manner.

![image](https://github.com/user-attachments/assets/f483f48c-6af0-4027-a993-01c108a50933)


## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program to traverse graph using BFS
Developed by: Jwalamukhi S
RegisterNumber:  212223040079
*/

/*#include <stdio.h>
#include <stdlib.h>
#define SIZE 40
 
struct queue {
  int items[SIZE];
  int front;
  int rear;
};
 
struct queue* createQueue();
void enqueue(struct queue* q, int);
int dequeue(struct queue* q);
void display(struct queue* q);
int isEmpty(struct queue* q);
void printQueue(struct queue* q);
 +
struct node {
  int vertex;
  struct node* next;
};
 
struct node* createNode(int);
 
struct Graph {
  int numVertices;
  struct node** adjLists;
  int* visited;
};*/
void printQueue(struct queue* q) {
 
 printf("Queue is empty");
 else
 {printf("Queue contains ");
 for(int i=q->front;i<q->rear+1;i++)
 {
     printf("%d ",q->items[i]); }
}}
```

## Output:

![Screenshot 2025-05-22 141011](https://github.com/user-attachments/assets/d0a25da5-b3ad-420b-9d28-d04d57687972)


## Result:
Thus, the code for the printQueue function of the following graph that is to be traversed in the breadth first manner is implemented successfully.
