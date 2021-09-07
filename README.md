# packer_debian

build image for virtualbox:

packer build -force -var 'version=1.2.0' debian-config-virtualbox.json

build image for vagrant:

packer build -force -var 'version=1.2.0' debian-config-vagrant.json
