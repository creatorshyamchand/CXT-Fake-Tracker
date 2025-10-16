🎯 CXT Fake Tracker 🔥

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0.0-blue" alt="Version">
  <img src="https://img.shields.io/badge/Python-3.8+-green" alt="Python">
  <img src="https://img.shields.io/badge/Platform-Termux%2FLinux-yellow" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-red" alt="License">
</p>

<p align="center">
  <b>Advanced Camera 📸 Location 📍 Device 📱 Video 🎞️ Hacking Tool for Educational Purposes Only</b>
</p>

---

📜 Hacker's Quote

"The quieter you become, the more you are able to hear." - Unknown Hacker

---

⚠️ DISCLAIMER

THIS TOOL IS CREATED FOR EDUCATIONAL AND SECURITY TESTING PURPOSES ONLY. THE DEVELOPER IS NOT RESPONSIBLE FOR ANY MISUSE OF THIS TOOL. USE IT ONLY ON SYSTEMS YOU OWN OR HAVE EXPLICIT PERMISSION TO TEST. UNAUTHORIZED ACCESS TO COMPUTER SYSTEMS IS ILLEGAL.

---

👨‍💻 Developer

Shyamchand - Cyber Security Researcher & Developer

🌐 Connect With Me:

<p align="center">
  <a href="https://www.youtube.com/@CREATORSHYAMCHAND" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
  </a>
  <a href="https://t.me/CXT_Official" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="https://github.com/creatorshyamchand" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://instagram.com/shyamchand_cxt" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
</p>

---

🚀 Features

· ✅ WAN Access - Works on any network worldwide
·✅ Real Camera Capture - 3 photos + 5-second video
·✅ Location Tracking - GPS coordinates with accuracy
·✅ Device Fingerprinting - Complete device information
·✅ IP Geolocation - City, country, ISP details
·✅ QR Code Generation - Easy sharing with victims
·✅ Multiple Tunnels - Cloudflare, Ngrok, Localhost.run
·✅ Gallery Saving - Photos/videos saved to device
·✅ Real-time Logging - Live data capture monitoring

---

📋 Prerequisites

· Termux App (Android)
·Python 3.8+
·Storage Permission
·Internet Connection

---

🛠️ Installation & Setup

1. Update & Upgrade Termux

```bash
pkg update && pkg upgrade -y
pkg install python -y
pkg install git -y
```

1. Install Required Packages

```bash
pkg install python python-pip -y
pip install --upgrade pip
```

1. Install Python Dependencies

```bash
pip install flask qrcode pillow colorama requests
```

1. Install Tunnel Services

```bash
pkg install cloudflared ngrok openssh -y
```

1. Setup Storage Permission

```bash
termux-setup-storage
```

---

📥 Download & Run

Method 1: Clone Repository

```bash
git clone https://github.com/creatorshyamchand/CreatorXcamera.git
cd CXT-Fake-Tracker
python3 CXT-Fake-Tracker.py
```

Method 2: Direct Download

```bash
curl -O https://github.com/creatorshyamchand/CreatorXcamera.git
python3 CXT-Fake-Tracker.py
```

Method 3: Manual Creation

```bash
nano cxt_tracker.py
# Copy the code below and save (Ctrl+X, Y, Enter)
python3 cxt_tracker.py
```

---

🎯 Usage Guide

Step 1: Run the Tool

```bash
python3 CXT-Fake-Tracker.py
```

Step 2: Unlock Tool

· Watch YouTube video
·Subscribe to channel
·Click bell icon
·Press Enter to continue

Step 3: Choose Tunnel Option

· Option 1: Auto (Recommended)
·Option 2: Cloudflare Only
·Option 3: Ngrok Only
·Option 4: Localhost.run Only

Step 4: Share Link

· Copy the generated URL
·Share via QR code or direct link
·Wait for victim to access

Step 5: Monitor Captured Data

· Real-time logging in terminal
·Photos/videos saved to gallery
·CSV report generated

---

📊 Captured Data

