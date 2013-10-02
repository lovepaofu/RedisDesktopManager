# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  #ubuntu 12
  config.vm.define "ubu12" , primary: true do |ubu12|
    ubu12.vm.box = "precise32"
    ubu12.vm.box_url = "http://files.vagrantup.com/precise32.box"
    ubu12.vm.provision :shell, :path => "install_ubuntu.sh"
  end 

  #debian 6
  config.vm.define "debi6" do |debi6|
    debi6.vm.box = "debi6"
    debi6.vm.box_url = "https://s3-eu-west-1.amazonaws.com/ffuenf-vagrant-boxes/debian/chef-11.4.0/debian-6.0.7-amd64.box"
    debi6.vm.provision :shell, :path => "install_ubuntu.sh"
  end 

  #debian 7
  config.vm.define "debi7" do |debi7|
    debi7.vm.box = "debi7"
    debi7.vm.box_url = "https://s3-eu-west-1.amazonaws.com/ffuenf-vagrant-boxes/debian/debian-7.1.0-amd64.box"
    debi7.vm.provision :shell, :path => "install_ubuntu.sh"
  end 

end
