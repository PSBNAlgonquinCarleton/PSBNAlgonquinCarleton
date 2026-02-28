# PSBNAlgonquinCarleton
# PSBN Prototype - Public Safety Broadband Network (Capstone)

A promotional GitHub Pages website for our capstone project: a **dual-band Public Safety Broadband Network (PSBN) prototype** that leverages **Band 14 LTE**, **n77 5G**, and **Multipath TCP (MPTCP)** to evaluate **mission-critical session continuity** during **outages, handovers, and network degradation**.

## What this project is

Public safety communications cannot tolerate session drops during critical operations.

This capstone explores a prototype architecture that:

- Uses **two independent cellular paths** (LTE + 5G)
- Implements **MPTCP** for transport-layer session continuity
- Prepares controlled **link failure and handover scenarios**
- Evaluates continuity using measurable performance metrics
- Aligns with principles of **resilient public safety broadband networks**

## Quick Summary

**Project type:** Capstone prototype  
**Goal:** Maintain usable TCP sessions during disruption  
**Bands:** Band 14 (LTE) + n77 (5G)  
**Transport layer:** Multipath TCP (MPTCP)  
**Testing focus:** link loss, handover, path degradation  
**Outputs:** structured demo scenarios + measurable continuity metrics  

## Website Pages

This repository is deployed as a **GitHub Pages promotional site**.

- `index.html` - Project overview  
- `solution.html` - Methodology and testing workflow  
- `architecture.html` - System architecture and traffic flow  
- `impact.html` - Evaluation framework and metrics  
- `team.html` - Capstone students and advisors  

## Methodology Overview

The prototype workflow follows a structured process:

1. **Dual-band configuration**  
   Establish LTE and 5G interfaces independently.

2. **MPTCP enablement**  
   Configure MPTCP within a Linux-based networking environment.

3. **Disruption scenario preparation**  
   Define controlled events such as:
   - Interface shutdown
   - Handover transitions
   - Path degradation

4. **Evidence collection**  
   Capture results using:
   - Scenario demonstration videos
   - Plots and tables
   - Concise technical summaries

## Demo Scenarios (Planned)

1. **Link Failure → Continuity**  
   Disable LTE or 5G during an active TCP session and observe session behavior.

2. **Handover Under Load**  
   Trigger path transitions during sustained traffic to evaluate stability.

3. **Degraded Path Performance**  
   Introduce latency or bandwidth constraints and measure recovery characteristics.

## Key Metrics (Examples)

- **Session persistence during link failure**
- **Recovery time after disruption**
- **Latency variation across transitions**
- **Throughput distribution across subflows**
- **Packet loss during handover events**

## Technologies Used

- Linux-based networking environment  
- Multipath TCP (MPTCP)  
- LTE (Band 14)  
- 5G (n77)  
- Network monitoring utilities  

## Project Context

This capstone prototype is developed within a research initiative focused on resilient communication architectures for public safety environments.

The repository serves as:

- Capstone documentation  
- Promotional project material  
- Architecture and methodology overview  

## Team
### Capstone Students
- Maxx Kennedy  
- Xander Xu  
- Samarth Doraiswami  

### Advisors
- Wahab Almuhtadi - Algonquin College  
- Jordan Melzer - TELUS  

Carleton University / Algonquin College 

## Project Status

Prototype platform: **In development**  
Testing phase: **Planned**  
Results publication: **Pending evaluation completion**

## Repo Structure
/ (root)
│
├── index.html
├── solution.html
├── architecture.html
├── impact.html
├── team.html
├── style.css
└── assets/
