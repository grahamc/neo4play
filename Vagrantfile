# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "neo4play"
  config.vm.box_url = "http://domain.com/path/to/above.box"
  config.vm.network :forwarded_port, guest: 4747, host: 4747
end

