Vagrant.configure("2") do |config|
    config.vm.box="ubuntu/trusty64"
    config.vm.provider "virtualbox" do |vb|
        vb.memory = 2048
        vb.cpus   = 1
        vb.name   = "vagrant_ansible"
    end
    config.vm.define"vansible" do |vansible|
        vansible.vm.network"private_network", ip:"192.168.1.100"
    end
end 