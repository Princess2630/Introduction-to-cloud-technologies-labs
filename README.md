# Cloud Technologies - Infrastructure Portfolio ☁️

This repository documents the architectural setup and management of cloud resources using AWS. It focuses on the deployment of secure, multi-tier virtual networks and compute instances.

---

## 🧪 Lab 01: AWS Multi-Tier VPC & EC2 Infrastructure
*Focus: Network Isolation, Subnetting Strategy, and Secure Remote Access*

<details>
<summary><b>📂 View Full Project Walkthrough (AWS Console Evidence)</b></summary>

### **Phase 1: Networking & Segmentation**
| Step 1: VPC Creation | Step 2: Subnetting (Public/Private) | Step 3: Route Table Logic |
| :---: | :---: | :---: |
| <img src="./images/cloud1_1.png" width="250"> | <img src="./images/cloud1_2.png" width="250"> | <img src="./images/cloud1_3.png" width="250"> |
| *Provisioning the 10.0.0.0/16 VPC* | *Segmenting AZs for High Availability* | *Configuring IGW for Public Access* |

### **Phase 2: Security & Compute Provisioning**
| Step 4: Security Group Inbound Rules | Step 5: EC2 Instance Launch | Step 6: Key Pair Management |
| :---: | :---: | :---: |
| <img src="./images/cloud1_4.png" width="250"> | <img src="./images/cloud1_5.png" width="250"> | <img src="./images/cloud1_6.png" width="250"> |
| *Hardening SSH (22) and HTTP (80) ports* | *Deploying Amazon Linux 2 AMI* | *Generating RSA .pem for secure auth* |

### **Phase 3: Validation & Connectivity**
| Step 7: Elastic IP Allocation | Step 8: SSH Terminal Access | Step 9: Resource Verification |
| :---: | :---: | :---: |
| <img src="./images/cloud1_7.png" width="250"> | <img src="./images/cloud1_8.png" width="250"> | <img src="./images/cloud1_9.png" width="250"> |
| *Mapping static IPs to instances* | *Successful remote CLI connection* | *Confirming instance "Running" state* |

**Key Takeaways:** * Implemented a **Multi-AZ** strategy to ensure infrastructure resilience.
* Applied the **Principle of Least Privilege** via Security Group rules, restricting access to only necessary ports.
* Managed the full lifecycle of a cloud resource from network design to remote administration.

</details>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%">
</p>

<p align="center">
  <b>🚀 Stay tuned for more AWS, Azure, and Cloud Security labs!</b><br>
  <i>Current Focus: Cloud Architecture & Serverless Security</i>
</p>
