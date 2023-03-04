# CursoDockerFernandoHerrera


# Instalar Docker

https://docs.docker.com/desktop/install/ubuntu/

sudo apt install gnome-terminal

sudo apt remove docker-desktop

rm -r $HOME/.docker/desktop
sudo rm /usr/local/bin/com.docker.cli
sudo apt purge docker-desktop


sudo apt-get update

cd <<carpeta de ubicacion del instalador>>

sudo apt-get install ./docker-desktop-<version>-<arch>.deb

apt install docker.io

sudo usermod -aG docker root

sudo docker run hello-world


## Otra forma

sudo apt-get remove docker docker-engine docker.io containerd runc


sudo apt-get update

sudo apt-get install \
    ca-certificates \
    curl \
    gnupg \
    lsb-release

sudo apt-get update

sudo mkdir -m 0755 -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null


  sudo apt-get update


  sudo chmod a+r /etc/apt/keyrings/docker.gpg
sudo apt-get update


sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin


sudo docker run hello-world


# Desinstalar Docker

sudo apt-get purge --auto-remove docker-ce

sudo rm -r /var/lib/docker/


## Comandos para optimizar sudo en cada ejecución post instalacion

https://docs.docker.com/engine/install/linux-postinstall/

sudo groupadd docker

sudo usermod -aG docker $USER

newgrp docker

docker run hello-world

## Dockerhub

https://hub.docker.com/_/hello-world




## VISUAL STUDIO EXTENSIONES


# activitusbar
ext install Gruntfuggly.activitusbar

# Aura Theme
ext install DaltonMenezes.aura-theme

# set de íconos
ext install PKief.material-icon-theme


# Instalacion Tableplus

https://tableplus.com/blog/2019/10/tableplus-linux-installation.html



