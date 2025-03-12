# LINKED-LIST-IMPLEMENTATION

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: TURPATI SAI SRIRAM

**INTERN ID**: CT12WLMZ

**DOMAIN**: C Programming

**BATCH DURATION**: January 10th, 2025 to April 10th, 2025

**MENTOR NAME**: Neela Santhosh Kumar

# DESCRIPTION:
# **LINKED LIST IN C LANGUAGE**  

A **linked list** is a dynamic data structure used in C programming to store a collection of elements. Unlike arrays, linked lists provide efficient memory usage by allowing elements to be stored in non-contiguous memory locations. Each element in a linked list is called a **node**, and it consists of two parts:  

1. **Data** – The actual value stored in the node.  
2. **Pointer** – A reference to the next node in the list.  

Linked lists are widely used in scenarios where the size of the data set changes frequently, making them a flexible alternative to arrays.  

## **Types of Linked Lists**  

1. **Singly Linked List** – Each node points to the next node in the sequence. The last node points to `NULL`, marking the end of the list.  
2. **Doubly Linked List** – Each node contains two pointers: one pointing to the next node and another pointing to the previous node. This allows traversal in both directions.  
3. **Circular Linked List** – The last node of the list points back to the first node, forming a circular structure. It can be singly or doubly linked.  

## **Operations on Linked Lists**  

### **1. Creation of a Linked List**  
A linked list is created dynamically by allocating memory for nodes as needed. Unlike arrays, which require a fixed size, linked lists grow and shrink based on the program’s requirements.  

### **2. Insertion in a Linked List**  
New nodes can be inserted at different positions:  
- **At the beginning** – A new node is created and set as the new head of the list.  
- **At the end** – The new node is linked to the last node of the list.  
- **At a specific position** – A new node is inserted between two existing nodes.  

### **3. Deletion from a Linked List**  
Nodes can be removed based on different conditions:  
- **Deleting the first node** – The head pointer is moved to the next node.  
- **Deleting the last node** – The second-last node is updated to point to `NULL`.  
- **Deleting a specific node** – The previous node is updated to bypass the node being deleted.  
### **4. Traversal of a Linked List**  
To access elements in a linked list, traversal is performed starting from the head node and moving through each node until the end (or back to the head in a circular list).  

### **5. Searching in a Linked List**  
A specific value can be found by iterating through the list and comparing each node’s data with the target value.  

### **6. Reversal of a Linked List**  
The order of nodes in a linked list can be reversed by modifying the pointers to point in the opposite direction.  

## **Advantages of Linked Lists**  
1. **Dynamic Memory Allocation** – Unlike arrays, linked lists do not require a predefined size, making them memory-efficient.  
2. **Efficient Insertions and Deletions** – Nodes can be added or removed easily without shifting elements, unlike arrays.  
3. **Better Utilization of Memory** – Memory is allocated as needed, avoiding wastage.  
4. **Flexibility** – Useful in applications requiring frequent insertions and deletions.  

## **Disadvantages of Linked Lists**  
1. **Extra Memory Usage** – Each node requires additional memory for the pointer.  
2. **Sequential Access** – Unlike arrays, direct access to elements is not possible. Traversal is required.  
3. **Complex Implementation** – Managing pointers requires careful handling to avoid memory leaks and segmentation faults.  


The implementation of a linked list in C involves defining a node structure and functions to perform various operations. The basic steps include:  
1. **Define a Node Structure** – Create a structure with data and a pointer to the next node.  
2. **Initialize the List** – Set the head pointer to `NULL`.  
3. **Implement Insert and Delete Functions** – Add or remove nodes dynamically.  
4. **Traverse the List** – Print or search for elements in the list.  
 

Linked lists are a powerful data structure that provides dynamic memory allocation and efficient operations. They are widely used in applications requiring flexible data storage, such as dynamic memory management, graph representations, and implementing stacks and queues. Understanding linked lists helps in efficient programming and problem-solving in C.


# OUTPUT:
![Image](https://github.com/user-attachments/assets/c0440f5e-f09d-4399-a66c-daada3f197eb)
