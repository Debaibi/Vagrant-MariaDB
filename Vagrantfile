Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"

  config.vm.provision :shell, :path => "install.sh"
 
   config.vm.network "private_network",
    virtualbox__intnet: "DB"
   config.ssh.insert_key = false
   config.vm.provider "virtualbox" do |vb|
    # Display the VirtualBox GUI when booting the machine
    # vb.gui = true

  end
end