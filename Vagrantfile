# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"  
  config.vm.define "Box1" do |box1|
     box1.vm.hostname = "BoxAnsible1"
     box1.vm.network "private_network", ip: "10.9.8.1"
  end   
  config.vm.define "Box2" do |box2|
     box2.vm.hostname = "BoxAnsible2"
     box2.vm.network "private_network", ip: "10.9.8.2"
  end
  config.vm.define "Box3" do |box3|
     box3.vm.hostname = "BoxAnsible3"
     box3.vm.network "private_network", ip: "10.9.8.3"
  end

  config.vm.define "Box4" do |box4|
     box4.vm.hostname = "BoxAnsible4"
     box4.vm.network "private_network", ip: "10.9.8.4"
  end  

end
