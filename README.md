# 🧠 ProcessSchedulerSim

A simple C++ project that simulates classic CPU scheduling algorithms, such as FCFS, SJF, Round Robin, and Priority Scheduling. This project is intended for learning and visualizing how operating system schedulers work.

---

## 🚀 Features

- ✅ **FCFS** (First-Come First-Served)
- ✅ **SJF** (Shortest Job First - Non-preemptive)
- ⏳ **Round Robin** (with configurable time quantum)
- ⏳ **Priority Scheduling** (Static Priority)
- ✅ Console-based Gantt Chart output
- ✅ Average waiting time & turnaround time calculation

---

## 🛠️ Build and Run

### Requirements
- C++11 or above
- g++ / clang++ / or any modern C++ compiler

### Compile
```bash
g++ main.cpp -o scheduler
```

### Run
```bash
./scheduler
```

---

## 📦 Example Output

```
Gantt Chart:
| P1 | P2 | P3 |

Process Summary:
PID  Arrival  Burst  Waiting  Turnaround
P1       0       4       0         4
P2       1       3       3         6
P3       2       1       5         6

Average Waiting Time: 2.7
Average Turnaround Time: 5.3
```

---

## 🔧 Planned Features

- [ ] Round Robin Scheduling
- [ ] Preemptive SJF (SRTF)
- [ ] Priority Scheduling (Preemptive & Non-preemptive)
- [ ] Dynamic input from file or CLI
- [ ] ASCII Gantt chart visualization
- [ ] GUI version (optional future)

---

## 📚 References

- Operating System Concepts, Silberschatz et al.
- Modern Operating Systems, Andrew Tanenbaum
- CSAPP (Computer Systems: A Programmer’s Perspective)

---

## 📄 License

MIT License
