# xv6 Operating System – Lab Assignments

This repository contains my completed **Operating Systems laboratory assignments**, based on the **xv6 Unix-like teaching operating system** developed at MIT.  
These labs were completed as part of the Operating Systems course and focus on understanding, modifying, and extending kernel-level functionality in xv6.

## 🧠 Overview

The goal of these labs is to gain hands-on experience with:
- Operating system structure and kernel design
- Process management and system calls
- Scheduling algorithms
- Memory management
- User–kernel interaction in a Unix-like OS

All projects are implemented directly in the xv6 kernel and user space.

---

## 🧪 Lab Assignments

### **Lab 1 – Introduction to xv6**

- Familiarization with xv6 architecture and source tree
- Building and running xv6 using QEMU
- Exploring kernel boot sequence
- Writing and running simple user-level programs
- Understanding core OS responsibilities

---

### **Lab 2 – System Calls**

- Understanding system call mechanism in xv6
- Adding new system calls
- Modifying kernel and user-space interfaces
- Argument passing between user space and kernel
- Testing and validating new syscalls

---

### **Lab 3 – Process Management**

- Deep dive into process creation and termination
- Modifying process-related kernel code
- Understanding `fork`, `exec`, and `wait`
- Process states and transitions
- Kernel scheduling basics

---

### **Lab 4 – CPU Scheduling**

- Implementation and comparison of scheduling algorithms
- Modifying xv6 scheduler
- Possible implementations include:
  - First Come First Serve (FCFS)
  - Round Robin (RR)
  - Priority-Based Scheduling (PBS)
- Measuring performance metrics such as waiting time and turnaround time

---

### **Lab 5 – Advanced Kernel Concepts**

- Advanced OS mechanisms (depending on lab specification), such as:
  - Memory management enhancements
  - Page table exploration
  - Kernel synchronization primitives
- Analysis and reporting of kernel behavior

---

## 🛠️ Technologies & Tools

- **Language:** C
- **Operating System:** xv6 (MIT)
- **Emulator:** QEMU
- **Environment:** Linux
- **Debugging:** GDB, kernel prints

---

## 📚 References

- MIT xv6 source code:  
  https://github.com/mit-pdos/xv6-public
- xv6 Book: *Operating Systems: Three Easy Pieces* (reference)
- Course-provided lab manuals (PDFs)
