# AWS EC2 T-Pot Honeypot Deployment

## 📌 Overview

This project demonstrates the deployment of T-Pot honeypot on AWS EC2 to capture real-world internet attacks. The setup exposes multiple honeypot services and visualizes attack data using the ELK stack.

The objective is to simulate a real-world SOC threat monitoring environment.

---

## 🎯 Objectives

* Deploy T-Pot honeypot on AWS EC2
* Capture real-time internet attacks
* Analyze attacker behavior
* Visualize attacks using Kibana
* Perform threat intelligence analysis

---

## 🛠️ Tools & Technologies

* AWS EC2
* Debian Linux
* T-Pot Honeypot
* Elasticsearch
* Logstash
* Kibana
* Cowrie Honeypot
* Dionaea Honeypot
* Honeytrap

---

## ☁️ Cloud Environment

* Cloud Provider: AWS
* Region: eu-north-1
* Instance Type: (Add your instance type)
* OS: Debian Linux
* Security Group: Ports 1-64000 Open

---

## 🏗️ Architecture
<img src="https://github.com/Prashant42125/AWS-EC2-T-Pot-Honeypot-Deployment/blob/main/0.Architecture_diagram.png" width="900">

---

## ⚙️ Workflow

1. Internet attackers scan public IP
2. Traffic allowed via AWS Security Group
3. EC2 instance receives malicious traffic
4. T-Pot distributes traffic to honeypots
5. Cowrie captures SSH brute force
6. Dionaea captures malware attempts
7. Honeytrap collects unknown traffic
8. ELK stack processes logs
9. Kibana visualizes attack dashboards

---

## 🔍 Honeypots Deployed

* Cowrie (SSH Honeypot)
* Dionaea (Malware Honeypot)
* Honeytrap (Generic Honeypot)

---

## 📊 ELK Stack

* Elasticsearch (Data storage)
* Logstash (Log processing)
* Kibana (Visualization)

---

## 📈 Data Collected

* Source IP addresses
* Attack ports
* Countries
* Malware payloads
* Login attempts
* Attack timestamps

---

## 📚 Skills Demonstrated

* Cloud Security Monitoring
* Honeypot Deployment
* Threat Intelligence
* ELK Stack Analysis
* Incident Detection

---

## 👤 Author

Prashant
CEHv13 | SOC Analyst | Blue Team
