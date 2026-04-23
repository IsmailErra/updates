# ChainSOC – Automated Decentralized SOC Prototype

## Project Objective

ChainSOC is a simplified SOC prototype built to automate log monitoring across multiple machines.

The system is designed to:

- collect logs
- detect suspicious activity
- generate alerts
- store logs securely
- automate the entire workflow

---

# Architecture

The project uses **3 virtual machines**:

## 1. Target Machine
Represents the monitored system.

Role:
- generates logs
- simulates suspicious activity

Example:

```bash
logger "chainsoc_test_ALERT"
