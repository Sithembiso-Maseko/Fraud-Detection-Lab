[README.md](https://github.com/user-attachments/files/29635802/README.md)
# Real-Time Fraud and Anomaly Detection System for Financial Transactions in Eswatini

This project is a simulation-based fraud detection lab for Eswatini's banking and mobile-money environment.

Because real banking systems and real customer data cannot be used, the project generates synthetic Eswatini-style financial transactions. The system will detect suspicious transactions using machine learning, deterministic fraud rules, PostgreSQL storage, and a Streamlit monitoring dashboard.

## Core Flow

Fake Eswatini Customers
→ Python Transaction Simulator
→ Fraud Detection API
→ PostgreSQL
→ Streamlit Dashboard
→ Optional n8n Telegram Alerts

## First Development Goal

The first goal is to generate a fake transaction dataset and save it as:

data/transactions.csv

## Current System Status

The current prototype supports:

- synthetic Eswatini-style transaction generation;
- Random Forest fraud scoring;
- deterministic fraud rule evaluation;
- FastAPI fraud detection API;
- PostgreSQL transaction and alert storage;
- Streamlit monitoring dashboard;
- n8n Telegram fraud alerts;
- Docker Compose deployment.

## How to Run

```powershell
docker compose up -d
