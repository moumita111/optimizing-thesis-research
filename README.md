# Optimizing Thesis Research Workflow Using A* Search

## 📌 Overview
This project demonstrates a creative application of the A* Search Algorithm to optimize the sequence of tasks in a graduate thesis process. Tasks like literature review, proposal writing, feedback integration, and data collection are modeled as nodes in a weighted, directed graph. A* is used to find the optimal path that minimizes total time while respecting task dependencies.

## 📁 Project Structure
- `AStar_Thesis_Technical_Report.docx`: Detailed report including problem definition, heuristic design, complexity analysis, and results.
- `AStar_Thesis_Presentation.pptx`: PowerPoint presentation summarizing the project for a talk or defense.
- `a_star_thesis.py`: Python implementation of the A* search tailored to this thesis task planning problem.
- `graph_diagram.png`: Visual representation of the thesis task graph (dependencies and time costs).

## ⚙️ Features
- Directed, weighted graph structure representing tasks and dependencies
- Modular A* implementation
- Custom heuristic estimating remaining effort
- Admissible and consistent heuristic design
- Demonstrates optimal scheduling path for thesis completion

## 🎯 Objective
- Start State: No tasks completed
- Goal State: All tasks (including Final Revision) completed
- Optimization Goal: Minimize total time while obeying dependencies

## 🧠 Heuristic Function
The heuristic estimates remaining work by summing durations of tasks ready to be performed (i.e., dependencies met but not yet done). This heuristic is admissible (never overestimates) and helps guide the search efficiently.

## 🧪 Results
Optimal task sequence found:
```
Start → Literature Review → Proposal → Feedback → Data Collection → Final Revision → Data Cleaning → Draft Writing
```
Total Time Cost: **27 units**

## 📈 Future Enhancements
- Add stress or cognitive load modeling
- Handle calendar-based scheduling (weekends, holidays)
- Integrate with academic deadlines or supervisor feedback loops


## 👨‍💻 Author
[Moumita Afreen]

