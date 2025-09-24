

# 🔗 Linked List Implementation in C++


## 🎯 Aim  
To study the concept of linked lists in C++, and implement basic operations such as node creation, insertion at head, and traversal.

---

## 📚 Theory  
A **linked list** is a linear data structure where each element (node) contains data and a pointer to the next node. Unlike arrays, linked lists allow dynamic memory allocation and efficient insertion/deletion.

### 🔑 Key Concepts  
- **Node**: Basic unit containing data and a pointer to the next node.  
- **Head**: Pointer to the first node in the list.  
- **Insertion**: Adding a new node to the list.  
- **Traversal**: Visiting each node to access or display data.  
- **Dynamic Allocation**: Nodes are created using `new` to allocate memory at runtime.

---

## 📋 Algorithms

### 🧾 1. Node Creation and Display (Basic)

**Start**  
- Define a class `Node` with `val` and `next`.  
- Create a new node using `new Node(10)`.  
- Print the value and pointer of the node.  
**End**

---

### 🧾 2. Node Creation with Constructor

**Start**  
- Define a class `Node` with a constructor that initializes `val` and sets `next` to `NULL`.  
- In `main()`, create a node with value `10`.  
- Print the node’s value and pointer.  
**End**

---

### 🧾 3. Insert at Head and Display List

**Start**  
- Define a class `Link` with `data` and `next`.  
- Create function `insert_head(Link* &head, int data)`:
  - Create a new node.
  - Point its `next` to current `head`.
  - Update `head` to new node.
- Create function `display(Link* head)`:
  - Traverse the list using a temporary pointer.
  - Print each node’s data followed by `->`.
- In `main()`:
  - Initialize `head` as `NULL`.
  - Call `insert_head()` with values.
  - Call `display()` after each insertion.  
**End**

---

## 🚀 Applications of Linked Lists

- Dynamic memory management  
- Implementation of stacks and queues  
- Graph adjacency representation  
- Polynomial arithmetic  
- Real-time data streams

---

## 🧠 Conclusion

This experiment illustrates:

- 📦 How nodes are dynamically created and linked  
- 🔁 How insertion at head modifies the list structure  
- 📤 How traversal accesses each node sequentially  
- 🧼 Clean modular functions for insertion and display

👉 Linked lists offer flexibility and efficiency for dynamic data structures, making them essential in system-level and algorithmic programming.
