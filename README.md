# gcp-security-demos
Mini projects using Google Cloud IAM, VPC, firewall rules, and security tools
# GCP Security Demos

This repository contains mini-projects and configurations exploring **security in Google Cloud Platform (GCP)**—including IAM, firewall rules, VPC segmentation, and basic threat prevention techniques.

---

### Learning Goals

- Understand and apply GCP Identity and Access Management (IAM)
- Configure secure Virtual Private Cloud (VPC) networks
- Set up firewall rules to control traffic flow
- Use Cloud Logging and Monitoring to track activity
- Test basic incident detection and prevention scenarios

---

###  Tools & Services Used

- **Google Cloud Console / Cloud Shell**
- **IAM Roles & Service Accounts**
- **Cloud Logging & Monitoring**
- **VPCs, Subnets, and Firewalls**
- **Cloud Armor (Web App Firewall)**

---

###  Example Projects

####  IAM Role Testing
- Created custom roles with least privilege
- Tested access boundaries using service accounts

####  VPC Firewall Demo
- Built secure network with multiple subnets
- Created deny-all by default, then allow explicit ports

####  Log Monitoring Lab
- Enabled Cloud Audit Logs
- Simulated user activity and visualized alerts in Cloud Logging

####  Cloud Armor (Basic Rules)
- Set up basic WAF rules to protect a test web app

---

###  Repo Structure

```plaintext
gcp-security-demos/
├── iam-demo/
│   └── least-privilege-role.md
├── vpc-firewall-demo/
│   └── firewall-rules-setup.md
├── cloud-logs-lab/
│   └── audit-logging-walkthrough.md
└── cloud-armor-demo/
    └── basic-waf-setup.md
```

---

###  Next Steps

- [ ] Add screenshots of IAM role permissions
- [ ] Record metrics for log-based alerts
- [ ] Map rules to MITRE ATT&CK Cloud Matrix

---

###  Author

**Rumbidzai **  
Google Cybersecurity Certified | Cloud Security Enthusiast 

---

> “The cloud is just someone else's computer—lock it down like it's yours.”
