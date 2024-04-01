### Linux Upskill Project

**1.** Spun up a new VM hosting Ubuntu server 22.04. Installation was straightforward. Updated/Upgraded all packages and installed Apache2.
###
![2024-03-27 17_03_42-pve01 - Proxmox Virtual Environment](https://github.com/Benrosan/Linux_Upskill/assets/160042310/b7992d8b-5624-457b-9f6a-dc91126235bd)
###
![2024-03-27 17_33_56-Apache2 Ubuntu Default Page_ It works](https://github.com/Benrosan/Linux_Upskill/assets/160042310/37db9b52-63d5-4c5a-a4b6-a70b99878e5d)
###
Launched an SSH session via PuTTY to make sure it was working. Will also set up PKI access as best practice.
###
![2024-03-27 17_15_52-pve01 - Proxmox Virtual Environment](https://github.com/Benrosan/Linux_Upskill/assets/160042310/109bb4d5-8d30-405f-baa8-b16238708ab6)
###
Creating SSH key pair.
###
![2024-03-28 12_45_33-PuTTY Key Generator](https://github.com/Benrosan/Linux_Upskill/assets/160042310/a13d37de-7ea6-4d61-8085-68d577c0b544)
###
Successfully logged in.
###
![2024-03-28 12_45_57-benrosan@apache_ ~](https://github.com/Benrosan/Linux_Upskill/assets/160042310/84926e11-d6ae-4499-8808-4fb6f38e54c5)
###
Installed the Network Manager package to grab the name of my NIC. Then ran **sudo iftop -i ens18** to take a look at network traffic.
###
![2024-03-28 13_22_27-benrosan@apache_ ~](https://github.com/Benrosan/Linux_Upskill/assets/160042310/4850dafa-5f7e-4b0c-a454-0e941b235a8a)
###
Also installed htop to be get a better look at resource utilization.
###
![2024-03-28 13_19_48-benrosan@apache_ ~](https://github.com/Benrosan/Linux_Upskill/assets/160042310/bdcbd96e-9221-4864-b2d7-0a680a958fc1)
###
Updated the timezone on my server.
###
![2024-04-01 09_17_26-root@apache_ ~](https://github.com/Benrosan/Linux_Upskill/assets/160042310/59b5dd91-0184-4d6d-b6ad-1d513b7a86d7)
###
Switched to my Kali Linux VM to try an crack my own password via John the Ripper (stopped process after a few mins). Interesting to note the uptick in resource utilization as the program uses CPU cores to try and crack the hash.
###
![2024-04-01 10_15_29-Kali Linux on GENIE - Virtual Machine Connection](https://github.com/Benrosan/Linux_Upskill/assets/160042310/fa5c351f-07be-4755-823f-e676d73d1971)
###
Navigating to various important folders and practicing working with important commands such as **find, cat, grep**.
###
![2024-04-01 10_37_24-benrosan@apache_ _](https://github.com/Benrosan/Linux_Upskill/assets/160042310/b46abd73-8b46-4015-873f-f787583f239d)
###
![2024-04-01 10_39_34-benrosan@apache_ _etc](https://github.com/Benrosan/Linux_Upskill/assets/160042310/923f7e1e-d0d3-4b3e-8d37-4e90d128d169)
###








