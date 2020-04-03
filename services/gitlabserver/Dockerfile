FROM gitlab/gitlab-ce:latest

# MISE A JOUR DE LA LISTE DES PAQUETS
RUN DEBIAN_FRONTEND=noninteractive apt-get update

# Mise a Jour des Paquets Installes
RUN DEBIAN_FRONTEND=noninteractive apt-get dist-upgrade -y
RUN DEBIAN_FRONTEND=noninteractive apt-get upgrade -y

## Installation des Paquets de Base
RUN DEBIAN_FRONTEND=noninteractive apt-get --reinstall  -y  install python3-pip software-properties-common zip unzip alien sudo net-tools awscli procps psmisc nmap psmisc wget curl nano netdiscover build-essential
RUN DEBIAN_FRONTEND=noninteractive apt-get --reinstall install -y curl wget vim git unzip socat bash-completion apt-transport-https build-essential gcc g++ make
RUN DEBIAN_FRONTEND=noninteractive apt-get --reinstall install -y git

# # RUN DEBIAN_FRONTEND=noninteractive pip3 install pip3 --upgrade
# RUN DEBIAN_FRONTEND=noninteractive pip3 install jinja2-cli --upgrade
