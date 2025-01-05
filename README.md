

**Module 1:  Structure and Union**

1. **What is a self-referential structure?** 
- A. A structure that refers to itself. 
- B. A structure that contains pointers to other structures of the same type. 
- C. A structure that can store data of multiple types. 
- D. None of the above. 

  **Answer:**  B 

2. **Which keyword is used to create an alias for a data type in C?** 
- A. typedef 
- B. alias 
- C. define 
- D. rename 

  **Answer:**  A 

3. **What is the correct way to access a member of a structure using a pointer?** 
- A. (\*ptr).member
- B. ptr.member
- C. ptr->member
- D. Both A and C 

  **Answer:**  D 

**Module 2: Arrays and Stacks** 

4. **Which of the following is NOT true about sparse matrices?** 
- A. Most elements are non-zero. 
- B. They are stored efficiently to save memory. 
- C. They can be represented using arrays or linked lists. 
- D. They are used in applications like graph algorithms. 

  **Answer:**  A 

5. **What is the postfix expression for the infix expression (A + B) \* C - D?** 
- A. A B + C \* D -
- B. A B C + \* D -
- C. A B + C D \* -
- D. A B C D + \* -

  **Answer:**  A 

6. **Which data structure is used to implement a priority queue?** 
- A. Array 
- B. Linked List 
- C. Heap 
- D. Stack 

  **Answer:**  C 

**Module 3:  Linked Lists** 

7. **Which of the following statements about circular linked lists is true?** 
- A. They have a fixed number of nodes. 
- B. The last node points back to the head node. 
- C. The nodes are always sorted. 
- D. They do not support deletion. 

  **Answer:**  B 

8. **In a doubly linked list, how many pointers are associated with each node?** 
- A. 1 
- B. 2 
- C. 3 
- D. 4 

  **Answer:**  B 

9. **Which of the following is a type of self-organizing list?** 
- A. Sorted list 
- B. Circular list 
- C. Move-to-front list 
- D. Doubly linked list 

  **Answer:**  C 

**Module 4:  Recursion** 

10. **Which problem is best solved using recursion?** 
- A. Linear Search 
- B. The Tower of Hanoi 
- C. Bubble Sort 
- D. Hashing 

  **Answer:**  B 

11. **What is the base case in recursion?** 
- A. The initial step. 
- B. The step where the recursion ends. 
- C. The first recursive call. 
- D. The maximum depth of recursion. **Answer:**  B 

**Module 5: Trees** 

12. **What is the time complexity of searching in a balanced binary search tree (BST)?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n²) 

  **Answer:**  B 

13. **Which type of tree traversal uses the order: left subtree → root → right subtree?** 
- A. Preorder 
- B. Inorder 
- C. Postorder 
- D. Level order 

  **Answer:**  B 

14. **What is an AVL tree?** 
- A. A binary tree with no duplicates. 
- B. A balanced binary search tree. 
- C. A tree with threaded nodes. 
- D. A tree that does not allow deletion. **Answer:**  B 

**Module 6:  Searching and Sorting** 

15. **Which sorting algorithm uses a divide-and-conquer approach?** 
- A. Selection Sort 
- B. Bubble Sort 
- C. Merge Sort 
- D. Insertion Sort 

  **Answer:**  C 

16. **Which searching algorithm is faster for a sorted array?** 
- A. Linear Search 
- B. Binary Search 
- C. Hashing 
- D. Depth-First Search 

  **Answer:**  B 

17. **What is the time complexity of Quick Sort in the average case?** 
- A. O(n) 
- B. O(n log n) 
- C. O(n²) 
- D. O(log n) 

  **Answer:**  B 

**Module 7:  Hashing** 

18. **What is the primary purpose of hashing?** 
- A. Data compression 
- B. Fast data retrieval 
- C. Sorting data 
- D. Encoding data 

  **Answer:**  B 

19. **Which technique resolves collisions by open addressing?** 
- A. Chaining 
- B. Linear Probing 
- C. Dynamic Hashing 
- D. Extendible Hashing 

  **Answer:**  B 

20. **Which property is required for a perfect hash function?** 
- A. No collisions 
- B. Dynamic table size 
- C. High memory usage 
- D. Slow search time 

  **Answer:**  A 

**Module 1: #Structure and Union**

1. **Which of the following is true about nested structures?** 
- A. Nested structures must always use pointers to reference inner structures. 
- B. Nested structures are limited to one level of nesting. 
- C. Nested structures allow a structure to have another structure as a member. 
- D. Nested structures cannot be passed to a function. 

  **Answer:**  C 

2. **If a structure contains a pointer to itself, how is memory allocation for such a structure handled?** 
- A. The memory is allocated dynamically. 
- B. The memory is allocated during compile time. 
- C. The structure cannot be created. 
- D. The pointer itself is allocated, but not the object it points to. 

  **Answer:**  D 

3. **What is the key difference between a structure and a union in C?** 
- A. Structures can store only integers, while unions can store all data types. 
- B. Structures store all members independently, while unions share the same memory location for all members. 
- C. Unions are faster than structures in all cases. 
- D. Structures require less memory than unions. 

  **Answer:**  B 

**Module 2:  Arrays and Stacks** 

4. **In a sparse matrix represented using a 2D array, which of the following is most efficient for storing and retrieving non-zero elements?** 
- A. Row-major order representation 
- B. Column-major order representation 
- C. Triple array representation 
- D. Direct mapping 

  **Answer:**  C 

5. **Consider the following postfix expression: AB+CD-\*. If A = 5, B = 3, C = 8, and D = 2, what is the result?** 
- A. 30 
- B. 16 
- C. 10 
- D. 6 

  **Answer:**  B 

  **Explanation:** Convert postfix to infix: (A + B) \* (C - D) = (5 + 3) \* (8 - 2) = 8 \* 6 = 48. 

6. **What is the time complexity of inserting an element into a priority queue implemented using a binary heap?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n log n) **Answer:**  B 

**Module 3:  Linked Lists** 

7. **What is the time complexity of searching for an element in a sorted singly linked list?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n log n) 

  **Answer:**  C 

8. **Which of the following scenarios benefits the most from a skip list?** 
- A. When frequent insertions are required. 
- B. When elements need to be accessed randomly with low latency. 
- C. When memory usage needs to be minimal. 
- D. When data is stored in a contiguous manner. 

  **Answer:**  B 

9. **What distinguishes a circular doubly linked list from other linked lists?** 
- A. It has two pointers per node and a tail pointer. 
- B. It is always sorted. 
- C. The last node points to the first node, and the first node points to the last node. 
- D. It cannot support recursion. 

  **Answer:**  C 

**Module 4:  Recursion** 

10. **Which of the following recurrence relations represents the time complexity of the Tower of Hanoi problem?** 
- A. T(n) = T(n-1) + 1 
- B. T(n) = 2T(n-1) + 1 
- C. T(n) = T(n-1) + T(n-2) 
- D. T(n) = n² 

  **Answer:**  B 

11. **How many recursive calls are made to solve the Tower of Hanoi problem for n = 4?** 
- A. 15 
- B. 16 
- C. 31 
- D. 32 

  **Answer:**  C 

  **Explanation:** Total calls = 2ⁿ - 1 = 2⁴ - 1 = 15. 

