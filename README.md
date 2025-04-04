# Crowd Tracking & Recognition System  

A real-time application for detecting, tracking, and recognizing individuals in crowded environments, featuring a web-based interface for monitoring and analysis.  

---

## 📋 Table of Contents  
- [Features](#-features)  
- [Prerequisites](#-prerequisites)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Web Interface](#-web-interface)  
- [Configuration](#-configuration)  
- [Troubleshooting](#-troubleshooting)  
- [License](#-license)  

---

## ✨ Features  
- **Real-time Detection**: Uses advanced computer vision to detect people in crowded scenes.  
- **Tracking**: Continuously follows individuals across video frames.  
- **Recognition**: Optional facial recognition (if configured).  
- **Web Dashboard**: View live results via a browser.  
- **Cross-Platform**: Works on Windows, Linux, and macOS.  

---

## 🛠 Prerequisites  
- **Python 3.9+** ([Download](https://www.python.org/downloads/))  
- **Git** ([Download](https://git-scm.com/))  
- **pip** (Included with Python)  

---

## 📥 Installation  

### 1. Clone the Repository  
```bash  
git clone https://github.com/BryanEugene/Crowd-Tracking-Recognition-System-using-Computer-Vision 
cd crowd-tracker  
```  

### 2. Initialize Submodules  
```bash  
git submodule sync  
git submodule update --init --recursive  
```  

### 3. Install Dependencies  
Run the automated installer:  
```bash  
python install_requirements.py  
```  
*This installs dependencies for the main project and submodules.*  

---

## 🚀 Usage  
Start the system with:  
```bash  
python main.py  
```  
- Press `Q` in the terminal to stop the application.  
- Use `--help` for command-line options (e.g., camera source, model selection).  

---

## 🌐 Web Interface  
After launching, access the dashboard:  
- **Local Machine**: [http://localhost:8000](http://localhost:8000)  
- **Network Access**: Replace `localhost` with your machine’s IP (e.g., `http://192.168.1.100:8000`).  

*Ensure port `8000` is open in your firewall.*  

---

## ⚙️ Configuration  
Modify `config.yaml` (if available) to adjust:  
- Camera/video input source  
- Detection sensitivity  
- Recognition settings  
- Output preferences  

---

## 🛠 Troubleshooting  
- **Dependency Errors**: Run `pip install -r requirements.txt` manually.  
- **Port Conflicts**: Change the port in `main.py` (look for `port=8000`).  
- **Submodule Issues**: Run:  
  ```bash  
  git submodule foreach git pull origin main  
  ```  

---

## 📜 License  
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.  

---

**📧 Contact**: For support, open an issue on [GitHub](https://github.com/BryanEugene/Crowd-Tracking-Recognition-System-using-Computer-Vision).  
**🔗 Repository**: [github.com/BryanEugene/Crowd-Tracking-Recognition-System-using-Computer-Vision](https://github.com/BryanEugene/Crowd-Tracking-Recognition-System-using-Computer-Vision)  

--- 

*Last updated: March 2024*