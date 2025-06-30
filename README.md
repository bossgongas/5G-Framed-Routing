# 🚀 5G Framed Routing – Open5GS Extension

**Academic project** developed in collaboration with **Altice Labs**, under the course **Projeto II** from the **Bachelor’s Degree in Electrical and Computer Engineering** at the **University of Coimbra**.

> 🏫 **University of Coimbra** – DEEC  
> 🧠 **Course:** Projeto II (2022/2023)  
> 🤝 **In partnership with:** Altice Labs  
> 👨‍💻 **Authors:** Gonçalo Bastos, Leonardo Cordeiro  
> 👩‍🏫 **Supervisor:** Prof. Maria Medeiros  
> 🧑‍💼 **Industry Mentors:** Eng. Francisco Fontes, Eng. Miguel Freitas

---

## 📌 Overview

This project implements and validates the **Framed Routing** feature in **Open5GS**, an open-source 5G Core, enabling a 5G User Equipment (UE) to operate as a **router for subnets**. The goal is to bypass NAT and provide **end-to-end reachability** to devices behind the UE.

Framed Routing allows the allocation of entire **IPv4/IPv6 subnets** to a UE, and ensures traffic is routed directly through the UPF without address translation.

---

## 🧠 Objectives

- ✅ Validate Framed Routing in a simulated 5G environment using **Open5GS** and **UERANSIM**
- ✅ Assign subnets to UEs via WebGUI and **MongoDB**
- ✅ Modify **SMF**, **UPF**, and WebUI components to handle static route provisioning
- ✅ Investigate compliance with **3GPP northbound APIs** (e.g. CAPIF)
- ✅ Demonstrate bidirectional IP connectivity through configured subnets
- 🔜 (Future work) Automate user provisioning and monitoring

---

## 🛠️ Technologies Used

- ⚙️ [Open5GS](https://open5gs.org/)
- 📶 [UERANSIM](https://github.com/aligungr/UERANSIM)
- 🗃️ MongoDB + MongoDB Compass
- 🌐 WebGUI (custom modified)
- 🐧 VirtualBox (5 VMs)
- 🛜 3GPP standards TS23.501, TS24.501, etc.

---

## 📁 Project Files

All documentation can be found in the [`/docs`](./docs) folder:

- `01_project_proposal.pdf` – Initial project proposal  
- `02_project_pitch.pdf` – Pitch and concept presentation  
- `03_mid_term_report.pdf` – Mid-term technical report  
- `04_final_report.pdf` – Final report with detailed implementation  
- `05_presentation.pdf` – Final presentation slides  

---

## System Diagram

![image](https://github.com/user-attachments/assets/bb83b717-c3ad-4b37-89b0-b59f798393b6)

![image](https://github.com/user-attachments/assets/aa49a695-c191-497b-a106-58efd0fa3498)

## Implementation Diagram

![image](https://github.com/user-attachments/assets/6784a146-31c3-4556-bdc2-eeeb23b293cc)

![image](https://github.com/user-attachments/assets/5f765fb4-9da1-4bba-b047-ae6a0173857b)


