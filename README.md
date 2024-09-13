# Elastic SIEM Homelab
This repository showcases my Elastic SIEM homelab. I created my own vitrual enviroment so I may learn how to monitor and manager web traffic within a SIEM. Utimately I was able to gain first hand experience in writing SIEM rules for the detection of suspious web events as well as how to utizile queries when investigating possible cyber attacks.

# How was my home lab made?
I created three virual machines on a Windows host PC, then connected each VM to a Host-Only VMware Network Apdater. The VMs each play a different role within the virtual network. An attacker which has an image of Kali Linux installed, a client computer that runs Windows 11, and a monitor with Ubuntu installed. The monitor collects and formats logs generated ny the client computer then forwards them to a SIEM deployed on the Elastic web application. The attacker's job will be to generate suspious logs by performing tasks like port scans on the client. The Elastic SIEM is then viewed and managed directly on the host PC from a browser.

![Elastic SIEM Homelab](https://github.com/user-attachments/assets/03814f6b-a87e-45e2-86f1-cddc4551ad24)
