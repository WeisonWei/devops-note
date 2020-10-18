# devops-note
# linux安装
```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io
systemctl start docker
sudo groupadd docker
sudo gpasswd -a $USER docker
newgrp docker
```

