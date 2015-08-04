Vagrant.configure(2) do |config|
 config.vm.define "web" do |web|
   	web.vm.box = "ubuntu/trusty64"
        config.vm.network "private_network", ip: "192.168.0.101/24"
    end
 config.vm.define "db" do |db|
 	db.vm.box = "ubuntu/trusty64"
	config.vm.network "private_network", ip: "192.168.0.102/24"
    end
end
