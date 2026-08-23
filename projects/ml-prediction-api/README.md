# ML Prediction API — FastAPI, Docker & AWS

A production-oriented machine-learning inference service exposing trained prediction models through a REST API and containerized cloud deployment workflow.

## Overview
The project demonstrates the transition from a trained ML model to a deployable backend service. FastAPI provides the API layer, Docker packages the application, and AWS services support deployment and model storage.

## Technology Stack
- Python
- Machine Learning
- FastAPI
- REST API
- Docker
- AWS EC2
- AWS S3

## Architecture
```text
Client
  ↓
FastAPI REST API
  ↓
Validation / Preprocessing
  ↓
Trained ML Model
  ↓
Prediction Response

Docker → AWS EC2
AWS S3 → Model / Object Storage
```

## Highlights
- REST-based model inference
- Input validation and preprocessing
- Dockerized deployment
- AWS EC2 deployment workflow
- AWS S3 integration
- Production-oriented prediction serving

## Reported Performance
The current CV reports testing at **100+ prediction requests per minute**.

## Security
Production deployments should keep credentials and secrets outside source control and use environment variables or a managed secrets service.

## Source Status
This project is documented here because a dedicated source repository is not currently present in the connected GitHub repository list. The README describes the project based on the current CV and portfolio rather than fabricating source code that is not available.

## Author
**Chandrika Bhattacharya** — Data Scientist | AI/ML Engineer

Portfolio: https://chandrika5189.github.io/chandrika-portfolio/
