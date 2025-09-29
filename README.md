# Experiment 18 – Queue using Array in C++

**Name:** Varnika Maurya  
**PRN:** 24070123160  

---

## 🎯 Objective
To study and implement the concept of a **Queue using Array in C++**, and perform basic operations:  
- Insertion (Enqueue)  
- Deletion (Dequeue)  
- Traversal (Display)  

---

## 📖 Theory
A **Queue** is a linear data structure that follows the **FIFO (First In, First Out)** principle.  
- **Enqueue** → Insert an element at the rear end.  
- **Dequeue** → Remove an element from the front end.  
- **Display** → Traverse and print all elements in the queue.  

Queues can be implemented using **arrays** or **linked lists**.  
In this experiment, we implement a **static queue** using arrays of fixed size.  

**Advantages:**
- Simple and easy to implement.  
- Useful in scheduling and buffering problems.  

**Disadvantages:**
- Fixed size (possible overflow if array is full).  
- Inefficient use of memory unless implemented as a circular queue.  

---

## 📝 Algorithm

1. **Start Program**.  
2. Define a class `Queue` with:  
   - An integer array `arr[SIZE]`.  
   - Two variables `front` and `rear` to track positions.  
   - Functions:  
     - `enqueue(int value)` → Insert value at the rear.  
     - `dequeue()` → Remove value from the front.  
     - `display()` → Show all elements from `front` to `rear`.  
3. In `main()`:  
   - Create a `Queue` object.  
   - Perform enqueue operations.  
   - Display the queue.  
   - Perform dequeue operation.  
   - Display queue again.  
   - Insert another element and display final queue.  
4. **End Program**.  

---

## ✅ Conclusion
From this experiment, we learned:  
- The working of a **queue** using arrays.  
- Implementation of **enqueue, dequeue, and display** operations.  
- Queues follow the **FIFO principle**, where the first element inserted is the first one to be removed.  
- Static queues are limited by array size; for better memory utilization, **circular queues** are used.  

---
