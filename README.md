# Multi-Threading

## Overview

This Python script benchmarks the performance of matrix multiplication using multi-threading. It generates 100 random matrices of size 1000x1000 and multiplies each of them with a constant matrix of the same size. The performance is measured for different numbers of threads ranging from 1 to 8.

## Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- Pandas
- psutil

The script will generate the following outputs:
    - Table showing the time taken for matrix multiplication with different numbers of threads.
    - Graph plotting the matrix multiplication time versus the number of threads.
    - CPU usages (if available).
    
## Results Interpretation

- **Time Taken (Sec):** Indicates the time taken for matrix multiplication in seconds. Lower values indicate better performance.
- **Number of Threads:** The number of threads used for matrix multiplication. Higher values may improve performance up to a certain point, depending on the system's capabilities.
- **CPU Usage:** Percentage of CPU being used.

## Result Graph
![multi-threading](https://github.com/MannatPruthi/Multi-Threading/assets/91721574/5fe7af89-5b9c-49f1-8cb4-0b6aa725e4be)

## Result Table
![Result Table](https://github.com/MannatPruthi/Multi-Threading/assets/91721574/fb9c9dcc-8e6e-41c8-ae88-e7e11ce59358)

## Result DataFrame

| Threads | Time Taken (Sec) | CPU Usage (%) |
|---------|------------------|---------------|
| 1       | 500              | 20            |
| 2       | 275              | 35            |
| 3       | 200              | 45            |
| 4       | 150              | 55            |
| 5       | 250              | 60            |
| 6       | 300              | 65            |
| 7       | 350              | 70            |
| 8       | 400              | 75            |

**Submitted by:**

Mannat Pruthi


B 3CS6


102117185
