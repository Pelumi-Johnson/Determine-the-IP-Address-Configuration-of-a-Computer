# 💻 Determine the IP Address Configuration of a Computer

📄 **Full Lab Report (Google Doc):**  
👉 [Click here to open the complete lab report](https://github.com/Pelumi-Johnson/-My-Local-Network-Home-Topology-Lab/blob/main/1.5.4%20Lab%20-%20My%20Local%20Network-1.docx%20(1).pdf)

---

## 📘 Project Summary
This project demonstrates practical network troubleshooting skills by analyzing the IP configuration of a Windows workstation using core command-line tools. It highlights the ability to interpret network settings, validate local connectivity, and identify key components of the TCP/IP stack foundational skills for IT support, networking, and cybersecurity roles.

---

## 🎯 Skills Demonstrated
- Network troubleshooting using Windows CLI  
- Interpreting IPv4 addressing and subnet masks  
- Identifying DNS, gateway, DHCP, and MAC information  
- Validating network stack functionality  
- Performing loopback and interface connectivity testing  
- Understanding physical vs. logical network components  

---

## 🔧 Tools Used
- `ipconfig`  
- `ipconfig /all`  
- `ping` (loopback + interface IP)

---

## 📝 Key Findings
During this project, I examined the network configuration of a Windows workstation and identified critical network parameters:

- **IPv4 Address:** 192.168.4.50  
- **Subnet Mask:** 255.255.255.0  
- **Default Gateway:** 192.168.4.254  
- **DNS Server:** 192.168.4.2  
- **MAC Address:** 54-BF-64-A4-96-78  
- **DHCP:** Enabled  

To validate connectivity:

- Successfully pinged the **loopback address** (`127.0.0.1`), confirming the TCP/IP stack is functioning.  
- Successfully pinged the **device’s own IP address**, confirming the NIC and drivers are operational.

These are essential diagnostic steps for identifying local vs. network-wide issues.

---

## 🖥️ (Optional) Screenshots  
If you choose to include screenshots, store them here:

