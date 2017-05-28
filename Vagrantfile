Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/xenial32"

  $prescript = %Q{
    sudo apt-get update
    sudo apt-get install nasm make build-essential grub qemu zip -y
  }
  config.vm.provision :shell, :inline => $prescript

end
