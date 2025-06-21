# 📘 MODULE 4: BUILD A HOME NETWORK

## 📡 Home Network Basics

- Home networks typically involve two layers:
  - Public network from the ISP (Internet Service Provider)
  - Local Area Network (LAN) within the home via a router

- Routers often include both **wired (Ethernet)** and **wireless (Wi-Fi)** capabilities.
- Devices commonly found on a home network:
  - Desktop computers, gaming consoles, smart TVs, printers, scanners, IP cameras, thermostats, etc.

### 🔧 Router Ports
- **Ethernet Ports** – Connect internal devices
- **Internet Port** – Connects to ISP modem
- **Radio Antenna** – Provides wireless access point functionality

---

## 📶 Network Technologies in the Home

### 🌐 Wireless Technologies
- Use **electromagnetic waves** in unlicensed frequency bands (2.4 GHz & 5 GHz).
- **IEEE 802.11 standards** govern wireless LANs (Wi-Fi).
- **Bluetooth** also operates on 2.4 GHz but with shorter range & lower power use.

### 📡 Wi-Fi vs Bluetooth
| Feature      | Wi-Fi (802.11) | Bluetooth |
|--------------|----------------|-----------|
| Frequency    | 2.4 GHz / 5 GHz| 2.4 GHz   |
| Range        | Long           | Short     |
| Throughput   | High           | Low       |
| Use Case     | Internet Access| Peripheral Connections |

### 🧷 Wired Alternatives
- **Ethernet (Cat 5e)** – Most common for wired LANs.
- **Powerline Networking** – Uses electrical wiring to transmit data.

---

## ⚙️ Wireless Router Configuration

### Key Settings:
- **Network Mode**: Specifies Wi-Fi standard (e.g., 802.11n, mixed mode)
- **SSID**: Identifies the WLAN; must be the same on all connecting devices
- **Channel**: Frequency band used; default is usually set to Auto
- **SSID Broadcast**: Can be enabled or disabled for security

> 🔐 *Disabling SSID broadcast improves security but requires manual entry of SSID.*

### Speed Optimization
- Use the same 802.11 standard across all devices to maximize throughput.
- **Mixed Mode** allows older and newer devices to coexist but may reduce speed.

---

## 📲 Mobile Device Connectivity

### 🌐 Wi-Fi Precautions for Mobile Devices:
- Avoid sending sensitive information over unencrypted text (plaintext)
- Use **VPNs** when accessing sensitive data
- Enable **WPA2 or WPA3 encryption**
- Secure your **home network router**

### 📱 Mobile OS Behavior
- Mobile devices default to Wi-Fi if available, fallback to cellular data otherwise.
- Common mobile OS: **Android & iOS**

---

## 🔗 Bluetooth Technology

### 🔄 Bluetooth Pairing
- Devices must:
  - Have Bluetooth enabled
  - One must be in **discoverable mode**
- Transmitted Info Includes:
  - Device name
  - Bluetooth class
  - Supported services
  - Technical specifications
- **PIN codes** may be required to authenticate pairing

---

## 🏠 Setting Up a Home Router

### 🛠️ Initial Configuration
1. Connect PC to router using **Ethernet cable**
2. Router’s **DHCP server** assigns IP address to the PC
3. Access router via web browser

### 🧠 Planning Ahead
- Define network usage & device roles
- Avoid revealing device model/brand in SSID
- Consider **MAC address filtering** for stricter access
- Set up **Guest Access** for internet-only connectivity

> ⚠️ *MAC filtering increases security but reduces convenience when connecting new devices.*

---

