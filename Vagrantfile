Vagrant.configure(2) do |config|

  config.vm.box = "precise32"
  config.vm.box_url = "http://files.vagrantup.com/precise32.box"

  config.vm.network :private_network, ip: "172.22.22.22"
  config.vm.provision :puppet

end
