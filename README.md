# 💻 Operating System Concepts & Lab Implementations

Welcome to my **Operating Systems** repository! This repository contains C/C++ implementations of core OS algorithms and system programming concepts assigned during our laboratory sessions.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Topics Covered](#-topics-covered)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [How to Run](#-how-to-run)
- [Tools & Technologies](#-tools--technologies)

---

## 🛠 Overview
This repository serves as a collection of practical implementations of foundational OS algorithms including CPU scheduling, process synchronization, memory management, and page replacement techniques.

---

## 📚 Topics Covered

- [x] **CPU Scheduling Algorithms**
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF) - Preemptive & Non-Preemptive
  - Priority Scheduling
  - Round Robin (RR)
- [x] **Process Synchronization**
  - Producer-Consumer Problem
  - Dining Philosophers Problem
  - Semaphores & Mutex Locks
- [x] **Deadlock Management**
  - Banker's Algorithm (Safety & Resource Request)
- [x] **Memory Management & Page Replacement**
  - First In First Out (FIFO)
  - Least Recently Used (LRU)
  - Optimal Page Replacement
- [x] **Disk Scheduling**
  - FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK

---

## 📁 Repository Structure

```text
.
├── 01-cpu-scheduling/
│   ├── fcfs.cpp
│   ├── sjf.cpp
│   └── round_robin.cpp
├── 02-process-sync/
│   ├── producer_consumer.cpp
│   └── bankers_algorithm.cpp
├── 03-page-replacement/
│   ├── lru.cpp
│   └── fifo.cpp
├── 04-disk-scheduling/
│   └── scan.cpp
└── README.md
