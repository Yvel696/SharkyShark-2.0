# 🦈 SharkySniffer 2.0

SharkySniffer is a Python-based lightweight packet sniffer inspired by Wireshark, designed for educational and network monitoring purposes. It offers packet capture, filtering, anomaly detection, and now includes **device discovery** with GUI labeling.

---

## 📦 Features

### ✅ Phase 1: Command-line Packet Sniffing
- Live capture of network traffic using `scapy`.
- Parses and displays IP, TCP, UDP, ICMP packets.

### ✅ Phase 2: Filtering
- Basic filtering by protocol (e.g., HTTP, DNS).
- Packet display updated in real-time.

### ✅ Phase 3: GUI Interface
- Built using `tkinter` and `ttk.Notebook`.
- Tabs for packet logs, statistics, and now devices.

### ✅ Phase 4: Export Options
- Save captured data to `.pcap` or `.csv`.

### ✅ Phase 5: Anomaly Detection
- Alerts on:
  - High packet frequency
  - Large packet sizes
  - Suspicious flags

### 🆕 Phase 6: **Device Discovery & Tagging**
- New GUI tab: **Connected Devices**
- Scans local network for active devices.
- Displays:
  - IP Address
  - MAC Address
  - Hostname (if available)
- Allows user to **tag unknown devices** with custom names for easy identification.


## 🛠️ Installation

### 1. 📥 Clone the repo:
```bash
git clone https://github.com/yourusername/SharkySniffer.git
cd SharkySniffer
