# Multicore and GPU Programming: Course Project

Welcome to the **Multicore and GPU Programming** course project phase!

This repository contains the guidelines for your final project. This is a unique opportunity to apply your knowledge of parallel computing, CUDA, and performance engineering to solve real-world systems problems.

## Project Phase: Proposal
**Current Status:** `Open for Submission`  
**Deadline:** December 31, 2025



## Project Topics

You must select **one** of the following three project topics. 

> **Important:** Please read the full **Topic Document** linked below for your chosen topic. It contains critical details on requirements, scope, and evaluation.

### [Topic 1: Training a CNN From Scratch Using CUDA](./Topic_1.md)
Implement and train a Convolutional Neural Network (CNN) entirely using CUDA. You must treat this as a **GPU systems problem first**, focusing on memory access patterns and kernel efficiency rather than just machine learning accuracy.
* **Read the full details:** [`Topic_1.md`](./Topic_1.md)

### [Topic 2: N-Body Simulation Using CUDA](./Topic_2.md)
Implement a general N-body simulation (e.g., a Solar System with a comet) focusing on the performance of computing $O(N^2)$ pairwise interactions. The goal is to maximize scalability and optimize global memory traffic.
* **Read the full details:** [`Topic_2.md`](./Topic_2.md)

### [Topic 3: Mixed-Precision Inference on GPUs](./Topic_3.md)
Analyze the performance impact of mixed-precision inference by choosing one of two sub-options: comparing **CUDA Cores vs. Tensor Cores**, or implementing **Row-Wise Scaling**. The primary objective is performance analysis and numerical accuracy tradeoffs.
* **Read the full details:** [`Topic_3.md`](./Topic_3.md)



## Team Formation

* **Individual:** You may work alone.
* **Pairs:** Teams of two are allowed and encouraged.
* **Trios:** Teams of three are **only** permitted if the project proposal is sufficiently complex and ambitious (must be justified).



## Proposal Submission

Your proposal should define your project based on the specific requirements outlined in your chosen **Topic Document**. 

Please refer to the **"Proposal requirement"** section inside the specific file (e.g., `Topic_1.md`) to know exactly what you need to address regarding your architecture, strategy, and timeline.

Good luck! We look forward to seeing your solutions.
