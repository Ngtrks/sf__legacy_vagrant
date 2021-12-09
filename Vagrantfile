# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "mbr/postgres"
  config.vm.network "forwarded_port", guest: 5432, host: 5432, host_ip: "127.0.0.1"
end
