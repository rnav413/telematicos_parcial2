# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
 config.vm.define :servidor do |servidor|
 servidor.vm.box = "bento/ubuntu-22.04"
 servidor.vm.network :private_network, ip: "192.168.50.3"
 servidor.vm.network :private_network, ip: "209.191.100.5"
 servidor.vm.hostname = "servidor"
 end
 config.vm.define :cliente do |cliente|
 cliente.vm.box = "bento/ubuntu-22.04"
 cliente.vm.network :private_network, ip: "192.168.50.2"
 cliente.vm.hostname = "cliente"
 end
end