# Windows installation

Just use this link:
[Windows](https://download.docker.com/win/stable/Docker%20for%20Windows%20Installer.exe)

# Linux installation

```sh
    sudo apt install docker.io -y
    sudo usermod -aG docker $USER
    sudo newgrp docker
    sudo systemctl status docker
    sudo systemctl start docker
```

# Basic commands:

```sh
    docker version
    docker container run hello-world
    docker container ls -a
```