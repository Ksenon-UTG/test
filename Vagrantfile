Vagrant.configure(2) do |config|
	#configuring new Vagrant config!!! DO NOT DELETE
 config.vm.define "web" do |web|
		#creating new VM called web with specified IP
   	    web.vm.box = "ubuntu/trusty64"
      	    config.vm.network "private_network", ip: "192.168.0.101/24"
    end
 config.vm.define "db" do |db|
		#creating new VM called db 
      	   db.vm.box = "ubuntu/trusty64"
           config.vm.network "private_network", ip: "192.168.0.102/24"
    end

	#if "vagrant up" - 2 VM's will be started

end
