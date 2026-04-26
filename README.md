# 🏗️ vSphere Resilience Architecture

> Designing a Self-Healing Enterprise Virtual Infrastructure

---

## 📄 Full Documentation

📘 Detailed explanation available here:  
👉 **[View Full Project Documentation (PDF)](./vSphere_Resilience_Architecture.pdf)**

---

## 💡 Project Overview

This project focuses on designing and implementing a **highly available, self-healing enterprise virtual infrastructure** using VMware vSphere.

The goal was to eliminate **single points of failure**, ensure **zero downtime for critical workloads**, and enable **intelligent resource optimization**.

---

## 🧱 Architecture Summary

- **Cluster Name:** Snagim Cluster  
- **Hosts:** 3 ESXi Servers  
- **Management:** vCenter Server Appliance (VCSA)  
- **Storage:** NFS Shared Datastore  
- **Network:** Dedicated VMkernel interfaces (Management, vMotion, FT)

---

## 🚀 Key Features

### 🔹 High Availability (HA)
- Automatic VM restart on host failure  
- Rapid recovery and service continuity  

### 🔹 Fault Tolerance (FT)
- Zero downtime for critical workloads  
- Live shadow VM for instant failover  

### 🔹 Distributed Resource Scheduler (DRS)
- Fully automated workload balancing  
- Optimized CPU & memory utilization  

### 🔹 vMotion
- Live migration of running VMs  
- No service interruption  

---

## ⚙️ Core Components

- VMware ESXi Hosts  
- vCenter Server Appliance (VCSA)  
- NFS Shared Storage  
- VMkernel Networking  
- Active Directory Integration (LDAP)

---

## 🔐 Security & Identity

- Integrated with Active Directory (iti.local)  
- Centralized authentication (SSO)  
- Role-Based Access Control (RBAC)  

---

## 🔄 Automation & Optimization

- Dynamic load balancing using DRS  
- Intelligent failover handling using HA  
- Real-time synchronization via FT  

---

## 🧪 Tested Scenarios

- Host failure simulation → ✅ Automatic VM recovery  
- Live migration (vMotion) → ✅ Zero downtime  
- Fault Tolerance activation → ✅ Continuous availability  

---

## 🧠 What I Learned

- Designing enterprise-grade infrastructure  
- Implementing high availability and fault tolerance  
- Managing virtualization at scale  
- Integrating identity and security into infrastructure  
- Building resilient and production-ready environments  

---

## 🛠️ Tech Stack

- VMware vSphere (ESXi, vCenter)  
- NFS Storage  
- Linux (NFS Server)  
- Windows Server (Active Directory)  

---

## 🤝 Team Collaboration

Developed as part of ITI Professional Training Program

---

## ⭐ Final Note

This project demonstrates building **reliable, scalable, and fault-tolerant infrastructure** aligned with real-world enterprise environments.
