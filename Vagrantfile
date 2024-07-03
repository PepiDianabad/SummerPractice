Vagrant.configure("2") do |config|
  config.vm.box = "generic/centos8"

  # Define VM1
  config.vm.define "vm1" do |vm1|
    vm1.vm.hostname = "vm1"
    vm1.vm.network "private_network", ip: "192.168.56.101"
    vm1.vm.provider "virtualbox" do |vb|
      vb.name = "vm1"
      vb.memory = "2048"
      vb.cpus = 2
    end
  end

  # Define VM2
  config.vm.define "vm2" do |vm2|
    vm2.vm.hostname = "vm2"
    vm2.vm.network "private_network", ip: "192.168.56.102"
    vm2.vm.provider "virtualbox" do |vb|
      vb.name = "vm2"
      vb.memory = "2048"
      vb.cpus = 2
    end
  end

  # Define VM3
  config.vm.define "vm3" do |vm3|
    vm3.vm.hostname = "vm3"
    vm3.vm.network "private_network", ip: "192.168.56.103"
    vm3.vm.provider "virtualbox" do |vb|
      vb.name = "vm3"
      vb.memory = "2048"
      vb.cpus = 2
    end
  end
end