12. **What is the auxiliary space complexity of recursive binary search?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n log n) 

  **Answer:**  B 

**Module 5:  Trees**

13. **What is the difference between a binary tree and a binary search tree?** 
- A. A binary tree can have at most two children, whereas a binary search tree does not have this restriction. 
- B. In a binary search tree, the left child is always smaller than the root, and the right child is always greater. 
- C. A binary search tree always has a balance factor of 1. 
- D. Binary trees cannot store duplicate elements, while binary search trees can. 

  **Answer:**  B 

14. **Which of the following is NOT true for AVL trees?** 
- A. An AVL tree is a height-balanced binary search tree. 
- B. The balance factor of each node must be either -1, 0, or 1. 
- C. The insertion operation has a time complexity of O(n). 
- D. AVL trees provide faster lookup compared to unbalanced binary search trees. 

  **Answer:**  C 

15. **Which traversal technique is ideal for converting a binary tree into its mirror image?** 
- A. Preorder 
- B. Inorder 
- C. Postorder 
- D. Level order 

  **Answer:**  A 

**Module 6:  Searching and Sorting** 

16. **What is the worst-case time complexity of Quick Sort?** 
- A. O(n) 
- B. O(n log n) 
- C. O(n²) 
- D. O(log n) 

  **Answer:**  C 

17. **Which sorting algorithm is considered unstable?** 
- A. Merge Sort 
- B. Quick Sort 
- C. Bubble Sort 
- D. Insertion Sort 

  **Answer:**  B 

18. **How many comparisons are required in the worst case for linear search on an array of size n?** 
- A. n 
- B. log n 
- C. n/2 
- D. n² 

  **Answer:**  A 

**Module 7: Hashing**

19. **What is the main disadvantage of open addressing in hashing?** 
- A. Requires additional memory for chains. 
- B. Suffers from clustering issues. 
- C. Does not support deletion of keys. 
- D. Does not allow dynamic resizing. 

  **Answer:**  B 

20. **Which hashing technique allows for resizing of the hash table without rehashing every element?** 
- A. Separate chaining 
- B. Coalesced hashing 
- C. Extendible hashing 
- D. Linear probing 

  **Answer:**  C 

21. **In perfect hashing, what is the ideal time complexity for searching?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n²) 

  **Answer:**  A 

**Module 1:  Structure and Union**: 

**Multiple-Choice Questions (MCQs)**
## Multiple-Choice Questions
 

1. **Which keyword is used to define a structure in C?** 
- A. struct 
- B. typedef 
- C. union 
- D. define 

  **Answer:**  A 

2. **Which of the following allows defining a new data type using an existing one?** 
- A. typedef 
- B. struct 
- C. enum 
- D. union 

  **Answer:**  A 

3. **What is the correct way to access a member of a structure using a structure variable?** 
- A. struct.member
- B. struct->member
- C. member.struct
- D. struct:member

  **Answer:**  A 

4. **What is a union in C?** 
- A. A data type that stores different data types in different memory locations. 
- B. A data type that stores different data types in the same memory location. ![ref1]
- C. A data type that is identical to a structure. 
- D. None of the above. 

  **Answer:**  B 

5. **What is the key difference between a structure and a union?** 
- A. A union uses less memory than a structure. 
- B. A structure allows only one member to be active at a time. 
- C. A union can hold multiple values simultaneously. 
- D. A union and a structure are identical. 

  **Answer:**  A 

6. **How are structure members accessed through a pointer?** 
- A. Using the . operator. 
- B. Using the -> operator. 
- C. Using the & operator. 
- D. Using the \* operator. 

  **Answer:**  B 

7. **Which of the following best describes a typedef in C?** 
- A. It is used for defining functions. 
- B. It is used for defining variables. 
- C. It is used for creating type aliases. 
- D. It is used for creating pointers. 

  **Answer:**  C 

8. **What happens if a union is assigned a value to one of its members?** 
- A. All members store the same value. 
- B. Only the assigned member has a valid value. 
- C. All members are initialized to zero. 
- D. It results in an error. 

  **Answer:**  B 

9. **What is a self-referential pointer?** 
- A. A pointer that points to another structure. 
- B. A pointer that points to itself. 
- C. A pointer that points to the structure it is defined in. 
- D. A pointer that points to NULL. 

  **Answer:**  C 

10. **Can a structure contain a pointer to another structure of the same type?** 
- A. Yes, but only one level of nesting is allowed. 
- B. Yes, it is called a self-referential structure. 
- C. No, it is not allowed in C. 
- D. No, it is only allowed in unions. 

  **Answer:**  B 

11. **How is memory allocated for a union?** 
- A. Equal to the sum of the sizes of all its members. 
- B. Equal to the size of its largest member. 
- C. Equal to the size of its smallest member. 
- D. None of the above. 

  **Answer:**  B 

12. **Which operator is used to dereference a structure pointer?** 
- A. . 
- B. ->
- C. \*
- D. & ![ref1]

  **Answer:**  B 

13. **What is a nested structure?** 
- A. A structure containing a pointer to itself. 
- B. A structure defined within another structure. 
- C. A structure containing multiple unions. 
- D. A structure with no members. 

  **Answer:**  B 

14. **How is a structure passed to a function?** 
- A. By value 
- B. By reference 
- C. Both A and B 
- D. Structures cannot be passed to functions. 

  **Answer:**  C 

15. **What is the size of a structure containing an integer and a char in C?** 
- A. 5 bytes 
- B. 8 bytes (due to padding) 
- C. 4 bytes 
- D. Depends on the compiler. 

  **Answer:**  D 

16. **Can a union contain a structure as one of its members?** 
- A. Yes 
- B. No 

  **Answer:**  A 

17. **What is the output of the following code?** 

    struct Example { 

    `    `int a; 

    `    `char b; 

    } ex = {5, 'c'}; 

    printf("%d %c", ex.a, ex.b); 

- A. 5 c 
- B. Compile error 
- C. Undefined behavior 
- D. None of the above 

  **Answer:**  A 

18. **How do you dynamically allocate memory for a structure in C?** 
- A. Using malloc. 
- B. Using calloc. 
- C. Both A and B. 
- D. Dynamic allocation is not possible for structures. 

  **Answer:**  C 

19. **Which of the following is a correct declaration of a typedef for a structure?** 
- A. typedef struct MyStruct { int a; } NewType;
- B. typedef MyStruct { int a; } NewType;
- C. struct typedef MyStruct { int a; } NewType;
- D. typedef struct { int a; } MyStruct NewType;

  **Answer:**  A 

20. **What does the following code do?** 

    typedef struct Node {     int data; 

    `    `struct Node\* next; } Node; 

- A. Creates a new type alias Node for the structure. 
- B. Creates a union with a self-referential pointer. 
- C. Creates an error due to recursion. 
- D. None of the above. 

  **Answer:**  A 

**Short-Answer Questions (SAQs)**
## Short-Answer Questions
 

1. **Explain the difference between a structure and a union.** 

   **Answer:**  Structures allocate separate memory for each member, while unions share memory for all members. 

2. **What is a self-referential structure? Provide an example.** 

   **Answer:**  A structure containing a pointer to the same type. 

   Example: 

   struct Node {   

   `    `int data;   

   `    `struct Node\* next;   }; 

