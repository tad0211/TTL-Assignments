# Assignment 10 – MLOps Workflow Simulation

## Overview

This assignment demonstrates an **end-to-end MLOps workflow simulation** for an automotive vehicle price prediction system.

The workflow covers experiment tracking, automated quality gates, model versioning, production promotion, containerization, API serving, testing, and CI/CD automation.

## Domain

**Automotive Telemetry Serving, Automated Quality Gates & Production Containerization**

## Objective

The objective is to simulate how a machine learning model can move from experimentation to a production-ready deployment pipeline.

The workflow includes:

- Automotive dataset generation and validation
- Model training and experimentation
- MLflow experiment tracking
- Hyperparameter experimentation
- Model performance evaluation
- Automated production quality gates
- Model registration and versioning
- Production model promotion
- FastAPI model serving
- Docker containerization
- Automated testing
- CI/CD workflow simulation

## MLOps Workflow

```text
Data
  ↓
Data Validation
  ↓
Model Training
  ↓
MLflow Experiment Tracking
  ↓
Model Evaluation
  ↓
Automated Quality Gate
  ↓
MLflow Model Registry
  ↓
Production Promotion
  ↓
FastAPI Model Serving
  ↓
Docker Containerization
  ↓
CI/CD Pipeline
