Vagrant.configure("2") do |config|
    config.vm.define "Mi-Servidor" do |servidor|
      servidor.vm.box = "ubuntu/bionic64"
      servidor.vm.network "private_network", ip: "192.168.56.10"
      servidor.vm.provider "virtualbox" do |vb|
        vb.name = "Mi-Servidor"
        vb.memory = "1024"  
        vb.cpus = 1
      end
    end
  end