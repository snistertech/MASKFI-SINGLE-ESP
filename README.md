# 🎭 MaskFi - Advanced WiFi Security Testing Tool

![MaskFi Logo](https://img.shields.io/badge/MaskFi-v2.0-orange?style=for-the-badge&logo=wifi)
![ESP8266](https://img.shields.io/badge/ESP8266-Compatible-blue?style=for-the-badge&logo=espressif)
![License](https://img.shields.io/badge/License-Educational%20Use-green?style=for-the-badge)

## 🚀 What is MaskFi?

**MaskFi** is a powerful ESP8266-based WiFi security testing tool designed for **legal penetration testing** and **educational purposes**. It combines multiple attack vectors into a single, portable device that security professionals and researchers can use to assess WiFi network vulnerabilities.

## ⚡ Key Features

### 🎯 **Deauthentication Attacks**
- Disconnect devices from target networks
- Real-time packet injection
- Multi-target support with network scanning
- Vendor identification (PLDT, Converge, Globe, Tenda, TP-Link, etc.)

### 🕸️ **Captive Portal Phishing**
- **Dynamic text loading from JSON** - Easily customizable portal content
- **Responsive design** - Works on mobile, tablet, and desktop devices
- **Multiple ISP templates** - PLDT, Converge, Globe, Tenda, TP-Link logos
- **Real-time password capture** - Stores credentials with timestamps
- **Password validation** - Optional real-time credential verification

### 🎨 **Advanced Customization**
- **External CSS support** - Upload custom stylesheets via web interface
- **Logo management** - Upload and switch between ISP logos
- **JSON configuration** - Easy text and settings modification
- **File upload system** - Supports .png, .json, and .css files

### 🔧 **Professional Dashboard**
- Real-time network scanning and analysis
- Password management and export
- Live attack monitoring and logs
- Device configuration and IP management
- Responsive web interface

## 🛠️ Technical Specifications

| Component | Details |
|-----------|---------|
| **Platform** | ESP8266 (NodeMCU, Wemos D1, etc.) |
| **Memory Usage** | 380KB program (76%), 43KB RAM (53%) |
| **Storage** | LittleFS for dynamic content |
| **Network** | 2.4GHz WiFi with AP/STA modes |
| **Interface** | Web-based dashboard |
| **Power** | USB or battery powered |

## 📋 What's New in v2.0

### 🆕 **Dynamic Content System**
- **JSON-based text loading** - All portal text now loads from `data/portal_text.json`
- **Fallback protection** - Hardcoded fallbacks ensure reliability
- **Multi-language ready** - Structured for easy localization

### 🎨 **Enhanced UI/UX**
- **Responsive CSS** - External `data/style.css` with mobile optimization
- **Logo consistency** - Logos now display on all portal pages
- **File upload support** - Dashboard supports CSS file uploads
- **Memory optimization** - Reduced program size by externalizing assets

### 🔧 **Improved Architecture**
- **Modular design** - Separated content from code
- **Better maintainability** - Easy customization without recompilation
- **Enhanced performance** - Optimized memory usage and loading

## 🎯 Use Cases

### 🔒 **Security Professionals**
- WiFi penetration testing
- Network vulnerability assessment
- Client security awareness training
- Red team exercises

### 🎓 **Educational Purposes**
- Cybersecurity training and workshops
- Understanding WiFi security protocols
- Demonstrating attack vectors
- Research and development

### 🏢 **IT Administrators**
- Testing network security policies
- Employee security awareness
- Infrastructure vulnerability assessment
- Compliance testing

## ⚠️ **Legal Disclaimer**

> **🚨 IMPORTANT: This tool is for LEGAL and EDUCATIONAL use only!**

- ✅ **Authorized testing** - Only use on networks you own or have explicit permission to test
- ✅ **Educational purposes** - Learning about WiFi security and vulnerabilities
- ✅ **Professional pentesting** - Authorized security assessments
- ❌ **Unauthorized access** - Never use against networks without permission
- ❌ **Malicious activities** - Not for illegal hacking or data theft
- ❌ **Public disruption** - Don't interfere with public or critical infrastructure

**Users are solely responsible for complying with all applicable laws and regulations.**

## 🚀 Quick Start

### 📦 **Hardware Requirements**
- ESP8266 development board (NodeMCU recommended)
- USB cable for programming
- Optional: External antenna for better range

### 💻 **Software Setup**
1. **Arduino IDE** with ESP8266 board package
2. **Required libraries**: ESP8266WiFi, DNSServer, LittleFS, ArduinoJson
3. **Upload data files** to LittleFS (portal_text.json, style.css, logos)
4. **Compile and upload** the firmware

### 🌐 **Usage**
1. **Power on** the device
2. **Connect** to the MaskFi access point, Wi-Fi password 'maskfi001'
3. **Navigate** to `192.168.1.1` in your browser
4. **Activate** with license key
5. **Configure** targets and start testing

## 📊 **Performance Metrics**

```
Compilation Results:
├── Program Storage: 380,588 bytes (76% of 499,696 bytes)
├── Dynamic Memory: 43,820 bytes (53% of 81,920 bytes)
├── Available RAM: 38,100 bytes for local variables
└── Status: ✅ Optimized and ready for deployment
```

## 🤝 **Community & Support**

- 📱 **Telegram**: [Join MaskFi Community](https://t.me/+zRnhTEWQUM5jMjhl)
- 🔑 **License**: [Get License Key](https://t.me/snistertech)
- 📚 **Documentation**: Comprehensive guides and tutorials
- 🐛 **Bug Reports**: Community-driven issue tracking

## 🏆 **Why Choose MaskFi?**

### ✨ **Professional Grade**
- Enterprise-level features in a portable package
- Reliable performance with extensive testing
- Regular updates and community support

### 🎯 **User-Friendly**
- Intuitive web interface
- No command-line knowledge required
- Comprehensive documentation and tutorials

### 🔧 **Highly Customizable**
- JSON-based configuration
- Custom CSS and branding
- Modular architecture for easy modifications

### 💰 **Cost-Effective**
- Affordable hardware platform
- One-time license fee
- No recurring subscriptions

---

## 📝 **Changelog v2.0**

- ✅ **Dynamic JSON text loading** - Externalized all portal content
- ✅ **Responsive CSS framework** - Mobile-optimized interface
- ✅ **Enhanced file upload** - Support for CSS customization
- ✅ **Logo consistency** - Unified branding across all pages
- ✅ **Memory optimization** - Reduced program size by 15%
- ✅ **Improved architecture** - Better separation of concerns
- ✅ **Fallback mechanisms** - Enhanced reliability and error handling

---

**MaskFi v2.0** - *Empowering ethical hackers and security professionals worldwide* 🌍

> *"Knowledge is power, but with great power comes great responsibility. Use MaskFi ethically and legally."*

---

*© 2024 MaskFi Project. For educational and authorized testing purposes only.*

