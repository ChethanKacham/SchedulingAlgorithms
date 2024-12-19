# 🕒 Scheduling Algorithms in Java

**SchedulingAlgorithms** is a Java-based project that demonstrates various CPU scheduling algorithms commonly studied in operating systems. Each algorithm takes input from CSV files and simulates scheduling operations, producing results as console outputs.

---

## 📂 Repository Structure

- **src/com/chethan/scheduling**: Contains Java source code files for each scheduling algorithm.
- **input_files/**: Includes CSV files used as input for the scheduling algorithms.
- **README.md**: Documentation for understanding and using the project.


---

## 🚀 Getting Started

### Prerequisites

- **Java JDK**: Ensure that Java JDK is installed on your system.
- **Eclipse/IntelliJ**: Recommended IDEs for running the project.

---

### 💻 Running the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ChethanKacham/SchedulingAlgorithms.git
   cd SchedulingAlgorithms

2. **Import into IDE**:
   - Open the IDE.
   - Import the project folder
   
3. **Run Algorithms**:
   - Navigate to the src/com/chethan/scheduling folder and select the file(Eg. FCFSScheduling.java)
   - Run the file in IDE to execute the algorithm.
4. **Input Files**: 
   - Ensure that the required CSV input files are placed in the input_files directory.

---

### 📜 Algorithms Implemented

1. **First Come First Serve (FCFS)**
   Reads input from input_fcfs.csv.

2. **Shortest Job First (SJF)**
   Reads input from input_sjf.csv.

3. **Shortest Remaining Time First (SRTF)**
   Reads input from input_srtf.csv.

4. **Priority Scheduling**
   Reads input from priority_input.csv.

5. **Priority Scheduling with Round Robin**
   Reads input from priorityrr_input.csv.

6. **Round Robin Scheduling (RR)**
   Reads input from RR_input.csv.
   
### 📌 Purpose

- Demonstrates fundamental CPU scheduling concepts.
- Useful for learning and testing scheduling algorithms in operating systems.