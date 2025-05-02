# Crime_OS
Ploysod
ps__2
ออนไลน์

sushi_cutie — 13/4/2566 15:50
https://discord.gg/3fDnUnQy
Ploysod
 เริ่มการโทรเป็นเวลา 3 ชั่วโมง — 24/6/2566 20:39
sushi_cutie — 24/6/2566 20:45
Sushicutiess#7173
ภาพ
Ploysod — 24/6/2566 22:14
ไม่ได้ยินอ่อ
sushi_cutie — 24/6/2566 22:14
ไม่ได้ยินนน
Ploysod — 24/6/2566 22:14
ตุยละ
Ploysod — 24/6/2566 22:29
คือช่วงนี้มันจะไม่ได้ยินเรอะ
sushi_cutie — 24/6/2566 22:29
ช่าย
sushi_cutie — 24/6/2566 23:29
ยังอยู่ป้ะ
ไม่ได้ยินน
Ploysod — 24/6/2566 23:29
อยู่ๆ
ไม่ได้ยินเลยอ่อ
sushi_cutie — 26/6/2566 20:03
เสร็จแล้วโทรมานะๆ
Ploysod
 เริ่มการโทรเป็นเวลา 2 ชั่วโมง — 26/6/2566 20:03
sushi_cutie — 26/6/2566 20:32
https://twitter.com/baekdoracute/status/1672605533432582144?s=61&t=cIrOH4nk-BRrSIb2z1Mn9Q

🌈🧸~คุณพยอน~🧸🌈 (@baekdoracute)
อยากจะอยู่กับผู้คนบนดินนนนนนนน~🥬🥬

อยากจะยลยิน คนเต้นรำอย่างไรหนอ~💃🏻💃🏻

ว่าแต่มนุดใช้อะไรเดินนะ “อ๋อ ไช เท้า” 🥬🥬
Likes
5097
Retweets
16326
ภาพ

Twitter•24/6/2566 21:00
sushi_cutie — 3/9/2566 13:08
https://docs.google.com/document/d/1LxVov8bb7TS89fAJe10A-0y1qP2sqCasXp4-I5Ci3nU/edit?usp=sharing
Google Docs
Ethics
Ploysod — 3/9/2566 13:12
This commandment is about respecting other people’s privacy and space. We should not go snooping around in someone else’s computer files or folders without permission. Including things like spamming someone’s email inbox or deliberately crashing someone’s computer.
sushi_cutie
 เริ่มการโทรเป็นเวลา 2 ชั่วโมง — 12/1/2567 21:02
sushi_cutie
 เริ่มการโทรเป็นเวลา 3 ชั่วโมง — 13/1/2567 22:07
Ploysod — 17/5/2567 21:55
https://discord.gg/hfmc2ggR
sushi_cutie — 18/5/2567 1:29
https://discord.gg/wutheringwaves
Tap now for a chance to claim 【Violet-Feathered Heron (5-star)】 for your account! 
Wuthering Waves, a brand new open-world ARPG #WutheringWaves
https://webevent-echoes-a.kurogames-global.com/share/060a5046a897ef70dee350e71de0fd98c3081461
Wuthering Waves Echo Summon Event
Get 5-Star Echo and Claim Astrites

https://webevent-echoes-a.kurogames-global.com/share/729ba4185f49cf726aa312793b550dcd52172ec5
Wuthering Waves Echo Summon Event
Get 5-Star Echo and Claim Astrites

Ploysod — 26/9/2567 18:18
อันนี้อันที่ต้องส่งอีกอัน
ประเภทไฟล์ที่แนบ: archive
WS_4.zip
647.56 KB
sushi_cutie — 26/9/2567 18:19
ขอบคุณคับบ
sushi_cutie — 26/10/2567 15:55

USE tinycollege;
-- Q1
INSERT INTO professor (EMP_NUM, EMP_FNAME, EMP_LNAME, EMP_DOB, DEPT_CODE)
VALUES (101, "Charles", "Xavier", 1975-5-4, "CIS");
ขยาย
L11ID6688071.sql
1 KB
Ploysod
 เริ่มการโทรเป็นเวลา 11 นาที — 14/11/2567 23:24
sushi_cutie — 14/11/2567 23:28
choice = input("Which flow control algorithm? (1: Go-Back-N ARQ or 2: Selective-Repeat ARQ): ")

if choice == "1":
    print(f"\nThe total number of frames to be transmitted is {num_frames}.")
    print(f"The loss frames are Frame {', '.join(map(str, loss_frames))}.\n")