3. **What is the purpose of the typedef keyword in C?** 

   **Answer:**  It is used to create type aliases for existing data types. 

4. **How is a structure passed to a function by reference? Provide an example.** **Answer:**  By passing the address of the structure. 

   Example: 

   void func(struct MyStruct\* ptr) {       // Access members using ptr->   } 

5. **How can a structure pointer be dereferenced?** 

   **Answer:**  Using the -> operator. 

6. **Why are unions useful in memory management?** 

   **Answer:**  They allow multiple members to share the same memory location, reducing memory usage. 

7. **Provide an example of a nested structure.** 

   **Answer:**  

   struct Inner {   

   `    `int x;   

   };   

   struct Outer {   

   `    `struct Inner in;       int y;   

   }; 

8. **What happens if you try to access multiple members of a union simultaneously?** **Answer:**  It leads to undefined behavior because unions share the same memory. 
9. **Write a code snippet to define a structure and a typedef alias for it.** **Answer:**  

   typedef struct {       int id;   

   `    `char name[20];   } Student; 

10. **What is the role of padding in structures?** 

    **Answer:**  Padding ensures proper memory alignment for faster access. 

**Module 2:  Arrays and Stacks**: 

**Multiple-Choice Questions (MCQs)**
## Multiple-Choice Questions
 

1. **What is the maximum number of dimensions an array can have in C?** 
- A. 1 
- B. 2 
- C. 3 
- D. Theoretical limit depends on compiler 

  **Answer:**  D 

2. **What is the index of the first element in an array in C?** 
- A. 1 
- B. 0 
- C. -1 
- D. Depends on the compiler 

  **Answer:**  B 

3. **What is a sparse matrix?** 
- A. A matrix with all elements non-zero 
- B. A matrix with most elements as zero 
- C. A matrix with only diagonal elements as non-zero 
- D. None of the above 

  **Answer:**  B 

4. **Which of the following is a correct way to represent a sparse matrix?** 
- A. Row-major order 
- B. Column-major order 
- C. Triplet representation 
- D. Contiguous array 

  **Answer:**  C 

5. **What is the time complexity of inserting an element in a 1D array of size n?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n²) 

  **Answer:**  C 

6. **What does a priority queue do?** 
- A. Operates on a FIFO principle 
- B. Operates on a LIFO principle ![ref1]
- C. Removes the smallest or largest element first 
- D. Randomly removes elements 

  **Answer:**  C 

7. **What is the main difference between a stack and a queue?** 
- A. Stack is FIFO, queue is LIFO 
- B. Stack is LIFO, queue is FIFO 
- C. Both are FIFO 
- D. Both are LIFO 

  **Answer:**  B 

8. **What does the postfix expression AB+CD-\* mean?** 
- A. Add A and B, multiply with the difference of C and D 
- B. Multiply A and B, then subtract C and D 
- C. Add C and D, multiply A and B 
- D. Subtract A and B, then multiply with C and D 

  **Answer:**  A 

9. **Which of the following is NOT an application of a stack?** 
- A. Function call management 
- B. Evaluating postfix expressions 
- C. Breadth-first search 
- D. Infix-to-postfix conversion 

  **Answer:**  C 

10. **How many 2D arrays are required to store a sparse matrix using triplet representation?** 
- A. 1 
- B. 2 
- C. 3 
- D. Depends on the matrix 

  **Answer:**  C 

11. **Which operation is NOT valid in a queue?** 
- A. Insertion at the rear 
- B. Deletion from the front 
- C. Random access 
- D. Traversing the queue 

  **Answer:**  C 

12. **What is the time complexity of converting an infix expression to a postfix expression using a stack?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n²) 

  **Answer:**  C 

13. **In a 2D array, if the base address is 1000 and each element is of size 4 bytes, what is the address of the element at position [2][3] (row-major order)?** 
- A. 1012 
- B. 1024 
- C. 1032 
- D. 1048 

  **Answer:**  C 

14. **What is the primary disadvantage of a priority queue implemented using an array?** 
- A. Limited to fixed size 
- B. Slow insertion 
- C. Slow deletion 
- D. No access to elements 

  **Answer:**  C 

15. **Which of the following is NOT true about multi-dimensional arrays?** 
- A. Memory is allocated contiguously. 
- B. They are represented as pointers to pointers. 
- C. They can be dynamically allocated. 
- D. They are less memory efficient than sparse matrices. 

  **Answer:**  B 

16. **Which of the following stack operations causes underflow?** 
- A. Push 
- B. Pop 
- C. Peek 
- D. None of the above 

  **Answer:**  B 

17. **What is the result of evaluating the postfix expression 6 2 / 3 -?** 
- A. 0 
- B. 1 
- C. -1 
- D. None of the above 

  **Answer:**  C 

18. **Which data structure is used in the Tower of Hanoi problem?** 
- A. Array 
- B. Stack 
- C. Queue 
- D. Linked List 

  **Answer:**  B 

19. **How do you declare a 3D array in C?** 
- A. int arr[ ][ ][ ];
- B. int arr[10][10];
- C. int arr[10][10][10];
- D. int\* arr;

  **Answer:**  C 

20. **What is the time complexity of searching for an element in a 2D array?** 
- A. O(1) 
- B. O(n) 
- C. O(n²) 
- D. O(log n) 

  **Answer:**  C 

**Short-Answer Questions (SAQs)**
## Short-Answer Questions
 

1. **Define a sparse matrix. Why is it important?** **Answer:**  A sparse matrix is a matrix where most elements are zero. It is important because storing only non-zero elements saves memory. 
1. **What is the difference between a stack and a queue?** **Answer:**  A stack uses LIFO (Last-In-First-Out), while a queue uses FIFO (First-In-First-Out). 
1. **Write a code snippet to create a 2D array in C.** 

   **Answer:**  

4. int arr[3][4];  // 3 rows, 4 columns 
4. **What is the time complexity of inserting an element into a stack?** **Answer:**  O(1). 
4. **Explain the concept of triplet representation of sparse matrices.** **Answer:**  It uses three arrays to store row index, column index, and non-zero values of a matrix. 
4. **Describe a real-life application of a queue.** **Answer:**  Managing tasks in a printer queue. 
4. **What is the priority queue, and where is it used?** **Answer:**  A priority queue removes the highest or lowest priority element first. It is used in Dijkstra's algorithm. 
4. **What is the purpose of the push() and pop() functions in a stack?** **Answer:**  push() adds an element to the stack, and pop() removes the top element. 
4. **Write a postfix expression for (A + B) \* (C - D).** **Answer:**  AB+CD-\*. 
4. **Explain the difference between 1D, 2D, and multi-dimensional arrays.** 

   **Answer:**  

- 1D: A single row of elements. 
- 2D: A table of elements with rows and columns. 
- Multi-Dimensional: Arrays with more than two dimensions. 
12. **What is the main disadvantage of an array over a linked list?** **Answer:**  Fixed size and expensive insertions/deletions. 
12. **Provide a code snippet to implement a stack using an array in C.** **Answer:**  

    #define SIZE 10 

    int stack[SIZE], top = -1; 

    void push(int val) { 

    `    `if (top == SIZE - 1) printf("Stack Overflow\n");     else stack[++top] = val; 

    } 

