# arpspoof_detector
A simple Python script using Scapy to detect ARP spoofing attacks on a network.


# ARP Spoof Detector 🔍

This is a simple Python script using the **Scapy** library to detect **ARP spoofing attacks** in a local network.

## 🛠️ How It Works

- Sniffs network traffic for ARP replies.
- Compares the MAC address in the packet with the real MAC address of the sender.
- If there's a mismatch → 🚨 possible spoofing detected!

## 🧪 Usage

### 🔹 Linux (Kali, Ubuntu, Parrot OS):

```bash
sudo python3 arp_spoof_detector.py
