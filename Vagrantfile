# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "precise64"
  config.vm.box_url = "http://files.vagrantup.com/precise64.box"

  config.vm.network :forwarded_port, guest: 3000, host: 3000   #api
  config.vm.network :forwarded_port, guest: 9000, host: 9000   #web server
  config.vm.network :forwarded_port, guest: 35729, host: 35729 #LiveReload

end
