# Real-Time Monitoring and Alerting System using Splunk 🚀

## 📌 Project Overview
As a recent graduate focusing on backend data and automation, I developed this project to demonstrate the power of **Log Analysis** and **Operational Intelligence**. This system ingests live data, processes it using **SPL (Search Processing Language)**, and triggers automated responses via **Python** scripts.

The goal of this project is to provide a "Single Pane of Glass" for monitoring system health and identifying anomalies before they become critical failures.

---

## 🛠️ Technical Stack
* **SIEM/Monitoring:** Splunk Enterprise
* **Automation:** Python (Alert Action Scripts)
* **Data Source:** SQL Database Logs & System Event Logs
* **Query Language:** SPL (Splunk Search Processing Language) & SQL

---

## 🌟 Key Features
* **Real-Time Dashboards:** Visualizing high-frequency data (CPU usage, Error rates, Traffic spikes).
* **Advanced SPL Querying:** Utilized logic similar to **SQL Joins and Aggregations** to filter through thousands of raw log entries.
* **Automated Alerting:** Configured custom alerts that trigger **Python scripts** to log incidents or send notifications.
* **Database Integration:** Correlated Splunk log data with **SQL database** records to identify specific user-impacted errors.

---

## 📂 Project Structure
```text
├── dashboards/             # XML source code for Splunk Dashboards
├── scripts/                # Python scripts for automated alert actions
├── queries/                # A collection of useful SPL and SQL queries used
├── logs/                   # Sample log data used for ingestion
└── README.md
