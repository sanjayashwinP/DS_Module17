# Ex23 Depth First Graph
## DATE:24/04/2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm


1. **Allocate Memory**: Use `malloc` to allocate memory for a new node of type `struct node`.<br/>
2. **Initialize Vertex**: Set the `vertex` field of the new node to the value `v`.<br/>
3. **Initialize Next Pointer**: Set the `next` pointer of the new node to `NULL`.<br/>
4. **Return Node**: Return the pointer to the newly created node.<br/>
5. **End Function**: Complete the function execution.  <br/>

## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by: SANJAY ASHWIN P
RegisterNumber:  212223040181
*/
struct node* createNode(int v) {
  struct node* newNode = malloc(sizeof(struct node));
  newNode->vertex = v;
  newNode->next = NULL;
  return newNode;
}

```

## Output:

![image](https://github.com/user-attachments/assets/1c965f91-76b3-455e-9a2a-ca76de60df4a)



## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
