Vagrant.configure("2") do |config|
  config.vm.provider:virtualbox do |vbox|
    vbox.name = "Ubuntu"
    vbox.memory = 1024
    vbox.cpus = 1
  end
    
  config.vm.define "ubuntu" do |ubu|
    ubu.vm.box = "generic/ubuntu2004"
    ubu.vm.network "public_network"
  end
end
