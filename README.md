# bandit-devsecops-lab

# Detecting Security Flaws Using Bandit in a GitHub Actions CI Pipeline

**Author:** Rupak Rajbanshi  
**Module:** Skills Development III  
**Lab:** DevSecOps – Lab 3  
**Date:** December 2025

## Overview
This repository demonstrates how Static Application Security Testing (SAST)
can be integrated into a CI pipeline using Bandit. The application is
intentionally vulnerable for educational purposes.

## Tools Used
- Python 3.10
- Bandit (SAST)
- pylint
- pytest
- GitHub Actions

## CI Pipeline Stages
1. Code quality analysis (pylint)
2. Security scanning (Bandit)
3. Functional testing (pytest)

## Key Learning Outcome
Functional tests may pass even when security vulnerabilities exist.
Integrating SAST tools enables early detection of insecure coding practices.

⚠️ **Warning:** This code is intentionally insecure. Do NOT use in production.
