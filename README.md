# PSBNAlgonquinCarleton
# Public Safety Broadband Network (PSBN) Prototype

A GitHub Pages website for our capstone project exploring a **Public Safety Broadband Network (PSBN)** prototype that integrates **Band 14 LTE**, **5G (n77)**, and **multipath protocols (MPTCP)** to evaluate **network resilience and session continuity** under real-world disruptions.

---

## Overview

Public safety communications must remain reliable in environments where networks are **dynamic, heterogeneous, and sometimes unavailable**.

This project investigates how **multipath transport protocols**, particularly **Multipath TCP (MPTCP)**, can improve:

- **Reliability**
- **Throughput**
- **Adaptability**
- **Session continuity**

The work is conducted using a **PSBN testbed environment**, where Band 14-enabled devices are combined with additional network technologies.

---

## Project Objective

The goal of this project is to:

> **Experimentally evaluate whether TCP-based applications remain usable during disruptions such as link failure, handover, and degraded network conditions.**

Rather than building a final system, this project focuses on:

- **Evaluating multipath communication behavior**
- **Understanding performance under failure scenarios**
- **Demonstrating continuity using real applications**

---

## Key Concepts

- **Public Safety Broadband Network (PSBN)**
- **Band 14 LTE (public safety spectrum)**
- **5G n77**
- **Multipath TCP (MPTCP)**
- **Heterogeneous network environments**
- **Transport-layer session continuity**

---

## Methodology (High-Level)

1. Establish baseline connectivity across available networks  
2. Enable multipath communication (MPTCP)  
3. Introduce controlled disruptions:
   - Link failure
   - Handover events
   - Network degradation  
4. Measure system behavior and application-level impact  

---

## Demo Scenarios (Planned)

- **Link Failure During Active Session**  
  Evaluate whether sessions remain active when a network path is lost  

- **Handover Under Load**  
  Observe performance during transitions between networks  

- **Degraded Network Conditions**  
  Analyze how traffic adapts when one path is weakened  

---

## Key Metrics

- **Session continuity**
- **Recovery time**
- **Throughput stability**
- **Application usability during disruptions**
- **Failover consistency**

---

## System Approach

The prototype operates in a **multi-network environment**, where:

- Band 14 LTE acts as a **public safety anchor network**
- Additional networks (e.g., 5G, WiFi) provide **complementary connectivity**
- MPTCP enables **simultaneous use of multiple paths**

This approach reflects real-world conditions where **PSBN is not the only available network**.

---

## Website Structure

This repository is deployed using **GitHub Pages**.

- `index.html` — Overview + abstract + trailer  
- `solution.html` — Methodology and workflow  
- `architecture.html` — System components and traffic flow  
- `impact.html` — Metrics and evaluation focus  
- `team.html` — Students and advisors  

---

## Project Status

This project is currently **in development**.

- Prototype setup: in progress  
- Scenario testing: planned  
- Results and media: to be added  

---

## Team

**Capstone Students**
- Maxx Kennedy  
- Xander Xu  
- Samarth Doraiswami  

**Advisors**
- Wahab Almuhtadi (Algonquin College)  
- Jordan Melzer (TELUS)

---

## Acknowledgement

This project is supported by a **government-funded research initiative** and conducted within the **Algonquin College PSBN testbed environment**.

---

## Deployment

This site is intended for deployment on **GitHub Pages** and serves as promotional material for:

- Capstone evaluation
- Academic presentation
- Industry demonstration

---

## Future Work

- Experimental validation across more network types  
- Evaluation of additional multipath protocols (e.g., QUIC-based approaches)  
- Expanded real-world public safety scenarios  

---
