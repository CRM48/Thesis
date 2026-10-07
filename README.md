# Cloud-Native Agentic AI for Personalised Portfolio Decision Support

This repository contains the implementation for my Master's thesis project at ZHAW.

The project looks at how an AI-based portfolio recommendation system can be built and deployed as a cloud-native distributed application. The main focus is on the cloud side of the system, including deployment, scalability, performance, and monitoring.

## Overview

The system has two main parts:

- A user-facing application where users provide portfolio information, preferences, and constraints.
- A background processing pipeline that updates market data and generates signals used by the recommendation system.

The application then uses these inputs to generate and rank possible portfolio recommendations.

## Main Technologies

The current design uses:

- Streamlit
- FastAPI
- LightGBM
- MLflow
- NoSQL storage
- Message broker and background workers
- OpenTelemetry
- Prometheus
- Grafana
- Docker
- Kubernetes / RKE2
- ZHAW OpenStack infrastructure

## Thesis Focus

Most of the evaluation is focused on the cloud deployment and performance of the system. This includes areas such as:

- Request latency and throughput
- Scaling different parts of the application
- Asynchronous processing performance
- Resource usage
- Failure handling
- Monitoring and observability
- Comparing different deployment approaches

## Status

This project is currently under development as part of my Master's thesis.

More information on the architecture, deployment, experiments, and results will be added as the project develops.

## Author

Curtis Mellsop  
MSc Engineering – Computer Science  
ZHAW School of Engineering
