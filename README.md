# 🛠️ Industrial Predictive Maintenance System

An end-to-end Machine Learning pipeline designed to forecast industrial equipment failures using longitudinal telemetry data. This project implements advanced data cleaning, time-series feature engineering, class-imbalance-aware modeling, and business-cost optimization to minimize unscheduled downtime while controlling maintenance expenses.

---

## 📌 Problem Statement & Business Context

In modern manufacturing, unscheduled equipment downtime causes significant financial losses due to halted production cycles, high emergency intervention costs, and workforce safety risks. 

This project aims to build a **binary classification system** (`failure = 1` vs `failure = 0`) using daily telemetry metrics to predict failures before they occur, enabling proactive, scheduled maintenance interventions.

---

## 🚨 Critical Technical Constraints

* **Class Imbalance:** Telemetry datasets suffer from severe class imbalance (~0.09% failure rate).
* **Selection Metric Constraint:** **Raw classification accuracy is strictly invalid** for final model selection. Models are evaluated using **PR-AUC (Average Precision)**, **Recall**, and **Total Maintenance Cost Optimization**.

---

## 📂 Repository Structure# Industrial-Predictive-Maintenance-System
In modern manufacturing, unscheduled equipment downtime causes significant financial losses due to halted production cycles, high emergency intervention costs, and workforce safety risks.
