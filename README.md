
 # CPU Scheduling Algorithms

This is my Operating Systems project cloning implementing CPU Scheduling Algorithms such as:

* First Come First Serve (FCFS)
* Shortest Process Next (SPN)
* Round Robin (RR)

The project simulates how a CPU schedules processes and shows results in a Gantt chart–style output.


## Steps you need to Follow

### 1. Clone the Repository

First,  cloned the project from GitHub using:

```bash
git clone https://github.com/harram871/CPU-Scheduling-Algorithms
```

### 2. Navigate to the Folder

then move into the project folder:

```bash
cd CPU-Scheduling-Algorithms
```

### 3. Compile the Program

I compiled the source code using:

```bash
mingw32-make
```

### 4. Run the Program

To run the program, I used:

```bash
./lab4
```

---

## Input Format

When running the program, we give input in the following format:

```
<time_step>,<time_quantum>
<total_simulation_time>
<number_of_processes>
<process_name>,<arrival_time>,<burst_time>
...
```

### Example:

```
1,2
10
3
P1,0,4
P2,1,3
P3,2,2
```

### Meaning:

* **1,2** → `1` = time step, `2` = Round Robin quantum
* **10** → simulation will run for 10 time units
* **3** → total 3 processes
* **P1,0,4** → Process P1 arrives at time 0 and needs 4 units of CPU burst time
* **P2,1,3** → Process P2 arrives at time 1 and needs 3 units
* **P3,2,2** → Process P3 arrives at time 2 and needs 2 units


## Output

The program shows CPU scheduling charts for each algorithm. Example:

```
RR-2
------------------------------------------------
P1 |*|*|.|.|...
P2 |.|*|*|.|...
P3 |.|.|*|*|...
------------------------------------------------
```

Here `*` means the process was running, `.` means waiting/idle.

---

## Screenshots
![image alt](https://github.com/harram871/CPU-Scheduling-Algorithms/blob/813422155bd15d1f400067a936b0f1081473f38a/screenshot%20no%201.PNG)




