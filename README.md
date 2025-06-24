# 📱 Hacking Android: Remote Access Backdoors

**BootCon 2025 Cybersecurity Project by Emmanuel Adewa & Sireen Rahhal**

This project demonstrates how Android APKs can be weaponized to create remote access backdoors, and what users can do to protect themselves.

---

## 🎯 Project Purpose

Android's global market share and open-source nature make it a prime target for attackers. This project simulates a realistic cyberattack using tools like **TheFatRat**, **Metasploit**, **Ngrok**, and an **Android emulator**. It emphasizes the ease of exploiting Android systems when proper defenses are not in place.

---

## ⚙️ Tools Used

- **Kali Linux**
- **TheFatRat** - Payload generation
- **Ngrok** - Remote access tunneling
- **Metasploit Framework** - Exploitation and session handling
- **Python HTTP Server** - Payload delivery
- **Genymotion Emulator** - Android target simulation
- **APKSigner, APKTool** - Payload signing

---

## 🧪 Demo Overview

> 🎥 [Watch the demo](./Project%204%20Demonstration.mp4)

1. **Setup environment**: Kali Linux + TheFatRat + Genymotion + Ngrok
2. **Create payload**: Signed malicious APK with reverse TCP payload
3. **Host payload**: Python server used to simulate delivery
4. **Exploit target**: Install APK on Android emulator
5. **Establish session**: Gain Meterpreter shell access
6. **Post-exploitation**:
   - Access contacts, SMS, call logs
   - Control webcam and mic
   - View system info and geolocation

---

## 🛡️ Mitigation Strategies

| Threat                          | Recommendation                                                |
|-------------------------------|---------------------------------------------------------------|
| Sideloaded APKs                | Disable "Install from unknown sources"                       |
| Social engineering             | Avoid clicking unknown links and deceptive messages          |
| Excessive permissions          | Only grant permissions that are absolutely necessary         |
| Malware protection             | Enable Google Play Protect or use trusted security apps      |
| OS & app vulnerabilities       | Always keep system and apps updated                          |

---

## 📁 Project Files

| File Name                                         | Description                                     |
|--------------------------------------------------|-------------------------------------------------|
| [`Emmanuel Adewa -BootCon Presentation 2025.pptx.pdf`](./Emmanuel%20Adewa%20-BootCon%20Presentation%202025.pptx.pdf) | Final project slide deck                       |
| [`Project 4 Demonstration.mp4`](./Project%204%20Demonstration.mp4)            | Live or recorded hacking demo                  |

---

## 💬 Final Thoughts

This project underscores the importance of ethical hacking education. While attackers continue to evolve their methods, so must our understanding of how to defend against them.

---

## ⚠️ Disclaimer

This project is **strictly for educational purposes**. All demonstrations were performed in controlled environments. Do not attempt unauthorized use of these techniques on live systems.

---

## 🔗 Connect

**Author:** Emmanuel Adewa  
**BootCon 2025 | Cybersecurity Presentation**
