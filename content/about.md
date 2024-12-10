+++
date = '2024-12-10T9:00:00+08:00'
title = 'About Me'
+++

# About Me

## Danxu ZHANG

I'm a final-year Computer Science student at [Nanyang Technological University, Singapore](ntu.edu.sg),
passionate about High Performance Computing (HPC) and Database Systems.

As a member of the [NTU High Performance Computing Team](ntuhpc.org),
I've competed and won awards in several international student competitions,
including achieving the highest Linpack benchmark at SC24.

When I'm not optimizing code or tuning clusters,
you'll find me exploring the world through photography
or immersed in books about history and geography.

Through this blog, I share my experiences in HPC, technical projects, and thoughts on my other interests.

## Current Projects

**HomeLab**.
Deploy HomeLab services and self-hosting with Ansible and Kubernetes,
automate with ESP8266 and Raspberry Pi Pico.

**Multi-Column Vector Search in MyRocks**.
Extend MyRocks, MySQL database with RocksDB storage engine,
to support multi-column topK vector search
by efficiently traversing multiple vector indexes inspired by Microsoft VBase.

## Past Projects

**Accelerating ICON with OpenACC**.
Part of ISC24 Student Competition, accelerated ICON grupel simulation with OpenACC
by parallelizing and offloading computation to GPU,
optimizing memory movements and cache utilization.

**BusTub**.
CMU 15-445 Intro to DBMS Project.

**TextSpotter**.
A Tesseract and EAST Backed Text Detection and Matching library.

**Digital Lung Scoring**.
Full-stack web application for scoring Lung samples using Django and React.

## HPC Competitions

### SC24 @ Atlanta, USA

- **Highest Linpack Benchmark Award**:
achieved 236 TFLOPS with 8x H100 under 4.5 kW power constraints;

- **Hardware and System Administration**: setup and managed a cluster of 3 nodes
connected by 400Gbps Infiniband network,
tuned system performance for benchmarks(HPL, MLPerf, NASA Parallel Benchmark);

- **HPC Application**: configured and ran weather model ICON for global weather simulation,
profiled I/O and optimized MPI communication.

### ISC24 @ Hamburg, Germany

- **Third Place in Online Component**;

- **Hardware and System Administration**: setup and managed a cluster of 3 nodes
connected by 200Gbps Infiniband network,
tuned system performance for benchmarks(HPL, HPCG, HPCC);

- **Coding Challenge**: accelerated weather model ICON's grupel simulation speed 37x times compared to baseline
by parallelizing and offloading computation to GPU and optimizing memory access and cache utilization.

- **HPC Application**: configured and ran fluid simulation application with OpenLB,
compared scalability for both multi-node CPU and GPU.

### 2023 APAC HPC-AI Competition

- **Third Place**

- **HPC Application**: configured and optimized weather model MPAS-atmosphere;

- **AI Application**: optimized Large Language Model Bloom inference.
