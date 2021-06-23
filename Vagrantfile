# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
config.vm.define :nodo1 do |nodo1|
    nodo1.vm.box = "generic/debian10"
    nodo1.vm.hostname = "nodo1"
    nodo1.vm.network :private_network, ip: "10.1.1.101"

  end
  config.vm.define :nodo2 do |nodo2|
    nodo2.vm.box = "generic/debian10"
    nodo2.vm.hostname = "nodo2"
    nodo2.vm.network :private_network, ip: "10.1.1.102"

  end
  config.vm.define :dns do |dns|
    dns.vm.box = "generic/debian10"
    dns.vm.hostname = "dns"
    dns.vm.network :private_network, ip: "10.1.1.103"
  end
end