14. **Explain how an array can be used to implement a queue.** **Answer:**  Use two indices, front and rear, to keep track of elements. 
14. **What is the difference between infix and postfix notation?** **Answer:**  Infix has operators between operands (e.g., A + B), while postfix places operators after operands (e.g., AB+). 
14. **What is a circular queue?** 

    **Answer:**  A queue where the last position connects to the first to form a circle. 

**Module 3:  Linked Lists**: 

**Multiple-Choice Questions (MCQs)**
## Multiple-Choice Questions
 

1. **What is a singly linked list?** 
- A. A list where each node points to the previous node 
- B. A list where each node points to the next node 
- C. A list where nodes are connected randomly 
- D. A circular list ![ref1]

  **Answer:**  B 

2. **Which of the following is NOT a type of linked list?** 
- A. Singly linked list 
- B. Doubly linked list 
- C. Circular linked list 
- D. Statically linked list 

  **Answer:**  D 

3. **In a doubly linked list, each node contains:** 
- A. Data and a pointer to the next node 
- B. Data and a pointer to the previous node 
- C. Data, a pointer to the next node, and a pointer to the previous node 
- D. Data only 

  **Answer:**  C 

4. **What is the main difference between a circular linked list and a normal linked list?** 
- A. Circular linked list has a fixed size 
- B. The last node of a circular linked list points to the head 
- C. Circular linked list uses arrays internally 
- D. Circular linked lists cannot be traversed 

  **Answer:**  B 

5. **What is the time complexity of searching for an element in a singly linked list?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n²) 

  **Answer:**  C 

6. **In a circular singly linked list with n nodes, how many links are there?** 
- A. n 
- B. n+1 
- C. n-1 
- D. 2n 

  **Answer:**  A 

7. **What is the advantage of a doubly linked list over a singly linked list?** 
- A. Easier deletion 
- B. Easier traversal in both directions 
- C. Faster access to elements 
- D. Both A and B 

  **Answer:**  D 

8. **Which operation is faster in a doubly linked list compared to a singly linked list?** 
- A. Searching 
- B. Insertion at the end 
- C. Deletion of a node 
- D. Random access 

  **Answer:**  C 

9. **What is the main disadvantage of a linked list compared to an array?** 
- A. Fixed size 
- B. Uses more memory due to pointers 
- C. Difficult to traverse 
- D. Random access is possible 

  **Answer:**  B 

10. **How is a stack implemented using a linked list?** 
- A. Use the tail node as the top of the stack ![ref1]
- B. Use the head node as the top of the stack 
- C. Use both head and tail nodes 
- D. Linked lists cannot implement a stack 

  **Answer:**  B 

11. **Which of the following operations is more efficient in a linked list compared to an array?** 
- A. Searching 
- B. Insertion at the middle 
- C. Deletion of the first element 
- D. Random access 

  **Answer:**  B 

12. **What is a self-organizing list?** 
- A. A list where elements reorganize based on frequency of access 
- B. A list with random access 
- C. A list that is always sorted 
- D. A circular linked list 

  **Answer:**  A 

13. **What is the difference between a circular doubly linked list and a circular singly linked list?** 
- A. Circular doubly linked list does not have a head node 
- B. Circular doubly linked list has both next and previous pointers 
- C. Circular singly linked list uses more memory 
- D. Circular singly linked list cannot traverse backwards 

  **Answer:**  B 

14. **Which of the following applications can be implemented using a linked list?** 
- A. Sparse matrix 
- B. Polynomial representation 
- C. Stack and queue 
- D. All of the above 

  **Answer:**  D 

15. **What is a skip list?** 
- A. A linked list that skips nodes randomly 
- B. A layered linked list with faster search 
- C. A doubly linked list with additional pointers 
- D. A circular linked list with shortcuts 

  **Answer:**  B 

16. **What is the main advantage of a skip list?** 
- A. Random access 
- B. Faster search time compared to a regular linked list 
- C. Uses less memory 
- D. Easier to implement 

  **Answer:**  B 

17. **What is the time complexity of inserting an element in a doubly linked list?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n²) 

  **Answer:**  A 

18. **In a self-organizing list, which technique moves the most recently accessed node to the front?** 
- A. Frequency count 
- B. Transpose 
- C. Move-to-front 
- D. Least Recently Used 

  **Answer:**  C 

19. **What is the main use of circular linked lists?** 
- A. Representing circular queues 
- B. Representing graphs 
- C. Sorting data 
- D. Representing sparse matrices 

  **Answer:**  A 

20. **Which of the following statements is true about linked lists?** 
- A. Deletion is faster in arrays than linked lists 
- B. Insertion at the middle is easier in linked lists 
- C. Linked lists have random access 
- D. Arrays use less memory than linked lists 

  **Answer:**  B 

**Short-Answer Questions (SAQs)**
## Short-Answer Questions
 

1. **Define a singly linked list.** **Answer:**  A singly linked list is a sequence of nodes where each node contains data and a pointer to the next node. 
1. **What is the difference between a singly and a doubly linked list?** **Answer:**  A singly linked list has one pointer (to the next node), while a doubly linked list has two pointers (to the next and previous nodes). 
1. **What are circular linked lists used for?** **Answer:**  Circular linked lists are used in applications like circular queues, buffers, and real-time systems. 
1. **Explain how a linked list can represent a polynomial.** **Answer:**  Each node contains the coefficient and exponent of a term, and nodes are linked to represent the polynomial. 
1. **What is the time complexity of deleting a node from the middle of a linked list?** **Answer:**  O(n). 
1. **What is a skip list, and where is it used?** **Answer:**  A skip list is a layered linked list for faster search, used in databases and memory management. 
1. **Why are linked lists preferred for dynamic memory allocation?** **Answer:**  Linked lists can grow or shrink dynamically without memory wastage. 
1. **Write a function to insert a node at the beginning of a singly linked list.** 

   **Answer:**  
```c
   void insertAtBeginning(Node\*\* head, int data) {     Node\* newNode = (Node\*)malloc(sizeof(Node));     newNode->data = data; 

 newNode->next = \*head; 

  \*head = newNode; 

   } 
```
9. **What is a self-organizing list? Give an example.** 

   **Answer:**  A self-organizing list reorganizes elements based on access patterns, e.g., move-to-front strategy. 

10. **What are the advantages of a circular linked list over a singly linked list?** **Answer:**  Efficient traversal and no need for null checks for the last node. 

**Module 4:  Recursion**: 

**Multiple-Choice Questions (MCQs)**
## Multiple-Choice Questions
 

1. **What is recursion?** 
- A. A function calling itself 
- B. A function calling another function 
- C. A loop inside a function 
- D. A function without return statements 

  **Answer:**  A 

2. **Which data structure is used for managing function calls in recursion?** 
- A. Queue 
- B. Array 
- C. Stack 
- D. Linked List 

  **Answer:**  C 

3. **What is the base case in recursion?** 
- A. The recursive step 
- B. The condition to terminate the recursion 
- C. An infinite loop 
- D. The main function 

  **Answer:**  B 

