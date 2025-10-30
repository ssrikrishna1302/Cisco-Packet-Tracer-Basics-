#  Connection Between 2 Switches

This Cisco Packet Tracer exercise demonstrates how to connect **two switches** and test connectivity between connected devices by **sending packets**.

---

## ⚙️ Objective
To establish a network connection between two switches and verify successful data transmission between PCs connected to them.

---

##  Network Setup
**Devices Used:**
- 2 Switches (e.g., Switch0 and Switch1)
- 2 PCs (PC0 and PC1)

**Connections:**
- Switch0 connected to Switch1 using a **copper straight-through cable**
- PC0 connected to Switch0  
- PC1 connected to Switch1

---

##  Configuration Steps
1. **Assign IP Addresses:**
   - PC0 → `192.168.1.10`
   - PC1 → `192.168.1.11`
   - Subnet Mask: `255.255.255.0`

2. **Connect Devices:**
   - Use straight-through cables to connect PCs to switches.
   - Connect the two switches using another straight-through cable.

3. **Verify Connectivity:**
   - Open the **Command Prompt** on PC0.
   - Use the command:  
     ```
     ping 192.168.1.11
     ```
   - Successful replies confirm both switches are properly connected and packets are transmitted.

---

##  Testing Packet Transmission
- Used the **Add Simple PDU tool** in Packet Tracer to send packets from PC0 to PC1.  
- Verified that packets were **successfully delivered**, confirming correct switch interconnection.

---

## 🖥️ Files Included
-  Cisco Packet Tracer project file  
-  Network topology image  
-  Screenshot of successful packet delivery
