Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-22.04"

  config.vm.define "web1" do |web1|
    web1.vm.hostname = "web1"
    web1.vm.network "private_network", ip: "192.168.50.10"
  end

  config.vm.define "web2" do |web2|
    web2.vm.hostname = "web2"
    web2.vm.network "private_network", ip: "192.168.50.20"
  end

  config.vm.define "lb" do |lb|
    lb.vm.hostname = "lb"
    lb.vm.network "private_network", ip: "192.168.50.30"
  end

  config.vm.define "cliente" do |cliente|
    cliente.vm.hostname = "cliente"
    cliente.vm.network "private_network", ip: "192.168.50.40"
  end
end

