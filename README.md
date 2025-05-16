

⚠️ **Disclaimer:** This tool is intended for educational and security research purposes **only**. Unauthorized scanning of systems you do not own is illegal. Use responsibly.  

---

## 🚀 **Features**  
✔️ **Scans common CCTV ports** (80, 443, 554, 8080, 8443)  
✔️ **Detects exposed camera login pages**  
✔️ **Checks if the device is a camera stream**  
✔️ **Identifies camera brands & known vulnerabilities**  
✔️ **Tests for default credentials on login pages**  
✔️ **Provides manual search links (Shodan, Censys, Zoomeye, Google Dorking)**  
✔️ **Google Dorking suggestions for deeper recon**  
✔️ **Enhanced Camera Detection** with detailed port analysis and brand identification  
✔️ **Live Stream Detection** for RTSP, RTMP, HTTP, and MMS protocols  
✔️ **Comprehensive IP & Location Information** with Google Maps/Earth links  
✔️ **Multi-threaded Port Scanning** for faster results  
✔️ **Enhanced Error Handling** and SSL support  
✔️ **Detailed Camera Brand Detection** (Hikvision, Dahua, Axis, Sony, Bosch, Samsung, Panasonic, Vivotek)  
✔️ **ONVIF Protocol Support** for standardized camera communication  
✔️ **Smart Brute-force Protection** with rate limiting  
✔️ **Detailed Port Analysis** showing server information and authentication types  


```  
```bash
pip install -r requirements.txt
```
---
```
python CamXploit.py
```
Enter the **public IP address** of the target device when prompted.  

### **🔍 What It Does:**  
1️⃣ **Scans open ports** (Common CCTV ports)  
2️⃣ **Checks if a camera is present**  
3️⃣ If a camera is found, it:  
   - Searches for **login pages**  
   - Checks **default credentials**  
   - Identifies **camera brand & vulnerabilities**  
   - Detects **live streams** (RTSP, RTMP, HTTP, MMS)  
   - Provides **location information** with maps  
   - Shows **server details** and authentication types  
4️⃣ Provides **manual search URLs** for deeper investigation  

---

---

## 🤖 **To-Do & Future Features**  
- [x] Add multi-threaded scanning for speed  
- [x] Expand camera brand detection  
- [ ] Implement logging feature  
- [ ] Add screenshot capture functionality  
- [ ] Implement report generation  
- [ ] Add network range scanning  
- [ ] Implement MAC address lookup  

---
## 🙌 **Contributions**  
Feel free to submit issues, suggestions, or pull requests!  

<h4 align="center"> If you find this GitHub repo useful, please consider giving it a star! ⭐️ </h4> 
