===============================
## OS Simulation with Crime Data
===============================

This project simulates Operating System (OS) concepts using real-world crime data as a dataset. It covers memory management, CPU scheduling, multithreading, disk I/O benchmarking, and log monitoring, all visualized and executed in Python using Google Colab.

---------------------------------
## Project Objectives
---------------------------------
- Simulate RAM usage and overload detection by shift time.
- Visualize CPU load across hours using crime event density.
- Schedule processes using Priority and Round-Robin algorithms.
- Simulate multithreading using ThreadPoolExecutor.
- Benchmark memory and disk I/O operations.
- Log events like an OS kernel and analyze logs.

---------------------------------
## Technologies & Libraries
---------------------------------
- Python 3 (Google Colab)
- pandas, numpy
- matplotlib, seaborn
- concurrent.futures (ThreadPoolExecutor)
- logging, mmap, tracemalloc, psutil

---------------------------------
## Architecture Flow
---------------------------------
1. [Crime CSV] 
2. [Load DataFrame]
3. [Preprocess Date / Time]
4. [Simulate: Memory | CPU Scheduling | I/O]
5. [Multithreading + Log Monitoring]
6. [Visualization & Analysis]

---------------------------------
## Simulation Features
---------------------------------

1. Memory Management
   - Simulate RAM with shift-based memory caps (e.g., DAY: 50, EVENING: 60).
   - Detect and plot overload using pandas pivot tables and visual charts.

2. CPU Scheduling
   - Priority-based sorting of offenses (HOMICIDE → THEFT).
   - Round-Robin simulation of fair task handling using itertools.cycle.

3. Parallel Processing
   - Use ThreadPoolExecutor to simulate crime task concurrency.
   - Log work time, start/finish timestamps, and steps per task.

4. Benchmarking
   - CPU-bound and GPU-bound operation times.
   - Memory usage via tracemalloc and psutil.
   - Disk I/O using CSV buffered read/write, unbuffered binary, and mmap.

5. Logging System
   - Track simulated OS logs and detect anomalies (e.g., memory spikes).
   - Write and read custom logs for memory events.

---------------------------------
## Visualizations Include
---------------------------------
- Crimes per shift (as CPU load)  
- Overload per day and season  
- Heatmaps of weekday vs. shift  
- Timeline of homicide cases  
- Hourly stacked histograms (parallel threads)  
- Heatmap of high-frequency crimes by hour  

---------------------------------
## How to Run (Colab)
---------------------------------
1. Upload crime CSV to Google Drive (e.g. Crime_Incidents_in_2024.csv).
2. Mount Drive in Colab.
3. Run all cells in order, starting with logging and dataset load.
4. Visual outputs and logs will be displayed or saved in `os_sim_log.txt`.

---------------------------------
File Output
---------------------------------
- `os_sim_log.txt` — Log of simulated system memory and processing events
- `disk_benchmark.csv` — Simulated file I/O benchmark output
