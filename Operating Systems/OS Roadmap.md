# Operating System (OS) Roadmap for Placement Preparation

## **1. Basics of Operating Systems**
- What is an Operating System?  
- Functions of OS  
- Types of OS (Batch, Time-Sharing, Distributed, Real-Time, etc.)  
- System Calls and APIs  
- OS Architecture (Monolithic, Microkernel, Hybrid)  

---

## **2. Process Management**
- **Processes**  
  - Definition of Process, Process States, PCB (Process Control Block)  
  - Context Switching  
- **Threads**  
  - User-level vs Kernel-level threads  
  - Multithreading, Benefits & Challenges  
- **CPU Scheduling**  
  - Preemptive vs Non-Preemptive Scheduling  
  - Scheduling Algorithms: FCFS, SJF, SRTF, Priority Scheduling, Round Robin, Multilevel Queue  
  - Gantt Charts and Average Waiting/Turnaround Time Calculations  

---

## **3. Process Synchronization**
- Race Conditions  
- Critical Section Problem  
- Synchronization Mechanisms  
  - Locks, Mutex, Semaphores (Binary, Counting)  
  - Monitors, Condition Variables  
  - Spinlocks  
- Classical Synchronization Problems  
  - Producer-Consumer Problem  
  - Readers-Writers Problem  
  - Dining Philosophers Problem  

---

## **4. Deadlocks**
- Deadlock Definition & Conditions (Coffman Conditions)  
- Deadlock Handling  
  - Prevention  
  - Avoidance (Banker’s Algorithm)  
  - Detection and Recovery  
- Resource Allocation Graphs  

---

## **5. Memory Management**
- Address Binding (Compile time, Load time, Execution time)  
- Logical vs Physical Address Space  
- **Memory Allocation**  
  - Contiguous Memory Allocation (Fixed, Dynamic Partitioning)  
  - Non-Contiguous Allocation (Paging, Segmentation)  
- Fragmentation (Internal vs External)  
- Virtual Memory  
  - Demand Paging, Page Faults  
  - Page Replacement Algorithms (FIFO, LRU, Optimal, LFU, Clock)  
  - Thrashing  

---

## **6. File Systems**
- File Concepts (Attributes, Operations, File Types)  
- File Access Methods (Sequential, Direct, Indexed)  
- File System Implementation (File Control Block, Inodes)  
- Directory Structure (Single-level, Two-level, Tree, Graph, etc.)  
- File Allocation Methods  
  - Contiguous  
  - Linked  
  - Indexed  
- Free Space Management  

---

## **7. Input/Output (I/O) Systems**
- I/O Hardware Basics  
- Programmed I/O, Interrupt-driven I/O, DMA (Direct Memory Access)  
- I/O Software Layers  
- Disk Scheduling Algorithms  
  - FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK  

---

## **8. Advanced Topics**
- Multiprogramming, Multitasking, Multiprocessing  
- Multi-core Processors and OS Challenges  
- Distributed Operating Systems  
- Real-Time Operating Systems (Hard vs Soft RTOS)  
- Virtualization Basics and OS Role in Virtualization  

---

## **9. Practical / PostgreSQL & OS Connections**
- Process and memory insights with **Linux commands** (`ps`, `top`, `htop`, `free`, `kill`, etc.)  
- File permissions and access control (`chmod`, `chown`)  
- Understanding **PostgreSQL performance tuning** with OS-level resources (memory usage, I/O scheduling, concurrency)  

---

## **10. Interview Focus**
- Commonly asked coding problems:  
  - Implement LRU Cache  
  - Producer-Consumer with Semaphores  
  - Readers-Writers synchronization  
  - Deadlock simulation with threads  
- Scenario-based questions:  
  - How does OS handle page faults?  
  - Difference between Process and Thread?  
  - How context switching works?  
  - Which scheduling algorithm suits which scenario?  

---