4. **Which of the following problems is best solved using recursion?** 
- A. Sorting an array 
- B. Calculating factorial 
- C. Searching in a sorted array 
- D. Adding two numbers 

  **Answer:**  B 

5. **What happens if the base case is not defined in a recursive function?** 
- A. The program terminates normally 
- B. The function executes only once 
- C. Infinite recursion leads to stack overflow 
- D. The program compiles with errors 

  **Answer:**  C 

6. **Which of the following is NOT an example of recursion?** 
- A. Tower of Hanoi 
- B. Binary Search 
- C. Factorial calculation 
- D. Bubble Sort 

  **Answer:**  D 

7. **What is the time complexity of calculating Fibonacci numbers using recursion without memoization?** 
- A. O(n) 
- B. O(n²) 
- C. O(2^n) 
- D. O(log n) ![ref1]

  **Answer:**  C 

8. **How many recursive calls are made for factorial(5)?** 
- A. 5 
- B. 4 
- C. 6 
- D. 1 

  **Answer:**  C 

9. **Which of the following uses tail recursion?** 
- A. Fibonacci calculation 
- B. Tower of Hanoi 
- C. Factorial calculation (tail recursion optimized) 
- D. Merge Sort 

  **Answer:**  C 

10. **What is the purpose of the internal stack in recursion?** 
- A. To store local variables and return addresses 
- B. To store input arguments only 
- C. To optimize memory usage 
- D. To prevent infinite loops 

  **Answer:**  A 

11. **What is the recurrence relation for the Tower of Hanoi problem?** 
- A. T(n) = 2T(n-1) + 1 
- B. T(n) = T(n-1) + T(n-2) 
- C. T(n) = nT(n-1) 
- D. T(n) = n² 

  **Answer:**  A 

12. **In which case is recursion not preferred?** 
- A. When there is a repetitive pattern in the problem 
- B. When stack memory usage needs to be minimized 
- C. When the problem can be divided into smaller subproblems 
- D. When the base case is easy to define 

  **Answer:**  B 

13. **What is the return value of factorial(0)?** 
- A. 0 
- B. 1 
- C. Undefined 
- D. Infinity 

  **Answer:**  B 

14. **Which of the following is a disadvantage of recursion?** 
- A. Requires less code 
- B. Can cause stack overflow 
- C. Cannot solve divide-and-conquer problems 
- D. Faster than iterative solutions 

  **Answer:**  B 

15. **What is the output of the following pseudo-code?** 

    def recursiveFunc(n):   

    `    `if n == 0:   

    `        `return 1   

    `    `else:   

    `        `return n \* recursiveFunc(n-1)   print(recursiveFunc(3))   

- A. 6 
- B. 9 
- C. 3 
- D. 1 

  **Answer:**  A 

16. **Which of the following problems uses recursion to solve efficiently?** 
- A. Calculating Fibonacci numbers 
- B. Merging two sorted arrays 
- C. Finding the maximum in an array 
- D. Linear search in an array 

  **Answer:**  A 

17. **What is the maximum number of moves required in the Tower of Hanoi for 4 disks?** 
- A. 7 
- B. 15 
- C. 31 
- D. 127 

  **Answer:**  B 

18. **What is tail recursion?** 
- A. Recursion with multiple calls in a single function 
- B. A recursive function where the recursive call is the last operation 
- C. A recursive function that does not terminate 
- D. A recursive function with no base case 

  **Answer:**  B 

19. **Which of the following is a recursive algorithm?** 
- A. Merge Sort 
- B. Quick Sort 
- C. Both A and B 
- D. Linear Search 

  **Answer:**  C 

20. **Which programming technique is often used to optimize recursion?** 
- A. Memoization 
- B. Loop unrolling 
- C. Dynamic arrays 
- D. None of the above 

  **Answer:**  A 

**Short-Answer Questions (SAQs)**
## Short-Answer Questions
 

1. **What is recursion?** **Answer:**  Recursion is a programming technique where a function calls itself to solve smaller instances of the same problem. 
1. **What is a base case in recursion? Why is it important?** **Answer:**  A base case is a condition that stops the recursion. It prevents infinite recursion and stack overflow. 
1. **Write the recursive formula for the Fibonacci sequence.** 

   **Answer:**  

   F(n)=F(n−1)+F(n−2),F(n) = F(n-1) + F(n-2), 

   with F(0)=0F(0) = 0 and F(1)=1F(1) = 1. 

4. **What is tail recursion?** 

   **Answer:**  Tail recursion is a type of recursion where the recursive call is the last operation in the function. 

5. **Write the recurrence relation for the Tower of Hanoi problem.** 

   **Answer:**  

   T(n)=2T(n−1)+1,T(n) = 2T(n-1) + 1, 

   where T(1)=1T(1) = 1. 

6. **What is the difference between recursion and iteration?** 

   **Answer:**  Recursion uses function calls and an implicit stack, while iteration uses loops and explicit variables. 

7. **What happens if a recursive function lacks a base case?** 

   **Answer:**  It causes infinite recursion, leading to a stack overflow error. 

8. **Write a recursive function to calculate factorial in pseudocode.** 

   **Answer:**  
```python
   def factorial(n):   
   if n == 0:   
   return 1   
   else:   
   return n \* factorial(n-1)   
```
9. **What is the time complexity of calculating Fibonacci numbers recursively?** **Answer:**  O(2^n) without memoization. 
9. **Why is recursion inefficient for large inputs in the Fibonacci sequence?** 

   **Answer:**  It leads to repeated calculations, which increase time complexity exponentially. 

11. **Write the recursive solution for the Tower of Hanoi problem.** 

    **Answer:**  

    def TowerOfHanoi(n, source, target, auxiliary):   

    `    `if n == 1:   

    `        `print("Move disk 1 from", source, "to", target)           return   

    `    `TowerOfHanoi(n-1, source, auxiliary, target)   

    `    `print("Move disk", n, "from", source, "to", target)       TowerOfHanoi(n-1, auxiliary, target, source)   

12. **What are the advantages of recursion?** 

    **Answer:**  Simplifies the code and is useful for problems like divide-and-conquer or tree traversal. 

13. **Explain with an example how recursion uses the stack.** 

    **Answer:**  Each recursive call pushes the function state onto the stack. For example, in factorial, the stack holds intermediate values until the base case is reached. 

14. **What is the output of factorial(4)?** 

    **Answer:**  24 (4 × 3 × 2 × 1). 

15. **How is the Tower of Hanoi problem solved recursively?** 

    **Answer:**  By moving n−1n-1 disks to an auxiliary peg, moving the largest disk to the target peg, and then moving n−1n-1 disks from the auxiliary peg to the target peg. 

**Module 5:  Trees**: 

**Multiple-Choice Questions (MCQs)**
## Multiple-Choice Questions
 

1. **What is a tree in data structures?** 
- A. A linear data structure 
- B. A hierarchical data structure 
- C. A graph without edges 
- D. A collection of sorted elements 

  **Answer:**  B 

2. **What is the maximum number of children a binary tree node can have?** 
- A. 1 
- B. 2 
- C. 3 
- D. Unlimited 

  **Answer:**  B 

3. **What is the height of a binary tree with only a root node?** 
- A. 0 
- B. 1 
- C. 2 
- D. Undefined 

  **Answer:**  A 

