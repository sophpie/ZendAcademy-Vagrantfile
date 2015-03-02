# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ZendAcademy"
  config.vm.network :private_network, ip: "192.168.20.30"
  config.vm.synced_folder "www", "/var/www", owner: "www-data"
end
