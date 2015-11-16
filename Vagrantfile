Vagrant.require_version ">= 1.5.0"
Vagrant.configure(2) do |config|
  config.vm.box = "hashicorp/precise64"
  config.vm.network "forwarded_port", guest: 8000, host: 8000, auto_correct: true
  config.vm.network "forwarded_port", guest: 8888, host: 8888, auto_correct: true
  config.vm.provision :shell, path: "bootstrap.sh"
end
