📚 Exam Invigilation Duty Planner using Scheduling & Graph Coloring (C++)
This project automates the assignment of exam invigilation duties to faculty members using graph coloring algorithms implemented in C++. It ensures conflict-free and fair scheduling based on exam times and available faculty.

🧠 Problem Statement
Manually assigning invigilation duties during exams is time-consuming and prone to conflicts. This project models the invigilation scheduling problem as a graph coloring task to:

Prevent scheduling conflicts

Distribute workload fairly among faculty

We represent:

Vertices → Exams

Edges → Conflicts (exams at the same time or location)

Colors → Faculty members

🛠️ Features
✅ Conflict-free exam scheduling

✅ Graph coloring algorithm implemented in C++

✅ Simple CLI-based interface

✅ Generates a structured invigilation duty chart

✅ Easily extendable for more constraints

📈 How It Works
Graph Construction
Each exam is treated as a node. An edge connects two exams if they cannot have the same invigilator (e.g., they occur at the same time).

Graph Coloring
A greedy coloring algorithm is used to assign faculty (colors) to each exam, ensuring no overlapping duties.

Schedule Generation
The final output is a mapping of exams to faculty members, which can be printed or written to a file.

⚙️ Technologies Used
C++

STL (Standard Template Library)

File I/O (optional)

Greedy coloring algorithm

🚀 How to Run
🔧 Prerequisites
Make sure you have a C++ compiler installed (like g++).

🧪 Build and Execute
bash
Copy
Edit
make
./invigilation_planner
Or using g++ directly:

bash
Copy
Edit
g++ src/main.cpp src/scheduler.cpp -o invigilation_planner
./invigilation_planner
🔮 Future Improvements
Add support for time and room constraints

Faculty availability limits

GUI or web-based frontend

Export output to CSV or PDF

🙌 Contributing
Feel free to fork the repo and submit pull requests. Open issues for bugs or feature requests.

