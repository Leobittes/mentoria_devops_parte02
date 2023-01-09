Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "Mentoria_DEVOPS"
    vb.memory = 1024
    #vb.cpus = 1
end
    config.vm.box = "ubuntu/focal64"
    config.vm.network "forwarded_port", guest: 80, host: 8090
    config.vm.network "public_network"
    
end