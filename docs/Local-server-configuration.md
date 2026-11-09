# Local Server Configuration

## 1. Objective
### What was the purpose of configuring this server?
The purpose is that the PC is beinf repurpose into local office server, hosting network-related services for DNS filtering, device monitoring, and service availability monitoring. It provides a centralized platform for managing these services and allows remote administration through SSH and Tailscale.

## 2. Initial Setup
- Hardware used: HP Slimline Desktop PC 270-p0xx
- Operating system: Ubuntu server 26.04.1 LTS

## 3. Implementation
### 3.1 OS Installation
I decide to install ubuntu server on this machine because the PC have a good specs for this purpose with the I7 7700 but the 8GB of ram is the limitting factor. The reason why i chose ubuntu compared to other distro like debian is because Ubuntu is a great option for this machine like i mention earlier but also it comes pre-packages with the apps that I  need for this purpose.

### 3.2 Remote Access (SSH)
First decide to configured the SSH so i can securely access the machine without needing to connect the machine to a screen. First i change the default port to 2222 so if someone is trying to scan the network it would make them check every port instead of the default 22 port. Next I change the 'permitrootlogin', then maxauthtries 3, and pubkeyauthentication yes. After that configuration I installed tailscale on the machine and opening the url that it gives on my host machine and using the email that is being shared with my mentor on this project.

### 3.3 AdGuard Home
I installed AdGuard with the curl command and using the automatic install and then after the installation was finished, I visited the site with my local server IP. After that I test it out on my local machine with the command 'nslookup ' 

## 4. Problems & Troubleshooting

| Problem | Cause | Solution |
|---|---|---|
| | | |

## 5. Final Result
What is working now? What remains unfinished?

## 6. Lessons Learned
What did I learn from this process?
