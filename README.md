# Portfolio
🔐 Jhonatan Robayo | Network Security & Cybersecurity Portfolio

> Network Security • Vulnerability Management • Incident Response • Cloud Security  
>  MSc Cybersecurity | BSc Computer Engineering | 10+ years Networking & ITS  
>  Target Roles: Network Security Engineer • SOC Analyst • Cloud Security Engineer • Cybersecurity

---

## Certifications (In Progress)
- CompTIA Security+ (SY0-701) — in progress (study plan + labs below)

---

## Security+ (SY0-701) Study Portfolio
This section contains labs + mini-projects aligned to Security+ domains and objectives.

### Lokheed Martin Project
#### SecureVision | FPGA Secure Boot + Encrypted AI Inference

SecureVision is an embedded security project that implements a **hardware Root of Trust and secure AI execution pipeline on FPGA**.  
The system protects application software and AI models using **secure boot, AES encryption, PUF-based key generation, and fault injection protections** while enabling **object detection with YOLOv3-tiny**.

The platform runs on the **PYNQ-Z2 FPGA board** and demonstrates how hardware security can protect AI workloads at the edge.

---

#### System Architecture

SecureVision implements a secure execution chain:

1. FPGA boots using a **Root of Trust**
2. Device generates a **PUF-based hardware key**
3. Encrypted application and AI model are loaded
4. **AES-128 decryption** unlocks protected software
5. **YOLOv3-tiny object detection** runs on the device
6. Runtime protections monitor for hardware attacks

---

#### Key Security Features

- **Secure Boot (Root of Trust)**
- **AES-128 encryption/decryption of application software**
- **PUF-based device-unique key generation**
- **Voltage glitch detection**
- **Encrypted software at rest**
- **Authenticated application execution**

---

#### AI / Computer Vision Component

The system runs **YOLOv3-tiny object detection** for lightweight edge inference.

Tasks implemented:

- Training YOLOv3-tiny to detect specific object
- Optimize inference for **PYNQ-Z2 embedded execution**
- Load and run the model through a **Python inference pipeline**
- Detect objects from input frames in real time
- Integrate detection with the secure boot environment

This demonstrates how **secure hardware can protect AI models deployed on embedded devices**.

---

#### PUF Key Generation
- Designed and tested **Ring Oscillator / Arbiter PUF**
- Generated **device-unique cryptographic keys**
- Evaluated reliability and uniqueness
- Tuned Vivado constraints (`LOC`, `BEL`, `DONT_TOUCH`)

#### AES Encryption / Decryption
- Implemented **AES-128 encryption and decryption flow**
- Used PUF-derived keys for secure software decryption
- Integrated cryptography into the secure boot pipeline

#### Secure AI Execution
- Integrated **YOLOv3-tiny inference**
- Built Python scripts to run object detection
- Supported model conversion and optimization for edge deployment

---

#### Technologies Used

**Hardware**
- PYNQ-Z2 FPGA

**Tools**
- Vivado
- Vitis / Jupyter
- Python

**Languages**
- Verilog
- Python

**Security Concepts**
- Root of Trust
- Secure Boot
- AES-128 Cryptography
- Physically Unclonable Functions (PUF)
- Fault Injection Detection

**AI / ML**
- YOLOv3-tiny
- TensorFlow Lite

---

#### What This Project Demonstrates

- Secure embedded system design
- Hardware-rooted trust architectures
- FPGA security implementation
- Encryption-protected software deployment
- AI inference on secured edge hardware

  **Demo:
  https://youtu.be/eikhU9D1p5s?si=8EU1AoXOgRXcrtnw**

---

### Mini-Projects (Reports / Diagrams / Playbooks)
- [Security Controls Cheat Sheet](projects/security-controls-cheatsheet.md)
- [Threat Model Mini-Report](projects/threat-model-online-banking.md)
- [Network Segmentation Design](projects/segmentation/segmentation-design.md)
- [TLS / PKI Explainer](projects/tls-pki-explainer.md)
- [Incident Response Playbook — Phishing](projects/ir-playbook-phishing.md)
- [Security Policy Pack](projects/policies/)

### Labs (Hands-on)
- [TryHackMe Labs](labs/tryhackme/)
- [CyberDefenders Labs](labs/cyberdefenders/)

### Practice / Mistake Log (what makes you pass fast)
- [Mistake Log](mistake-log/mistakes.md)

---

## Projects (Professional Labs)

| Project | Skills | Tools | Link |
|--------|--------|--------|------|
| Vulnerability Management Lab | CVE tracking, remediation, reporting | Greenbone, Nmap, Python | [View](projects/vuln-management/) |
| Network Design & Defense Lab | VLAN segmentation, ACLs, VPN, routing & security | Cisco, GNS3/EVE-NG, OSPF, BGP, IPSec | [View](projects/network-design-defense/) |
| SOC + SIEM (Home Lab) | Log collection, detection, alerts | Wazuh, Elastic Stack, Security Onion | [View](projects/soc-siem-homelab/) |
| Firewall Rule Automation | ACL auditing, automation | Python (Netmiko/NAPALM), Cisco | [View](projects/firewall-automation/) |
| Cloud Security Monitoring | AWS IAM, VPC monitoring, alerts | CloudWatch, GuardDuty, Terraform | [View](projects/cloud-security-monitoring/) |

---

## Tech Stack
`Cisco` `BGP` `OSPF` `Firewalls` `VPN` `IDS/IPS` `Nmap` `Greenbone` `SIEM` `AWS` `Wireshark` `Python`

---

## 📫 Connect
🔗 LinkedIn: https://linkedin.com/in/jhonatan-robayo-h  
📧 Email: Jhonatan.robayo@gmail.com
