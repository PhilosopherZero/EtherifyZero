# 🧾 Changelog

## [0.2.0] - 2026-06-21

### ✨ New Features
- 🖥️ Added GUI with near 0% CPU / GPU usage when idle  
- 💾 Added backup tab system using Windows restore points  
- 🚀 Added option to start Etherify Zero after login with a 1-minute delay  
- 📊 Added Info tab showing full system and adapter details, including CPU, RAM, GPU(s), MTU, IP, DNS, and other network/interface statistics
- 🏠 Added Home page for quick access to key actions, adapter info, profile status, recommendations, and pinned tools (MTU optimization, adapter restart, etc.)  
- 🧰 Added Tools tab with full network utilities: MTU optimization, DNS optimization, IPv4/IPv6 MTU configuration (global), soft/hard adapter restarts, and network cache reset  
- 📈 Added Benchmark tab with detailed network performance metrics (min/avg/max latency, packet loss, and score) with basic interpretation and actionable insights (more interpretation planned)  
- ⚙️ Added Settings tab with startup control and option to reset to default Windows network settings  
- 📌 Added ability to pin favorite tool actions to the Home page for faster access  
- 👀 Added changelog preview popup before applying auto-optimizations or reset actions (shows pending changes before execution)  
- 🔴 Added restart-required indicator widget that glows red when an action requires a system reboot  
- 📡 Added status bar for ongoing background operations to prevent accidental app closure during processes (some tasks may still lack consistent reporting)  
- 🕒 Added local benchmark history tracking to view network performance over time for troubleshooting and analysis (interpretation improvements planned)
- 💎Added 6 new optimizations that improve network priority, stability and performance

---

### 🧩 Fixes & Improvements
- 🧰 Improved MTU discovery process now ~16s average and ~4.6× faster, with higher accuracy  
- 🚀 DNS optimization process improved ~6 minutes and ~4× faster with better accuracy  
- ⚙️ Fixed startup behavior app now launches more reliably after installation  
- 🌐 Improved DHCP/DNS reset handling when restoring default network settings  
- 🌙 Fixed light mode users experiencing unusable UI by defaulting to dark mode (light mode may be added later if needed)
- 🩹 Updated and fixed network optimization parameters and settings default values to be based on latest version of windows documentation and fresh windows install iso



## [0.1.1] - 2025-10-20

### 🧩 Fixes & Improvements
- 🧰 **Fixed perfect MTU setter** not working for Ethernet (was assuming Wi-Fi only)  
- ⚙️ **Failed to Fix startup issue** — app now launches more reliably on boot *(tentative fix)*  
- 🚀 **Fixed launcher integration** — “Launch Software” now correctly opens the main app  
- 🌐 **Added & fixed congestion controller reset** when restoring default network settings  


## [0.1.0] - 2025-10-17

### 🚀 Features

#### ⚙️ Core Optimizations
- 🧠 **Auto Optimize** – One-click intelligent optimization  
- ⚡ **Latency Benchmark** – Measure real-world ping and jitter  
- 🌐 **MTU Optimization** – Prevents fragmentation and packet loss  
- 🧩 **DNS Optimization** – Selects lowest latency + highest stability resolvers  
- 🔧 **TCP Optimization** – Tunes congestion and performance settings  
- 🛡 **Latency Shield Lite** – Reduces instability under fluctuating network load  

#### 🧰 Network Tools
- 🔁 **Adapter Restart** – Quickly refreshes network interfaces  
- 🧹 **Cache Reset** – Clears cached network data (DNS, ARP, etc.)  
- ⚙️ **Reset to Default** – Restores original network configuration  

#### 🧮 Custom Settings
- 📏 **Set Custom MTU** – Define manual MTU values  
- 🎯 **Set MTU 1280** – Quick preset for minimal fragmentation  
- 🧭 **Show MTU Value** – Displays current adapter MTU  
- 🌍 **Show TCP Settings** – Displays both Global and Supplemental TCP settings  

#### 🧩 System Integration
- 💻 **OS Detection** – Supports Windows 10 and Windows 11 *(optimize-aware)*  
- 🛜 **Network Detection** – Supports Wi-Fi & Ethernet *(optimize-aware)*  