· 📍 Location: Latitude, Longitude, Accuracy
·🌐 IP Info: IP Address, City, Country, ISP
·📱 Device: User Agent, Screen Size, Platform
·🖥️ Browser: Type, Version, Language
·📸 Media: 3 Photos + 5-second Video
·⏰ Timestamp: Access time and date

---

🗂️ Output Files

· reward_qr.png - QR code for sharing
·reports.csv - All captured data in CSV format
·CXT_Photo_.jpg - Captured photos in gallery
·CXT_Video_.webm - Captured videos in gallery

---

🔧 Troubleshooting

Common Issues & Solutions

1. Tool not running:

```bash
chmod +x CXT-Fake-Tracker.py
python3 CXT-Fake-Tracker.py
```

1. Missing dependencies:

```bash
pip install --force-reinstall flask qrcode pillow colorama requests
```

1. Tunnel not working:

```bash
pkg reinstall cloudflared ngrok -y
```

1. Storage permission denied:

```bash
termux-setup-storage
termux-storage-get /sdcard
```

1. Port already in use:

```bash
pkill -f python
python3 CXT-Fake-Tracker.py
```

---

🌐 Tunnel Services Explained

1. Cloudflare Tunnel ⭐

· Most reliable
·Free forever
·Fast connection
·URL: https://xxx.trycloudflare.com

1. Ngrok Tunnel

· Easy to use
·Good performance
·URL: https://xxx.ngrok.io

1. Localhost.run

· SSH-based
·No installation needed
·URL: https://xxx.localhost.run

---

📱 Victim Perspective

1. Sees fake reward page: "Congratulations! You won $500!"
2. Clicks "CLAIM YOUR REWARD NOW"
3. Grants camera permission
4. System automatically captures:
   · 3 photos from front camera
   · 5-second video recording
   · GPS location
   · Device information
   · IP address details

---

🔒 Security Features

· No data stored on external servers
·All data saved locally on your device
·Automatic media scanner update
·Multiple gallery backup locations
·Encrypted data transmission

---

⚡ Quick Commands Cheat Sheet

```bash
# Start tool
python3 CXT-Fake-Tracker.py

# Update tool
git pull origin main

# Reinstall dependencies
pip install -r requirements.txt

# Fix permissions
chmod +x CXT-Fake-Tracker.py

# Clear cache
rm -rf reports.csv reward_qr.png

# Check services
cloudflared --version
ngrok --version
```

---

🎨 Customization

Change Reward Amount:

Edit the HTML template and change:

```html
<div class="reward">$500</div>
```

Modify Gallery Paths:

Edit the GALLERY_PATHS list in code.

Add New Data Capture:

Extend the JavaScript collectedData object.

---

📞 Support & Community

Join Our Community:

· YouTube: Creator Shyamchand
·Telegram: CXT Official
·GitHub: ShyamchandCXT

Report Issues:

Create an issue on GitHub with:

· Error message
·Steps to reproduce
·Device information
·Screenshots if possible

---

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

🙏 Acknowledgements

· Thanks to all subscribers for their support
·Open source community for amazing tools
·Beta testers for valuable feedback

---

⭐ Support the Project

If you find this tool helpful, please:

1. Star the GitHub repository
2. Subscribe to our YouTube channel
3. Share with fellow security researchers
4. Follow on social media

---

<p align="center">
  <b>Made with ❤️ by Shyamchand | Creator Dev</b>
</p>

<p align="center">
  <i>"Knowledge is power, but wisdom is using it responsibly."</i>
</p>

---

🚨 Final Warning

THIS TOOL IS FOR LEGAL SECURITY TESTING AND EDUCATIONAL PURPOSES ONLY. USERS ARE SOLELY RESPONSIBLE FOR COMPLYING WITH ALL APPLICABLE LAWS. THE DEVELOPER ASSUMES NO LIABILITY FOR MISUSE.

---

© 2025 CXT Fake Tracker | Developed by Shyamchand

🔥 Complete Python Script (CXT-Fake-Tracker.py)