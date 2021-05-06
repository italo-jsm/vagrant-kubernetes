Vagrant.configure("2") do |workers|

    workers.vm.provider "virtualbox" do |vworker|
        vworker.memory = 2048
        vworker.cpus = 2
    end

    workers.vm.define "node1" do |node1|
        node1.vm.box = "ubuntu/xenial64"
        node1.vm.network "public_network"
    end

    workers.vm.define "node2" do |node2|
        node2.vm.box = "ubuntu/xenial64"
        node2.vm.network "public_network"
    end

end