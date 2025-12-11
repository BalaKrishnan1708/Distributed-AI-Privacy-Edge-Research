# Distributed AI for Privacy-Preserving Edge Computing

## Project Overview
This repository contains the source code, paper drafts, and literature review materials for the research project focused on developing a lightweight and robust distributed AI framework for resource-constrained edge environments with strong privacy guarantees.

## 1. Problem Statement
The proliferation of IoT devices necessitates shifting AI to the edge to reduce latency and bandwidth use. This shift creates a fundamental conflict: the need for collective intelligence via model updates versus the mandate for user data privacy. Existing solutions either violate privacy by exposing raw data or become computationally infeasible for resource-limited edge devices when applying complex privacy-preserving techniques (e.g., Homomorphic Encryption). This research aims to fill the critical gap by balancing **Privacy, Accuracy, and Efficiency** for heterogeneous edge networks.

## 2. Research Objectives (Measurable Goals)
1. To design and implement a novel, lightweight Federated Learning (FL) architecture optimized for efficient gradient aggregation and minimal communication overhead.
2. To integrate an advanced, computationally-efficient Differential Privacy (DP) mechanism to protect individual client updates against inference attacks without significantly degrading model utility.
3. To empirically evaluate the proposed framework against baseline FL and other state-of-the-art methods across key metrics: model accuracy, communication latency, and on-device energy consumption.
4. To demonstrate the framework's superior performance in balancing the Privacy-Accuracy-Efficiency trade-off using real-world, non-IID edge datasets.
