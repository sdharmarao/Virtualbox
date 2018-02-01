# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.


Vagrant.configure("2") do |config|
  
  #For CentOS
  config.vm.define "CentOS" do |centos|
  centos.vm.box = "centos/7"
  centos.vm.network:private_network, ip:"192.168.56.10"
  end

  #For RHEL
  config.vm.define "RedHat" do |redhat|
  redhat.vm.box = "iamseth/rhel-7.3"
  redhat.vm.box_version = "1.0.0"
  redhat.vm.network:private_network, ip:"192.168.56.11"
  end

  #For Ubuntu
  config.vm.define "Ubuntu" do |ubuntu|
  ubuntu.vm.box = "ubuntu/trusty64"
  ubuntu.vm.network:private_network, ip:"192.168.56.12"
  end
  
end

