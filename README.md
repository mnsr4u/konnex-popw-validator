# Konnex PoPW Validator

Prototype subnet for validating edge-device telemetry using Proof-of-Physical-Work (PoPW).

## Overview

Konnex PoPW Validator is a lightweight prototype designed to simulate decentralized validation of physical-world telemetry data.

The subnet evaluates:
- GPS consistency
- Signal integrity
- Device telemetry
- Validator scoring

## Architecture

### Components
- Telemetry miners
- Validator nodes
- Mission coordinator
- PoPW scoring engine

### Workflow
1. Edge devices submit telemetry
2. Validators verify signal quality
3. Scores are assigned
4. Rewards distributed on-chain

## Prototype Features

- Simulated telemetry generation
- Validator scoring logic
- Streamlit monitoring dashboard
- Modular validator architecture

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy

## Future Roadmap

- Multi-validator consensus
- Sensor fusion support
- Real-time telemetry ingestion
- Konnex SDK integration
- Mission reputation scoring

## Running Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Research Focus

This prototype explores scalable Proof-of-Physical-Work validation mechanisms for decentralized physical-AI workloads.

## Open Research Tasks

- Distributed validator consensus
- Telemetry anomaly detection
- Reputation-weighted scoring
- Real-time mission verification