4. **Which of the following is NOT a type of binary tree traversal?** 
- A. In-order 
- B. Pre-order 
- C. Post-order 
- D. Reverse-order 

  **Answer:**  D 

5. **What is the in-order traversal of a binary search tree?** 
- A. Left, Root, Right 
- B. Root, Left, Right 
- C. Root, Right, Left 
- D. Right, Left, Root 

  **Answer:**  A 

6. **Which traversal visits the root node first, then the left subtree, and finally the right subtree?** 
- A. Pre-order 
- B. Post-order 
- C. In-order 
- D. Level-order 

  **Answer:**  A 

7. **Which of the following trees has all levels filled except possibly the last level, which is filled from left to right?** 
- A. Full binary tree 
- B. Complete binary tree 
- C. Perfect binary tree 
- D. Skewed binary tree 

  **Answer:**  B 

8. **In a binary search tree (BST), where are smaller elements stored compared to the root?** 
- A. Left subtree 
- B. Right subtree ![ref1]
- C. Root node 
- D. Both left and right subtrees 

  **Answer:**  A 

9. **What is the time complexity of searching an element in a balanced binary search tree?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n log n) 

  **Answer:**  B 

10. **What is a threaded binary tree?** 
- A. A tree with nodes having multiple children 
- B. A binary tree that replaces NULL pointers with inorder successor/predecessor links 
- C. A binary tree used for multithreading 
- D. A binary tree with a circular structure 

  **Answer:**  B 

11. **What does AVL stand for in AVL trees?** 
- A. Adelson-Velsky and Landis 
- B. Automated Variable Locator 
- C. Abstract Vector Library 
- D. Average Value Locator 

  **Answer:**  A 

12. **What is the balance factor of a node in an AVL tree?** 
- A. Difference between the number of nodes in the left and right subtrees 
- B. Difference between heights of left and right subtrees 
- C. The sum of the heights of left and right subtrees 
- D. Always 0 

  **Answer:**  B 

13. **What is the maximum allowed balance factor for any node in an AVL tree?** 
- A. 0 
- B. 1 
- C. 2 
- D. Unlimited 

  **Answer:**  B 

14. **What is the time complexity for inserting an element in an AVL tree?** 
- A. O(log n) 
- B. O(n) 
- C. O(n log n) 
- D. O(n²) 

  **Answer:**  A 

15. **In a binary tree, the maximum number of nodes at level ll is:** 
- A. 2l2^l 
- B. 2l−12^{l-1} 
- C. 2l+1−12^{l+1} - 1 
- D. l×2l \times 2 

  **Answer:**  2l−12^{l-1} 

16. **Which rotation is performed in an AVL tree when a node is inserted into the right subtree of the right child?** 
- A. Left rotation 
- B. Right rotation 
- C. Left-right rotation 
- D. Right-left rotation 

  **Answer:**  A 

17. **Which tree traversal technique is also known as Depth-First Search?** 
- A. In-order 
- B. Level-order 
- C. Pre-order 
- D. Both A and C 

  **Answer:**  D 

18. **In a binary search tree, what is the successor of a node with the maximum value in its left subtree?** 
- A. Root node 
- B. The node itself 
- C. The rightmost node in its left subtree 
- D. The leftmost node in its right subtree 

  **Answer:**  D 

19. **What is the height of an AVL tree with nn nodes?** 
- A. O(log n) 
- B. O(n) 
- C. O(n²) 
- D. O(1) 

  **Answer:**  A 

20. **Which of the following is NOT an operation performed on binary search trees?** 
- A. Insertion 
- B. Deletion 
- C. Traversal 
- D. Hashing 

  **Answer:**  D 

**Short-Answer Questions (SAQs)**
## Short-Answer Questions
 

1. **What is a binary tree?** **Answer:**  A binary tree is a hierarchical data structure in which each node has at most two children, called the left child and the right child. 
1. **What is the difference between a binary tree and a binary search tree?** **Answer:**  In a binary tree, nodes have at most two children, whereas in a binary search tree, the left child contains values smaller than the parent, and the right child contains values larger than the parent. 
1. **Define height-balanced tree.** **Answer:**  A height-balanced tree, such as an AVL tree, is a binary tree where the height difference between the left and right subtrees of any node is at most 1. 
1. **What is the difference between complete and full binary trees?** 

   **Answer:**  A complete binary tree has all levels fully filled except possibly the last, which is filled from left to right. A full binary tree has every node with either 0 or 2 children. 

5. **What is the balance factor of a node in an AVL tree?** ![ref1]

   **Answer:**  It is the difference between the height of the left and right subtrees. 

6. **Write the in-order traversal of the following binary tree:** 

   `     ` 5

   `   `/ \   
   ` `3   8 

   **Answer:**  3, 5, 8 

7. **Explain the concept of a threaded binary tree.** 

   **Answer:**  A threaded binary tree replaces NULL pointers with links to inorder successor or predecessor to improve traversal efficiency. 

8. **What is a full binary tree?** 

   **Answer:**  A binary tree where every node has either 0 or 2 children. 

9. **What is the time complexity of searching in a binary search tree?** 

   **Answer:**  O(log n) for a balanced BST, and O(n) for an unbalanced BST. 

10. **What is a binary search tree (BST)?** 

    **Answer:**  A BST is a binary tree where the left subtree contains elements less than the root, and the right subtree contains elements greater than the root. 

11. **What are the types of rotations in AVL trees?** 

    **Answer:**  Left rotation, right rotation, left-right rotation, and right-left rotation. 

12. **Explain the purpose of rotations in AVL trees.** 

    **Answer:**  Rotations are performed to maintain the balance factor of AVL trees after insertion or deletion of nodes. 

13. **What is a perfect binary tree?** 

    **Answer:**  A binary tree in which all interior nodes have two children, and all leaf nodes are at the same level. 

14. **What is the purpose of a height-balanced tree like an AVL tree?** 

    **Answer:**  To ensure efficient operations like insertion, deletion, and search with a time complexity of O(log n). 

15. **Explain the insertion process in an AVL tree.** 

    **Answer:**  Insert the node as in a BST, then check the balance factor and perform rotations to maintain balance if necessary. 

**Module 6:  Searching and Sorting**:

**Multiple-Choice Questions (MCQs)**
## Multiple-Choice Questions
 

1. **What is the time complexity of a linear search in the worst case?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n²) 

  **Answer:**  C 

2. **Which algorithm divides the array into two halves repeatedly to find an element?** 
- A. Linear Search 
- B. Binary Search 
- C. Quick Sort 
- D. Merge Sort 

  **Answer:**  B 

3. **What is the prerequisite for performing binary search?** 
- A. The array should be sorted. 
- B. The array should be unsorted. 
- C. The array should have unique elements. 
- D. The array should be reversed. 

  **Answer:**  A 

4. **What is the worst-case time complexity of binary search?** 
- A. O(1) 
- B. O(n) 
- C. O(log n) 
- D. O(n log n) 

  **Answer:**  C 

5. **Which sorting algorithm works by repeatedly selecting the smallest element and placing it at the beginning?** 
- A. Insertion Sort 
- B. Selection Sort 
- C. Merge Sort 
- D. Quick Sort 

  **Answer:**  B 

