CPU Scheduling Simulator
An interactive, web-based tool designed to visualize and compare the performance of various CPU scheduling algorithms. This simulator provides a hands-on learning experience for students and enthusiasts of operating systems.

Developed by Pushkar Lal.

🚀 Features
Interactive Process Management: Easily add, remove, or modify processes with custom Arrival Times, Burst Times, and Priorities.

Multiple Scheduling Algorithms: Simulate and visualize four fundamental CPU scheduling algorithms:

First-Come, First-Served (FCFS)

Shortest Job First (SJF) (Non-Preemptive)

Priority Scheduling (Non-Preemptive)

Round Robin (RR)

Dynamic Gantt Chart: See a real-time, color-coded Gantt chart that illustrates how processes are executed on the CPU over time.

Detailed Performance Metrics: Get instant feedback on key performance indicators, including average waiting time and average turnaround time.

Aesthetic & Modern UI: A clean, responsive interface with smooth animations and a stylish 3D background powered by three.js.

⚙️ How It Works
The simulator is designed to be intuitive and easy to use. Here’s a step-by-step guide:

1. Managing Processes
The Process List card on the left is your control center for defining the workload.

Add a Process: Click the "Add Process" button to add a new process to the list. It will appear with default values.

Modify a Process: You can directly edit the Arrival time, Burst time, and Priority for any process by clicking on its value in the table and typing a new number.

Remove a Process: Click the red "×" button at the end of a process row to delete it.

Reset: Click the "Reset Defaults" button to clear the current list and load the initial set of sample processes.

2. Running a Simulation
Once you have set up your desired processes, you can run a simulation.

Select an Algorithm: Choose the scheduling algorithm you want to visualize from the "Algorithm" dropdown menu in the "Controls" card.

Set Time Quantum (for Round Robin): If you select "Round Robin", an input field for the Time Quantum will appear. You can set the time slice value here.

Simulate: Click the "Simulate" button. The Gantt chart and Results table on the right will instantly update to reflect the simulation's outcome.

3. Understanding the Output
The results of the simulation are displayed in two main areas:

Gantt Chart: This visual timeline shows which process (represented by a colored bar labeled P_id) is running on the CPU at any given moment. Idle blocks indicate periods where the CPU was waiting for a process to arrive. The numbers on the timeline below the chart mark the completion time of each execution block.

Results Table: This table provides a detailed breakdown of each process's journey through the system:

PID: The unique Process ID.

Arrival: The time the process entered the ready queue.

Burst: The total CPU time required by the process.

Priority: The priority level of the process (lower number = higher priority).

Start: The time the process first gets access to the CPU.

Completion: The time the process finishes its execution.

Waiting Time: The total time the process spent waiting in the ready queue (Turnaround Time - Burst Time).

Turnaround Time: The total time from arrival to completion (Completion Time - Arrival Time).

Average Metrics: Below the results table, you can find the average waiting and turnaround times for all processes, which are key indicators for comparing algorithm efficiency.


