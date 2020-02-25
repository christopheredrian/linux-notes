# ssh.md

## Installing SSH 

https://www.cyberciti.biz/faq/ubuntu-linux-install-openssh-server/


```bash

sudo apt update
sudo apt upgrade
sudo apt install openssh-server
sudo systemctl enable ssh
sudo systemctl start ssh
sudo systemctl status ssh

sudo ufw allow ssh
sudo ufw enable
sudo ufw status
```

