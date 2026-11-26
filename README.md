# Performance Evaluation and Adaptive Workload Distribution in Hybrid Edge-Cloud Architecture for Real-Time IoT-Based Smart Agriculture

## 1. Project Overview

This project evaluates workload distribution strategies in a Hybrid Edge-Cloud architecture for real-time IoT-based Smart Agriculture.

The research compares centralized cloud processing, conventional hybrid edge-cloud processing, and adaptive workload distribution approaches.

## 2. Research Objectives

- Evaluate the performance of centralized cloud and hybrid edge-cloud architectures.
- Compare adaptive workload distribution methods.
- Evaluate traffic prediction models for workload estimation.
- Analyze response time, task completion rate, dropped tasks, and network traffic.

## 3. Prediction Models

The evaluated prediction models are:

- 1D Convolutional Neural Network (1DCNN)
- Long Short-Term Memory (LSTM)
- Transformer
- Transformer with Positional Encoding (Transformer-PE)

## 4. Workload Datasets

Four workload patterns are used:

- Sine
- Triangle
- Sawtooth
- Random

## 5. Workload Distribution Methods

- Cloud-Only
- Conventional Hybrid
- Adaptive Moving Average
- Adaptive LSTM

## 6. Evaluation Metrics

Prediction evaluation:
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Training Time
- Inference Time
- Throughput

Simulation evaluation:
- Average Response Time
- Task Completion Rate
- Dropped Tasks
- Network Traffic

## 7. Experimental Environment

The experiments were conducted using Google Colab with Python and TensorFlow. The GPU environment used an NVIDIA Tesla T4.

## 8. Repository Structure

- `notebooks/`: Experimental Jupyter notebooks.
- `datasets/`: Workload datasets.
- `results/`: Experimental results and figures.
- `src/`: Supporting Python source code.
- `docs/`: Research documentation.

## 9. Reproducibility

Refer to the notebooks and documentation for experiment configurations, data preparation, model training, evaluation, and workload simulation.

## 10. Project Status

Research and experimental evaluation in progress.