6. **Which sorting algorithm has a time complexity of O(n²) in the worst case?** 
- A. Merge Sort 
- B. Quick Sort 
- C. Selection Sort 
- D. Shell Sort 

  **Answer:**  C 

7. **Which sorting algorithm is based on the divide-and-conquer technique?** 
- A. Bubble Sort 
- B. Merge Sort 
- C. Selection Sort 
- D. Insertion Sort 

  **Answer:**  B 

8. **Which sorting algorithm is the most efficient for small input sizes?** 
- A. Bubble Sort 
- B. Quick Sort ![ref1]
- C. Insertion Sort 
- D. Merge Sort 

  **Answer:**  C 

9. **In Quick Sort, the element used to partition the array is called the:** 
- A. Key 
- B. Pivot 
- C. Median 
- D. Divider 

  **Answer:**  B 

10. **Which sorting algorithm sorts in place and does not require extra memory?** 
- A. Merge Sort 
- B. Quick Sort 
- C. Heap Sort 
- D. Both B and C 

  **Answer:**  D 

11. **What is the best-case time complexity of Quick Sort?** 
- A. O(n²) 
- B. O(n log n) 
- C. O(n) 
- D. O(log n) 

  **Answer:**  B 

12. **What is the key difference between Merge Sort and Quick Sort?** 
- A. Merge Sort is in-place, Quick Sort is not. 
- B. Quick Sort is in-place, Merge Sort is not. 
- C. Both are in-place sorting algorithms. 
- D. Both require additional memory. 

  **Answer:**  B 

13. **Which sorting algorithm repeatedly compares adjacent elements and swaps them if they are in the wrong order?** 
- A. Bubble Sort 
- B. Selection Sort 
- C. Insertion Sort 
- D. Merge Sort 

  **Answer:**  A 

14. **What is the time complexity of Bubble Sort in the worst case?** 
- A. O(n) 
- B. O(log n) 
- C. O(n²) 
- D. O(n log n) 

  **Answer:**  C 

15. **Which sorting algorithm uses a “gap” to reduce the number of comparisons?** 
- A. Bubble Sort 
- B. Selection Sort 
- C. Shell Sort 
- D. Insertion Sort 

  **Answer:**  C 

16. **What is the primary advantage of Merge Sort over Quick Sort?** 
- A. It is faster for small inputs. 
- B. It guarantees O(n log n) time complexity in all cases. 
- C. It uses less memory. 
- D. It is simpler to implement. 

  **Answer:**  B 

17. **What is the worst-case time complexity of Merge Sort?** 
- A. O(n) 
- B. O(n²) 
- C. O(n log n) 
- D. O(log n) 

  **Answer:**  C 

18. **Which of the following sorting algorithms is NOT stable?** 
- A. Merge Sort 
- B. Quick Sort 
- C. Bubble Sort 
- D. Insertion Sort 

  **Answer:**  B 

19. **What is Shell Sort primarily used for?** 
- A. Sorting small arrays 
- B. Improving Insertion Sort by reducing the number of comparisons 
- C. Sorting linked lists 
- D. Sorting in constant time 

  **Answer:**  B 

20. **Which sorting algorithm is fastest for nearly sorted data?** 
- A. Bubble Sort 
- B. Insertion Sort 
- C. Quick Sort 
- D. Merge Sort 

  **Answer:**  B 

**Short-Answer Questions (SAQs)**
## Short-Answer Questions
 

1. **What is linear search?** **Answer:**  Linear search is a searching algorithm where each element in the list is checked sequentially until the desired element is found or the list ends. 
1. **What is binary search?** **Answer:**  Binary search is a searching algorithm that repeatedly divides a sorted array into halves to locate a target value. 
1. **List the conditions under which binary search is preferred over linear search.** **Answer:**  Binary search is preferred when the array is sorted and random access to elements is possible. 
1. **Define the term “pivot” in Quick Sort.** **Answer:**  The pivot is the element used to partition the array into two parts in Quick Sort. 
1. **What is the difference between stable and unstable sorting algorithms?** **Answer:**  A stable sorting algorithm maintains the relative order of elements with equal values, while an unstable algorithm does not. 
1. **Explain the time complexity of Merge Sort in all cases.** 

   **Answer:**  The time complexity of Merge Sort is O(n log n) in the best, worst, and average cases. 

7. **Why is Bubble Sort considered inefficient for large datasets?** 

   **Answer:**  Bubble Sort has a worst-case and average-case time complexity of O(n²), making it inefficient for large datasets. 

8. **What is the advantage of Insertion Sort over other O(n²) algorithms?** 

   **Answer:**  Insertion Sort is efficient for small or nearly sorted datasets. 

9. **What is the difference between internal and external sorting?** 

   **Answer:**  Internal sorting is performed in main memory, while external sorting uses external storage like disks for sorting large datasets. 

10. **Describe the main steps of Merge Sort.** 

    **Answer:**  Divide the array into two halves, recursively sort each half, and then merge the sorted halves. 

11. **When does Quick Sort perform poorly?** 

    **Answer:**  Quick Sort performs poorly when the pivot divides the array into highly unbalanced parts (e.g., already sorted arrays with a poor pivot selection). 

12. **What is the role of the “gap” in Shell Sort?** 

    **Answer:**  The gap is used to compare and sort elements that are far apart, reducing the number of overall comparisons. 

13. **Explain why Merge Sort requires additional memory.** 

    **Answer:**  Merge Sort requires extra memory to store temporary arrays during the merge process. 

14. **What is the main disadvantage of Quick Sort?** 

    **Answer:**  Its worst-case time complexity is O(n²), which occurs with poor pivot selection. 

15. **Explain the process of Insertion Sort.** 

    **Answer:**  Insertion Sort builds the final sorted array one element at a time by inserting each element into its correct position. 

16. **What is the difference between iterative and recursive binary search?** 

    **Answer:**  Iterative binary search uses loops, while recursive binary search uses function calls to divide the array. 

17. **Why is Merge Sort preferred for linked lists?** 

    **Answer:**  Merge Sort does not require random access and works efficiently with linked lists. 

18. **How can you modify Quick Sort to make it stable?** 

    **Answer:**  Quick Sort can be made stable by keeping the relative order of equal elements during partitioning. 

19. **Why is Selection Sort not considered stable?** 

    **Answer:**  Selection Sort swaps elements indiscriminately, which can disturb the relative order of equal elements. 

20. **Write the algorithm for linear search.** 

    **Answer:**  

    for each element in the list:     if element == target: 

    `        `return index 

    return -1 

**Module 7:  Hashing**

**Multiple-Choice Questions (MCQs)**
## Multiple-Choice Questions
 

1. **What is the primary purpose of hashing?** 
- A. Searching 
- B. Sorting 
- C. Efficient data retrieval 
- D. Data compression 

  **Answer:**  C 

2. **What is a hash function?** 
- A. A function that encrypts data 
- B. A function that maps keys to addresses in a hash table 
- C. A function that sorts data 
- D. A function that compresses data 

  **Answer:**  B 

3. **Which of the following is a common issue in hashing?** 
- A. Sorting 
- B. Collisions 
- C. Searching 
- D. Encryption 

  **Answer:**  B 

