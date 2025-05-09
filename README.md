# Disk-scheduling-algorithm

This C program simulates three disk scheduling algorithms:  
- **First-Come, First-Served (FCFS)**  
- **SCAN (Elevator Algorithm)**  
- **C-SCAN (Circular SCAN)**

It runs on a disk with **5,000 cylinders** numbered from `0` to `4999`, and generates **1,000 random disk I/O requests**. The program reports the **order of service** and the **total head movement** for each algorithm.

---

## 🔧 How It Works

1. Generates 1,000 random cylinder requests within the range `[0, 4999]`.
2. Accepts an initial disk head position via the command line.
3. Simulates each scheduling algorithm.
4. Outputs the order in which requests are serviced and the total head movement for each algorithm.

## Output

## The program prints:

- The servicing order for FCFS, SCAN, and C-SCAN.
- The total head movement required for each algorithm.

---
## Author Team 
- Ahmed Ali Hassn
- Mahmoud Mohamed Abdelhafez
- Sayed Esmail Sayed
- Abdelrahman Eid Masoud
- Karim Mahmoud Sayed

----
