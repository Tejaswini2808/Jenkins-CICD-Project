# CI/CD_End-to-End_Implementation
CI/CD Pipeline Implementation | TicTacToe Game

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Connecting Ubuntu server to VSCode**

**Ubuntu**
+ sudo apt update
+ sudo apt install openssh-server
+ ssh -V // to check version
+ sudo systemctl status ssh // enter password if prompted (TejaswiniL@28)
+ sudo systemctl start ssh
+ ip a // copy ip address from enp0s3 (192.168.29.228)

**VS Code**
- Install Remote Explorer (Tunnel/SSH) extension
- Search for "Remote-SSH: Connect to Host"
- Add new SSH Host (ssh ubuntu@192.168.29.228)
- select /.ssh/config file
- Enter password
- VSCode installs VS Code server automatically
- Open Terminal and play around
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Launching AWS EC2 Instance**

