# Enterprise GRC Automation Lab

## Overview

This project simulates a cloud-based SaaS enterprise environment implementing:

- Continuous compliance monitoring
- Automated evidence collection
- Risk register automation
- Executive-level risk reporting

The lab is aligned conceptually with SOC 2, ISO 27001, and NIST CSF principles.

---

## Simulated Company

Northstar Health SaaS  
Industry: Cloud SaaS handling sensitive customer data  
Region: Canada / United States  
Compliance Target: SOC 2-aligned controls  

---

## Architecture

The architecture includes:

- Microsoft Entra ID (Identity Governance)
- Azure Resource Environment
- Centralized Logging (Log Analytics)
- SIEM (Microsoft Sentinel)
- Azure Policy + Defender for Cloud
- Automated Evidence Storage
- Risk Register
- Executive Dashboard

Architecture Diagram:

![Architecture](01-Architecture/northstar-architecture.png)

---

## Objectives

1. Enforce least privilege identity model
2. Implement continuous configuration compliance
3. Automatically collect audit evidence
4. Convert failed controls into tracked business risks
5. Provide executive risk visibility

---

## Project Structure

01-Architecture – System design diagrams  
02-Terraform – Infrastructure as Code  
03-Policies – Control definitions and mappings  
04-Automation – Evidence pipeline logic  
05-Risk-Register – Risk tracking model  
06-Dashboard – Executive reporting layer  
07-Executive-Report – Board-level snapshot  

---

## Why This Matters

Most organizations struggle with:

- Manual audit preparation
- Configuration drift
- Lack of centralized evidence
- Risk registers disconnected from real security posture

This lab demonstrates an automated governance model designed to reduce operational risk and audit friction.

