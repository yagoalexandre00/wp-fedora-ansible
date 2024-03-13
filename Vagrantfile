Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  
  config.vm.hostname = "ubuntu-server"
  
  config.vm.network "private_network", ip: "192.168.56.190"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
  end
end
