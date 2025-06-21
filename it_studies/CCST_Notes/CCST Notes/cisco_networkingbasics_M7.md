# 📘 MODULE 7: THE ACCESS LAYER

---

## 📦 Encapsulation & De-encapsulation

- **Encapsulation**: Wrapping data in a specific format for transmission.
  - Similar to placing a letter in an envelope.
  - Ensures the message follows network rules for delivery and processing.

- **De-encapsulation**: The receiving device reverses the process to retrieve the original data.

---

## 🌐 Ethernet Frame Structure

The **Ethernet protocol** governs communication by defining:
- **Frame Format**: Includes fields like source/destination MAC, preamble, type, and frame check sequence.
- **Frame Size**: Specifies minimum and maximum lengths.
- **Timing & Encoding**: Synchronization and data conversion rules.

### 🧾 Key Components of an Ethernet Frame:
- **Preamble**: Synchronizes communication between sender and receiver.
- **Start of Frame Delimiter (SFD)**: Marks the beginning of the frame.
- **Destination MAC Address**: Indicates where the frame is going.
- **Source MAC Address**: Identifies where the frame came from.
- **Length/Type**: Specifies data length or protocol type.
- **Frame Check Sequence (FCS)**: Used to detect errors during transmission.

---

## 🏠 The Access Layer

### 📌 Definition:
The **Access Layer** is the network entry point for users to connect to shared resources like files and printers.

### 🔌 Ethernet Hub (Legacy Device):
- Contains multiple ports for host connections.
- Only one message can be transmitted at a time.
- **Collisions** occur if multiple devices transmit simultaneously.
- **Obsolete** due to inefficiency and collision-prone design.

### 🧠 Ethernet Switch (Modern Device):
- Operates at **Layer 2 (Data Link Layer)**.
- Builds a **MAC Address Table** that maps host MACs to specific ports.
- **Reduces collisions** by:
  - Reading source/destination MAC addresses.
  - Establishing a **temporary circuit** between sender and receiver.
  - Supporting **full-duplex** transmission (send/receive at the same time on one cable).

### 🧬 MAC Address Learning:
- A switch learns MAC addresses dynamically:
  - Reads source MAC from every frame.
  - Adds new MAC-port pairs to the MAC Address Table.
  - Continuously updates as new hosts join or respond to messages.

---

