# Kali-Rescue-Toolkit
Auto-detects common post-update issues <br/>
Fixes: <br/>
Wi-Fi firmware missing <br/>
NVIDIA driver mismatch <br/>
Broken network manager <br/>
Monitor mode not working <br/>


Folder struction <br/> 
kali-rescue-toolkit/ <br/>
├── README.md <br/>
├── install.sh <br/>
├── kali-rescue <br/>
├── lib/ <br/>
│   ├── common.sh <br/>
│   ├── detect_wifi.sh <br/>
│   ├── fix_wifi.sh <br/>
│   ├── detect_networkmanager.sh <br/>
│   ├── fix_networkmanager.sh <br/>
│   ├── detect_monitor_mode.sh <br/>
│   ├── fix_monitor_mode.sh <br/>
│   ├── detect_nvidia.sh <br/>
│   └── fix_nvidia.sh <br/>
└── logs/ <br/>
    └── .gitkeep <br/>

MVP commands

./kali-rescue diagnose → prints results + creates log

./kali-rescue fix wifi

./kali-rescue fix network

./kali-rescue fix monitor

./kali-rescue fix nvidia

Disclaimer<br/>

Use only on systems you own or have explicit permission to administer.
This toolkit focuses on stability/troubleshooting, not exploitation.
