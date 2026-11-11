<h1 align="center">Hi there 👋 I'm Bandar Alsubhi</h1>
<h3 align="center">Software Engineer | Systems Programming in C & Linux | Machine Learning</h3>

---

### 🧑‍💻 About Me
- 🎓 Computer Science graduate (Computer Engineering track) from **King Abdulaziz University**, GPA 4.53 / 5.00
- 🏕️ Graduate of the 26-week **Systems Engineering & Programming Bootcamp** at **Tuwaiq Academy**
- 🔭 I build systems that catch problems early, from the Linux kernel up to deep learning
- 💼 Looking for an entry-level **Software Engineering** or **Systems Programming** role, open to relocating anywhere in Saudi Arabia
- 📍 Based in **Jeddah, Saudi Arabia**

### 🛡️ Featured Project: VFS-Sentinel
A Linux daemon in C that **stops ransomware before it can read a single file**. Instead of relying on known malware signatures, it plants a decoy "canary" file in the protected folder, so even brand-new ransomware with no known signature is caught.

- **Kernel-level interception:** uses fanotify `FAN_OPEN_PERM` to freeze a process before it opens a file, then allows or denies access
- **Automated response:** kills the malicious process, denies access, and logs forensic details (PID, executable path)
- **Safety net:** one-time backups of touched files with `copy_file_range`, `O_EXCL`, inode-based naming and a 20 MB cap
- **Low false positives:** whitelists trusted system processes such as desktop indexers

👉 [View the project](https://github.com/Bandar12123/VFS-Sentinel)

### 🚀 Projects

| Project | Description |
|---------|-------------|
| 🧠 OncoBrain | Brain tumor diagnosis platform: an ensemble of 5 pre-trained CNNs (ResNet50, AlexNet, VGG-16, DenseNet121, SqueezeNet) with majority voting, a web UI and auto-generated PDF reports (graduation project) |
| 📡 [PacketWatch](https://github.com/Bandar12123/PacketWatch) | Real-time network traffic monitor in Python with Scapy and a PySide6 dashboard (team of three) |
| 💬 [ChatServer](https://github.com/Bandar12123/ChatServer) | Multi-user chat system in C, single-threaded and event-driven using `poll()` |
| 🎥 [C-Live-Audio-Video-Streaming](https://github.com/Bandar12123/C-Live-Audio-Video-Streaming) | Low-latency live camera and microphone streaming over UDP in C |
| ⚙️ [Zero-Virtual-Machine](https://github.com/Bandar12123/Zero-Virtual-Machine) | 8-bit virtual machine in C with its own registers, stack and 32-instruction assembly set |
| 🔍 [Executable-Linkable-Format-Project](https://github.com/Bandar12123/Executable-Linkable-Format-Project) | Lightweight `readelf`-style parser in C for 64-bit ELF headers, sections and symbols |

### 🤝 Contributions

| Project | Description |
|---------|-------------|
| ☕ [V6O](https://github.com/m7md-d/V6O) | Automated V60-style drip coffee machine on Arduino Nano ESP32, with a web UI to customize the brew |
| 🚁 [SDCS](https://github.com/m7md-d/SDCS) | Smart Drone Controller System: draw on a web page using a drone controller connected to an Arduino, with Gemini API shape matching and scoring |

### 🛠️ Tech Stack
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-654FF0?style=for-the-badge&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-CNNs-EE4C2C?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 📊 GitHub Stats
<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Bandar12123&show_icons=true&theme=radical" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bandar12123&layout=compact&theme=radical" />
</p>

### 📫 Get in Touch
<p>
  <a href="https://www.linkedin.com/in/bandar-alsubhi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:bandarhatim11@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
