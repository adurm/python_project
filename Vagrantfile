
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"
  config.vm.provision "shell", path: "provision.sh"
  config.vm.synced_folder 'app' , '/home/ubuntu/app'

end
