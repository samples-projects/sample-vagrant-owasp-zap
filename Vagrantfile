# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "kalilinux/rolling"
  config.vm.box_version = "2020.3.0"
  config.vm.box_check_update = false

  config.vm.provider "virtualbox" do |vb|
    vb.name = "owaspzap"
    vb.gui = true
    vb.cpus = 1
    vb.memory = 1024
  end

  # config.vm.provision "shell", inline: <<-SHELL
  #   apt update -y
  #   apt upgrade -y
  #   apt dist-upgrade -y
  # SHELL
end