ขยาย
message.txt
3 KB
https://colab.research.google.com/drive/1oTRpVf99040zt3ef0pd-kmVwIjGOGUHy?usp=sharing
Google Colab
ภาพ
elif choice == "2":
    print(f"\nThe total number of frames to be transmitted is {num_frames}.")
    print(f"The lost frames are Frame {', '.join(map(str, loss_frames))}.\n")

    print(f"Selective-Repeat ARQ (Window Size = {WsizeSR}; Sequence Number 0 to {MaxSeq})")

    last_ack = 0  # Start the ACK number from 0
    retransmit_q = []  # Store retransmission requests
    nack_q = []  # Store NACK requests

    for i in range(num_frames):

        seq_num = i % (MaxSeq + 1)

        if i in loss_frames:
            # Frame is lost
            print(f"      Frame {i:3d}: Seq No. {seq_num:2d} (Loss)\t\t\t  -")
            nack_q.append(seq_num)  # Queue for retransmission
            retransmit_q.append(i)  # Frame will need to be retransmitted
            if i + 1 == num_frames:  # Last frame loss handling
                print(f"      Frame {i:3d}: Seq No. {seq_num:2d}\t\t\t\tNACK {nack_q[0]:3d}")

        elif nack_q:
            # If there are any NACKs, retransmit the lost frames
            retransmit_frame = nack_q.pop(0)
            retransmit_seq = retransmit_frame % (MaxSeq + 1)
            print(f"      Frame {i:3d}: Seq No. {seq_num:2d}\t\t\t\tNACK {retransmit_seq:3d}")

Now retransmit the frame and send the ACK for the last successful frame
            retransmit_frame = retransmit_q.pop(0)
            retransmit_seq = retransmit_frame % (MaxSeq + 1)
            print(f"      Frame {retransmit_frame:3d}:
sushi_cutie — 13/3/2568 21:52
ประเภทไฟล์ที่แนบ: unknown
ITCS227_Lab08_Assignment_6688071.ipynb
717.03 KB
<?xml version='1.0' encoding='utf-8'?>
<scheme version="2.0" title="" description="">
<nodes>
<node id="0" name="Import Images" qualified_name="orangecontrib.imageanalytics.widgets.owimageimport.OWImportImages" project_name="Orange3-ImageAnalytics" version="" title="Import Images" position="(175.0, 151.0)" />
<node id="1" name="Image Embedding" qualified_name="orangecontrib.imageanalytics.widgets.owimageembedding.OWImageEmbedding" project_name="Orange3-ImageAnalytics" version="" title="Image Embedding" position="(308.0, 153.0)" />
<node id="2" name="Data Table" qualified_name="Orange.widgets.data.owtable.OWTable" project_name="Orange3" version="" title="Data Table" position="(424.0, 149.0)" />... (เหลืออีก 83 KB)
ขยาย
DOGCAT_6688071.ows.xml
133 KB
sushi_cutie — 28/3/2568 13:11
ประเภทไฟล์ที่แนบ: archive
6688071-express.zip
1.28 MB
Ploysod — 25/4/2568 14:47
===============================
 OS Simulation with Crime Data
===============================

This project simulates core **Operating System (OS)** concepts using real-world **crime data** as a dataset. It covers **memory management**, **CPU scheduling**, **multithreading**, **disk I/O benchmarking**, and **log monitoring**, all visualized and executed in Python (Google Colab friendly).
ขยาย
message.txt
4 KB
# 🧠 OS Simulation using Crime Data

> A Google Colab project simulating core **Operating System concepts** using **real-world crime data** — including memory management, CPU scheduling, multithreading, and I/O benchmarking.

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![Colab Ready](https://img.shields.io/badge/Run%20in-Google%20Colab-orange)](https://colab.research.google.com/)
ขยาย
message.txt
2 KB
sushi_cutie — 25/4/2568 16:52
===============================
 OS Simulation with Crime Data
===============================

This project simulates Operating System (OS) concepts using real-world crime data as a dataset. It covers memory management, CPU scheduling, multithreading, disk I/O benchmarking, and log monitoring, all visualized and executed in Python using Google Colab.
ขยาย
message.txt
4 KB
﻿
===============================
 OS Simulation with Crime Data
===============================

This project simulates Operating System (OS) concepts using real-world crime data as a dataset. It covers memory management, CPU scheduling, multithreading, disk I/O benchmarking, and log monitoring, all visualized and executed in Python using Google Colab.

---------------------------------
Project Objectives
---------------------------------
- Simulate RAM usage and overload detection by shift time.
- Visualize CPU load across hours using crime event density.
- Schedule processes using Priority and Round-Robin algorithms.
- Simulate multithreading using ThreadPoolExecutor.
- Benchmark memory and disk I/O operations.
- Log events like an OS kernel and analyze logs.

---------------------------------
Technologies & Libraries
---------------------------------
- Python 3 (Google Colab)
- pandas, numpy
- matplotlib, seaborn
- concurrent.futures (ThreadPoolExecutor)
- logging, mmap, tracemalloc, psutil

---------------------------------
Architecture Flow
---------------------------------
1. [Crime CSV] 
2. [Load DataFrame]
3. [Preprocess Date / Time]
4. [Simulate: Memory | CPU Scheduling | I/O]
5. [Multithreading + Log Monitoring]
6. [Visualization & Analysis]

---------------------------------
Simulation Features
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
Visualizations Include
---------------------------------
- Crimes per shift (as CPU load)  
- Overload per day and season  
- Heatmaps of weekday vs. shift  
- Timeline of homicide cases  
- Hourly stacked histograms (parallel threads)  
- Heatmap of high-frequency crimes by hour  

---------------------------------
How to Run (Colab)
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
message.txt
4 KB
