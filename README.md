# Kali-Rescue-Toolkit
Auto-detects common post-update issues <br/>
Fixes: <br/>
Wi-Fi firmware missing <br/>
NVIDIA driver mismatch <br/>
Broken network manager <br/>
Monitor mode not working <br/>

Folder struction <br/> 
kali-rescue-toolkit/
├── README.md
├── install.sh
├── kali-rescue
├── lib/
│   ├── common.sh
│   ├── detect_wifi.sh
│   ├── fix_wifi.sh
│   ├── detect_networkmanager.sh
│   ├── fix_networkmanager.sh
│   ├── detect_monitor_mode.sh
│   ├── fix_monitor_mode.sh
│   ├── detect_nvidia.sh
│   └── fix_nvidia.sh
└── logs/
    └── .gitkeep

MVP commands

./kali-rescue diagnose → prints results + creates log

./kali-rescue fix wifi

./kali-rescue fix network

./kali-rescue fix monitor

./kali-rescue fix nvidia

    
