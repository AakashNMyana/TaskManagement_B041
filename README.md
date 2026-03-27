# Task Optimization System (Python CLI)

## Overview
This is a simple Python-based command-line application that helps users manage and prioritize tasks efficiently.

Tasks are organized based on:
- Urgency (l, m, h)
- Importance (l, m, h)
- Estimated completion time (in minutes)

The program sorts and displays tasks so users can focus on what matters most.

---

## Features
- Add multiple tasks
- Prioritize tasks automatically
- Simple CLI interaction
- Clean task display

---

## Tech Stack
- Python 3
- OOP (Classes & Objects)
- Lists & Sorting

---

## Project Structure
task-optimizer/
│
├── main.py
└── README.md

---

## How It Works

### Job Class
Stores task details:
- name
- urgency
- importance
- estimated time

### Optimizer Class
Manages tasks:
- add_job() → adds task
- prioritize_jobs() → sorts tasks
- print_jobs() → displays tasks

---

## Sorting Logic
Tasks are sorted using:
(job.urgency, job.imp, job.est_time)

Note:
Sorting is lexicographical (l < m < h), which may not always reflect real-world priority perfectly.

---

## How to Run

1. Install Python
   python --version

2. Run the program
   python main.py

---

## Example

Input:
Enter Task name: Study
Enter Urgency: h
Enter Importance: h
Enter Time: 120

Enter Task name: Watch TV
Enter Urgency: l
Enter Importance: l
Enter Time: 60

Output:
Optimized Task List:
Watch TV (l, l, 60)
Study (h, h, 120)

---

## Limitations
- No data saving
- Basic sorting logic
- CLI only (no UI)

---

## Future Improvements
- Add weighted priority system
- Save tasks to file/database
- Build GUI or web version

---

## Author
Aakash Myana

---

## License
GNU General Public License v3.0