4. **What is separate chaining?** 
- A. A method to resolve collisions by linking keys to a separate hash table 
- B. A method to store multiple values in the same location 
- C. A method to resolve collisions using linked lists 
- D. A method to avoid collisions by rehashing 

  **Answer:**  C 

5. **Which technique resolves collisions by probing subsequent empty slots?** 
- A. Separate Chaining 
- B. Open Addressing 
- C. Coalesced Hashing 
- D. Extendible Hashing 

  **Answer:**  B 

6. **What is double hashing?** 
- A. Using two hash tables 
- B. Using two hash functions to resolve collisions 
- C. Combining two keys into one 
- D. A type of dynamic hashing 

  **Answer:**  B 

7. **In open addressing, what happens when a collision occurs?** 
- A. The key is discarded 
- B. A linked list is created 
- C. The next available slot is checked 
- D. The hash table is rehashed 

  **Answer:**  C 

8. **What is rehashing?** 
- A. Deleting all keys in the hash table 
- B. Applying a new hash function when the table becomes full 
- C. A method to handle collisions ![ref1]
- D. Encrypting data for security 

  **Answer:**  B 

9. **Which hashing technique requires additional memory to store overflow chains?** 
- A. Open Addressing 
- B. Separate Chaining 
- C. Linear Probing 
- D. Double Hashing 

  **Answer:**  B 

10. **What is the load factor in hashing?** 
- A. The number of keys divided by the table size 
- B. The number of collisions divided by the table size 
- C. The number of probes for a key 
- D. The efficiency of the hash function 

  **Answer:**  A 

11. **Which collision resolution method is most suitable for large data sets with frequent collisions?** 
- A. Linear Probing 
- B. Separate Chaining 
- C. Quadratic Probing 
- D. Double Hashing 

  **Answer:**  B 

12. **What is the time complexity for search, insert, and delete operations in an ideal hash table?** 
- A. O(1) 
- B. O(log n) 
- C. O(n) 
- D. O(n log n) 

  **Answer:**  A 

13. **What is the main disadvantage of using open addressing?** 
- A. Increased memory usage 
- B. Increased time complexity for insertion 
- C. Clustering of elements 
- D. It cannot resolve collisions 

  **Answer:**  C 

14. **What is coalesced hashing?** 
- A. A combination of open addressing and separate chaining 
- B. A hashing technique for dynamic tables 
- C. A technique for perfect hashing 
- D. A rehashing method for overflow keys 

  **Answer:**  A 

15. **What is dynamic hashing?** 
- A. A method to encrypt data 
- B. A technique to expand or shrink the hash table dynamically 
- C. A way to handle collisions 
- D. A static hashing technique 

  **Answer:**  B 

16. **What is the goal of perfect hashing?** 
- A. To ensure O(log n) time complexity for all operations 
- B. To eliminate collisions entirely 
- C. To optimize memory usage 
- D. To support dynamic resizing 

  **Answer:**  B 

17. **Which hashing technique resolves collisions by creating a secondary hash table for overflow keys?** 
- A. Extendible Hashing 
- B. Separate Chaining 
- C. Open Addressing 
- D. Coalesced Hashing 

  **Answer:**  A 

18. **Which of the following hash functions is most commonly used?** 
- A. Modulo Function 
- B. Multiplicative Function 
- C. Folding Method 
- D. Division Method 

  **Answer:**  D 

19. **What is the primary advantage of dynamic hashing?** 
- A. Eliminates collisions 
- B. Adapts to the number of elements 
- C. Uses less memory 
- D. Faster than static hashing 

  **Answer:**  B 

20. **What is the purpose of a hash function in a hash table?** 
- A. To compress data 
- B. To generate unique keys for each element 
- C. To map keys to specific locations in a hash table 
- D. To sort data 

  **Answer:**  C 

**Short-Answer Questions (SAQs)**
## Short-Answer Questions
 

1. **Define hashing.** **Answer:**  Hashing is a technique to map data to a fixed-size table using a hash function for efficient searching and retrieval. 
1. **What is a collision in hashing?** **Answer:**  A collision occurs when two keys produce the same hash value and are assigned to the same location in a hash table. 
1. **What is the difference between static and dynamic hashing?** **Answer:**  Static hashing uses a fixed-size hash table, while dynamic hashing allows the table to grow or shrink based on the number of elements. 
1. **What is open addressing?** **Answer:**  Open addressing is a collision resolution technique where a new slot is found for a colliding key within the hash table. 
1. **Explain separate chaining.** **Answer:**  Separate chaining resolves collisions by linking all keys with the same hash value in a linked list. 
1. **How does rehashing improve hash table performance?** **Answer:**  Rehashing reduces the load factor by increasing the size of the hash table and reapplying the hash function. 
1. **What is linear probing?** 

   **Answer:**  Linear probing resolves collisions by checking the next available slot in the hash table sequentially. 

8. **Describe the process of quadratic probing.** 

   **Answer:**  Quadratic probing resolves collisions by probing slots at increasing distances from the original position (e.g., 1², 2², 3²). 

9. **What is the difference between linear probing and double hashing?** 

   **Answer:**  Linear probing searches sequentially for empty slots, while double hashing uses a second hash function to determine the next slot. 

10. **What is a good hash function?** 

    **Answer:**  A good hash function minimizes collisions, distributes keys uniformly, and is computationally efficient. 

11. **What is the main disadvantage of separate chaining?** 

    **Answer:**  Separate chaining requires additional memory for linked lists. 

12. **How is clustering avoided in double hashing?** 

    **Answer:**  Clustering is avoided by using a secondary hash function to determine the step size, ensuring better distribution of keys. 

13. **What is the purpose of the load factor in hashing?** 

    **Answer:**  The load factor determines the ratio of filled slots to the total slots in the hash table and helps decide when to rehash. 

14. **Explain perfect hashing with an example.** 

    **Answer:**  Perfect hashing ensures no collisions by using a secondary hash table for overflow keys. For example, if keys 5 and 15 hash to the same slot, a secondary hash table is created. 

15. **What is extendible hashing?** 

    **Answer:**  Extendible hashing is a dynamic hashing technique that adjusts the hash table size and structure as keys are added or removed. 

16. **What is the difference between primary and secondary clustering?** 

    **Answer:**  Primary clustering occurs in linear probing due to consecutive filled slots, while secondary clustering occurs when the hash function produces similar step sizes. 

17. **What is the advantage of coalesced hashing over separate chaining?** 

    **Answer:**  Coalesced hashing uses a single hash table for overflow keys, reducing memory usage compared to separate chaining. 

18. **Why is choosing a good hash function important?** 

    **Answer:**  A good hash function reduces collisions, ensures efficient data retrieval, and optimizes 

    hash table performance. 

19. **Explain the difference between static and dynamic hashing with examples.** 

    **Answer:**  Static hashing uses a fixed-size table (e.g., a hash table with 10 slots), while dynamic hashing grows (e.g., extendible hashing) as the number of keys increases. 

20. **Write an algorithm to handle collisions using separate chaining.** 

    **Answer:**  
```c
function insert(key, value):

index = hashFunction(key)

if table[index] is empty:

create a new linked list

append (key, value) to the linked list at table[index] 
```


