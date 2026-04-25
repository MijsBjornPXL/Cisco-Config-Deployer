# Cisco-CSR1000v

Repository containing configuration files and automation examples for the **Cisco CSR1000v** virtual router.

## 📘 Overview

This repository is used to store and manage reusable CSR1000v configurations for labs, testing environments, and network automation assignments.

The goal is to keep configurations centralized, version-controlled, and easy to deploy.

---

## 📂 Repository Structure

```text
Cisco-CSR1000v/
│
├── Configs/        # XML / JSON / YANG configurations
└── README.md       # Project documentation
```

---

## ⚙️ Included Configurations

Examples may include:

- Hostname configuration
- Interface IP addressing
- VLAN interfaces
- OSPF routing
- Static routes
- RESTCONF compatible configs
- NETCONF compatible configs
- Full IOS-XE lab deployments

---

## 🚀 Use Cases

This repository can be used for:

- Cisco CSR1000v lab environments
- Network automation testing
- RESTCONF deployments
- NETCONF deployments
- GitHub as Single Source of Truth
- Infrastructure as Code practice

---

## 🔄 Example Workflow

1. Store desired router configuration in this repository
2. Retrieve config using Python or automation tools
3. Push config to CSR1000v via RESTCONF or NETCONF
4. Validate changes
5. Reuse and version future updates

---

## 🧰 Technologies

- Cisco IOS-XE
- Cisco CSR1000v
- RESTCONF
- NETCONF
- YANG Models
- Python
- GitHub

---

## 📌 Notes

- Configurations are intended for educational and lab purposes
- Always verify IP addresses and credentials before deployment
- Test changes in a non-production environment first

---

## 👨‍💻 Author

**Bjorn Mijs**  
GitHub: [MijsBjornPXL](https://github.com/MijsBjornPXL)

---

## ⭐ Version Control

All changes are tracked through GitHub commits for easy rollback and collaboration.