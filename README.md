---

````markdown
# 🧠 CPU Scheduling Simulator

An interactive, web-based tool designed to **visualize and compare the performance of various CPU scheduling algorithms**. This simulator provides a hands-on learning experience for students and enthusiasts of operating systems.

> Developed by **Pushkar Lal**

---

## 🚀 Features

- **🎛️ Interactive Process Management**  
  Easily add, remove, or modify processes with custom **Arrival Times**, **Burst Times**, and **Priorities**.

- **🧮 Multiple Scheduling Algorithms**  
  Simulate and visualize four fundamental CPU scheduling algorithms:
  - First-Come, First-Served (FCFS)
  - Shortest Job First (SJF) *(Non-Preemptive)*
  - Priority Scheduling *(Non-Preemptive)*
  - Round Robin (RR)

- **📊 Dynamic Gantt Chart**  
  Real-time, color-coded Gantt chart that illustrates how processes are executed on the CPU over time.

- **📈 Detailed Performance Metrics**  
  Get instant feedback on:
  - Average Waiting Time
  - Average Turnaround Time

- **✨ Modern & Aesthetic UI**  
  Clean, responsive design with **smooth animations** and a stylish **3D background** powered by [three.js](https://threejs.org).

---

## ⚙️ How It Works

### 1. Managing Processes

Use the **Process List** panel to define your workload:

- ➕ **Add a Process**: Click `Add Process` to append a new row with default values.
- 📝 **Modify a Process**: Click on the values in the table to edit **Arrival**, **Burst**, or **Priority**.
- ❌ **Remove a Process**: Click the red `×` to delete a process row.
- 🔄 **Reset Defaults**: Click `Reset Defaults` to reload sample processes.

---

### 2. Running a Simulation

- 🔽 **Select an Algorithm**: Use the dropdown to choose a scheduling algorithm.
- ⏱ **Set Time Quantum** (if using RR): An input will appear to specify the quantum.
- ▶️ **Simulate**: Hit `Simulate` to generate the results and visual output.

---

### 3. Understanding the Output

#### 📍 Gantt Chart
A visual timeline showing which process is executing when:
- Color-coded bars for each `P_id`
- Gray "Idle" bars indicate CPU is waiting for arriving processes
- Timeline labels show execution end times

#### 📊 Results Table
Detailed breakdown for each process:

| Column       | Description |
|--------------|-------------|
| `PID`        | Process ID |
| `Arrival`    | Arrival time |
| `Burst`      | CPU time needed |
| `Priority`   | Lower value = higher priority |
| `Start`      | First time on CPU |
| `Completion` | When process finishes |
| `Waiting Time` | Turnaround - Burst |
| `Turnaround Time` | Completion - Arrival |

Below the table, you’ll also find:
- 📉 **Average Waiting Time**
- 📊 **Average Turnaround Time**

These help you **compare the efficiency** of different scheduling strategies.

---

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **UI Library**: [Bootstrap](https://getbootstrap.com)
- **3D Background**: [Three.js](https://threejs.org)

---

## 📸 Demo Screenshots

> *(Add screenshots here if available)*

---

## 📦 Installation

Clone this repository:

```bash
git clone https://github.com/your-username/cpu-scheduling-simulator.git
cd cpu-scheduling-simulator
````

Then simply open `index.html` in your browser:

```bash
start index.html
```

---

## 🙌 Contributions

Contributions, suggestions, and bug reports are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

> 💡 *Learn by doing — visualize how CPU scheduling algorithms work in real time!*

```



