# Agentic Kubernetes Security

## Overview
This project demonstrates an open-source, Kubernetes-native Agentic AI workflow that transforms vulnerability alerts into safe, explainable, and human-approved remediation actions.

## Problem
Security tools generate alerts. DevOps teams manually remediate them.
This increases MTTR, operational risk, and alert fatigue.

## Solution
A multi-agent system running on Kubernetes:
- Scans for vulnerabilities
- Correlates runtime context
- Recommends remediation
- Requires human authorization
- Executes and validates fixes

- ## Vector Database for Audit and Reasoning

The system uses a vector database to store historical vulnerability patterns,
remediation decisions, approvals, and execution outcomes.

This enables:
- Explainable recommendations based on past actions
- Faster remediation planning using known-good fixes
- Audit and compliance evidence retrieval
- Trend analysis across environments

The vector database acts as the long-term memory layer for the agentic system.


## Key Principles
- Human-in-the-loop by default
- Explainable recommendations
- Safe execution with rollback
- Kubernetes-native design
- GitOps friendly

## Status
This is a reference architecture and proof-of-concept intended for education and experimentation.
<img width="1171" height="541" alt="Agen-k8s-security drawio" src="https://github.com/user-attachments/assets/5530cf16-ebc7-478f-a59c-72398ab6f081" />
