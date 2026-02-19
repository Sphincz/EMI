# Engineering of Intelligent Models (MLOps & LLMOps)
This repository contains the source code, lecture materials, slides, and practical resources for the course **Engineering of Intelligent Models (MLOps & LLMOps)**, offered in the Postgraduate Programme in Applied Machine Learning.
The course focuses on the engineering, operationalisation, and lifecycle management of machine learning systems, covering reproducibility, orchestration, deployment, monitoring, and LLM operations.

## Course Overview
(S = Synchronous Class, AS = Asynchronous Class)

| Module | Class | Type | Topics                                     |
|--------|-------|------|--------------------------------------------|
| M1     | 1     | S1   | Introduction to MLOps                      |
|        |       |      | ML Lifecycle & Production Challenges       |
|        |       |      | CRISP-ML(Q)                                |
|        | 2     | AS1  | MLOps Ecosystem Overview                   |
|        |       |      | Experiment Tracking (`MLflow`)             |
|        |       |      | Tooling Landscape                          |
| M2     | 3     | AS2  | Data Versioning & Reproducibility          |
|        |       |      | Project Structuring with `DVC`             |
|        | 4     | AS3  | Experiment Management                      |
|        |       |      | Configuration Management with `Hydra`      |
|        | 5     | S2   | Governance & Traceability                  |
|        |       |      | Integrating `DVC` ↔ `MLflow`               |
| M3     | 6     | AS4  | Workflow Orchestration                     |
|        |       |      | Apache Airflow (DAGs)                      |
|        | 7     | AS5  | Pipeline Automation                        |
|        |       |      | Ingestion, Training & Evaluation Pipelines |
|        | 8     | AS6  | Tracking & Observability                   |
|        |       |      | Logs, Metrics & Model Artefacts            |
| M4     | 9     | S3   | Model Lifecycle Management                 |
|        |       |      | Model Registry & Versioning                |
|        | 10    | AS7  | Model Serving & Monitoring                 |
|        |       |      | API Development with `FastAPI`             |
|        |       |      | Containerisation with `Docker`             |
|        |       |      | Drift & Monitoring Concepts                |
| M5     | 11    | S4   | Introduction to LLMOps                     |
|        |       |      | LLM Lifecycle & Tracing                    |
|        | 12    | AS8  | Prompt Management & Evaluation             |
|        |       |      | Reliability & Responsible LLM Deployment   |

## Learning Objectives
By the end of this course, students will be able to:
-   Design reproducible and traceable machine learning systems.
-   Implement automated ML pipelines with orchestration mechanisms.
-   Deploy and monitor machine learning models in production environments.
-   Manage model lifecycle transitions and version control.
-   Understand the operational challenges associated with Large Language Models (LLMs).
-   Apply MLOps principles to real-world ML engineering scenarios.

## Repository Structure
Each module has its own directory containing lecture materials, slides, code examples, and laboratory exercises.
```
├── M1_MLOps_Foundations/
├── M2_Design_Data_Model_Engineering/
├── M3_Model_Orchestration_Automation/
├── M4_Operations_Deployment_Monitoring/
├── M5_LLMOps_Essentials/
├── projects/
├── slides/
└── resources/
```

### Directory Description
-   `M1_*`: Foundations, lifecycle concepts, tracking introduction
-   `M2_*`: Reproducibility, data versioning, configuration management
-   `M3_*`: Pipeline orchestration and automation
-   `M4_*`: Deployment, serving, monitoring
-   `M5_*`: LLMOps concepts and evaluation

## Core Tools Used in This Course
The course adopts widely used industry-standard tools:
-   **MLflow** – Experiment tracking and model registry
-   **DVC** – Data and pipeline versioning
-   **Hydra** – Configuration management
-   **Apache Airflow** – Workflow orchestration
-   **FastAPI** / **LitServe** – Model serving via REST APIs / LLM-specific serving
-   **Docker** – Containerisation for reproducibility

## Recommended Python Environment
To ensure reproducibility and compatibility:
-   Python 3.13+
-   Virtual environment using `conda`, `venv`, or `uv`
-   Core libraries:
    -   `mlflow`
    -   `dvc`
    -   `hydra-core`
    -   `apache-airflow`
    -   `fastapi`
    -   `uvicorn`
    -   `docker`
    -   `pandas`, `scikit-learn`, `prophet`, `transformers` (for LLMs)
-   Jupyter Notebook or VS Code for development

## Capstone Objective
Throughout the course, students progressively build an end-to-end production-ready ML system, integrating:
-   Reproducible experimentation
-   Automated pipelines
-   Model registry
-   API-based serving
-   Monitoring strategies

The final system reflects a complete MLOps lifecycle implementation.

## Academic Context
This repository is intended for educational purposes within the postgraduate programme in Applied Machine Learning.  
It emphasises engineering discipline, reproducibility, and production-readiness rather than algorithmic modelling alone.