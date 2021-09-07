# Packer Debian

build image for virtualbox:

packer build -force -var 'version=1.2.0' debian-config-virtualbox.json

build image for vagrant:

packer build -force -var 'version=1.2.0' debian-config-vagrant.json

---

Add SSH key for ansible

Add SSH key for ME

Settings SSH, only key 

Setings FW, only SSH
