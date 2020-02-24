# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile pactica
#creado por: Camilo Arias, Henry Salazar

Vagrant.configure("2") do |config|
  config.vm.define "web0" do |web|
    web.vm.box = "ubuntu/xenial64"
    web.vm.hostname = "web0"
    web.vm.network "private_network", ip: "192.168.200.100"
    web.vm.provision "shell", path: "installServer.sh"
  end
end