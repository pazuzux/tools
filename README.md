# Tools

Instalar pacotes e softwares usados no meu dia a dia.
Útil para configuração nova de máquina

> **_Importante_** :  
> Ubuntu version 18+

## Instalação

> Todas configurações estão em `ubuntu.yaml`.

1. Install Ansible
```bash
sudo apt update && sudo apt install ansible unzip git -y
```
2. Clone this repository
```bash
git clone https://github.com/pazuzux/tools.git
```

3. Apply the configuration
```bash
ansible-playbook tools/ubuntu.yaml --ask-become-pass
```
>Type your password when asked to give root permissions for some actions.

