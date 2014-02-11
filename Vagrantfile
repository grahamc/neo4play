# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "neo4play"
  config.vm.box_url = "https://github.com/grahamc/neo4play/releases/download/0.0.1/package.box"
  config.vm.network :forwarded_port, guest: 7474, host: 7474
end

