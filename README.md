# BASIC GANTT CHART BUILDER

## Overview

The **BASIC GANTT CHART BUILDER** is a Python-based application designed to visualize CPU scheduling algorithms. It currently supports the **First-Come, First-Served (FCFS)** scheduling algorithm and provides an interactive graphical user interface (GUI) for users to input processes and burst times. The application generates a Gantt chart to visually represent the scheduling timeline.

## Features

- **Interactive GUI**: Built using `Tkinter`, the application allows users to input process names and burst times in a user-friendly interface.
- **Dynamic Gantt Chart**: Visualizes the scheduling timeline for processes using a Gantt chart.
- **Error Handling**: Ensures proper validation of user inputs, such as matching the number of processes and burst times.
- **Educational Tool**: Ideal for students and professionals to understand CPU scheduling concepts.

## Technologies Used

- **Python**: Core programming language.
- **Tkinter**: For building the graphical user interface.
- **Matplotlib**: For generating the Gantt chart.
- **NumPy**: For efficient numerical operations (if applicable).

## How It Works

1. Users input the process names (comma-separated) and their corresponding burst times (comma-separated) in the GUI.
2. The application validates the inputs to ensure correctness.
3. The **FCFS scheduling algorithm** calculates the start and completion times for each process.
4. A Gantt chart is generated to visualize the scheduling timeline.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/BASIC_GANTT_CHART_BUILDER.git
   ```
