---
title: "Operating Systems"
date: 2022-09-01T14:37:27+05:30
draft: false
---

[~/](../../)
[~/posts/](../)

### Objective

> To learn the mechanisms of OS to handle processes and threads and their
>communication

> To learn the mechanisms involved in memory management in contemporary OS

> To gain knowledge on distributed operating system concepts that includes architecture,
>Mutual exclusion algorithms, deadlock detection algorithms and agreement protocols

> To know the components and management aspects of concurrency management

#### Pre-Requisite
- Computer Organization &Architecture

----

1. [x]**Introduction**:
    Generations
    of Operating
    systems,
    Concept of
    Operating
    Systems,
    Types of Operating Systems, OS Services, System Calls,
    Structure of an OS - Layered, Monolithic,
    Microkernel Operating Systems, Concept of Virtual
    Machine. Case study on UNIX and WINDOWS
    Operating System.

2. [x]**Processes**: Definition, Process Relationship, Different
    states of a Process, Process State transitions, Process
    Control Block (PCB), Context switching
    [x]**Thread**: Definition, Various states, Benefits of threads,
    Types of threads, Concept of multithreads,
    [ ]**Process** Scheduling: Foundation and Scheduling
    objectives, Types of Schedulers, Scheduling criteria:
    CPU utilization, Throughput, Turnaround Time,
    Waiting Time, Response Time; [ ]**Scheduling algorithms**:
    Pre-emptive and Non pre-emptive, FCFS, SJF, RR;
    [ ]**Multiprocessor scheduling**: Real Time scheduling: RM
    and EDF.

3. [ ]**Inter-process Communication**: Critical Section, Race
    Conditions, Mutual Exclusion, Hardware Solution,
    Strict Alternation, Peterson’s Solution, The Producer
    Consumer Problem, Semaphores, Event Counters,
    Monitors, Message Passing, Classical IPC Problems:
    Reader’s & Writer Problem, Dinning Philosopher
    Problemetc.

4. [ ]**Deadlocks**: Definition, Necessary and sufficient
    conditions for Deadlock, Deadlock Prevention,
    Deadlock Avoidance: Banker’s algorithm, Deadlock
    detection and Recovery.

5. [ ]**Memory Management**: Basic concept, Logical and
    Physical address map, Memory allocation: Contiguous
    Memory allocation– Fixed and variable partition–
    Internal and External fragmentation and Compaction;
    Paging: Principle of operation –Page allocation
    Hardware support for paging, Protection and
    sharing, Disadvantages of paging.

    - [ ]**Virtual Memory**: Basics of Virtual Memory –
    Hardware and control structures – Locality of
    reference, Page fault , Working Set , Dirty page/Dirty
    bit – Demand paging, Page Replacement algorithms:
    Optimal, First in First Out (FIFO), Second Chance
    (SC), Not recently used (NRU) and Least Recently used(LRU).

6. [ ]**I/O Hardware**: I/O devices, Device controllers, Direct
    memory access Principles of I/O Software: Goals of
    Interrupt handlers, Device drivers, Device independent
    I/O software, Secondary-Storage Structure: Disk
    structure, Disk scheduling algorithms.

    - [ ]**File Management**: Concept of File, Access methods,
    File types, File operation, Directory structure, File
    System structure, Allocation methods (contiguous,
    linked, indexed), Free-space management (bit vector,
    linked list, grouping), directory implementation
    (linear list, hash table), efficiency andperformance.

    - [ ]**Disk Management**: Disk structure, Disk scheduling -
    FCFS, SSTF, SCAN, C-SCAN, Disk reliability, Disk
    formatting, Boot-block, Bad blocks
