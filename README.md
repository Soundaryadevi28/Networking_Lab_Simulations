You can copy and paste this directly into your GitHub README file. It is formatted with professional "Markdown" to make it look great for recruiters.

---

# Networking-Lab-Simulations

### 🌐 Project: Basic LAN Setup and ICMP Connectivity Verification
This project demonstrates the foundational principles of Local Area Network (LAN) design, device addressing, and end-to-end communication testing using the Cisco Packet Tracer simulation environment.

---

### 🚀 Objective
To design and implement a Peer-to-Peer network using a Layer 2 switch, configure static IPv4 addressing, and verify successful data packet transmission across the network.

### 🛠️ Technical Implementation
* **Network Topology:** Star Topology using a Cisco Catalyst 2960 Switch.
* **Hardware Simulation:** 2 Generic PCs connected via Copper Straight-Through cabling.
* **Logical Addressing:** * **PC0:** `192.168.1.1` (Subnet Mask: `255.255.255.0`)
    * **PC1:** `192.168.1.2` (Subnet Mask: `255.255.255.0`)
* **Protocol Testing:** Used the **ICMP (Internet Control Message Protocol)** via the `ping` command to verify connectivity.

### 📊 Results
* **Packet Statistics:** Sent = 4, Received = 4, Lost = 0 (0% loss).
* **Verification:** Successful 4-way handshake confirmed low-latency communication between nodes.

### 📁 Files in this Repository
* `Basic_LAN_Project.pkt`: The original Cisco Packet Tracer simulation file.
* `Screenshots/`: Visual proof of the physical topology and successful ping test.

---

### 💡 Key Learning Outcomes
1.  Understanding **Layer 2 Data Link** interactions using a network switch.
2.  Practical experience in assigning **IPv4 addresses** and subnet masks.
3.  Utilizing the **Command Line Interface (CLI)** for network troubleshooting and diagnostic testing.
