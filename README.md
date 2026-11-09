# 🧬 Automated University Exam Timetable Optimizer (Genetic Algorithm)

An evolutionary computation and constraint-satisfaction engine that generates **conflict-free university examination schedules** using **Genetic Algorithms (GA)** in Python, paired with an interactive GUI schedule viewer.

---

## 🎯 Key Features

- **Hard & Soft Constraint Optimization**:
  - Eliminates student overlapping exam conflicts across concurrent timeslots.
  - Enforces classroom seating capacity limits (`classrooms.csv`).
  - Balances instructor invigilation loads (`instructors.csv`) and spreads exams across available days (`timeslots.csv`).
- **Genetic Operators**:
  - Population initialization, tournament/roulette selection, multi-point chromosome crossover, and adaptive mutation.
- **Interactive Schedule GUI (`exam_schedule_gui.ipynb`)**:
  - Filter generated timetables by Student ID, Course Code, Instructor, or Classroom.

---

## 📂 Repository Structure

| File | Description |
| :--- | :--- |
| `Exam Scheduling Using Genetic Algorithm.ipynb` | Core Genetic Algorithm implementation, fitness function evaluation, and convergence plots |
| `exam_schedule_gui.ipynb` | Interactive GUI for browsing and validating the optimized exam schedule |
| `Exam Scheduling Using Genetic Algorithm__Report.pdf` | Full technical report detailing chromosome encoding, fitness penalties, and experimental results |
| `courses.csv` / `classrooms.csv` / `instructors.csv` / `timeslots.csv` | Input constraint datasets |

---

## 🚀 Quick Start

```bash
pip install numpy pandas matplotlib jupyter
jupyter notebook "Exam Scheduling Using Genetic Algorithm.ipynb"
```
