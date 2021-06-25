# Chapter1 Introduction

- What is OS?
  a layer of software, provide user programs to handle managing all the resources
- OS History
  - OS Classif ication
     
  - OS Concepts
  
  - System Calls
  
  - OS Structure
  
     Chapter2 Process and Thread (1)
     Process Model
     Multiprogramming, concurrency
      Process
     Definition
     Process vs. Program
     ❖ Process States
     Three basic states
     Transition between these states
     ❖ Process creation and termination
     4
     ❖ Process Control Block (PCB)
     Function and contents
     ❖ Process context switch
     ❖ Thread
     What is thread?
     Why need threads?
     Thread vs. process
     TCB
     Implementation (kernel & user space)
     Chapter2 Process and Thread (2)
     5
     ❖ Inter-Process Communication (IPC)
     Process Synchronization and Mutual Exclusion
     Critical Resource, Critical Region/Section
     Semaphore and PV operations
     Monitors, why use monitor?
     Message passing
     Using semaphore to solve Classical IPC
     problems
     ❖Dining-Philosophers Problem
     ❖Readers and Writers Problem
     Chapter2 Process and Thread (3)
     6
     ❖ Process Scheduling
     Scheduling opportunity (when to schedule)
     Scheduling algorithm
     ❖Batch systems
     First-Come First-Served (FCFS)
     Short Job First (SJF)
     ❖Interactive system
     Round Robin (RR)
     Priority Scheduling
     Multi Queue & Multi-level Feedback
     Chapter2 Process and Thread (4)
     7
     ❖ Resource Type
     Preemptable Resources
     Non-preemptable Resources
     ❖ Deadlock Definition
     ❖ Four Conditions for Deadlock
     Mutual exclusion condition
     Hold and wait condition
     No preemption condition
     Circular wait condition
     Chapter6 Deadlock (1)
     8
     ❖ Deadlock Modeling
     Resource Allocation Graph
     ❖ Methods for Handling Deadlocks
     The Ostrich Algorithm
     Detection
     ❖One resource of each type: resource allocation
     graph algorithm
     ❖ Multiple resources of each type: matrix-based
     algorithm
     Chapter6 Deadlock (2)
     9
     ❖ Methods for Handling Deadlocks
     Recovery
     ❖Through preemption
     ❖Through rollback
     ❖Through killing process
     Avoidance
     ❖Safe state
     ❖Banker’s algorithm
     Prevention
     ❖Attacking one of the conditions for deadlock
     Chapter6 Deadlock (3)
     10
     ❖ Storage Hierarchy
     ❖ Memory Management Schema
     No Memory Abstraction
     ❖Every program simply saw the physical memory
     ❖It is not possible to run two programs in memory at
     the same time.
     Address Space
     ❖Protection & Relocation: base and limit register
     Swapping
     Memory Management: Bitmap, Linked List
     Partition Allocation: First fit, Next fit, Best fit, Worst
     fit, Quick fit
     Chapter3 Memory Management (1)
     11
     ❖ Virtual Memory
     Principal
     Implementation: Paging, Segmentation with paging
     ❖ Paging
     Page tables
     ❖TLB
     ❖Multi-level page tables, Inverted page tables
     Address Translation Scheme
     Page Fault
     Page Replacement Algorithm
     ❖Optimal, FIFO, Second Chance, Clock, NRU, LRU,
     NFU, Aging, Working Set, WSClock
     Chapter3 Memory Management (2)
     12
     ❖ Design Issues for Paging Systems
     Replacement Scope
     ❖Local Replacement
     ❖Global Replacement
     Page Size
     Separate Instruction and Data Spaces
     Shared Pages
     ❖ Segmentation: Address Translation
     ❖ Segmentation with paging: Address Translation
     Chapter3 Memory Management (3)
     13
     ❖ File and File System
     File: A named collection of related information that
     is recorded on secondary storage.
     File System: A method for storing and organizing
     files and the data they contain to make it easy to
     find and access them.
     ❖ Basic Functions of File System
     Present logical (abstract) view of files and
     directories
     Facilitate efficient use of storage devices
     Support sharing
     Chapter4 File System (1)
     14
     ❖ Files Types
     Regular file (ASCII, Binary) and Directory
     Character and Block special file (UNIX)
     ❖ File Structure
     ❖ File Access: Sequential and Random access
     ❖ Directory Structure
     One-level directory system
     Two-level directory system
     Hierarchical directory system
     ❖ Path Name: Absolute and Relative path name
     Chapter4 File System (2)
     15
     ❖ File Implementation
     Contiguous Allocation
     Linked List Allocation
     Indexed Allocation
     ❖ Directory Implementation
     Directory entry
     i-node
     ❖ Shared Files: Hard link, Symbolic link
     ❖ Disk Space Management
     ❖ File System Reliability (block consistency)
     ❖ Example File Systems (UNIX)
     Chapter4 File System (3)
     16
     ❖ Devices Classification
     Block Devices
     Character Devices
     ❖ Device Controller
     ❖ I/O Addressing
     Separate I/O and memory space
     Memory-mapped I/O
     Hybrid Scheme
     Chapter5 Input/Output (1)
     17
     ❖ Principles of I/O Software
     Goals of I/O Software: Device independence…
     I/O Operations
     ❖Programmed I/O
     ❖Interrupt-driven I/O
     ❖I/O using DMA
     ❖ I/O Software Layers
     Interrupt handlers
     Device drivers
     Device independent OS Software
     User-level I/O Software
     Chapter5 Input/Output (2)
     18
     ❖ Disk
     Disk Organization
     Disk Formatting
     Cylinder Skew
     Disk Arm Scheduling Algorithms
     ❖FCFS
     ❖Shortest Seek First (SSF)
     ❖Elevator Algorithm