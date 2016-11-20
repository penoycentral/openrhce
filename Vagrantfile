# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
    config.hostmanager.enabled = true

  config.vm.define "server1" do |h|
    h.vm.network "private_network", ip: "192.168.135.100"
    h.vm.hostname = "server1.lab.local"
#    h.vm.provision "shell", path: "scripts/bootstrap-centos6.sh"
#    h.vm.synced_folder "", ""

  end


end
