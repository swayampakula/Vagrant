# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |stackroute|
  stackroute.vm.box = "rahman6848/Stackroute-Vagrantbox"
  stackroute.vm.network "forwarded_port", guest: 8080, host: 8080
  stackroute.vm.provision :puppet
end
