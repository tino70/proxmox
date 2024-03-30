# Installation automatique de HAOS sur Proxmox
### Description
Commande a utilisée dans le shell Proxmox pour installer HAOS avec les paramètres suivants par défaut :
   - Core : 8
   - RAM : 10 Go
   - Disk : 200 Go
### Installation
```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/tino70/proxmox/main/haos-vm.sh)"
```
