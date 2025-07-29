# 📊 Simulation-Based Analytics Projects: Public Transit & Global Supply Chains

This repository showcases two advanced projects built using **System Dynamics Modeling** and **Predictive Analytics with Generative AI**. Both projects focus on solving real-world challenges in transportation systems—one in the context of **urban public transit** and the other in **global logistics optimization**.

---

## 🚇 Project 1: STM Montréal Public Transit – System Dynamics Simulation

### 🎯 Introduction & Scope

Public transportation is central to sustainable urban development. Montréal's **Société de transport de Montréal (STM)** aims to boost accessibility, quality, and efficiency in transit services. This project models the **interdependencies between ridership levels and service quality**, allowing STM to explore, simulate, and optimize social sustainability outcomes.

We developed a **System Dynamics Model** in **AnyLogic** to simulate how ridership levels and service quality evolve over time based on various influencing factors.

### 🧠 What is System Dynamics?

System Dynamics is a modeling methodology for analyzing and simulating complex systems using:
- **Stocks & Flows**: Accumulations and rates of change
- **Feedback Loops**: Reinforcing and balancing behaviors
- **Time Delays**: Lagged effects across system components

In this model:
- **Stocks**: Ridership Level, Service Quality Score
- **Flows**: Inflows and outflows based on user behavior and operational changes

### 📌 Project Objective

- Understand interdependencies between **service quality** and **ridership**
- Identify **critical variables** (e.g. satisfaction, security, infrastructure)
- Simulate impacts of various policy scenarios
- Provide actionable strategies for STM to increase ridership and optimize quality

### 🔍 Key Parameters (2006–2014 STM Data)

- Population growth rate  
- Accessibility rate  
- Fare incentives  
- Security perception & officer training  
- Paratransit availability  
- Infrastructure improvement  
- Network coverage  
- Service interruptions  
- Fleet aging

### 🔄 Model Architecture

#### 🟦 Ridership Subsystem
- **Inflow Drivers**: Customer satisfaction, discounted fare incentives, accessibility rate, population growth, bus availability  
- **Outflow Drivers**: Fare increases, dissatisfaction, service interruptions

#### 🟨 Service Quality Subsystem
- **Improvement Factors**: Total ridership feedback, security training, infrastructure upgrades, coverage expansion  
- **Degradation Factors**: Old vehicle fleets, interruptions

The two systems are interlinked via causal relationships to allow bidirectional influence.

### 📈 Outcome

- A flexible, scenario-driven simulation model
- Insights into feedback structures driving transit behavior
- Identification of bottlenecks and leverage points for STM policy makers
- Visualization of long-term trade-offs between service investment and ridership growth

### 📁 Key Files

| File                               | Description                                      |
|------------------------------------|--------------------------------------------------|
| `/models/stm_anylogic_model.alp`   | Complete STM simulation in AnyLogic             |
| `/data/stm_indicators_2006_2014.csv`| Historical transit performance indicators       |
| `/docs/STM_Model_Report.pdf`       | Full project report and validation notes         |

---

## 🚚 Project 2: Optimizing Global Supply Chains with Predictive Analytics

### 🧭 Background

A multinational logistics company operating across continents faced compounding inefficiencies in managing its supply chain, impacted by:
- Fluctuating demand
- Weather disruptions
- Inventory imbalances
- Route planning failures
- Cost overruns and delayed deliveries

Traditional linear planning approaches were no longer sufficient.

### 🚀 Predictive Analytics Solution

A robust **AI-powered predictive analytics engine** was deployed using:
- **Digital Twin Modeling** – mirroring the real supply chain in simulation  
- **Monte Carlo Simulations** – scenario testing for uncertainty  
- **Reinforcement Learning** – continuous feedback optimization  
- **ERP, GPS & Weather API Feeds** – real-time input layers


## 🧩 Business Challenge

A global logistics enterprise with a sprawling network of suppliers, warehouses, and transportation hubs faced mounting challenges in managing its supply chain effectively. The traditional approach—based on historical data and static planning—was increasingly ineffective in dealing with:

- Fluctuating demand across markets  
- Weather-related disruptions  
- Geopolitical events and trade restrictions  
- Inventory imbalance and overstocking  
- Missed delivery timelines and higher freight costs  

These limitations threatened service-level commitments, increased operational costs, and eroded customer satisfaction.

---

## 🧠 Solution Overview

To address these dynamic challenges, the company implemented a **predictive analytics engine** built on **generative AI and machine learning**. Key components of the solution:

### 🚀 Technology Stack
- **Python & TensorFlow** – model development  
- **Reinforcement Learning (RL)** – for continuous optimization  
- **Monte Carlo Simulations** – to assess uncertainty and risk  
- **Digital Twin Architecture** – virtual replication of the supply chain  
- **ERP Integration** – real-time inputs from inventory and demand systems  
- **Weather & GPS APIs** – to monitor live disruption risks  

### 🧪 Model Capabilities
- Created a **digital twin** of the supply chain to simulate thousands of scenarios  
- Integrated **real-time data feeds** from multiple sources  
- Forecasted **bottlenecks, delays, and excess inventory** before they occurred  
- Recommended **optimal routing, load balancing, and inventory reallocation**

---

## 💡 Business Impact

| Metric                        | Before (Baseline) | After (With AI)  |
|------------------------------|-------------------|------------------|
| Transportation Costs         | Baseline          | 🔻 10% reduction |
| Inventory Holding Costs      | Baseline          | 🔻 5% reduction  |
| On-Time Delivery Rate        | 90%               | 🔺 93%           |
| Fleet Utilization Efficiency | 72%               | 🔺 84%           |

This resulted in:
- Multi-million dollar savings in logistics spending  
- Increased **resilience** during supply chain shocks  
- Higher **customer satisfaction** and **on-time delivery reliability**  
- A replicable model for **scenario planning** across geographies  

---

## 📉 Architecture Overview

```
+----------------------+       +---------------------+
|  External APIs       |<----->|  Data Ingestion     |
|  (Weather, GPS, ERP) |       |  + Streaming Input  |
+----------------------+       +---------------------+
         |                              |
         v                              v
+----------------------+       +---------------------+
| Digital Twin Engine  |<----->| Predictive Models   |
| (Simulations)        |       | (Monte Carlo, RL)   |
+----------------------+       +---------------------+
         |                              |
         v                              v
+----------------------+       +---------------------+
| Decision Layer       |       | Dashboard + Alerts  |
| (Route & Stock Plans)|       | (Power BI / Grafana)|
+----------------------+       +---------------------+
```
<img width="1024" height="1536" alt="Supplychain Ai integration" src="https://github.com/user-attachments/assets/592f952d-a851-403f-b66a-7112efb96ed1" />

---

## 🔍 What You’ll Find in This Repo

| File/Folder              | Description                                      |
|--------------------------|--------------------------------------------------|
| `/notebooks/`            | Jupyter notebooks for model experimentation      |
| `/data/`                 | Sample synthetic data for demonstration          |
| `/models/`               | Scripts for reinforcement learning and MCS       |
| `README.md`              | You're here.                                     |
| `digital_twin_diagram.png` | Architecture schematic of supply chain engine   |

---

## 📚 Learnings & Highlights

- Predictive analytics becomes powerful when combined with **real-time decisioning**
- **Digital twins** enable safe experimentation before real-world rollouts
- Reinforcement learning adapts rapidly to volatile logistics conditions
- This solution template is extensible to industries like **retail, pharma, manufacturing**

---


