Vagrant.configure("2") do |config|
 
  
  config.vm.define "vm1" do|vm1|
    vm1.vm.box =  "ubuntu/trusty64"
    vm1.vm.hostname = "ansibleServer"
    vm1.vm.network :private_network, ip: "10.0.0.10"
  end


  config.vm.define "vm2" do |vm2|
    vm2.vm.box = "centos/8"
    vm2.vm.hostname = "centos1Node"
    vm2.vm.network :private_network, ip: "10.0.0.11"
  end
 
  config.vm.define "vm3" do |vm3|
    vm3.vm.box = "centos/8"
    vm3.vm.hostname = "centos2Node"
     vm3.vm.network :private_network, ip: "10.0.0.12"
  end
end


